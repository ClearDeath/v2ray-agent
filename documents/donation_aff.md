- [TG群](https://t.me/technologyshare)、[TG频道-更新通知](https://t.me/joinchat/VuYxsKnlIQp3VRw-)、[博客地址](https://www.v2ray-agent.com/)

# 网络差异比较大，买之前建议执行以下两个步骤
- 测试一下testIP的丢包，traceroute一下testIP的路由，是否商家宣传的一样
- 以下商家仅作为推荐，实际效果需自测
- 便宜机器都可能会出现Google人机验证问题（因为滥用），可以套warp解决（脚本中有此功能）
- 谨记一分钱一分货

<!-- more -->

# 1.CN2 GIA
## 1.推荐理由
- 可用作主力机
- 电信国际精品网络，CN2线路中的顶级产品，回程基本全部走59.43高速节点
- 线路一般比较稳定，延迟一般180ms以下，晚高峰基本上不丢包

## 2.推荐商家
### 1.[搬瓦工](https://bandwagonhost.com/cart.php?aff=64917)
- 老牌商家在vps圈声望比较高，非常稳定，补货后基本很快会被抢空
- 6.58%折扣码：BWH3HYATVBJW
- 12%优惠码：BWHNY2022


套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
CN2 GIA 限量版|1G|1核|20G|500G|1Gbps|89.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=64917&pid=105)
CN2 GIA|1G|2核|20G|1T|2.5Gbps|169.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=64917&pid=87)
HONG KONG CN2 GIA|2G|2核|40G|500G|1Gbps|$899.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=64917&pid=95)

### 2.Gigsgigscloud
- 老牌商家，成立较早，工单回复慢
- 退款需要符合条件，需耐心等待，处理比较慢

套餐名称|内存|CPU|硬盘|流量|带宽|价格|折扣码|购买链接
---|---|---|---|---|---|---|---|---
LAX:SimpleCloud V01 电信gia 联通9929|500M|1核|20G|1T|1Gbps|12 USD/月|5% 折扣码 GYP1WPSCQV0T|[购买链接](https://clientarea.gigsgigscloud.com/?affid=3361)
CLOUD V JP:Japan Tokyo Premium 三网 CN2 GIA|1G|1核|20G|250G|100Mbps|48 USD/月|5% 折扣码 03K5VKLPPALX|[购买链接](https://clientarea.gigsgigscloud.com/?affid=3361)

### 3.Dmit
- 去程路由：电信联通走CN2 GIA，移动CMI
- 回程路由：三网CN2 GIA

套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
LosAngles PVM.LAX.Pro.TINY|1G|1核|10G|650G|500Mbps|28.88 USD/季|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=100)

# 2.联通 AS9929（A网）

## 1.推荐理由
- 价格略贵，可用作主力机，一般网络都很稳定
- 相对于联通AS4837（民用），延迟更低、更稳定
- 适合联通用户，同样也贵一些
- 有些厂商三网回程都走AS9929，这样的商家同样比较适合移动和电信

## 2.推荐商家
### 1.olink
- 三网回程强制都走AS9929
- 优惠一：终身九折折扣码 OLINK
- 优惠二：
```
预计周期优惠：（可与优惠一叠加）
半年付：仅需支付5个月（买半年只需要支付5个月） 半年付28刀 月均4.5刀
年付：仅需支付9个月（买一年只需要支付9个月） 年付50刀 月均4刀多一点
```
- 在线测速：http://speedtest.olink.cloud
- 测试 IP（美国圣何塞）：104.165.62.200
- 测试 IP（德国法兰克福）：31.22.111.254

套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
San Jose Premium VPS|1G|1核|10G|500G|1Gbps|7 USD/月|[购买链接](https://www.olink.cloud/clients/aff.php?aff=281)

### 2.Gigsgigscloud
- 老牌商家，成立较早，工单回复慢
- 退款需要符合条件，需耐心等待，处理比较慢
- 下面这个套餐只有联通是AS9929，电信是gia

套餐名称|内存|CPU|硬盘|流量|带宽|价格|折扣码|购买链接
---|---|---|---|---|---|---|---|---
LAX:SimpleCloud V01 电信gia 联通AS9929|500M|1核|20G|1T|1Gbps|12 USD/月|5% 折扣码 GYP1WPSCQV0T|[购买链接](https://clientarea.gigsgigscloud.com/?affid=3361)


# 3.联通 AS4837（普通民用网）
## 1.推荐理由
- 价格便宜，当备用机很香，晚高峰视本地网络环境不同，可能略炸
- 比如适合联通，电信尚可，一般都可以YouTube流畅1080p
- 相对其他线路比较便宜，适合对网络要求不是特别高，预算有限的用户


## 2.推荐商家

### 1.racknerd
- 流量双向计费，比如3T实际可用1.5T
- 洛杉矶动态路由，有时候会很拉垮
- sanjose大概率会跳Google人机验证，可通过warp或者任意门解锁解决此问题

套餐名称|内存|CPU|硬盘(SSD)|流量|带宽|价格|推荐理由|购买链接
---|---|---|---|---|---|---|---|---
[INTEL-SSD] 768 MB KVM VPS Special|768M|1核|12 GB Pure SSD|2T|1Gbps|$9.49 USD|此机器价格比较便宜，有可能出现人机验证，联通去程回程都走AS4837，路由一般不会变，位置建议【San Jose】|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=476)
1GB KVM VPS Special|1G|1核|17 GB Pure SSD|3T|1Gbps|$10.98 USD|价格便宜，联通去程回程都走AS4837|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=358)
1 GB RAM - LA-DC02 PURE SSD PROMO|1.5G|1核|20 GB Pure SSD|3T|1Gbps|$12.79 USD|价格便宜，联通去程回程都走AS4837，本人使用|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=498)
[RYZEN-NVMe] 512MB Ryzen KVM VPS |0.5G|1x AMD Ryzen 3900X CPU Core|10 GB NVMe SSD Storage|2T|1Gbps|$14.18 USD|价格、流量比较适中，联通去程回程都走AS4837|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=461)
XMas Sale - 1.5GB KVM|1.5G|1核|20 GB SSD Cached RAID-10 Storage|4.5T|1Gbps|$15.71 USD|联通去程回程都走AS4837，大流量机器|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=52)
[6.18 SALE - 2021] 1.8 GB KVM VPS Special |1.8G|2核|18 GB Pure SSD|5T|1Gbps|$17.88 USD|联通去程回程都走AS4837，大流量机器|[购买链接](https://my.racknerd.com/aff.php?aff=2705&pid=508)

# 4.联通 日本软银

## 1.推荐理由
- 可用作主力机
- 线路一般比较稳定，延迟一般80ms以下，晚高峰基本上不丢包

## 2.推荐商家
### 1.[搬瓦工](https://bandwagonhost.com/cart.php?aff=64917)
- 老牌商家在vps圈声望比较高，非常稳定，补货后基本很快会被抢空
- 不接受退款
- 6.58%折扣码：BWH3HYATVBJW
- location是【JP-Equinix Osaka Softbank】

套餐名称|内存|CPU|硬盘|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
CN2 GIA 限量版|1G|1核|20G|500G|1Gbps|89.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=64917&pid=105)
CN2 GIA|1G|2核|20G|1T|2.5Gbps|169.99 USD/年|[购买链接](https://bandwagonhost.com/aff.php?aff=64917&pid=87)

### 2.Gigsgigscloud
- 老牌商家，成立较早，工单回复慢
- 退款需要符合条件，需耐心等待，处理比较慢

套餐名称|内存|CPU|硬盘|流量|带宽|价格|折扣码|购买链接
---|---|---|---|---|---|---|---|---
CLOUD K JP: JAPAN TOKYO SOFTBANK IP TRANSIT|512M|1核|10G|500G|100Mbps|8.2 USD/月|5% 折扣码 0P559NYMKTTW|[购买链接](https://clientarea.gigsgigscloud.com/?affid=3361)


# 5.CMI
## 1.推荐理由
- 回程三网CMI
- 可用作主力机
- 移动国际精品网络
- 线路大多数情况下比较稳定，偶尔会被打

### 1.DMIT HongKong Lite
- [TOS](https://t.me/DMIT_INC_CN/544)
- 流量双向计费
- 去程有可能更换
- 线路实测为主
- [speedtest](http://dmit-hkg-lite.gubo.org/speedtest/)
- 测试ip：103.135.248.22

#### 去程

- 联通、电信 绕日NTT（4837->日本NTT->HK PCCW【2022-5-9】
- 移动CMI

#### 回程
- 三网CMI

#### 折扣码【仅适用于 STARTER 及以上规格的 Lite 产品，TINY 不包含在内】
- 年付七折：Lite-Annually-Recur-30OFF
- 半年付八折：Lite-Semi-Annually-Recur-20OFF



套餐名称| 内存 |CPU|硬盘(SSD)|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
PVM.HKG.Lite.TINY| 0.75G |1 vCPU|10 GB SSD|2T|1Gbps|$6.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=109)
PVM.HKG.Lite.STARTER| 1.5G |1 vCPU|20 GB SSD|4T|1Gbps|$12.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=110)
PVM.HKG.Lite.MINI| 2G |2 vCPU|40 GB SSD|6T|2Gbps|$21.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=111)

PVM.HKG.Lite.MICRO| 4G |2 vCPU|60 GB SSD|8T|2Gbps|$32.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=111)

PVM.HKG.Lite.MINI| 4G |4 vCPU|80 GB SSD|6T|2Gbps|$49.9 USD/月|[购买链接](https://www.dmit.io/aff.php?aff=3084&a=add&pid=111)


### 2.RFCHOST Hong Kong 3 Premium
#### 去程【截止发文日期2022-4-19】

- 电信CN2-PCCW
- 联通去程4837-4134-CN2-PCCW
- 移动CMI

#### 回程
- 三网CMI

#### 折扣码（九折）
- hkg3openup

#### TestIP
- 199.15.77.1


套餐名称| 内存 |CPU|硬盘(SSD)|流量|带宽|价格|购买链接
---|---|---|---|---|---|---|---
HKG3-Premium-Micro| 512MB |1 CPU|8 GB SSD|500G（只计算出方向流量）|500Mbps|$9.9 USD/月|[购买链接](https://my.rfchost.com/aff.php?aff=899)
HKG3-Premium-Mini| 1.5G |1 CPU|10 GB SSD|1T|1Gbps|$12.99 USD/月|[购买链接](https://my.rfchost.com/aff.php?aff=899)
HKG3-Premium-Medium| 2G |2 CPU|20 GB SSD|2T|1Gbps|$21.9 USD/月|[购买链接](https://my.rfchost.com/aff.php?aff=899)
