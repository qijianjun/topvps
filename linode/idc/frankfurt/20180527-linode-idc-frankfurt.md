#  多地到Linode法兰克福[Frankfurt]机房的Ping测试（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode法兰克福\[Frankfurt\]机房的Ping测试（20180527）](/images/thumbnails/to_linode_Frankfurt.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[德国-法兰克福机房](https://vps123.top/linode-facilities.html#frankfurt)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的德国-法兰克福机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180527-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆30个省市的967个有效测试样本中，共有超时点12个；响应均值为278毫秒，最快的三地区为北京、青海、天津，最慢的三地区为云南、四川、吉林；江苏、湖南、北京、河南、山东等8处有响应超时情况；辽宁、河北、湖南、湖北、广西等6处丢包率较高。海外21个国家地区的87个有效测试样本中，共有超时点1个；响应均值为180毫秒，最快的三地区为意大利、法国、荷兰，最慢的三地区为澳大利亚、柬埔寨、菲律宾；美国有响应超时情况。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于法兰克福\[Frankfurt\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/linode_20180527/plot_idc_linode_germany-frankfurt_20180527_mainland.png)

**大陆各省份到Linode德国-法兰克福机房的测速数据 [20180527]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
北京 | 8个 | 1个 | 235ms | 2.3%  
青海 | 4个 | 0 | 236ms | 2.0%  
天津 | 5个 | 0 | 246ms | 0  
宁夏 | 12个 | 0 | 251ms | 1.1%  
安徽 | 36个 | 0 | 260ms | 3.9%  
辽宁 | 38个 | 0 | 260ms | 12.0%  
江苏 | 63个 | 3个 | 261ms | 3.1%  
广东 | 82个 | 0 | 261ms | 2.1%  
河北 | 34个 | 0 | 263ms | 8.4%  
上海 | 8个 | 0 | 265ms | 3.6%  
山西 | 35个 | 0 | 271ms | 2.4%  
河南 | 53个 | 1个 | 272ms | 2.0%  
内蒙古 | 34个 | 0 | 272ms | 2.7%  
海南 | 14个 | 0 | 272ms | 2.6%  
陕西 | 32个 | 0 | 274ms | 3.2%  
黑龙江 | 40个 | 0 | 275ms | 2.3%  
均值 | 967个 | 12个 | 278ms | 3.9%  
湖南 | 47个 | 3个 | 279ms | 6.8%  
山东 | 52个 | 1个 | 283ms | 2.8%  
重庆 | 15个 | 1个 | 283ms | 5.0%  
浙江 | 48个 | 0 | 287ms | 1.7%  
湖北 | 43个 | 1个 | 287ms | 6.2%  
江西 | 25个 | 0 | 289ms | 2.5%  
甘肃 | 23个 | 0 | 290ms | 4.4%  
广西 | 39个 | 0 | 291ms | 5.9%  
福建 | 35个 | 0 | 293ms | 2.2%  
贵州 | 27个 | 0 | 294ms | 5.4%  
新疆 | 27个 | 0 | 294ms | 2.9%  
云南 | 22个 | 0 | 306ms | 3.9%  
四川 | 47个 | 1个 | 313ms | 4.8%  
吉林 | 19个 | 0 | 315ms | 2.5%  
  
**简评：** 如果你考虑在Linode的法兰克福[Frankfurt]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于法兰克福[Frankfurt]的机房的连通状况。到此机房的ping监测点共有967个，其中超时点12个，平均响应时间为278毫秒，丢包率为3%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的27个，超过300毫秒的3个；  
超时点较多的省份：北京；  
丢包率较高的省份：辽宁；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于法兰克福\[Frankfurt\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/linode_20180527/plot_idc_linode_germany-frankfurt_20180527_overseas.png)

**海外线路到Linode德国-法兰克福机房的测速数据 [20180527]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
意大利 | 1个 | 0 | 9ms | -  
法国 | 1个 | 0 | 10ms | 0  
荷兰 | 1个 | 0 | 10ms | 0  
德国 | 3个 | 0 | 12ms | 0  
英国 | 2个 | 0 | 34ms | 0  
俄罗斯 | 1个 | 0 | 95ms | 0  
加拿大 | 3个 | 0 | 98ms | 0  
美国 | 21个 | 1个 | 152ms | 2.8%  
均值 | 87个 | 1个 | 180ms | 0.5%  
新加坡 | 6个 | 0 | 190ms | 0  
南非 | 2个 | 0 | 201ms | 0.5%  
印度尼西亚 | 1个 | 0 | 208ms | 0  
香港 | 20个 | 0 | 217ms | 1.7%  
马来西亚 | 5个 | 0 | 218ms | 0.2%  
巴西 | 1个 | 0 | 219ms | 0  
日本 | 1个 | 0 | 244ms | 0  
越南 | 2个 | 0 | 261ms | 0.5%  
韩国 | 12个 | 0 | 282ms | 0  
台湾 | 1个 | 0 | 289ms | -  
澳大利亚 | 1个 | 0 | 330ms | 0  
柬埔寨 | 1个 | 0 | 334ms | 2.0%  
菲律宾 | 1个 | 0 | 374ms | 2.0%  
  
**简评：** 如果你考虑在Linode的法兰克福[Frankfurt]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于法兰克福[Frankfurt]的机房的连通状况。到此机房的ping监测点共有87个，其中超时点1个，平均响应时间为180毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的5个，在50-100毫秒间的2个，在100-200毫秒间的2个，在200-300毫秒间的9个，超过300毫秒的3个；

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
    * [佛利蒙](/linode/idc/fremont/20180527-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180527")
    * [伦敦](/linode/idc/london/20180527-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180527")
    * [纽瓦克](/linode/idc/newark/20180527-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180527")
    * [新加坡](/linode/idc/singapore/20180527-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180527")
    * [东京](/linode/idc/tokyo/20180527-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180527")
  * 到Linode法兰克福机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/frankfurt/20180514-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180514")
    * [20180622](/linode/idc/frankfurt/20180622-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180622")
    * [20180804](/linode/idc/frankfurt/20180804-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180804")
    * [20180918](/linode/idc/frankfurt/20180918-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180918")
  * 本期报告：在法兰克福部署机房的 _其他VPS提供商_ ： 
    * [Digital Ocean](do/idc/frankfurt/20180527-do-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180527")
    * [Vultr](/vultr/idc/frankfurt/20180527-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180527")



本文最初发表于[多地到Linode法兰克福[Frankfurt]机房的Ping测试（20180527）](https://vps123.top/pingtest/20180527-linode-idc-frankfurt.html)
