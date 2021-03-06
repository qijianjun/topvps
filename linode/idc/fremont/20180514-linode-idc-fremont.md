#  多地到Linode佛利蒙[Fremont]机房的Ping测试（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode佛利蒙\[Fremont\]机房的Ping测试（20180514）](/images/thumbnails/to_linode_Fremont.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-佛利蒙机房](https://vps123.top/linode-facilities.html#fremont)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-佛利蒙机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180514-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514多地到Linode美国-佛利蒙机房的PING测试结果，连通概况如下：大陆30个省市的957个有效测试样本中，共有超时点9个；响应均值为225毫秒，最快的三地区为上海、天津、福建，最慢的三地区为甘肃、青海、新疆；浙江、山东、福建、广东、北京等6处有响应超时情况；新疆、浙江、安徽、宁夏、湖南等25处丢包率较高。海外17个国家地区的77个有效测试样本中，无超时点；响应均值为177毫秒，最快的三地区为美国、加拿大、日本，最慢的三地区为马来西亚、印度尼西亚、南非。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_idc_linode_usa-fremont_20180514_mainland.png)

**大陆各省份到Linode美国-佛利蒙机房的测速数据 [20180514]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 7个 | 0 | 171ms | 2.9%  
天津 | 5个 | 0 | 176ms | 2.2%  
福建 | 36个 | 1个 | 197ms | 4.3%  
广东 | 78个 | 1个 | 199ms | 6.9%  
北京 | 8个 | 1个 | 201ms | 8.9%  
安徽 | 42个 | 0 | 203ms | 15.4%  
江苏 | 59个 | 1个 | 204ms | 14.6%  
海南 | 10个 | 0 | 204ms | 5.2%  
广西 | 38个 | 0 | 206ms | 8.9%  
吉林 | 14个 | 0 | 208ms | 4.8%  
重庆 | 15个 | 0 | 208ms | 5.0%  
贵州 | 26个 | 0 | 209ms | 7.9%  
湖北 | 45个 | 0 | 218ms | 5.6%  
河北 | 31个 | 0 | 219ms | 6.7%  
江西 | 26个 | 0 | 221ms | 12.4%  
湖南 | 46个 | 0 | 222ms | 15.0%  
陕西 | 30个 | 0 | 225ms | 9.1%  
均值 | 957个 | 9个 | 225ms | 10.7%  
云南 | 23个 | 0 | 226ms | 10.0%  
四川 | 49个 | 0 | 229ms | 5.5%  
河南 | 59个 | 0 | 235ms | 14.5%  
辽宁 | 39个 | 0 | 235ms | 10.8%  
宁夏 | 12个 | 0 | 238ms | 15.3%  
浙江 | 47个 | 3个 | 239ms | 15.9%  
山东 | 49个 | 2个 | 242ms | 13.4%  
山西 | 36个 | 0 | 248ms | 12.2%  
黑龙江 | 38个 | 0 | 250ms | 12.4%  
内蒙古 | 34个 | 0 | 252ms | 11.1%  
甘肃 | 22个 | 0 | 261ms | 14.2%  
青海 | 4个 | 0 | 262ms | 13.3%  
新疆 | 29个 | 0 | 285ms | 16.0%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有957个，其中超时点9个，平均响应时间为225毫秒，丢包率为10%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的4个，在200-300毫秒间的26个；  
超时点较多的省份：北京；  
丢包率较高的省份：安徽、江苏、江西、湖南、云南、河南、辽宁、宁夏、浙江、山东、山西、黑龙江、内蒙古、甘肃、青海、新疆；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_idc_linode_usa-fremont_20180514_overseas.png)

**海外线路到Linode美国-佛利蒙机房的测速数据 [20180514]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
美国 | 18个 | 0 | 17ms | 1.7%  
加拿大 | 3个 | 0 | 81ms | 1.0%  
日本 | 2个 | 0 | 127ms | 0  
韩国 | 13个 | 0 | 138ms | 0  
法国 | 2个 | 0 | 150ms | 0  
英国 | 2个 | 0 | 152ms | 1.5%  
德国 | 2个 | 0 | 159ms | 0  
澳大利亚 | 2个 | 0 | 172ms | 0  
台湾 | 1个 | 0 | 173ms | -  
新加坡 | 6个 | 0 | 176ms | 0  
均值 | 77个 | 0 | 177ms | 0.3%  
巴西 | 1个 | 0 | 181ms | 0  
香港 | 18个 | 0 | 185ms | 0  
菲律宾 | 1个 | 0 | 188ms | 0  
俄罗斯 | 1个 | 0 | 235ms | 0  
马来西亚 | 3个 | 0 | 242ms | 0.7%  
印度尼西亚 | 1个 | 0 | 303ms | 0  
南非 | 1个 | 0 | 341ms | 0  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有77个，其中超时点0个，平均响应时间为177毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的1个，在100-200毫秒间的11个，在200-300毫秒间的2个，超过300毫秒的2个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180514 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180514 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180514-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180514")
    * [达拉斯](/linode/idc/dallas/20180514-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180514")
    * [法兰克福](/linode/idc/frankfurt/20180514-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180514")
    * [伦敦](/linode/idc/london/20180514-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180514")
    * [纽瓦克](/linode/idc/newark/20180514-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180514")
    * [新加坡](/linode/idc/singapore/20180514-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180514")
    * [东京](/linode/idc/tokyo/20180514-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180514")
  * 到Linode佛利蒙机房的 _其他近期报告_ ： 
    * [20180527](/linode/idc/fremont/20180527-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180527")
    * [20180622](/linode/idc/fremont/20180622-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180622")
    * [20180804](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [20180918](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
  * 本期报告：在佛利蒙部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/fremont/20180514-bwg-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180514")



本文最初发表于[多地到Linode佛利蒙[Fremont]机房的Ping测试（20180514）](https://vps123.top/pingtest/20180514-linode-idc-fremont.html)
