#  江西到Vultr各机房的测速数据（20180804） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![江西到Vultr各机房的测速数据（20180804）](/images/thumbnails/Jiangxi_to_vultr.png)

本文的数据视角为 **江西到[Vultr](https://vps123.top/go/vultr)的各机房**的PING响应值、丢包率的比较；若你在江西且打算运行[Vultr](https://vps123.top/go/vultr)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Vultr的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

测速点的运营商线路为电信、联通、移动，有效样本点1485个，其中超时点23个。连通概况如下：大陆线路响应均值为273毫秒，最快的三个机房所在地为东京、新加坡、西雅图，最慢的三个为新泽西、巴黎、迈阿密；东京、硅谷、达拉斯、法兰克福、伦敦有响应超时情况；新加坡、东京、悉尼、西雅图、硅谷等8处丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 江西图表数据

![大陆省份江西到VPS提供商Vultr各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/vultr_20180804/plot_isp_jiangxi_vultr_20180804.png)

### 全部运营商

**江西全部运营商到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 131个 | 7个 | 162ms | 19%  
新加坡 | 75个 | 0 | 195ms | 20%  
西雅图 | 75个 | 0 | 243ms | 16%  
洛杉矶 | 75个 | 0 | 245ms | 3%  
硅谷 | 139个 | 4个 | 257ms | 10%  
达拉斯 | 135个 | 4个 | 258ms | 3%  
均值 | 1485个 | 23个 | 273ms | 7%  
悉尼 | 75个 | 0 | 283ms | 17%  
芝加哥 | 75个 | 0 | 295ms | 6%  
法兰克福 | 135个 | 4个 | 295ms | 1%  
伦敦 | 139个 | 4个 | 302ms | 2%  
亚特兰大 | 75个 | 0 | 315ms | 1%  
阿姆斯特丹 | 75个 | 0 | 318ms | 6%  
新泽西 | 131个 | 0 | 320ms | 2%  
巴黎 | 75个 | 0 | 324ms | 3%  
迈阿密 | 75个 | 0 | 329ms | 6%  
  
**简评：** 本表展示了江西的 **电信、联通、移动** 线路到Vultr各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻江西，可从此表了解你常用的网络到Vultr各个机房的平均响应速度以及丢包率。从表中数据可以看到， **洛杉矶** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

**江西电信到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 71个 | 3个 | 217ms | 49%  
新加坡 | 43个 | 0 | 280ms | 55%  
西雅图 | 43个 | 0 | 261ms | 0  
洛杉矶 | 43个 | 0 | 295ms | 8%  
硅谷 | 79个 | 0 | 238ms | 3%  
达拉斯 | 75个 | 0 | 277ms | 7%  
均值 | 845个 | 3个 | 309ms | 12%  
悉尼 | 43个 | 0 | 396ms | 43%  
芝加哥 | 43个 | 0 | 325ms | 7%  
法兰克福 | 79个 | 0 | 318ms | 3%  
伦敦 | 79个 | 0 | 321ms | 3%  
亚特兰大 | 43个 | 0 | 340ms | 1%  
阿姆斯特丹 | 43个 | 0 | 358ms | 7%  
新泽西 | 75个 | 0 | 386ms | 4%  
巴黎 | 43个 | 0 | 345ms | 4%  
迈阿密 | 43个 | 0 | 384ms | 4%  
  
**简评：** 如果你是来自江西的 **电信** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **硅谷** 的机房；从数据看，你的网络到这里的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_1)吧！

### 联通

**江西联通到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 16个 | 0 | 155ms | 7%  
新加坡 | 8个 | 0 | 189ms | 4%  
西雅图 | 8个 | 0 | 237ms | 6%  
洛杉矶 | 8个 | 0 | 233ms | 1%  
硅谷 | 16个 | 0 | 296ms | 3%  
达拉斯 | 16个 | 0 | 259ms | 3%  
均值 | 168个 | 0 | 263ms | 3%  
悉尼 | 8个 | 0 | 261ms | 8%  
芝加哥 | 8个 | 0 | 302ms | 2%  
法兰克福 | 16个 | 0 | 229ms | 0  
伦敦 | 16个 | 0 | 319ms | 1%  
亚特兰大 | 8个 | 0 | 279ms | 2%  
阿姆斯特丹 | 8个 | 0 | 309ms | 2%  
新泽西 | 16个 | 0 | 302ms | 3%  
巴黎 | 8个 | 0 | 275ms | 1%  
迈阿密 | 8个 | 0 | 314ms | 3%  
  
**简评：** 如果你是来自江西的 **联通** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **新加坡、法兰克福、洛杉矶** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、西雅图** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_2)吧！

### 移动

**江西移动到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 44个 | 4个 | 116ms | 0  
新加坡 | 24个 | 0 | 117ms | 1%  
西雅图 | 24个 | 0 | 231ms | 40%  
洛杉矶 | 24个 | 0 | 207ms | 0  
硅谷 | 44个 | 4个 | 238ms | 24%  
达拉斯 | 44个 | 4个 | 238ms | 0  
均值 | 472个 | 20个 | 247ms | 6%  
悉尼 | 24个 | 0 | 193ms | 0  
芝加哥 | 24个 | 0 | 257ms | 9%  
法兰克福 | 40个 | 4个 | 339ms | 1%  
伦敦 | 44个 | 4个 | 267ms | 2%  
亚特兰大 | 24个 | 0 | 327ms | 0  
阿姆斯特丹 | 24个 | 0 | 286ms | 8%  
新泽西 | 40个 | 0 | 271ms | 0  
巴黎 | 24个 | 0 | 353ms | 4%  
迈阿密 | 24个 | 0 | 291ms | 12%  
  
**简评：** 如果你是来自江西的 **移动** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **东京、新加坡、悉尼、洛杉矶、达拉斯** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **西雅图、硅谷** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_3)吧！

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180804) 
    * [全部](https://vps123.top/pingtests/20180804 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180804 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180804 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180804 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期 _其他省份_ 到Vultr各机房的报告： 
    * [安徽](/vultr/isp/anhui/20180804-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180804")
    * [北京](/vultr/isp/beijing/20180804-vultr-isp-beijing.md "北京到Vultr各机房的Ping测试 20180804")
    * [大陆](/vultr/isp/china/20180804-vultr-isp-china.md "大陆到Vultr各机房的Ping测试 20180804")
    * [重庆](/vultr/isp/chongqing/20180804-vultr-isp-chongqing.md "重庆到Vultr各机房的Ping测试 20180804")
    * [福建](/vultr/isp/fujian/20180804-vultr-isp-fujian.md "福建到Vultr各机房的Ping测试 20180804")
    * [甘肃](/vultr/isp/gansu/20180804-vultr-isp-gansu.md "甘肃到Vultr各机房的Ping测试 20180804")
    * [广东](/vultr/isp/guangdong/20180804-vultr-isp-guangdong.md "广东到Vultr各机房的Ping测试 20180804")
    * [广西](/vultr/isp/guangxi/20180804-vultr-isp-guangxi.md "广西到Vultr各机房的Ping测试 20180804")
    * [贵州](/vultr/isp/guizhou/20180804-vultr-isp-guizhou.md "贵州到Vultr各机房的Ping测试 20180804")
    * [海南](/vultr/isp/hainan/20180804-vultr-isp-hainan.md "海南到Vultr各机房的Ping测试 20180804")
    * [河北](/vultr/isp/hebei/20180804-vultr-isp-hebei.md "河北到Vultr各机房的Ping测试 20180804")
    * [黑龙江](/vultr/isp/heilongjiang/20180804-vultr-isp-heilongjiang.md "黑龙江到Vultr各机房的Ping测试 20180804")
    * [河南](/vultr/isp/henan/20180804-vultr-isp-henan.md "河南到Vultr各机房的Ping测试 20180804")
    * [湖北](/vultr/isp/hubei/20180804-vultr-isp-hubei.md "湖北到Vultr各机房的Ping测试 20180804")
    * [湖南](/vultr/isp/hunan/20180804-vultr-isp-hunan.md "湖南到Vultr各机房的Ping测试 20180804")
    * [内蒙古](/vultr/isp/innermongolia/20180804-vultr-isp-innermongolia.md "内蒙古到Vultr各机房的Ping测试 20180804")
    * [江苏](/vultr/isp/jiangsu/20180804-vultr-isp-jiangsu.md "江苏到Vultr各机房的Ping测试 20180804")
    * [吉林](/vultr/isp/jilin/20180804-vultr-isp-jilin.md "吉林到Vultr各机房的Ping测试 20180804")
    * [辽宁](/vultr/isp/liaoning/20180804-vultr-isp-liaoning.md "辽宁到Vultr各机房的Ping测试 20180804")
    * [宁夏](/vultr/isp/ningxia/20180804-vultr-isp-ningxia.md "宁夏到Vultr各机房的Ping测试 20180804")
    * [青海](/vultr/isp/qinghai/20180804-vultr-isp-qinghai.md "青海到Vultr各机房的Ping测试 20180804")
    * [山西](/vultr/isp/shan1xi/20180804-vultr-isp-shan1xi.md "山西到Vultr各机房的Ping测试 20180804")
    * [陕西](/vultr/isp/shan3xi/20180804-vultr-isp-shan3xi.md "陕西到Vultr各机房的Ping测试 20180804")
    * [山东](/vultr/isp/shandong/20180804-vultr-isp-shandong.md "山东到Vultr各机房的Ping测试 20180804")
    * [上海](/vultr/isp/shanghai/20180804-vultr-isp-shanghai.md "上海到Vultr各机房的Ping测试 20180804")
    * [四川](/vultr/isp/sichuan/20180804-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180804")
    * [天津](/vultr/isp/tianjin/20180804-vultr-isp-tianjin.md "天津到Vultr各机房的Ping测试 20180804")
    * [西藏](/vultr/isp/tibet/20180804-vultr-isp-tibet.md "西藏到Vultr各机房的Ping测试 20180804")
    * [新疆](/vultr/isp/xinjiang/20180804-vultr-isp-xinjiang.md "新疆到Vultr各机房的Ping测试 20180804")
    * [云南](/vultr/isp/yunnan/20180804-vultr-isp-yunnan.md "云南到Vultr各机房的Ping测试 20180804")
    * [浙江](/vultr/isp/zhejiang/20180804-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180804")
  * 江西到Vultr各机房的 _其他近期报告_ ： 
    * [20180514](/vultr/isp/jiangxi/20180514-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180514")
    * [20180527](/vultr/isp/jiangxi/20180527-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180527")
    * [20180622](/vultr/isp/jiangxi/20180622-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180622")
    * [20180918](/vultr/isp/jiangxi/20180918-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180918")
  * 本期报告：江西到 _其他VPS提供商_ 各机房的测速报告： 
    * [BandwagonHost](/bandwagon/isp/jiangxi/20180804-bandwagon-isp-jiangxi.md "江西到BandwagonHost各机房的Ping测试 20180804")
    * [Digital Ocean](/digitalocean/isp/jiangxi/20180804-digitalocean-isp-jiangxi.md "江西到Digital Ocean各机房的Ping测试 20180804")
    * [Linode](/linode/isp/jiangxi/20180804-linode-isp-jiangxi.md "江西到Linode各机房的Ping测试 20180804")



本文最初发表于[江西到Vultr各机房的测速数据（20180804）](https://vps123.top/pingtest/20180804-vultr-isp-jiangxi.html)
