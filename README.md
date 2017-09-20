# McMasterGradStuManual
McMaster研究生新生手册

# Branch
1. master: Production, build for http://mcmaster.readthedocs.io/en/latest/
2. staging: Test before Production, build for http://mcmaster.readthedocs.io/en/staging/

So when you update code. First push to staging branch, readthedocs will automatically compile the code (you can look at the compile process in https://readthedocs.org/projects/mcmaster/builds/). It will show you the result in http://mcmaster.readthedocs.io/en/staging/ . If everything is Okay, make a pull request to merge staging into master. readthedocs will compile http://mcmaster.readthedocs.io/en/latest/ .

# Development guide for Collaborators
## 0. first time usage
### 0.1 Install Python
### 0.2 Install Sphinx
```
pip install sphinx sphinx-autobuild
```
In Linux and macOS, you might need sudo.

### 0.3 Clone the project
Clone the whole project to your disk, create a new branch called staging
```
git clone https://github.com/zhaowei19920524/McMasterGradStuManual
cd McMasterGradStuManual
git checkout -b staging
```

## 1. update your local repo first before adding any content!!!
Just in case other people have updated the branch on github. So update your local repo
```
git checkout master
git pull origin master
git checkout staging
git pull origin staging
```

## 2. update the content in staging branch.

Note:

The Tree level

一、二、三...：Only for Title
```
1 2 3 4 5...

	A B C D E...

		a b c d e...

			I II III IV V...

				i ii iii iv v...
```
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
git push origin staging
```

## 4. check result and merge to master branch
you can view the compile process: https://readthedocs.org/projects/mcmaster/builds/

view the result: http://mcmaster.readthedocs.io/en/staging/

If it looks Okay then make a pull request from staging to master, then merge the code.

**I highly recommand you guys to make a code review or contact me before merging into master**

Once merged, the result will show in: http://mcmaster.readthedocs.io/en/latest/
