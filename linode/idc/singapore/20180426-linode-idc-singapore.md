#  多地到Linode新加坡[Singapore]机房的Ping测试（20180426） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode新加坡\[Singapore\]机房的Ping测试（20180426）](/images/thumbnails/to_linode_Singapore.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[新加坡-新加坡机房](https://vps123.top/linode-facilities.html#singapore)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的新加坡-新加坡机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180426-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180426多地到Linode新加坡-新加坡机房的PING测试结果，连通概况如下：大陆31个省市的818个有效测试样本中，共有超时点7个；响应均值为173毫秒，最快的三地区为天津、河南、山东，最慢的三地区为贵州、北京、重庆；浙江、河南、江苏、内蒙古、甘肃等6处有响应超时情况；西藏、青海、甘肃、新疆、河南等29处丢包率较高。海外19个国家地区的79个有效测试样本中，共有超时点2个；响应均值为155毫秒，最快的三地区为新加坡、马来西亚、印度尼西亚，最慢的三地区为法国、俄罗斯、南非；香港、美国有响应超时情况；南非丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/linode_20180426/plot_idc_linode_singapore-singapore_20180426_mainland.png)

**大陆各省份到Linode新加坡-新加坡机房的测速数据 [20180426]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
天津 | 5个 | 0 | 132ms | 3.3%  
河南 | 49个 | 1个 | 133ms | 17.5%  
山东 | 46个 | 0 | 133ms | 14.4%  
山西 | 31个 | 0 | 146ms | 10.9%  
安徽 | 38个 | 0 | 151ms | 16.2%  
江苏 | 50个 | 1个 | 152ms | 14.2%  
陕西 | 27个 | 0 | 154ms | 13.8%  
浙江 | 36个 | 2个 | 162ms | 14.3%  
广东 | 60个 | 0 | 162ms | 10.4%  
内蒙古 | 30个 | 1个 | 163ms | 13.5%  
河北 | 27个 | 0 | 166ms | 9.3%  
黑龙江 | 32个 | 0 | 170ms | 11.6%  
吉林 | 15个 | 0 | 170ms | 6.1%  
均值 | 818个 | 7个 | 173ms | 13.3%  
广西 | 33个 | 0 | 176ms | 12.3%  
云南 | 26个 | 0 | 177ms | 15.0%  
青海 | 4个 | 0 | 179ms | 24.8%  
江西 | 19个 | 0 | 183ms | 14.6%  
宁夏 | 10个 | 0 | 185ms | 13.2%  
四川 | 43个 | 0 | 186ms | 8.5%  
海南 | 12个 | 0 | 186ms | 10.8%  
西藏 | 1个 | 0 | 190ms | 47.0%  
湖南 | 38个 | 0 | 191ms | 16.0%  
上海 | 8个 | 0 | 193ms | 12.6%  
辽宁 | 34个 | 0 | 197ms | 10.1%  
福建 | 27个 | 0 | 201ms | 10.9%  
湖北 | 36个 | 0 | 202ms | 12.4%  
甘肃 | 21个 | 1个 | 211ms | 21.1%  
新疆 | 26个 | 0 | 215ms | 19.6%  
贵州 | 21个 | 0 | 221ms | 13.5%  
北京 | 4个 | 1个 | 250ms | 0.3%  
重庆 | 9个 | 0 | 285ms | 17.1%  
  
**简评：** 如果你考虑在Linode的新加坡[Singapore]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有818个，其中超时点7个，平均响应时间为173毫秒，丢包率为13%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的24个，在200-300毫秒间的7个；  
超时点较多的省份：北京；  
丢包率较高的省份：河南、山东、山西、安徽、江苏、陕西、浙江、广东、内蒙古、黑龙江、广西、云南、青海、江西、宁夏、海南、西藏、湖南、上海、辽宁、福建、湖北、甘肃、新疆、贵州、重庆；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/linode_20180426/plot_idc_linode_singapore-singapore_20180426_overseas.png)

**海外线路到Linode新加坡-新加坡机房的测速数据 [20180426]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
新加坡 | 5个 | 0 | 1ms | 0  
马来西亚 | 4个 | 0 | 22ms | 0  
印度尼西亚 | 1个 | 0 | 23ms | 0  
香港 | 20个 | 1个 | 61ms | 0  
台湾 | 1个 | 0 | 63ms | -  
越南 | 1个 | 0 | 66ms | 0  
日本 | 2个 | 0 | 80ms | 0.5%  
菲律宾 | 1个 | 0 | 85ms | 0  
韩国 | 12个 | 0 | 114ms | 0  
澳大利亚 | 2个 | 0 | 120ms | 0.5%  
均值 | 79个 | 2个 | 155ms | 0.6%  
德国 | 1个 | 0 | 167ms | 0  
柬埔寨 | 1个 | 0 | 178ms | 0  
美国 | 16个 | 1个 | 196ms | 0  
荷兰 | 2个 | 0 | 212ms | 0  
英国 | 3个 | 0 | 227ms | 0  
加拿大 | 3个 | 0 | 245ms | 0.5%  
法国 | 2个 | 0 | 276ms | 0  
俄罗斯 | 1个 | 0 | 325ms | 0  
南非 | 1个 | 0 | 489ms | 10.0%  
  
**简评：** 如果你考虑在Linode的新加坡[Singapore]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有79个，其中超时点2个，平均响应时间为155毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的3个，在50-100毫秒间的5个，在100-200毫秒间的5个，在200-300毫秒间的4个，超过300毫秒的2个；  
丢包率较高的国家/地区：南非；

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
    * [佛利蒙](/linode/idc/fremont/20180426-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180426")
    * [伦敦](/linode/idc/london/20180426-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180426")
    * [纽瓦克](/linode/idc/newark/20180426-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180426")
    * [东京](/linode/idc/tokyo/20180426-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180426")
  * 到Linode新加坡机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/singapore/20180514-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180514")
    * [20180527](/linode/idc/singapore/20180527-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180527")
    * [20180622](/linode/idc/singapore/20180622-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180622")
    * [20180804](/linode/idc/singapore/20180804-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180804")
    * [20180918](/linode/idc/singapore/20180918-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180918")
  * 本期报告：在新加坡部署机房的 _其他VPS提供商_ ： 
    * [Digital Ocean](do/idc/singapore/20180426-do-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180426")
    * [Vultr](/vultr/idc/singapore/20180426-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180426")



本文最初发表于[多地到Linode新加坡[Singapore]机房的Ping测试（20180426）](https://vps123.top/pingtest/20180426-linode-idc-singapore.html)
