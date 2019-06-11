#  多地到Linode亚特兰大[Atlanta]机房的Ping测试（20180918） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode亚特兰大\[Atlanta\]机房的Ping测试（20180918）](/images/thumbnails/to_linode_Atlanta.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-亚特兰大机房](https://vps123.top/linode-facilities.html#atlanta)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-亚特兰大机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180918-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180918多地到Linode美国-亚特兰大机房的PING测试结果，连通概况如下：大陆31个省市的1336个有效测试样本中，共有超时点18个；响应均值为259毫秒，最快的三地区为安徽、广西、福建，最慢的三地区为新疆、青海、西藏；江苏、广东、浙江、湖北、河南等7处有响应超时情况；北京、吉林、重庆、上海、河南等22处丢包率较高。海外17个国家地区的80个有效测试样本中，无超时点；响应均值为192毫秒，最快的三地区为加拿大、美国、意大利，最慢的三地区为赞比亚、越南、菲律宾。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于亚特兰大\[Atlanta\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_usa-atlanta_20180918_mainland.png)

大陆各省份到Linode美国-亚特兰大机房的测速数据 [20180918] 省份 | 测速点 | 超时点 | 响应时间 | 丢包率 | 省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
安徽 | 66个 | 0 | 240ms | 3.0% | 均值 | 1336个 | 18个 | 259ms | 7.7%  
广西 | 54个 | 0 | 241ms | 6.6% | 重庆 | 7个 | 0 | 261ms | 16.9%  
福建 | 41个 | 0 | 243ms | 3.5% | 河南 | 83个 | 2个 | 264ms | 14.9%  
江苏 | 90个 | 5个 | 246ms | 6.9% | 北京 | 6个 | 0 | 265ms | 25.2%  
广东 | 113个 | 4个 | 246ms | 5.5% | 云南 | 27个 | 0 | 268ms | 1.9%  
河北 | 47个 | 0 | 246ms | 8.5% | 内蒙古 | 52个 | 0 | 268ms | 8.7%  
上海 | 7个 | 0 | 246ms | 16.2% | 贵州 | 40个 | 0 | 269ms | 7.7%  
江西 | 39个 | 0 | 247ms | 5.7% | 四川 | 71个 | 0 | 270ms | 3.4%  
浙江 | 66个 | 3个 | 248ms | 8.4% | 黑龙江 | 52个 | 0 | 275ms | 12.9%  
天津 | 6个 | 0 | 249ms | 0.6% | 吉林 | 18个 | 0 | 275ms | 17.2%  
湖北 | 51个 | 2个 | 252ms | 4.4% | 陕西 | 43个 | 0 | 277ms | 5.3%  
湖南 | 67个 | 1个 | 252ms | 3.7% | 甘肃 | 31个 | 0 | 288ms | 0.8%  
海南 | 14个 | 0 | 253ms | 5.3% | 宁夏 | 7个 | 0 | 289ms | 0  
山西 | 52个 | 1个 | 254ms | 9.0% | 新疆 | 31个 | 0 | 302ms | 7.4%  
山东 | 89个 | 0 | 258ms | 13.2% | 青海 | 6个 | 0 | 326ms | 12.9%  
辽宁 | 57个 | 0 | 259ms | 11.2% | 西藏 | 3个 | 0 | 429ms | 7.7%  
  
简评：如果你考虑在Linode的亚特兰大[Atlanta]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于亚特兰大[Atlanta]的机房的连通状况。到此机房的ping监测点共有1336个，其中超时点18个，平均响应时间为259毫秒，丢包率为7%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的28个，超过300毫秒的3个；  
丢包率较高的省份：上海、山东、辽宁、重庆、河南、北京、黑龙江、吉林、青海；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于亚特兰大\[Atlanta\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/linode_20180918/plot_idc_linode_usa-atlanta_20180918_overseas.png)

海外线路到Linode美国-亚特兰大机房的测速数据 [20180918] 国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率 | 国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
加拿大 | 3个 | 0 | 28ms | 0 | 日本 | 3个 | 0 | 193ms | 0  
美国 | 14个 | 0 | 74ms | 0.2% | 新加坡 | 5个 | 0 | 195ms | 0  
意大利 | 1个 | 0 | 90ms | - | 香港 | 21个 | 0 | 200ms | 0  
德国 | 3个 | 0 | 114ms | 0 | 澳大利亚 | 2个 | 0 | 240ms | 1.7%  
台湾 | 2个 | 0 | 116ms | 0 | 印度尼西亚 | 1个 | 0 | 254ms | 3.3%  
韩国 | 12个 | 0 | 171ms | 0 | 马来西亚 | 5个 | 0 | 270ms | 0  
俄罗斯 | 2个 | 0 | 174ms | 0 | 赞比亚 | 2个 | 0 | 275ms | 2.7%  
荷兰 | 1个 | 0 | 189ms | 0 | 越南 | 2个 | 0 | 305ms | 0.5%  
均值 | 80个 | 0 | 192ms | 0.7% | 菲律宾 | 1个 | 0 | 378ms | 3.0%  
  
简评：如果你考虑在Linode的亚特兰大[Atlanta]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于亚特兰大[Atlanta]的机房的连通状况。到此机房的ping监测点共有80个，其中超时点0个，平均响应时间为192毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的2个，在100-200毫秒间的8个，在200-300毫秒间的4个，超过300毫秒的2个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180918) 
    * [全部](https://vps123.top/pingtests/20180918 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180918 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180918 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180918 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [达拉斯](/linode/idc/dallas/20180918-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180918")
    * [法兰克福](/linode/idc/frankfurt/20180918-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180918")
    * [佛利蒙](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
    * [伦敦](/linode/idc/london/20180918-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180918")
    * [纽瓦克](/linode/idc/newark/20180918-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180918")
    * [新加坡](/linode/idc/singapore/20180918-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180918")
    * [东京](/linode/idc/tokyo/20180918-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180918")
  * 到Linode亚特兰大机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/atlanta/20180514-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180514")
    * [20180527](/linode/idc/atlanta/20180527-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180527")
    * [20180622](/linode/idc/atlanta/20180622-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180622")
    * [20180804](/linode/idc/atlanta/20180804-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180804")
  * 本期报告：在亚特兰大部署机房的 _其他VPS提供商_ ： 
    * [Vultr](/vultr/idc/atlanta/20180918-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180918")



本文最初发表于[多地到Linode亚特兰大[Atlanta]机房的Ping测试（20180918）](https://vps123.top/pingtest/20180918-linode-idc-atlanta.html)