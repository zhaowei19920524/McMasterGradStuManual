学校email激活与收发
===========================
.. attention::
   **学校email只有等注册后才能激活**

学校的邮件系统为所有学生和员工提供一个 MacID@mcmaster.ca 的邮箱，具体分为2部分

- 本科生和研究生使用的是Google的企业邮箱服务，就是Gmail的企业版，在国内无法登陆，甚至激活都不可以，大家来Canada之后再激活登陆。如果想在国内激活并访问，请自行搜索翻墙方法。
- Post doc、访问学者、联培学生和学校教职工使用的是Microsoft Exchange企业邮箱，就是Outlook的企业版，这个在国内可以登陆，现在已经可以激活并且使用了。

激活方法
---------------------------------------
1. 方法一：在手机上登录mosaic

| 第一步：登陆mosica之后，在右上角点击三个横线的图标

.. image:: /resource/activate_email_on_phone_1.png
   :align: center
   :scale: 50%

| 第二步：选择Navigator

.. image:: /resource/activate_email_on_phone_2.png
   :align: center
   :scale: 50%

| 第三步：选择Email Management

.. image:: /resource/activate_email_on_phone_3.png
   :align: center
   :scale: 50%

| 第四步：点击“Manage you Email Service”，找到学校的邮箱，选择Activate。同时也设置一下Primary Email Account，就是默认接受学校发的Email的邮箱。

.. image:: /resource/activate_email_on_phone_4.png
   :align: center
   :scale: 50%

以上截图感谢17-PH-朱莹提供

在线登录方法
-----------------------------------------------
- 本科生、研究生：https://studentmail.mcmaster.ca
- Post doc、访问学者、联培学生和学校教职工：https://macmail.mcmaster.ca/

邮箱客户端收发方法
-------------------------------------------------


iOS和macOS自带的邮件客户端只能收邮件不能发邮件，请最好用Outlook和Gmail客户端。

1. 本科生、研究生

| 首先在邮箱网页里设置允许IMAP协议和允许客户端访问（见附1）。然后是两种设置客户端的方法。

| 方法一：
| Account type: IMAP 
| Incoming server: mcmasterimap.mcmaster.ca 
| Outgoing server: mcmastersmtp.mcmaster.ca 
| SSL encryption for both incoming and outgoing servers turned on. 
| Incoming port 993 
| Outgoing port 465 
| Outgoing server to require authentication using the same credentials as the incoming server. 
| 具体看这里： http://mcmaster.ca/uts/gmailforstudents/imapsetup.html 

| 方法二（建议）：使用客户端自动配置功能。见附2。

2. Post doc、访问学者、联培学生和学校教职工

| iPhone - http://macmailhelp.mcmaster.ca/docs/default-source/default-document-library/uts-documents/macmail---how-to-configure-iphone.pdf?sfvrsn=2
| Android - http://macmailhelp.mcmaster.ca/docs/default-source/default-document-library/uts-documents/macmail---how-to-configure-android.pdf?sfvrsn=2 

如果有其它原因导致Email收发不成功，请联系学校UTS，http://www.mcmaster.ca/uts/

注
--------------------------------------
1) Android phones：May require that the encryption method be set SSL-accept all certificates instead of just SSL。
#) MACID区分大小写。
#) 学校的邮箱在没激活之前，都会先转发到你的申请邮箱里。学校Email激活后可以设置默认转发到McMaster的邮箱里，方法是mosaic->Student Center->Personal Information->email addresses，把你希望设置为默认接受学校邮件的Email勾上Preferred。

附
-------------------------------------------
1) 设置允许IMAP协议和允许客户端访问

| 第一步：在网页上登录邮箱选”Settings“。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_1.png
   :align: center

| 第二步：在“Forwarding and POP/IMAP”列表下，选择“Enable IMAP”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_2.png
   :align: center

| 第三步：点击右上角头像图标，在弹出框里选“My Account”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_3.png
   :align: center

| 第四步：点击“Apps with account access”。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_4.png
   :align: center

| 第五步：把“Allow less secure apps”的开关打开。

.. image:: /resource/XueXiaoemailSheZhi/IMAP_5.png
   :align: center

2) 手机Outlook客户端设置方法（本科生、研究生的邮箱）

  步骤：

| 第一步：
| 下载客户端
| iOS：https://itunes.apple.com/ca/app/microsoft-outlook-email-and-calendar/id951937596?mt=8
| Android：https://play.google.com/store/apps/details?id=com.microsoft.office.outlook

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_1.png
   :align: center
   :scale: 25%

| 第二步：
| 打开后点击左上角的三条横线的图标，然后点击加号。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_2.png
   :align: center
   :scale: 25%

| 第三步：
| 输入McMaster邮箱的地址：MacID@mcmaster.ca。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_3.png
   :align: center
   :scale: 25%

| 第四步：
| 点击右上角“Not Exchange”。再选“Change Account Provider”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_4.png
   :align: center
   :scale: 25%

| 第五步：
| 选“Google”。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_5.png
   :align: center
   :scale: 25%

| 第六步：
| 在弹出的网页里登录邮箱。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_6.png
   :align: center
   :scale: 25%

| 第七步：
| 点击McMaster的邮箱账户。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_7.png
   :align: center
   :scale: 25%

| 第八步：
| 点击Allow。Outlook客户端就会开始自动同步McMaster邮箱。

.. image:: /resource/XueXiaoemailSheZhi/outlook_ios_8.png
   :align: center
   :scale: 25%