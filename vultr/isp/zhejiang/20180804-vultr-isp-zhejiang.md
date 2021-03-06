#  浙江到Vultr各机房的测速数据（20180804） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![浙江到Vultr各机房的测速数据（20180804）](/images/thumbnails/Zhejiang_to_vultr.png)

本文的数据视角为 **浙江到[Vultr](https://vps123.top/go/vultr)的各机房**的PING响应值、丢包率的比较；若你在浙江且打算运行[Vultr](https://vps123.top/go/vultr)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Vultr的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

测速点的运营商线路为电信、联通、移动，有效样本点2940个，其中超时点180个。连通概况如下：大陆线路响应均值为273毫秒，最快的三个机房所在地为东京、西雅图、洛杉矶，最慢的三个为巴黎、伦敦、阿姆斯特丹；新加坡、悉尼、东京、迈阿密、硅谷等15处有响应超时情况；新加坡、东京、悉尼、硅谷、芝加哥等6处丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 浙江图表数据

![大陆省份浙江到VPS提供商Vultr各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/vultr_20180804/plot_isp_zhejiang_vultr_20180804.png)

### 全部运营商

**浙江全部运营商到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 242个 | 19个 | 187ms | 20%  
西雅图 | 162个 | 7个 | 209ms | 1%  
洛杉矶 | 158个 | 10个 | 210ms | 3%  
新加坡 | 174个 | 22个 | 213ms | 21%  
硅谷 | 234个 | 13个 | 233ms | 10%  
达拉斯 | 238个 | 10个 | 252ms | 1%  
均值 | 2940个 | 180个 | 273ms | 7%  
芝加哥 | 158个 | 7个 | 274ms | 7%  
悉尼 | 162个 | 22个 | 297ms | 20%  
亚特兰大 | 170个 | 10个 | 303ms | 3%  
新泽西 | 220个 | 10个 | 308ms | 3%  
迈阿密 | 182个 | 16个 | 309ms | 7%  
法兰克福 | 238个 | 7个 | 309ms | 1%  
巴黎 | 174个 | 7个 | 320ms | 3%  
伦敦 | 246个 | 7个 | 336ms | 3%  
阿姆斯特丹 | 182个 | 13个 | 345ms | 3%  
  
**简评：** 本表展示了浙江的 **电信、联通、移动** 线路到Vultr各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻浙江，可从此表了解你常用的网络到Vultr各个机房的平均响应速度以及丢包率。从表中数据可以看到， **西雅图、洛杉矶** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

**浙江电信到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 108个 | 15个 | 213ms | 41%  
西雅图 | 76个 | 3个 | 240ms | 0  
洛杉矶 | 76个 | 6个 | 219ms | 3%  
新加坡 | 84个 | 18个 | 263ms | 46%  
硅谷 | 108个 | 6个 | 243ms | 8%  
达拉斯 | 104个 | 6个 | 279ms | 2%  
均值 | 1354个 | 111个 | 290ms | 12%  
芝加哥 | 80个 | 3个 | 294ms | 4%  
悉尼 | 80个 | 18个 | 358ms | 41%  
亚特兰大 | 80个 | 3个 | 345ms | 4%  
新泽西 | 94个 | 6个 | 340ms | 7%  
迈阿密 | 84个 | 9个 | 371ms | 7%  
法兰克福 | 108个 | 3个 | 302ms | 3%  
巴黎 | 84个 | 3个 | 295ms | 5%  
伦敦 | 104个 | 3个 | 317ms | 4%  
阿姆斯特丹 | 84个 | 9个 | 345ms | 4%  
  
**简评：** 如果你是来自浙江的 **电信** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **洛杉矶、西雅图** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、硅谷** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_1)吧！

### 联通

**浙江联通到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 67个 | 0 | 228ms | 16%  
西雅图 | 43个 | 0 | 199ms | 4%  
洛杉矶 | 39个 | 0 | 205ms | 5%  
新加坡 | 43个 | 0 | 263ms | 12%  
硅谷 | 67个 | 0 | 219ms | 5%  
达拉斯 | 67个 | 0 | 238ms | 1%  
均值 | 793个 | 6个 | 276ms | 5%  
芝加哥 | 39个 | 0 | 271ms | 8%  
悉尼 | 43个 | 0 | 332ms | 19%  
亚特兰大 | 43个 | 3个 | 300ms | 4%  
新泽西 | 59个 | 0 | 308ms | 3%  
迈阿密 | 51个 | 3个 | 272ms | 2%  
法兰克福 | 67个 | 0 | 287ms | 0  
巴黎 | 43个 | 0 | 327ms | 1%  
伦敦 | 71个 | 0 | 345ms | 2%  
阿姆斯特丹 | 51个 | 0 | 343ms | 2%  
  
**简评：** 如果你是来自浙江的 **联通** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **西雅图、洛杉矶、硅谷、达拉斯** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_2)吧！

### 移动

**浙江移动到Vultr各机房的测速数据 [20180804]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 67个 | 4个 | 120ms | 4%  
西雅图 | 43个 | 4个 | 189ms | 0  
洛杉矶 | 43个 | 4个 | 206ms | 0  
新加坡 | 47个 | 4个 | 112ms | 6%  
硅谷 | 59个 | 7个 | 236ms | 16%  
达拉斯 | 67个 | 4个 | 239ms | 0  
均值 | 793个 | 63个 | 253ms | 3%  
芝加哥 | 39个 | 4个 | 257ms | 9%  
悉尼 | 39个 | 4个 | 201ms | 0  
亚特兰大 | 47个 | 4个 | 263ms | 0  
新泽西 | 67个 | 4个 | 275ms | 0  
迈阿密 | 47个 | 4个 | 283ms | 11%  
法兰克福 | 63个 | 4个 | 339ms | 1%  
巴黎 | 47个 | 4个 | 337ms | 3%  
伦敦 | 71个 | 4个 | 347ms | 2%  
阿姆斯特丹 | 47个 | 4个 | 347ms | 2%  
  
**简评：** 如果你是来自浙江的 **移动** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **东京、西雅图、悉尼、洛杉矶、达拉斯** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **新加坡、硅谷** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_3)吧！

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
    * [江西](/vultr/isp/jiangxi/20180804-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180804")
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
  * 浙江到Vultr各机房的 _其他近期报告_ ： 
    * [20180514](/vultr/isp/zhejiang/20180514-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180514")
    * [20180527](/vultr/isp/zhejiang/20180527-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180527")
    * [20180622](/vultr/isp/zhejiang/20180622-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180622")
    * [20180918](/vultr/isp/zhejiang/20180918-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180918")
  * 本期报告：浙江到 _其他VPS提供商_ 各机房的测速报告： 
    * [BandwagonHost](/bandwagon/isp/zhejiang/20180804-bandwagon-isp-zhejiang.md "浙江到BandwagonHost各机房的Ping测试 20180804")
    * [Digital Ocean](/digitalocean/isp/zhejiang/20180804-digitalocean-isp-zhejiang.md "浙江到Digital Ocean各机房的Ping测试 20180804")
    * [Linode](/linode/isp/zhejiang/20180804-linode-isp-zhejiang.md "浙江到Linode各机房的Ping测试 20180804")



本文最初发表于[浙江到Vultr各机房的测速数据（20180804）](https://vps123.top/pingtest/20180804-vultr-isp-zhejiang.html)
