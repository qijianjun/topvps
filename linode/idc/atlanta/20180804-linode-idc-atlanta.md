#  多地到Linode亚特兰大[Atlanta]机房的Ping测试（20180804） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode亚特兰大\[Atlanta\]机房的Ping测试（20180804）](/images/thumbnails/to_linode_Atlanta.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-亚特兰大机房](https://vps123.top/linode-facilities.html#atlanta)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-亚特兰大机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180804-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的5389个有效测试样本中，共有超时点39个；响应均值为285毫秒，最快的三地区为广东、海南、山东，最慢的三地区为新疆、甘肃、西藏；浙江、江西、江苏、上海、广东等8处有响应超时情况；西藏、青海、天津、辽宁、北京等22处丢包率较高。海外19个国家地区的234个有效测试样本中，无超时点；响应均值为181毫秒，最快的三地区为加拿大、荷兰、美国，最慢的三地区为印度尼西亚、马来西亚、菲律宾；菲律宾丢包率较高。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于亚特兰大\[Atlanta\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/linode_20180804/plot_idc_linode_usa-atlanta_20180804_mainland.png)

**大陆各省份到Linode美国-亚特兰大机房的测速数据 [20180804]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
广东 | 418个 | 3个 | 259ms | 2.6%  
海南 | 52个 | 0 | 265ms | 3.4%  
山东 | 362个 | 0 | 268ms | 3.1%  
天津 | 20个 | 0 | 270ms | 11.5%  
北京 | 36个 | 0 | 271ms | 9.2%  
湖南 | 261个 | 3个 | 272ms | 2.8%  
浙江 | 244个 | 10个 | 273ms | 5.4%  
河北 | 244个 | 0 | 273ms | 5.7%  
江苏 | 337个 | 6个 | 274ms | 5.2%  
湖北 | 209个 | 0 | 274ms | 5.4%  
广西 | 239个 | 0 | 274ms | 5.7%  
山西 | 194个 | 0 | 275ms | 4.7%  
安徽 | 244个 | 0 | 282ms | 8.7%  
均值 | 5389个 | 39个 | 285ms | 5.8%  
宁夏 | 32个 | 0 | 286ms | 6.3%  
福建 | 169个 | 3个 | 287ms | 9.1%  
云南 | 127个 | 0 | 287ms | 7.5%  
重庆 | 31个 | 0 | 289ms | 3.0%  
河南 | 347个 | 0 | 290ms | 8.3%  
贵州 | 151个 | 0 | 290ms | 4.3%  
四川 | 285个 | 3个 | 291ms | 3.5%  
吉林 | 100个 | 0 | 296ms | 6.4%  
江西 | 139个 | 7个 | 297ms | 7.7%  
内蒙古 | 228个 | 0 | 300ms | 7.4%  
上海 | 31个 | 4个 | 302ms | 8.5%  
辽宁 | 227个 | 0 | 305ms | 10.1%  
黑龙江 | 200个 | 0 | 306ms | 6.0%  
陕西 | 163个 | 0 | 316ms | 5.8%  
青海 | 16个 | 0 | 325ms | 13.7%  
新疆 | 163个 | 0 | 328ms | 3.5%  
甘肃 | 112个 | 0 | 331ms | 8.8%  
西藏 | 8个 | 0 | 458ms | 14.2%  
  
**简评：** 如果你考虑在Linode的亚特兰大[Atlanta]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于亚特兰大[Atlanta]的机房的连通状况。到此机房的ping监测点共有5389个，其中超时点39个，平均响应时间为285毫秒，丢包率为5%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的23个，超过300毫秒的8个；  
超时点较多的省份：上海；  
丢包率较高的省份：天津、辽宁、青海、西藏；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于亚特兰大\[Atlanta\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/linode_20180804/plot_idc_linode_usa-atlanta_20180804_overseas.png)

**海外线路到Linode美国-亚特兰大机房的测速数据 [20180804]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
加拿大 | 15个 | 0 | 36ms | 0  
荷兰 | 3个 | 0 | 52ms | 0  
美国 | 48个 | 0 | 85ms | 0.2%  
巴西 | 3个 | 0 | 89ms | 0  
意大利 | 3个 | 0 | 92ms | -  
德国 | 9个 | 0 | 113ms | 0  
英国 | 6个 | 0 | 122ms | 0  
俄罗斯 | 3个 | 0 | 136ms | -  
日本 | 3个 | 0 | 180ms | 3.0%  
均值 | 234个 | 0 | 181ms | 1.1%  
新加坡 | 15个 | 0 | 193ms | 0  
南非 | 6个 | 0 | 197ms | 0.5%  
香港 | 66个 | 0 | 198ms | 0  
韩国 | 21个 | 0 | 198ms | 0  
台湾 | 3个 | 0 | 200ms | 0  
法国 | 3个 | 0 | 218ms | 0  
澳大利亚 | 6个 | 0 | 243ms | 0  
印度尼西亚 | 6个 | 0 | 259ms | 0  
马来西亚 | 12个 | 0 | 266ms | 1.0%  
菲律宾 | 3个 | 0 | 576ms | 13.3%  
  
**简评：** 如果你考虑在Linode的亚特兰大[Atlanta]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于亚特兰大[Atlanta]的机房的连通状况。到此机房的ping监测点共有234个，其中超时点0个，平均响应时间为181毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的4个，在100-200毫秒间的9个，在200-300毫秒间的4个，超过300毫秒的1个；  
丢包率较高的国家/地区：菲律宾；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180804) 
    * [全部](https://vps123.top/pingtests/20180804 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180804 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180804 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180804 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [达拉斯](/linode/idc/dallas/20180804-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180804")
    * [法兰克福](/linode/idc/frankfurt/20180804-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180804")
    * [佛利蒙](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [伦敦](/linode/idc/london/20180804-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180804")
    * [纽瓦克](/linode/idc/newark/20180804-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180804")
    * [新加坡](/linode/idc/singapore/20180804-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180804")
    * [东京](/linode/idc/tokyo/20180804-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180804")
  * 到Linode亚特兰大机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/atlanta/20180514-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180514")
    * [20180527](/linode/idc/atlanta/20180527-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180527")
    * [20180622](/linode/idc/atlanta/20180622-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180622")
    * [20180918](/linode/idc/atlanta/20180918-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180918")
  * 本期报告：在亚特兰大部署机房的 _其他VPS提供商_ ： 
    * [Vultr](/vultr/idc/atlanta/20180804-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180804")



本文最初发表于[多地到Linode亚特兰大[Atlanta]机房的Ping测试（20180804）](https://vps123.top/pingtest/20180804-linode-idc-atlanta.html)
