#  多地到Linode佛利蒙[Fremont]机房的Ping测试（20180426） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode佛利蒙\[Fremont\]机房的Ping测试（20180426）](/images/thumbnails/to_linode_Fremont.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-佛利蒙机房](https://vps123.top/linode-facilities.html#fremont)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-佛利蒙机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180426-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180426多地到Linode美国-佛利蒙机房的PING测试结果，连通概况如下：大陆31个省市的301个有效测试样本中，共有超时点6个；响应均值为174毫秒，最快的三地区为重庆、北京、四川，最慢的三地区为青海、新疆、西藏；浙江、北京、甘肃、河北、江苏有响应超时情况；天津、北京、江苏、湖南、吉林等11处丢包率较高。海外19个国家地区的80个有效测试样本中，无超时点；响应均值为184毫秒，最快的三地区为美国、加拿大、日本，最慢的三地区为印度尼西亚、南非、柬埔寨。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/linode_20180426/plot_idc_linode_usa-fremont_20180426_mainland.png)

**大陆各省份到Linode美国-佛利蒙机房的测速数据 [20180426]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
重庆 | 2个 | 0 | 91ms | 1.0%  
北京 | 4个 | 1个 | 129ms | 19.7%  
四川 | 18个 | 0 | 140ms | 2.5%  
山东 | 25个 | 0 | 150ms | 4.4%  
广东 | 16个 | 0 | 161ms | 1.6%  
宁夏 | 5个 | 0 | 162ms | 1.2%  
广西 | 16个 | 0 | 163ms | 2.4%  
甘肃 | 7个 | 1个 | 167ms | 4.2%  
湖北 | 20个 | 0 | 169ms | 2.1%  
天津 | 3个 | 0 | 171ms | 21.0%  
黑龙江 | 11个 | 0 | 171ms | 5.8%  
吉林 | 6个 | 0 | 171ms | 8.0%  
均值 | 301个 | 6个 | 174ms | 4.4%  
江西 | 5个 | 0 | 175ms | 3.4%  
辽宁 | 14个 | 0 | 175ms | 4.2%  
浙江 | 20个 | 2个 | 178ms | 5.4%  
湖南 | 10个 | 0 | 179ms | 8.1%  
山西 | 10个 | 0 | 179ms | 7.0%  
贵州 | 5个 | 0 | 180ms | 8.0%  
福建 | 16个 | 0 | 186ms | 5.9%  
河北 | 16个 | 1个 | 188ms | 3.0%  
河南 | 7个 | 0 | 189ms | 1.0%  
江苏 | 15个 | 1个 | 191ms | 10.2%  
上海 | 6个 | 0 | 193ms | 1.2%  
安徽 | 5个 | 0 | 194ms | 3.8%  
内蒙古 | 14个 | 0 | 194ms | 2.8%  
陕西 | 6个 | 0 | 197ms | 1.7%  
海南 | 3个 | 0 | 197ms | 5.7%  
云南 | 7个 | 0 | 206ms | 2.3%  
青海 | 1个 | 0 | 222ms | 0  
新疆 | 7个 | 0 | 231ms | 1.7%  
西藏 | 1个 | 0 | 250ms | 0  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有301个，其中超时点6个，平均响应时间为174毫秒，丢包率为4%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在50-100毫秒间的1个，在100-200毫秒间的26个，在200-300毫秒间的4个；  
超时点较多的省份：北京、甘肃；  
丢包率较高的省份：北京、天津、江苏；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/linode_20180426/plot_idc_linode_usa-fremont_20180426_overseas.png)

**海外线路到Linode美国-佛利蒙机房的测速数据 [20180426]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
美国 | 16个 | 0 | 17ms | 0  
加拿大 | 3个 | 0 | 68ms | 0  
日本 | 3个 | 0 | 120ms | 0  
荷兰 | 2个 | 0 | 142ms | 0  
英国 | 3个 | 0 | 147ms | 0  
韩国 | 12个 | 0 | 150ms | 0.2%  
法国 | 2个 | 0 | 151ms | 0  
德国 | 1个 | 0 | 160ms | 0  
香港 | 20个 | 0 | 162ms | 0  
台湾 | 1个 | 0 | 173ms | -  
新加坡 | 5个 | 0 | 174ms | 0  
均值 | 80个 | 0 | 184ms | 0.3%  
澳大利亚 | 2个 | 0 | 192ms | 0  
越南 | 1个 | 0 | 215ms | 0  
马来西亚 | 4个 | 0 | 237ms | 0.5%  
俄罗斯 | 1个 | 0 | 238ms | 0  
菲律宾 | 1个 | 0 | 239ms | 1.0%  
印度尼西亚 | 1个 | 0 | 269ms | 0  
南非 | 1个 | 0 | 288ms | 0  
柬埔寨 | 1个 | 0 | 364ms | 4.0%  
  
**简评：** 如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有80个，其中超时点0个，平均响应时间为184毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的1个，在100-200毫秒间的10个，在200-300毫秒间的6个，超过300毫秒的1个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180426) 
    * [全部](https://vps123.top/pingtests/20180426 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180426 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180426 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180426 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180426-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180426")
    * [达拉斯](/linode/idc/dallas/20180426-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180426")
    * [法兰克福](/linode/idc/frankfurt/20180426-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180426")
    * [伦敦](/linode/idc/london/20180426-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180426")
    * [纽瓦克](/linode/idc/newark/20180426-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180426")
    * [新加坡](/linode/idc/singapore/20180426-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180426")
    * [东京](/linode/idc/tokyo/20180426-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180426")
  * 到Linode佛利蒙机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/fremont/20180514-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180514")
    * [20180527](/linode/idc/fremont/20180527-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180527")
    * [20180622](/linode/idc/fremont/20180622-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180622")
    * [20180804](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [20180918](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
  * 本期报告：在佛利蒙部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/fremont/20180426-bwg-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180426")



本文最初发表于[多地到Linode佛利蒙[Fremont]机房的Ping测试（20180426）](https://vps123.top/pingtest/20180426-linode-idc-fremont.html)
