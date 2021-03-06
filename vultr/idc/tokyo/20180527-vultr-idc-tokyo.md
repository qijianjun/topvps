#  多地到Vultr东京[Tokyo]机房的Ping测试（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Vultr东京\[Tokyo\]机房的Ping测试（20180527）](/images/thumbnails/to_vultr_Tokyo.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Vultr](https://vps123.top/go/vultr)的[日本-东京机房](https://vps123.top/vultr-facilities.html#tokyo)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Vultr](https://vps123.top/go/vultr)的日本-东京机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Vultr全部机房](/vultr/isp/china/20180527-vultr-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆30个省市的954个有效测试样本中，共有超时点16个；响应均值为177毫秒，最快的三地区为湖南、北京、福建，最慢的三地区为重庆、新疆、吉林；江苏、广东、山东、湖北、北京等9处有响应超时情况；上海、天津、江西、江苏、浙江等30处丢包率较高。海外21个国家地区的87个有效测试样本中，无超时点；响应均值为176毫秒，最快的三地区为日本、台湾、韩国，最慢的三地区为法国、柬埔寨、南非；柬埔寨、韩国丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Vultr位于东京\[Tokyo\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/vultr_20180527/plot_idc_vultr_japan-tokyo_20180527_mainland.png)

**大陆各省份到Vultr日本-东京机房的测速数据 [20180527]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
湖南 | 46个 | 0 | 155ms | 9.6%  
北京 | 8个 | 1个 | 159ms | 11.0%  
福建 | 36个 | 0 | 160ms | 11.3%  
广东 | 78个 | 3个 | 163ms | 11.6%  
广西 | 40个 | 0 | 163ms | 11.1%  
江西 | 23个 | 0 | 164ms | 17.2%  
安徽 | 36个 | 0 | 164ms | 14.2%  
山西 | 37个 | 0 | 164ms | 9.2%  
江苏 | 62个 | 4个 | 167ms | 16.1%  
青海 | 4个 | 0 | 169ms | 8.3%  
浙江 | 47个 | 1个 | 170ms | 16.0%  
海南 | 14个 | 0 | 171ms | 14.8%  
天津 | 5个 | 0 | 174ms | 17.9%  
上海 | 7个 | 0 | 175ms | 24.1%  
贵州 | 24个 | 0 | 176ms | 10.6%  
均值 | 954个 | 16个 | 177ms | 12.4%  
黑龙江 | 40个 | 1个 | 178ms | 10.8%  
陕西 | 32个 | 0 | 178ms | 11.0%  
河南 | 55个 | 1个 | 179ms | 11.5%  
云南 | 21个 | 0 | 180ms | 11.3%  
辽宁 | 40个 | 0 | 181ms | 11.6%  
山东 | 52个 | 2个 | 182ms | 11.1%  
湖北 | 42个 | 2个 | 182ms | 13.5%  
宁夏 | 12个 | 0 | 182ms | 12.0%  
甘肃 | 22个 | 0 | 192ms | 11.8%  
内蒙古 | 33个 | 0 | 193ms | 12.1%  
四川 | 45个 | 0 | 196ms | 14.7%  
河北 | 33个 | 0 | 197ms | 11.5%  
重庆 | 14个 | 1个 | 198ms | 13.6%  
新疆 | 27个 | 0 | 205ms | 9.7%  
吉林 | 19个 | 0 | 209ms | 14.5%  
  
**简评：** 如果你考虑在Vultr的东京[Tokyo]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于东京[Tokyo]的机房的连通状况。到此机房的ping监测点共有954个，其中超时点16个，平均响应时间为177毫秒，丢包率为12%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的28个，在200-300毫秒间的2个；  
超时点较多的省份：北京；  
丢包率较高的省份：北京、福建、广东、广西、江西、安徽、江苏、浙江、海南、天津、上海、贵州、黑龙江、陕西、河南、云南、辽宁、山东、湖北、宁夏、甘肃、内蒙古、四川、河北、重庆、吉林；

## 海外测速点

![海外各国家地区到VPS提供商Vultr位于东京\[Tokyo\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/vultr_20180527/plot_idc_vultr_japan-tokyo_20180527_overseas.png)

**海外线路到Vultr日本-东京机房的测速数据 [20180527]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
日本 | 2个 | 0 | 12ms | 1.0%  
台湾 | 1个 | 0 | 41ms | -  
韩国 | 12个 | 0 | 67ms | 7.0%  
香港 | 18个 | 0 | 71ms | 0  
菲律宾 | 1个 | 0 | 79ms | 0  
越南 | 2个 | 0 | 80ms | 0  
新加坡 | 5个 | 0 | 94ms | 0  
印度尼西亚 | 1个 | 0 | 100ms | 0  
马来西亚 | 5个 | 0 | 104ms | 0.2%  
美国 | 21个 | 0 | 117ms | 2.1%  
加拿大 | 4个 | 0 | 158ms | 0  
均值 | 87个 | 0 | 176ms | 1.5%  
意大利 | 1个 | 0 | 231ms | -  
德国 | 3个 | 0 | 238ms | 0  
澳大利亚 | 2个 | 0 | 239ms | 0  
英国 | 2个 | 0 | 248ms | 0  
巴西 | 1个 | 0 | 261ms | 0  
俄罗斯 | 1个 | 0 | 266ms | 0  
荷兰 | 1个 | 0 | 268ms | 0  
法国 | 1个 | 0 | 284ms | 0  
柬埔寨 | 1个 | 0 | 335ms | 16.0%  
南非 | 2个 | 0 | 403ms | 1.5%  
  
**简评：** 如果你考虑在Vultr的东京[Tokyo]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于东京[Tokyo]的机房的连通状况。到此机房的ping监测点共有87个，其中超时点0个，平均响应时间为176毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在50-100毫秒间的6个，在100-200毫秒间的3个，在200-300毫秒间的8个，超过300毫秒的2个；  
丢包率较高的国家/地区：柬埔寨；

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180527) 
    * [全部](https://vps123.top/pingtests/20180527 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180527 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180527 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180527 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期到Vultr _其他机房_ 的报告： 
    * [阿姆斯特丹](/vultr/idc/amsterdam/20180527-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180527")
    * [亚特兰大](/vultr/idc/atlanta/20180527-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180527")
    * [芝加哥](/vultr/idc/chicago/20180527-vultr-idc-chicago.md "多地到Vultr芝加哥机房的Ping测试 20180527")
    * [达拉斯](/vultr/idc/dallas/20180527-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180527")
    * [法兰克福](/vultr/idc/frankfurt/20180527-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180527")
    * [伦敦](/vultr/idc/london/20180527-vultr-idc-london.md "多地到Vultr伦敦机房的Ping测试 20180527")
    * [洛杉矶](/vultr/idc/losangeles/20180527-vultr-idc-losangeles.md "多地到Vultr洛杉矶机房的Ping测试 20180527")
    * [迈阿密](/vultr/idc/miami/20180527-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180527")
    * [新泽西](/vultr/idc/newjersey/20180527-vultr-idc-newjersey.md "多地到Vultr新泽西机房的Ping测试 20180527")
    * [巴黎](/vultr/idc/paris/20180527-vultr-idc-paris.md "多地到Vultr巴黎机房的Ping测试 20180527")
    * [西雅图](/vultr/idc/seattle/20180527-vultr-idc-seattle.md "多地到Vultr西雅图机房的Ping测试 20180527")
    * [硅谷](/vultr/idc/siliconvalley/20180527-vultr-idc-siliconvalley.md "多地到Vultr硅谷机房的Ping测试 20180527")
    * [新加坡](/vultr/idc/singapore/20180527-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180527")
    * [悉尼](/vultr/idc/sydney/20180527-vultr-idc-sydney.md "多地到Vultr悉尼机房的Ping测试 20180527")
  * 到Vultr东京机房的 _其他近期报告_ ： 
    * [20180514](/vultr/idc/tokyo/20180514-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180514")
    * [20180622](/vultr/idc/tokyo/20180622-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180622")
    * [20180804](/vultr/idc/tokyo/20180804-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180804")
    * [20180918](/vultr/idc/tokyo/20180918-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180918")
  * 本期报告：在东京部署机房的 _其他VPS提供商_ ： 
    * [Linode](/linode/idc/tokyo/20180527-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180527")



本文最初发表于[多地到Vultr东京[Tokyo]机房的Ping测试（20180527）](https://vps123.top/pingtest/20180527-vultr-idc-tokyo.html)
