#  多地到Linode新加坡[Singapore]机房的Ping测试（20180918） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode新加坡\[Singapore\]机房的Ping测试（20180918）](/images/thumbnails/to_linode_Singapore.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[新加坡-新加坡机房](https://vps123.top/linode-facilities.html#singapore)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的新加坡-新加坡机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180918-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180918多地到Linode新加坡-新加坡机房的PING测试结果，连通概况如下：大陆31个省市的1434个有效测试样本中，共有超时点13个；响应均值为196毫秒，最快的三地区为广西、湖南、河南，最慢的三地区为宁夏、西藏、青海；江苏、浙江、广东、山西、河南等6处有响应超时情况；天津、青海、西藏、北京、山东等9处丢包率较高。海外15个国家地区的62个有效测试样本中，无超时点；响应均值为140毫秒，最快的三地区为印度尼西亚、越南、新加坡，最慢的三地区为加拿大、菲律宾、德国；菲律宾丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_singapore-singapore_20180918_mainland.png)

**大陆各省份到Linode新加坡-新加坡机房的测速数据 [20180918]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
广西 | 59个 | 0 | 156ms | 1.1%  
湖南 | 71个 | 0 | 172ms | 2.6%  
河南 | 86个 | 1个 | 177ms | 5.2%  
广东 | 124个 | 2个 | 178ms | 2.0%  
山东 | 95个 | 0 | 179ms | 6.8%  
黑龙江 | 58个 | 0 | 182ms | 2.9%  
安徽 | 73个 | 0 | 183ms | 3.4%  
山西 | 58个 | 2个 | 185ms | 5.4%  
福建 | 44个 | 0 | 187ms | 2.7%  
海南 | 14个 | 0 | 188ms | 0.9%  
贵州 | 43个 | 0 | 189ms | 1.7%  
河北 | 58个 | 0 | 193ms | 4.5%  
江西 | 38个 | 0 | 195ms | 3.9%  
吉林 | 23个 | 0 | 195ms | 0.1%  
陕西 | 45个 | 0 | 196ms | 2.2%  
均值 | 1434个 | 13个 | 196ms | 3.8%  
天津 | 6个 | 0 | 198ms | 15.7%  
内蒙古 | 58个 | 0 | 198ms | 4.4%  
重庆 | 9个 | 0 | 199ms | 0.3%  
上海 | 9个 | 0 | 204ms | 3.5%  
浙江 | 62个 | 3个 | 206ms | 4.4%  
江苏 | 91个 | 4个 | 212ms | 3.1%  
北京 | 9个 | 0 | 218ms | 8.4%  
辽宁 | 59个 | 0 | 219ms | 6.3%  
云南 | 29个 | 0 | 220ms | 2.3%  
四川 | 70个 | 1个 | 229ms | 3.8%  
甘肃 | 35个 | 0 | 232ms | 3.3%  
湖北 | 55个 | 0 | 234ms | 3.7%  
新疆 | 36个 | 0 | 247ms | 4.3%  
宁夏 | 8个 | 0 | 257ms | 5.8%  
西藏 | 3个 | 0 | 287ms | 10.8%  
青海 | 6个 | 0 | 319ms | 14.9%  
  
**简评：** 如果你考虑在Linode的新加坡[Singapore]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有1434个，其中超时点13个，平均响应时间为196毫秒，丢包率为3%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的18个，在200-300毫秒间的12个，超过300毫秒的1个；  
丢包率较高的省份：天津、西藏、青海；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_singapore-singapore_20180918_overseas.png)

**海外线路到Linode新加坡-新加坡机房的测速数据 [20180918]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
印度尼西亚 | 1个 | 0 | 27ms | 3.3%  
越南 | 2个 | 0 | 49ms | 0  
新加坡 | 4个 | 0 | 50ms | 0  
马来西亚 | 5个 | 0 | 52ms | 0  
日本 | 3个 | 0 | 78ms | 0  
台湾 | 2个 | 0 | 114ms | 0  
香港 | 17个 | 0 | 116ms | 0  
均值 | 62个 | 0 | 140ms | 2.5%  
荷兰 | 1个 | 0 | 141ms | 0  
美国 | 9个 | 0 | 148ms | 0  
韩国 | 8个 | 0 | 153ms | 1.7%  
澳大利亚 | 2个 | 0 | 154ms | 0  
俄罗斯 | 2个 | 0 | 190ms | 0  
加拿大 | 2个 | 0 | 228ms | 0  
菲律宾 | 2个 | 0 | 252ms | 33.2%  
德国 | 2个 | 0 | 355ms | 0  
  
**简评：** 如果你考虑在Linode的新加坡[Singapore]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有62个，其中超时点0个，平均响应时间为140毫秒，丢包率为2%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的3个，在50-100毫秒间的2个，在100-200毫秒间的7个，在200-300毫秒间的2个，超过300毫秒的1个；  
丢包率较高的国家/地区：菲律宾；

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
    * [佛利蒙](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
    * [伦敦](/linode/idc/london/20180918-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180918")
    * [纽瓦克](/linode/idc/newark/20180918-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180918")
    * [东京](/linode/idc/tokyo/20180918-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180918")
  * 到Linode新加坡机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/singapore/20180514-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180514")
    * [20180527](/linode/idc/singapore/20180527-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180527")
    * [20180622](/linode/idc/singapore/20180622-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180622")
    * [20180804](/linode/idc/singapore/20180804-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180804")
  * 本期报告：在新加坡部署机房的 _其他VPS提供商_ ： 
    * [Digital Ocean](do/idc/singapore/20180918-do-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180918")
    * [Vultr](/vultr/idc/singapore/20180918-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180918")



本文最初发表于[多地到Linode新加坡[Singapore]机房的Ping测试（20180918）](https://vps123.top/pingtest/20180918-linode-idc-singapore.html)
