#  多地到Linode达拉斯[Dallas]机房的Ping测试（20180804） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode达拉斯\[Dallas\]机房的Ping测试（20180804）](/images/thumbnails/to_linode_Dallas.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-达拉斯机房](https://vps123.top/linode-facilities.html#dallas)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-达拉斯机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180804-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的5453个有效测试样本中，共有超时点39个；响应均值为259毫秒，最快的三地区为海南、广东、广西，最慢的三地区为青海、新疆、西藏；浙江、江西、江苏、山西、上海等6处有响应超时情况；天津、上海、西藏、内蒙古、辽宁等9处丢包率较高。海外19个国家地区的237个有效测试样本中，无超时点；响应均值为175毫秒，最快的三地区为荷兰、加拿大、美国，最慢的三地区为印度尼西亚、马来西亚、菲律宾；菲律宾丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于达拉斯\[Dallas\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/linode_20180804/plot_idc_linode_usa-dallas_20180804_mainland.png)

**大陆各省份到Linode美国-达拉斯机房的测速数据 [20180804]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
海南 | 52个 | 0 | 232ms | 0.6%  
广东 | 441个 | 0 | 234ms | 2.0%  
广西 | 243个 | 0 | 240ms | 1.3%  
湖南 | 265个 | 0 | 242ms | 2.3%  
山东 | 370个 | 0 | 243ms | 2.6%  
江苏 | 337个 | 6个 | 243ms | 3.3%  
浙江 | 246个 | 13个 | 245ms | 3.4%  
北京 | 32个 | 0 | 247ms | 3.7%  
湖北 | 213个 | 0 | 250ms | 2.7%  
河北 | 248个 | 0 | 251ms | 4.6%  
江西 | 139个 | 7个 | 253ms | 2.1%  
重庆 | 37个 | 0 | 256ms | 3.0%  
四川 | 289个 | 0 | 258ms | 1.3%  
均值 | 5453个 | 39个 | 259ms | 4.0%  
贵州 | 155个 | 0 | 262ms | 4.5%  
吉林 | 96个 | 0 | 262ms | 4.2%  
福建 | 172个 | 0 | 263ms | 4.8%  
安徽 | 239个 | 0 | 265ms | 6.2%  
山西 | 197个 | 6个 | 265ms | 5.8%  
辽宁 | 230个 | 3个 | 265ms | 7.2%  
宁夏 | 32个 | 0 | 268ms | 4.1%  
云南 | 135个 | 0 | 271ms | 6.3%  
甘肃 | 112个 | 0 | 271ms | 3.5%  
天津 | 20个 | 0 | 272ms | 15.0%  
陕西 | 163个 | 0 | 272ms | 3.0%  
内蒙古 | 224个 | 0 | 273ms | 7.8%  
上海 | 28个 | 4个 | 273ms | 8.9%  
河南 | 363个 | 0 | 286ms | 6.6%  
黑龙江 | 196个 | 0 | 289ms | 5.0%  
青海 | 16个 | 0 | 294ms | 2.3%  
新疆 | 155个 | 0 | 302ms | 3.2%  
西藏 | 8个 | 0 | 470ms | 8.2%  
  
**简评：** 如果你考虑在Linode的达拉斯[Dallas]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于达拉斯[Dallas]的机房的连通状况。到此机房的ping监测点共有5453个，其中超时点39个，平均响应时间为259毫秒，丢包率为4%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的29个，超过300毫秒的2个；  
超时点较多的省份：上海；  
丢包率较高的省份：天津；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于达拉斯\[Dallas\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/linode_20180804/plot_idc_linode_usa-dallas_20180804_overseas.png)

**海外线路到Linode美国-达拉斯机房的测速数据 [20180804]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
荷兰 | 3个 | 0 | 25ms | 0  
加拿大 | 15个 | 0 | 47ms | 0  
美国 | 48个 | 0 | 71ms | 0  
意大利 | 3个 | 0 | 107ms | -  
巴西 | 3个 | 0 | 108ms | 0  
英国 | 6个 | 0 | 137ms | 0  
德国 | 9个 | 0 | 152ms | 0  
俄罗斯 | 3个 | 0 | 157ms | -  
日本 | 6个 | 0 | 167ms | 1.0%  
韩国 | 21个 | 0 | 168ms | 0  
新加坡 | 15个 | 0 | 175ms | 0  
均值 | 237个 | 0 | 175ms | 1.0%  
香港 | 66个 | 0 | 180ms | 1.4%  
法国 | 3个 | 0 | 197ms | 0  
南非 | 6个 | 0 | 198ms | 0.5%  
台湾 | 3个 | 0 | 203ms | 0  
澳大利亚 | 6个 | 0 | 203ms | 0  
印度尼西亚 | 6个 | 0 | 245ms | 0  
马来西亚 | 12个 | 0 | 251ms | 1.5%  
菲律宾 | 3个 | 0 | 530ms | 13.3%  
  
**简评：** 如果你考虑在Linode的达拉斯[Dallas]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于达拉斯[Dallas]的机房的连通状况。到此机房的ping监测点共有237个，其中超时点0个，平均响应时间为175毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在50-100毫秒间的1个，在100-200毫秒间的11个，在200-300毫秒间的4个，超过300毫秒的1个；  
丢包率较高的国家/地区：菲律宾；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180804) 
    * [全部](https://vps123.top/pingtests/20180804 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180804 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180804 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180804 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180804-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180804")
    * [法兰克福](/linode/idc/frankfurt/20180804-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180804")
    * [佛利蒙](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [伦敦](/linode/idc/london/20180804-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180804")
    * [纽瓦克](/linode/idc/newark/20180804-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180804")
    * [新加坡](/linode/idc/singapore/20180804-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180804")
    * [东京](/linode/idc/tokyo/20180804-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180804")
  * 到Linode达拉斯机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/dallas/20180514-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180514")
    * [20180527](/linode/idc/dallas/20180527-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180527")
    * [20180622](/linode/idc/dallas/20180622-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180622")
    * [20180918](/linode/idc/dallas/20180918-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180918")
  * 本期报告：在达拉斯部署机房的 _其他VPS提供商_ ： 
    * [Vultr](/vultr/idc/dallas/20180804-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180804")



本文最初发表于[多地到Linode达拉斯[Dallas]机房的Ping测试（20180804）](https://vps123.top/pingtest/20180804-linode-idc-dallas.html)
