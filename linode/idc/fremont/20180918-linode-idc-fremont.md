#  多地到Linode佛利蒙[Fremont]机房的Ping测试（20180918） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode佛利蒙\[Fremont\]机房的Ping测试（20180918）](/images/thumbnails/to_linode_Fremont.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-佛利蒙机房](https://vps123.top/linode-facilities.html#fremont)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-佛利蒙机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180918-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180918多地到Linode美国-佛利蒙机房的PING测试结果，连通概况如下：大陆31个省市的1399个有效测试样本中，共有超时点14个；响应均值为209毫秒，最快的三地区为北京、福建、安徽，最慢的三地区为黑龙江、青海、西藏；江苏、浙江、广东、福建、江西等7处有响应超时情况；河南、吉林、青海、辽宁、山东等13处丢包率较高。海外17个国家地区的71个有效测试样本中，无超时点；响应均值为176毫秒，最快的三地区为台湾、美国、加拿大，最慢的三地区为马来西亚、赞比亚、菲律宾；菲律宾、赞比亚丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_usa-fremont_20180918_mainland.png)

**大陆各省份到Linode美国-佛利蒙机房的测速数据 [20180918]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
北京 | 7个 | 0 | 180ms | 4.4%  
福建 | 42个 | 1个 | 185ms | 2.6%  
安徽 | 71个 | 0 | 185ms | 2.7%  
广东 | 117个 | 2个 | 187ms | 4.0%  
江苏 | 90个 | 5个 | 188ms | 4.7%  
广西 | 61个 | 0 | 189ms | 3.9%  
宁夏 | 7个 | 0 | 191ms | 0  
江西 | 41个 | 1个 | 193ms | 2.9%  
海南 | 13个 | 0 | 199ms | 6.6%  
浙江 | 66个 | 3个 | 201ms | 3.5%  
天津 | 6个 | 0 | 201ms | 0.2%  
重庆 | 8个 | 0 | 201ms | 5.3%  
河北 | 55个 | 0 | 202ms | 6.4%  
湖南 | 69个 | 0 | 202ms | 3.6%  
湖北 | 52个 | 0 | 208ms | 1.9%  
上海 | 7个 | 0 | 209ms | 9.5%  
均值 | 1399个 | 14个 | 209ms | 6.1%  
辽宁 | 57个 | 0 | 210ms | 12.9%  
贵州 | 42个 | 0 | 211ms | 3.3%  
陕西 | 45个 | 0 | 212ms | 4.0%  
山东 | 94个 | 0 | 214ms | 10.3%  
内蒙古 | 54个 | 0 | 217ms | 8.3%  
四川 | 70个 | 1个 | 218ms | 4.1%  
甘肃 | 33个 | 0 | 218ms | 0.5%  
云南 | 29个 | 0 | 221ms | 3.3%  
山西 | 55个 | 1个 | 225ms | 9.5%  
河南 | 88个 | 0 | 230ms | 14.4%  
吉林 | 23个 | 0 | 242ms | 14.2%  
新疆 | 33个 | 0 | 246ms | 7.4%  
黑龙江 | 54个 | 0 | 249ms | 7.0%  
青海 | 6个 | 0 | 277ms | 13.2%  
西藏 | 4个 | 0 | 306ms | 3.3%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有1399个，其中超时点14个，平均响应时间为209毫秒，丢包率为6%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的9个，在200-300毫秒间的21个，超过300毫秒的1个；  
丢包率较高的省份：辽宁、山东、河南、吉林、青海；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_usa-fremont_20180918_overseas.png)

**海外线路到Linode美国-佛利蒙机房的测速数据 [20180918]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
台湾 | 1个 | 0 | 22ms | 0  
美国 | 12个 | 0 | 41ms | 0.2%  
加拿大 | 3个 | 0 | 73ms | 0  
韩国 | 10个 | 0 | 125ms | 0  
新加坡 | 5个 | 0 | 135ms | 0  
意大利 | 1个 | 0 | 140ms | -  
日本 | 2个 | 0 | 155ms | 0  
俄罗斯 | 2个 | 0 | 155ms | 0  
德国 | 3个 | 0 | 165ms | 0  
香港 | 17个 | 0 | 166ms | 0  
均值 | 71个 | 0 | 176ms | 2.8%  
澳大利亚 | 2个 | 0 | 184ms | 0  
越南 | 2个 | 0 | 207ms | 0.5%  
印度尼西亚 | 1个 | 0 | 210ms | 0  
荷兰 | 1个 | 0 | 232ms | 0  
马来西亚 | 6个 | 0 | 240ms | 0  
赞比亚 | 1个 | 0 | 351ms | 13.3%  
菲律宾 | 2个 | 0 | 396ms | 30.5%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有71个，其中超时点0个，平均响应时间为176毫秒，丢包率为2%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在50-100毫秒间的1个，在100-200毫秒间的8个，在200-300毫秒间的4个，超过300毫秒的2个；  
丢包率较高的国家/地区：赞比亚、菲律宾；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180918) 
    * [全部](https://vps123.top/pingtests/20180918 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180918 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180918 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180918 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180918-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180918")
    * [达拉斯](/linode/idc/dallas/20180918-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180918")
    * [法兰克福](/linode/idc/frankfurt/20180918-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180918")
    * [伦敦](/linode/idc/london/20180918-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180918")
    * [纽瓦克](/linode/idc/newark/20180918-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180918")
    * [新加坡](/linode/idc/singapore/20180918-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180918")
    * [东京](/linode/idc/tokyo/20180918-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180918")
  * 到Linode佛利蒙机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/fremont/20180514-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180514")
    * [20180527](/linode/idc/fremont/20180527-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180527")
    * [20180622](/linode/idc/fremont/20180622-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180622")
    * [20180804](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
  * 本期报告：在佛利蒙部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/fremont/20180918-bwg-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180918")



本文最初发表于[多地到Linode佛利蒙[Fremont]机房的Ping测试（20180918）](https://vps123.top/pingtest/20180918-linode-idc-fremont.html)
