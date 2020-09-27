WiFi与Internet
==================================
Canada稍大一点的城市里随处都可以搜到免费的WiFi。下面我来为大家介绍一下：

一、 学校的WiFi和Internet
-------------------------------------------------
1. WiFi热点：Mac-WiFi

- 这个是主要的Internet接入方式。不限流量。速度是50Mb/s下载，10Mb/s上传。在McMaster所有的校区都能访问。
- 用电子设备搜到这个热点后，用户名是MacID，密码是登录Mosaic的密码。
- 连接成功后，你的设备会获得一个[172.16.0.0~172.31.255.255]区间内的B类私有IP地址，可以无限制的访问Internet。

2. LAN：插网线

- 对于有实验室的同学来说，LAN是一种极好的上网方式，速度极快，网络稳定，不限流量。网速是500Mb/s下载，500Mb/s上传。
- 插上网线就可以使用，如果不行，就去找所在学院的Technical staff帮忙设置一下。
- 连接成功后，你的设备会获得一个130.113.*.*的公网IP地址，可以访问学校里的所有的网络资源。包括图书馆、超级计算机的计算服务、远程桌面或远程登录lab里的电脑、打印服务等等。这个IP虽然是公网IP，但由于学校防火墙设置，在学校外是无法直接访问校内的分配有该类IP的设备，ping也会失败。

3. 高校通用WiFi热点：eduroam

- 这个是一个备用的Internet接入方式。在Canada以及世界上大部分高等学校都能搜到。不限流量。McMaster提供的速度是50Mb/s下载，10Mb/s上传。
- 用电子设备搜到这个热点后，用户名是MacID@mcmaster.ca（就是McMaster的邮箱），密码是登录Mosaic的密码。
- 举例：在多伦多大学搜到这个热点后，用McMaster的账户也能认证成功并上网。可以无限制的访问Internet，但由于各个学校里的政策不同，基本上无法访问学校里的任何网络资源。

4. VPN

- 如果想在校外访问校内的各种网络资源，那就需要使用McMaster提供的VPN服务了。
- https://uts.mcmaster.ca/virtual-private-networks-vpn/
- 此时你的设备会分到一个130.113.*.*的IP地址，就可以像在学校里面一样使用了。
- 对于学生来说，有两种VPN可以使用：

  - Student General VPN：VPN服务器地址：studentvpn.mcmaster.ca。如果大家需要访问保密权限比较高的网页，或者用学校图书馆下论文，可以使用这个。
  - Express VPN For Students Located in China：麦马从2020年暑期开始针对中国学生新开的VPN服务。使用这个服务，在国内上网课可以减少网络延迟。此外还可以访问Gmail。

二、城市里的热点
----------------------------------------------
1. Tim Hortons和Starburks里一定有free WiFi。
2. Hamilton市政厅周边可以搜到市政厅提供的free WiFi。详细请看 https://www.hamilton.ca/government-information/site-policies/wireless-network
3. Toronto的市区也可以搜到TTC提供的free WiFi。

三、家庭宽带
-------------------------------------------------------
- Canada提供宽带的公司不计其数，大的公司有Bell、Rogers，小的公司有Carry、altima, start.ca，CIK等等。
- 小公司一般是先从大的公司购买宽带，再卖给家庭，优惠幅度极大，但是晚上等用网高峰时段，网络时常不稳定，网速波动较大。

以下是常见的提供宽带服务的公司：

- Bell：http://www.bell.ca/Bell_Internet/Internet_access 网络最稳定，价格也相对较高。Bell每年开学有个对学生优惠的活动（50Mb下载、10Mb上传）。
- Rogers：https://www.rogers.com/web/consumer/internet 网络同样非常稳定，价格也相对较高。且已经完全为家庭用户提供了ipv6的支持。
- Carry：http://www.carrytel.ca/internet-plans.aspx 这虽然是一家小公司，但确实是价格最便宜的，并且网络也基本稳定。建议大家先考虑这家公司。

  - 办理Fiber 25/50可以用以下promotion code：ZH11194（由17-CAS-赵伟提供），这样购买modem可以便宜$10，并且没有安装费。
  - 如果办理Cable 40/60/75/120/150可以用CE148951，这样一次性便宜$10的当月网费。（注：这家公司的modem信号太弱，强烈建议自带无线路由或网线）
- altima：https://www.altimatel.com/shop/internet
- start.ca：https://www.start.ca/
- CIK：https://www.ciktel.com/InternetPlans/FiberLiteInternet
- Cogego：https://www.cogeco.ca/en/internet/packages

其它便宜的Internet，大家可以去51.ca（加国无忧网）搜索一下。打开 http://www.51.ca/service/ ， 找到“上网电视“。里面有很多优惠活动。大家可以放心去打电话办理，至今没听说诈骗的情况。

注
-------------------------
1) 虽然学校LAN速度很快，但希望大家尽量不要用LAN下载违规的资源。JHE楼曾经严查了一次。
#) 住公寓的同学，建议从国内带一个路由器，比如小米路由器。因为公寓信号之间干扰太严重，这会严重降低网速和大幅度增加网络延时。用一根至少20米长的网线外接一个无线路由器放在自己的卧室里可以放大信号。对于自己的台式机或笔记本电脑，如果条件允许，也可以再带几根1~2米的网线连接自己卧室的路由器，插网线上网。