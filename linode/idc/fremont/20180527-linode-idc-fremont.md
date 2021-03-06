#  多地到Linode佛利蒙[Fremont]机房的Ping测试（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode佛利蒙\[Fremont\]机房的Ping测试（20180527）](/images/thumbnails/to_linode_Fremont.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-佛利蒙机房](https://vps123.top/linode-facilities.html#fremont)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-佛利蒙机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180527-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆30个省市的973个有效测试样本中，共有超时点9个；响应均值为197毫秒，最快的三地区为天津、广东、上海，最慢的三地区为甘肃、青海、新疆；山东、北京、江苏、河南、山西等8处有响应超时情况；青海、天津、湖南、山西、内蒙古等11处丢包率较高。海外21个国家地区的88个有效测试样本中，无超时点；响应均值为183毫秒，最快的三地区为美国、加拿大、日本，最慢的三地区为柬埔寨、菲律宾、南非。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/linode_20180527/plot_idc_linode_usa-fremont_20180527_mainland.png)

**大陆各省份到Linode美国-佛利蒙机房的测速数据 [20180527]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
天津 | 5个 | 0 | 177ms | 7.2%  
广东 | 79个 | 0 | 179ms | 2.6%  
上海 | 8个 | 0 | 179ms | 0  
北京 | 8个 | 1个 | 182ms | 4.7%  
福建 | 36个 | 0 | 183ms | 3.8%  
江苏 | 62个 | 1个 | 187ms | 4.9%  
广西 | 39个 | 0 | 187ms | 5.7%  
河北 | 36个 | 0 | 190ms | 5.7%  
海南 | 14个 | 0 | 191ms | 5.1%  
河南 | 56个 | 1个 | 192ms | 5.2%  
山东 | 54个 | 2个 | 192ms | 4.8%  
山西 | 37个 | 1个 | 192ms | 6.3%  
浙江 | 48个 | 0 | 193ms | 4.3%  
重庆 | 14个 | 1个 | 193ms | 2.6%  
江西 | 24个 | 0 | 196ms | 3.4%  
安徽 | 37个 | 0 | 196ms | 2.1%  
湖南 | 44个 | 1个 | 197ms | 7.2%  
辽宁 | 40个 | 0 | 197ms | 6.2%  
均值 | 973个 | 9个 | 197ms | 4.5%  
贵州 | 26个 | 0 | 198ms | 4.1%  
陕西 | 33个 | 0 | 199ms | 4.4%  
吉林 | 19个 | 0 | 200ms | 4.5%  
内蒙古 | 34个 | 0 | 202ms | 6.3%  
宁夏 | 12个 | 0 | 203ms | 3.4%  
云南 | 22个 | 0 | 205ms | 2.0%  
湖北 | 44个 | 0 | 206ms | 2.4%  
四川 | 47个 | 0 | 207ms | 3.9%  
黑龙江 | 40个 | 1个 | 213ms | 5.3%  
甘肃 | 23个 | 0 | 221ms | 2.7%  
青海 | 4个 | 0 | 223ms | 8.3%  
新疆 | 28个 | 0 | 249ms | 4.7%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有973个，其中超时点9个，平均响应时间为197毫秒，丢包率为4%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的21个，在200-300毫秒间的9个；  
超时点较多的省份：北京；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/linode_20180527/plot_idc_linode_usa-fremont_20180527_overseas.png)

**海外线路到Linode美国-佛利蒙机房的测速数据 [20180527]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
美国 | 21个 | 0 | 14ms | 1.1%  
加拿大 | 3个 | 0 | 82ms | 0  
日本 | 1个 | 0 | 119ms | 0  
韩国 | 12个 | 0 | 141ms | 0  
台湾 | 1个 | 0 | 142ms | -  
意大利 | 1个 | 0 | 142ms | -  
荷兰 | 1个 | 0 | 149ms | 0  
英国 | 2个 | 0 | 150ms | 0  
德国 | 3个 | 0 | 153ms | 0  
法国 | 1个 | 0 | 153ms | 0  
香港 | 20个 | 0 | 170ms | 0  
新加坡 | 6个 | 0 | 178ms | 0  
巴西 | 1个 | 0 | 182ms | 0  
均值 | 88个 | 0 | 183ms | 0.3%  
澳大利亚 | 2个 | 0 | 195ms | 0  
越南 | 2个 | 0 | 206ms | 0  
俄罗斯 | 1个 | 0 | 231ms | 0  
马来西亚 | 5个 | 0 | 254ms | 0  
印度尼西亚 | 1个 | 0 | 271ms | 0  
柬埔寨 | 1个 | 0 | 292ms | 2.0%  
菲律宾 | 1个 | 0 | 297ms | 1.0%  
南非 | 2个 | 0 | 324ms | 1.0%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有88个，其中超时点0个，平均响应时间为183毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的1个，在100-200毫秒间的12个，在200-300毫秒间的6个，超过300毫秒的1个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180527) 
    * [全部](https://vps123.top/pingtests/20180527 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180527 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180527 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180527 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180527-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180527")
    * [达拉斯](/linode/idc/dallas/20180527-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180527")
    * [法兰克福](/linode/idc/frankfurt/20180527-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180527")
    * [伦敦](/linode/idc/london/20180527-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180527")
    * [纽瓦克](/linode/idc/newark/20180527-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180527")
    * [新加坡](/linode/idc/singapore/20180527-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180527")
    * [东京](/linode/idc/tokyo/20180527-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180527")
  * 到Linode佛利蒙机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/fremont/20180514-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180514")
    * [20180622](/linode/idc/fremont/20180622-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180622")
    * [20180804](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [20180918](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
  * 本期报告：在佛利蒙部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/fremont/20180527-bwg-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180527")



本文最初发表于[多地到Linode佛利蒙[Fremont]机房的Ping测试（20180527）](https://vps123.top/pingtest/20180527-linode-idc-fremont.html)
