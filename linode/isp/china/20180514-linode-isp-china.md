#  中国大陆到Linode各机房的测速数据（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![中国大陆到Linode各机房的测速数据（20180514）](/images/thumbnails/China_to_linode.png)

本文的数据视角为 **中国大陆各省份/运营商到[Linode](https://vps123.top/go/linode)的各机房**的PING响应值、丢包率的比较；若你在大陆，打算在[Linode](https://vps123.top/go/linode)的机房架设代理服务器或进行云计算，后面的图表数据可以帮你形成评估Linode各机房的大概印象，排除一些数据较差的机房，锁定一些潜在的目标机房。要确定最适合你的机房，请通过本文结尾的链接，查看你所在省份的数据，它们更准确、针对性更强；你也可以通过文末链接查看其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514中国大陆到Linode各机房的PING测试结果，测速点的运营商线路为电信、联通、移动，有效样本点7716个，其中超时点106个。连通概况如下：大陆线路响应均值为245毫秒，最快的三个机房所在地为东京、新加坡、佛利蒙，最慢的三个为纽瓦克、法兰克福、伦敦；法兰克福、东京、新加坡、达拉斯、亚特兰大等8处有响应超时情况；亚特兰大、佛利蒙、达拉斯、伦敦、法兰克福等6处丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆图表数据

![大陆省份大陆到VPS提供商Linode各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_isp_china_linode_20180514.png)

### 全部运营商

**大陆全部运营商到Linode各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 968个 | 15个 | 121ms | 5%  
新加坡 | 956个 | 14个 | 162ms | 3%  
佛利蒙 | 957个 | 9个 | 225ms | 10%  
均值 | 7716个 | 106个 | 245ms | 8%  
达拉斯 | 975个 | 14个 | 260ms | 10%  
亚特兰大 | 951个 | 14个 | 283ms | 15%  
纽瓦克 | 984个 | 12个 | 290ms | 3%  
法兰克福 | 949个 | 16个 | 290ms | 6%  
伦敦 | 976个 | 12个 | 328ms | 8%  
  
**简评：** 本表展示了大陆的 **电信、联通、移动** 线路到Linode各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；籍此我们可以快速了解，整个大陆地区到Linode各个机房的平均响应速度以及丢包率：如果某机房的响应值、丢包率较高，那么大概率各省到此机房的网络也不理想，用来建站是不大合适的；而如果此处的响应值、丢包率还不错，我们可再具体了解一个省份的数据。  
在这里， **东京、新加坡** 的响应速度小于250ms，且丢包率在5%以内，值得关注。如果你主要关心某运营商的网络概况，后面几个表格的数据更有参考价值。  
如果你打算将VPS用作科学上网、云存储、远程任务、游戏服务器等用途，请 **关注你所在的省份** 到Linode各机房的测速数据，它们可以给你更有益的参考。

### 电信

**大陆电信到Linode各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 405个 | 10个 | 131ms | 8%  
新加坡 | 394个 | 9个 | 220ms | 6%  
佛利蒙 | 395个 | 4个 | 196ms | 3%  
均值 | 3234个 | 60个 | 247ms | 5%  
达拉斯 | 411个 | 6个 | 262ms | 5%  
亚特兰大 | 404个 | 9个 | 282ms | 7%  
纽瓦克 | 413个 | 4个 | 283ms | 2%  
法兰克福 | 403个 | 10个 | 272ms | 3%  
伦敦 | 409个 | 8个 | 334ms | 7%  
  
**简评：** 如果你关注电信的网络到Linode各机房的连通性，此表数据提供了一个不错的概览， **佛利蒙** 的整体的连通速度、丢包率都比较不错， **东京、新加坡** 也值得关注，如果要选择一个机房用于科学上网、云存储、远程任务、游戏服务器等用途，请查看你所在的省份的更具体的测评。如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_1)吧！

### 联通

**大陆联通到Linode各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 277个 | 2个 | 107ms | 2%  
新加坡 | 279个 | 3个 | 138ms | 1%  
佛利蒙 | 273个 | 4个 | 203ms | 5%  
均值 | 2213个 | 31个 | 233ms | 3%  
达拉斯 | 281个 | 7个 | 239ms | 5%  
亚特兰大 | 266个 | 3个 | 249ms | 6%  
纽瓦克 | 281个 | 5个 | 278ms | 2%  
法兰克福 | 271个 | 4个 | 325ms | 2%  
伦敦 | 285个 | 3个 | 321ms | 3%  
  
**简评：** 如果你关注联通的网络到Linode各机房的连通性，此表数据提供了一个不错的概览， **东京、新加坡、佛利蒙、达拉斯** 的整体的连通速度、丢包率都比较不错， **亚特兰大** 也值得关注，如果要选择一个机房用于科学上网、云存储、远程任务、游戏服务器等用途，请查看你所在的省份的更具体的测评。如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_2)吧！

### 移动

**大陆移动到Linode各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 286个 | 3个 | 116ms | 3%  
新加坡 | 283个 | 2个 | 113ms | 1%  
佛利蒙 | 289个 | 1个 | 278ms | 24%  
均值 | 2269个 | 15个 | 254ms | 15%  
达拉斯 | 283个 | 1个 | 279ms | 19%  
亚特兰大 | 281个 | 2个 | 315ms | 35%  
纽瓦克 | 290个 | 3个 | 309ms | 6%  
法兰克福 | 275个 | 2个 | 285ms | 13%  
伦敦 | 282个 | 1个 | 329ms | 16%  
  
**简评：** 如果你关注移动的网络到Linode各机房的连通性，此表数据提供了一个不错的概览， **新加坡、东京** 的整体的连通速度、丢包率都比较不错，如果要选择一个机房用于科学上网、云存储、远程任务、游戏服务器等用途，请查看你所在的省份的更具体的测评。如果看好了，就果断[去让机器跑起来](https://vps123.top/go/linode/_3)吧！

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180514 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180514 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期 _其他省份_ 到Linode各机房的报告： 
    * [安徽](/linode/isp/anhui/20180514-linode-isp-anhui.md "安徽到Linode各机房的Ping测试 20180514")
    * [北京](/linode/isp/beijing/20180514-linode-isp-beijing.md "北京到Linode各机房的Ping测试 20180514")
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
  * 大陆到Linode各机房的 _其他近期报告_ ： 
    * [20180527](/linode/isp/china/20180527-linode-isp-china.md "大陆到Linode各机房的Ping测试 20180527")
    * [20180622](/linode/isp/china/20180622-linode-isp-china.md "大陆到Linode各机房的Ping测试 20180622")
    * [20180804](/linode/isp/china/20180804-linode-isp-china.md "大陆到Linode各机房的Ping测试 20180804")
    * [20180918](/linode/isp/china/20180918-linode-isp-china.md "大陆到Linode各机房的Ping测试 20180918")
  * 本期报告：大陆到 _其他VPS提供商_ 各机房的测速报告： 
    * [Vultr](/vultr/isp/china/20180514-vultr-isp-china.md "大陆到Vultr各机房的Ping测试 20180514")
    * [BandwagonHost](/bandwagon/isp/china/20180514-bandwagon-isp-china.md "大陆到BandwagonHost各机房的Ping测试 20180514")
    * [Digital Ocean](/digitalocean/isp/china/20180514-digitalocean-isp-china.md "大陆到Digital Ocean各机房的Ping测试 20180514")



本文最初发表于[中国大陆到Linode各机房的测速数据（20180514）](https://vps123.top/pingtest/20180514-linode-isp-china.html)
