#  北京到Linode各机房的测速数据（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![北京到Linode各机房的测速数据（20180514）](/images/thumbnails/Beijing_to_linode.png)

本文的数据视角为 **北京到[Linode](https://vps123.top/go/linode)的各机房**的PING响应值、丢包率的比较；若你在北京且打算运行[Linode](https://vps123.top/go/linode)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Linode的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514北京到Linode各机房的PING测试结果，测速点的运营商线路为电信、联通、移动，有效样本点58个，其中超时点9个。连通概况如下：大陆线路响应均值为225毫秒，最快的三个机房所在地为东京、佛利蒙、新加坡，最慢的三个为纽瓦克、伦敦、法兰克福；东京、佛利蒙、新加坡、达拉斯、亚特兰大等8处有响应超时情况；亚特兰大、东京、佛利蒙、伦敦、达拉斯丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 北京图表数据

![大陆省份北京到VPS提供商Linode各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_isp_beijing_linode_20180514.png)

### 全部运营商

北京全部运营商到Linode各机房的测速数据 [20180514] 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率 | 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
东京 | 8个 | 2个 | 98ms | 10% | 亚特兰大 | 7个 | 1个 | 234ms | 11%  
佛利蒙 | 8个 | 1个 | 198ms | 8% | 纽瓦克 | 7个 | 1个 | 259ms | 1%  
新加坡 | 7个 | 1个 | 214ms | 0 | 伦敦 | 7个 | 1个 | 260ms | 6%  
均值 | 58个 | 9个 | 225ms | 5% | 法兰克福 | 7个 | 1个 | 300ms | 4%  
达拉斯 | 7个 | 1个 | 233ms | 5% |  |  |  |  |   
  
简评：本表展示了北京的 **电信、联通、移动** 线路到Linode各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻北京，可从此表了解你常用的网络到Linode各个机房的平均响应速度以及丢包率。从表中数据可以看到， **新加坡、达拉斯** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

北京电信到Linode各机房的测速数据 [20180514] 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率 | 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
东京 | 4个 | 2个 | 93ms | 20% | 亚特兰大 | 3个 | 1个 | 225ms | 0  
佛利蒙 | 5个 | 1个 | 168ms | 0 | 纽瓦克 | 3个 | 1个 | 220ms | 0  
新加坡 | 3个 | 1个 | 249ms | 0 | 伦敦 | 3个 | 1个 | 293ms | 15%  
均值 | 27个 | 9个 | 224ms | 5% | 法兰克福 | 3个 | 1个 | 360ms | 10%  
达拉斯 | 3个 | 1个 | 203ms | 0 |  |  |  |  |   
  
简评：如果你是来自北京的 **电信** 用户，想运行Linode的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **佛利蒙、达拉斯、纽瓦克、亚特兰大、新加坡** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_1)吧！

### 联通

北京联通到Linode各机房的测速数据 [20180514] 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率 | 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
东京 | 3个 | 0 | 113ms | 10% | 亚特兰大 | 3个 | 0 | 278ms | 33%  
佛利蒙 | 3个 | 0 | 229ms | 17% | 纽瓦克 | 3个 | 0 | 323ms | 5%  
新加坡 | 3个 | 0 | 135ms | 0 | 伦敦 | 3个 | 0 | 259ms | 4%  
均值 | 24个 | 0 | 225ms | 11% | 法兰克福 | 3个 | 0 | 220ms | 3%  
达拉斯 | 3个 | 0 | 244ms | 17% |  |  |  |  |   
  
简评：如果你是来自北京的 **联通** 用户，想运行Linode的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **新加坡、法兰克福** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、佛利蒙、达拉斯** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_2)吧！

### 移动

北京移动到Linode各机房的测速数据 [20180514] 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率 | 机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
东京 | 1个 | 0 | 90ms | 0 | 亚特兰大 | 1个 | 0 | 200ms | 0  
佛利蒙 | - | - | - | - | 纽瓦克 | 1个 | 0 | 235ms | 0  
新加坡 | 1个 | 0 | 258ms | 0 | 伦敦 | 1个 | 0 | 229ms | 0  
均值 | 7个 | 0 | 226ms | 0 | 法兰克福 | 1个 | 0 | 322ms | 0  
达拉斯 | 1个 | 0 | 253ms | 0 |  |  |  |  |   
  
简评：如果你是来自北京的 **移动** 用户，想运行Linode的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **东京、亚特兰大、伦敦、纽瓦克** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_3)吧！

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180514 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180514 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期 _其他省份_ 到Linode各机房的报告： 
    * [安徽](/linode/isp/anhui/20180514-linode-isp-anhui.md "安徽到Linode各机房的Ping测试 20180514")
    * [大陆](/linode/isp/china/20180514-linode-isp-china.md "大陆到Linode各机房的Ping测试 20180514")
    * [重庆](/linode/isp/chongqing/20180514-linode-isp-chongqing.md "重庆到Linode各机房的Ping测试 20180514")
    * [福建](/linode/isp/fujian/20180514-linode-isp-fujian.md "福建到Linode各机房的Ping测试 20180514")
    * [甘肃](/linode/isp/gansu/20180514-linode-isp-gansu.md "甘肃到Linode各机房的Ping测试 20180514")
    * [广东](/linode/isp/guangdong/20180514-linode-isp-guangdong.md "广东到Linode各机房的Ping测试 20180514")
    * [广西](/linode/isp/guangxi/20180514-linode-isp-guangxi.md "广西到Linode各机房的Ping测试 20180514")
    * [贵州](/linode/isp/guizhou/20180514-linode-isp-guizhou.md "贵州到Linode各机房的Ping测试 20180514")
    * [海南](/linode/isp/hainan/20180514-linode-isp-hainan.md "海南到Linode各机房的Ping测试 20180514")
    * [河北](/linode/isp/hebei/20180514-linode-isp-hebei.md "河北到Linode各机房的Ping测试 20180514")
    * [黑龙江](/linode/isp/heilongjiang/20180514-linode-isp-heilongjiang.md "黑龙江到Linode各机房的Ping测试 20180514")
    * [河南](/linode/isp/henan/20180514-linode-isp-henan.md "河南到Linode各机房的Ping测试 20180514")
    * [湖北](/linode/isp/hubei/20180514-linode-isp-hubei.md "湖北到Linode各机房的Ping测试 20180514")
    * [湖南](/linode/isp/hunan/20180514-linode-isp-hunan.md "湖南到Linode各机房的Ping测试 20180514")
    * [内蒙古](/linode/isp/innermongolia/20180514-linode-isp-innermongolia.md "内蒙古到Linode各机房的Ping测试 20180514")
    * [江苏](/linode/isp/jiangsu/20180514-linode-isp-jiangsu.md "江苏到Linode各机房的Ping测试 20180514")
    * [江西](/linode/isp/jiangxi/20180514-linode-isp-jiangxi.md "江西到Linode各机房的Ping测试 20180514")
    * [吉林](/linode/isp/jilin/20180514-linode-isp-jilin.md "吉林到Linode各机房的Ping测试 20180514")
    * [辽宁](/linode/isp/liaoning/20180514-linode-isp-liaoning.md "辽宁到Linode各机房的Ping测试 20180514")
    * [宁夏](/linode/isp/ningxia/20180514-linode-isp-ningxia.md "宁夏到Linode各机房的Ping测试 20180514")
    * [青海](/linode/isp/qinghai/20180514-linode-isp-qinghai.md "青海到Linode各机房的Ping测试 20180514")
    * [山西](/linode/isp/shan1xi/20180514-linode-isp-shan1xi.md "山西到Linode各机房的Ping测试 20180514")
    * [陕西](/linode/isp/shan3xi/20180514-linode-isp-shan3xi.md "陕西到Linode各机房的Ping测试 20180514")
    * [山东](/linode/isp/shandong/20180514-linode-isp-shandong.md "山东到Linode各机房的Ping测试 20180514")
    * [上海](/linode/isp/shanghai/20180514-linode-isp-shanghai.md "上海到Linode各机房的Ping测试 20180514")
    * [四川](/linode/isp/sichuan/20180514-linode-isp-sichuan.md "四川到Linode各机房的Ping测试 20180514")
    * [天津](/linode/isp/tianjin/20180514-linode-isp-tianjin.md "天津到Linode各机房的Ping测试 20180514")
    * [新疆](/linode/isp/xinjiang/20180514-linode-isp-xinjiang.md "新疆到Linode各机房的Ping测试 20180514")
    * [云南](/linode/isp/yunnan/20180514-linode-isp-yunnan.md "云南到Linode各机房的Ping测试 20180514")
    * [浙江](/linode/isp/zhejiang/20180514-linode-isp-zhejiang.md "浙江到Linode各机房的Ping测试 20180514")
  * 北京到Linode各机房的 _其他近期报告_ ： 
    * [20180527](/linode/isp/beijing/20180527-linode-isp-beijing.md "北京到Linode各机房的Ping测试 20180527")
    * [20180622](/linode/isp/beijing/20180622-linode-isp-beijing.md "北京到Linode各机房的Ping测试 20180622")
    * [20180804](/linode/isp/beijing/20180804-linode-isp-beijing.md "北京到Linode各机房的Ping测试 20180804")
    * [20180918](/linode/isp/beijing/20180918-linode-isp-beijing.md "北京到Linode各机房的Ping测试 20180918")
  * 本期报告：北京到 _其他VPS提供商_ 各机房的测速报告： 
    * [Vultr](/vultr/isp/beijing/20180514-vultr-isp-beijing.md "北京到Vultr各机房的Ping测试 20180514")
    * [BandwagonHost](/bandwagon/isp/beijing/20180514-bandwagon-isp-beijing.md "北京到BandwagonHost各机房的Ping测试 20180514")
    * [Digital Ocean](/digitalocean/isp/beijing/20180514-digitalocean-isp-beijing.md "北京到Digital Ocean各机房的Ping测试 20180514")



本文最初发表于[北京到Linode各机房的测速数据（20180514）](https://vps123.top/pingtest/20180514-linode-isp-beijing.html)