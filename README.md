# McMasterGradStuManual
McMaster研究生新生手册

# Branch
1. master: Production, build for http://mcmaster.readthedocs.io/en/latest/
2. staging: Test before Production, build for http://mcmaster.readthedocs.io/en/staging/

So when you update code. First push to staging, readthedocs will automatically compile the code (you can look at the compile process in https://readthedocs.org/projects/mcmaster/builds/). It will show you the result in http://mcmaster.readthedocs.io/en/staging/ . If everything is Okay, make a pull request to merge staging into master. readthedocs will compile http://mcmaster.readthedocs.io/en/latest/ .

# Development guide for Collaborators
## 0. first time usage
Clone the whole project to your disk, create a new branch called staging
```
git clone https://github.com/zhaowei19920524/McMasterGradStuManual
cd McMasterGradStuManual
git checkout -b staging
```

## 1. update your local repo first before adding any content!!!
Just in case other people have updated branch on github. So update your local repo
```
git chekcout master
git pull origin master
git checkout staging
git pull origin staging
```

## 2. update the content in staging branch.

compile code in your disk
```
cd docs/
make html
```
The output html file in McMasterGradStuManual/docs/_build/html

If it looks Okay, then get ready to push to github

## 3. push to github
Push to staging branch!!!
```
git add -u
git commit -m "[why you change the code]"
gitt push origin staging
```

## 4. check result and merge to master branch
you can view the comple process: https://readthedocs.org/projects/mcmaster/builds/

view the result: http://mcmaster.readthedocs.io/en/staging/

If it looks Okay then make a pull request from staging to master, then merge the code.

**I recommand you guys make a code review or call me before merge into master**

Once merged, the result will show in: http://mcmaster.readthedocs.io/en/latest/
