#  安徽到Vultr各机房的测速数据（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![安徽到Vultr各机房的测速数据（20180527）](/images/thumbnails/Anhui_to_vultr.png)

本文的数据视角为 **安徽到[Vultr](https://vps123.top/go/vultr)的各机房**的PING响应值、丢包率的比较；若你在安徽且打算运行[Vultr](https://vps123.top/go/vultr)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Vultr的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

测速点的运营商线路为电信、联通、移动，有效样本点573个，其中超时点5个。连通概况如下：大陆线路响应均值为263毫秒，最快的三个机房所在地为东京、硅谷、新加坡，最慢的三个为阿姆斯特丹、悉尼、伦敦；新加坡、洛杉矶、西雅图、迈阿密、法兰克福有响应超时情况；达拉斯、悉尼、亚特兰大、东京、新加坡等11处丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 安徽图表数据

![大陆省份安徽到VPS提供商Vultr各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/vultr_20180527/plot_isp_anhui_vultr_20180527.png)

### 全部运营商

**安徽全部运营商到Vultr各机房的测速数据 [20180527]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 36个 | 0 | 166ms | 13%  
硅谷 | 38个 | 0 | 206ms | 9%  
新加坡 | 38个 | 1个 | 208ms | 12%  
洛杉矶 | 39个 | 1个 | 224ms | 2%  
西雅图 | 38个 | 1个 | 252ms | 6%  
均值 | 573个 | 5个 | 263ms | 8%  
迈阿密 | 39个 | 1个 | 269ms | 9%  
法兰克福 | 38个 | 1个 | 280ms | 1%  
芝加哥 | 39个 | 0 | 281ms | 6%  
巴黎 | 38个 | 0 | 284ms | 2%  
达拉斯 | 39个 | 0 | 287ms | 15%  
新泽西 | 38个 | 0 | 289ms | 5%  
亚特兰大 | 38个 | 0 | 292ms | 13%  
阿姆斯特丹 | 39个 | 0 | 306ms | 1%  
悉尼 | 38个 | 0 | 308ms | 14%  
伦敦 | 38个 | 0 | 321ms | 5%  
  
**简评：** 本表展示了安徽的 **电信、联通、移动** 线路到Vultr各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻安徽，可从此表了解你常用的网络到Vultr各个机房的平均响应速度以及丢包率。从表中数据可以看到， **洛杉矶** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

**安徽电信到Vultr各机房的测速数据 [20180527]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 16个 | 0 | 186ms | 25%  
硅谷 | 17个 | 0 | 201ms | 1%  
新加坡 | 17个 | 0 | 250ms | 22%  
洛杉矶 | 18个 | 1个 | 228ms | 5%  
西雅图 | 17个 | 0 | 259ms | 3%  
均值 | 259个 | 2个 | 258ms | 6%  
迈阿密 | 18个 | 0 | 258ms | 2%  
法兰克福 | 17个 | 1个 | 236ms | 0  
芝加哥 | 18个 | 0 | 301ms | 5%  
巴黎 | 17个 | 0 | 244ms | 0  
达拉斯 | 18个 | 0 | 273ms | 3%  
新泽西 | 17个 | 0 | 318ms | 3%  
亚特兰大 | 17个 | 0 | 266ms | 5%  
阿姆斯特丹 | 18个 | 0 | 244ms | 0  
悉尼 | 17个 | 0 | 340ms | 26%  
伦敦 | 17个 | 0 | 275ms | 1%  
  
**简评：** 如果你是来自安徽的 **电信** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **硅谷、洛杉矶、法兰克福、巴黎、阿姆斯特丹** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、新加坡** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_1)吧！

### 联通

**安徽联通到Vultr各机房的测速数据 [20180527]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 7个 | 0 | 186ms | 10%  
硅谷 | 7个 | 0 | 194ms | 14%  
新加坡 | 7个 | 1个 | 254ms | 12%  
洛杉矶 | 7个 | 0 | 226ms | 0  
西雅图 | 7个 | 1个 | 229ms | 14%  
均值 | 105个 | 3个 | 265ms | 8%  
迈阿密 | 7个 | 1个 | 266ms | 17%  
法兰克福 | 7个 | 0 | 315ms | 2%  
芝加哥 | 7个 | 0 | 271ms | 12%  
巴黎 | 7个 | 0 | 321ms | 4%  
达拉斯 | 7个 | 0 | 256ms | 8%  
新泽西 | 7个 | 0 | 282ms | 10%  
亚特兰大 | 7个 | 0 | 269ms | 6%  
阿姆斯特丹 | 7个 | 0 | 333ms | 1%  
悉尼 | 7个 | 0 | 319ms | 14%  
伦敦 | 7个 | 0 | 328ms | 4%  
  
**简评：** 如果你是来自安徽的 **联通** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **洛杉矶** 的机房；从数据看，你的网络到这里的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、硅谷、西雅图** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_2)吧！

### 移动

**安徽移动到Vultr各机房的测速数据 [20180527]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 13个 | 0 | 128ms | 2%  
硅谷 | 14个 | 0 | 225ms | 10%  
新加坡 | 14个 | 0 | 122ms | 2%  
洛杉矶 | 14个 | 0 | 217ms | 2%  
西雅图 | 14个 | 0 | 269ms | 3%  
均值 | 209个 | 0 | 267ms | 8%  
迈阿密 | 14个 | 0 | 283ms | 9%  
法兰克福 | 14个 | 0 | 288ms | 2%  
芝加哥 | 14个 | 0 | 270ms | 1%  
巴黎 | 14个 | 0 | 288ms | 2%  
达拉斯 | 14个 | 0 | 332ms | 33%  
新泽西 | 14个 | 0 | 267ms | 2%  
亚特兰大 | 14个 | 0 | 341ms | 30%  
阿姆斯特丹 | 14个 | 0 | 341ms | 2%  
悉尼 | 14个 | 0 | 266ms | 3%  
伦敦 | 14个 | 0 | 359ms | 10%  
  
**简评：** 如果你是来自安徽的 **移动** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **新加坡、东京、洛杉矶** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **硅谷** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_3)吧！

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180527) 
    * [全部](https://vps123.top/pingtests/20180527 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180527 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180527 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180527 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期 _其他省份_ 到Vultr各机房的报告： 
    * [北京](/vultr/isp/beijing/20180527-vultr-isp-beijing.md "北京到Vultr各机房的Ping测试 20180527")
    * [大陆](/vultr/isp/china/20180527-vultr-isp-china.md "大陆到Vultr各机房的Ping测试 20180527")
    * [重庆](/vultr/isp/chongqing/20180527-vultr-isp-chongqing.md "重庆到Vultr各机房的Ping测试 20180527")
    * [福建](/vultr/isp/fujian/20180527-vultr-isp-fujian.md "福建到Vultr各机房的Ping测试 20180527")
    * [甘肃](/vultr/isp/gansu/20180527-vultr-isp-gansu.md "甘肃到Vultr各机房的Ping测试 20180527")
    * [广东](/vultr/isp/guangdong/20180527-vultr-isp-guangdong.md "广东到Vultr各机房的Ping测试 20180527")
    * [广西](/vultr/isp/guangxi/20180527-vultr-isp-guangxi.md "广西到Vultr各机房的Ping测试 20180527")
    * [贵州](/vultr/isp/guizhou/20180527-vultr-isp-guizhou.md "贵州到Vultr各机房的Ping测试 20180527")
    * [海南](/vultr/isp/hainan/20180527-vultr-isp-hainan.md "海南到Vultr各机房的Ping测试 20180527")
    * [河北](/vultr/isp/hebei/20180527-vultr-isp-hebei.md "河北到Vultr各机房的Ping测试 20180527")
    * [黑龙江](/vultr/isp/heilongjiang/20180527-vultr-isp-heilongjiang.md "黑龙江到Vultr各机房的Ping测试 20180527")
    * [河南](/vultr/isp/henan/20180527-vultr-isp-henan.md "河南到Vultr各机房的Ping测试 20180527")
    * [湖北](/vultr/isp/hubei/20180527-vultr-isp-hubei.md "湖北到Vultr各机房的Ping测试 20180527")
    * [湖南](/vultr/isp/hunan/20180527-vultr-isp-hunan.md "湖南到Vultr各机房的Ping测试 20180527")
    * [内蒙古](/vultr/isp/innermongolia/20180527-vultr-isp-innermongolia.md "内蒙古到Vultr各机房的Ping测试 20180527")
    * [江苏](/vultr/isp/jiangsu/20180527-vultr-isp-jiangsu.md "江苏到Vultr各机房的Ping测试 20180527")
    * [江西](/vultr/isp/jiangxi/20180527-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180527")
    * [吉林](/vultr/isp/jilin/20180527-vultr-isp-jilin.md "吉林到Vultr各机房的Ping测试 20180527")
    * [辽宁](/vultr/isp/liaoning/20180527-vultr-isp-liaoning.md "辽宁到Vultr各机房的Ping测试 20180527")
    * [宁夏](/vultr/isp/ningxia/20180527-vultr-isp-ningxia.md "宁夏到Vultr各机房的Ping测试 20180527")
    * [青海](/vultr/isp/qinghai/20180527-vultr-isp-qinghai.md "青海到Vultr各机房的Ping测试 20180527")
    * [山西](/vultr/isp/shan1xi/20180527-vultr-isp-shan1xi.md "山西到Vultr各机房的Ping测试 20180527")
    * [陕西](/vultr/isp/shan3xi/20180527-vultr-isp-shan3xi.md "陕西到Vultr各机房的Ping测试 20180527")
    * [山东](/vultr/isp/shandong/20180527-vultr-isp-shandong.md "山东到Vultr各机房的Ping测试 20180527")
    * [上海](/vultr/isp/shanghai/20180527-vultr-isp-shanghai.md "上海到Vultr各机房的Ping测试 20180527")
    * [四川](/vultr/isp/sichuan/20180527-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180527")
    * [天津](/vultr/isp/tianjin/20180527-vultr-isp-tianjin.md "天津到Vultr各机房的Ping测试 20180527")
    * [新疆](/vultr/isp/xinjiang/20180527-vultr-isp-xinjiang.md "新疆到Vultr各机房的Ping测试 20180527")
    * [云南](/vultr/isp/yunnan/20180527-vultr-isp-yunnan.md "云南到Vultr各机房的Ping测试 20180527")
    * [浙江](/vultr/isp/zhejiang/20180527-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180527")
  * 安徽到Vultr各机房的 _其他近期报告_ ： 
    * [20180514](/vultr/isp/anhui/20180514-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180514")
    * [20180622](/vultr/isp/anhui/20180622-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180622")
    * [20180804](/vultr/isp/anhui/20180804-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180804")
    * [20180918](/vultr/isp/anhui/20180918-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180918")
  * 本期报告：安徽到 _其他VPS提供商_ 各机房的测速报告： 
    * [BandwagonHost](/bandwagon/isp/anhui/20180527-bandwagon-isp-anhui.md "安徽到BandwagonHost各机房的Ping测试 20180527")
    * [Digital Ocean](/digitalocean/isp/anhui/20180527-digitalocean-isp-anhui.md "安徽到Digital Ocean各机房的Ping测试 20180527")
    * [Linode](/linode/isp/anhui/20180527-linode-isp-anhui.md "安徽到Linode各机房的Ping测试 20180527")



本文最初发表于[安徽到Vultr各机房的测速数据（20180527）](https://vps123.top/pingtest/20180527-vultr-isp-anhui.html)
