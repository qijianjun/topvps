#  多地到Vultr东京[Tokyo]机房的Ping测试（20180426） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Vultr东京\[Tokyo\]机房的Ping测试（20180426）](/images/thumbnails/to_vultr_Tokyo.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Vultr](https://vps123.top/go/vultr)的[日本-东京机房](https://vps123.top/vultr-facilities.html#tokyo)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Vultr](https://vps123.top/go/vultr)的日本-东京机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Vultr全部机房](/vultr/isp/china/20180426-vultr-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180426多地到Vultr日本-东京机房的PING测试结果，连通概况如下：大陆31个省市的789个有效测试样本中，共有超时点5个；响应均值为166毫秒，最快的三地区为北京、天津、山西，最慢的三地区为甘肃、四川、新疆；浙江、北京、江苏、陕西有响应超时情况；四川、上海、山东、湖北、江苏等29处丢包率较高。海外18个国家地区的80个有效测试样本中，共有超时点2个；响应均值为189毫秒，最快的三地区为日本、台湾、香港，最慢的三地区为印度尼西亚、南非、柬埔寨；香港、美国有响应超时情况；柬埔寨、韩国丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Vultr位于东京\[Tokyo\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/vultr_20180426/plot_idc_vultr_japan-tokyo_20180426_mainland.png)

**大陆各省份到Vultr日本-东京机房的测速数据 [20180426]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
北京 | 4个 | 1个 | 118ms | 15.7%  
天津 | 5个 | 0 | 121ms | 16.0%  
山西 | 28个 | 0 | 132ms | 13.7%  
福建 | 27个 | 0 | 140ms | 11.8%  
河南 | 50个 | 0 | 149ms | 12.9%  
江苏 | 48个 | 1个 | 150ms | 18.1%  
湖南 | 36个 | 0 | 153ms | 13.7%  
河北 | 33个 | 0 | 156ms | 16.1%  
内蒙古 | 25个 | 0 | 158ms | 13.7%  
黑龙江 | 30个 | 0 | 159ms | 16.0%  
陕西 | 26个 | 1个 | 160ms | 9.5%  
西藏 | 1个 | 0 | 163ms | 0  
辽宁 | 34个 | 0 | 163ms | 14.8%  
上海 | 8个 | 0 | 165ms | 22.6%  
均值 | 789个 | 5个 | 166ms | 15.3%  
山东 | 47个 | 0 | 167ms | 20.9%  
广东 | 55个 | 0 | 167ms | 11.3%  
浙江 | 36个 | 2个 | 168ms | 12.9%  
广西 | 29个 | 0 | 168ms | 15.2%  
安徽 | 38个 | 0 | 170ms | 18.0%  
吉林 | 12个 | 0 | 171ms | 17.1%  
青海 | 4个 | 0 | 172ms | 2.8%  
江西 | 22个 | 0 | 172ms | 13.6%  
海南 | 10个 | 0 | 172ms | 18.0%  
重庆 | 9个 | 0 | 173ms | 15.2%  
湖北 | 37个 | 0 | 174ms | 19.1%  
宁夏 | 9个 | 0 | 177ms | 15.8%  
云南 | 25个 | 0 | 178ms | 12.0%  
贵州 | 22个 | 0 | 183ms | 14.0%  
甘肃 | 21个 | 0 | 183ms | 12.3%  
四川 | 35个 | 0 | 205ms | 24.8%  
新疆 | 23个 | 0 | 215ms | 12.3%  
  
**简评：** 如果你考虑在Vultr的东京[Tokyo]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于东京[Tokyo]的机房的连通状况。到此机房的ping监测点共有789个，其中超时点5个，平均响应时间为166毫秒，丢包率为15%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的29个，在200-300毫秒间的2个；  
超时点较多的省份：北京；  
丢包率较高的省份：北京、天津、山西、福建、河南、江苏、湖南、河北、内蒙古、黑龙江、辽宁、上海、山东、广东、浙江、广西、安徽、吉林、江西、海南、重庆、湖北、宁夏、云南、贵州、甘肃、四川、新疆；

## 海外测速点

![海外各国家地区到VPS提供商Vultr位于东京\[Tokyo\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180426](/images/pingtests/vultr_20180426/plot_idc_vultr_japan-tokyo_20180426_overseas.png)

**海外线路到Vultr日本-东京机房的测速数据 [20180426]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
日本 | 3个 | 0 | 10ms | 0.3%  
台湾 | 1个 | 0 | 41ms | -  
香港 | 20个 | 1个 | 64ms | 0  
韩国 | 12个 | 0 | 78ms | 5.5%  
新加坡 | 5个 | 0 | 98ms | 0  
美国 | 16个 | 1个 | 123ms | 0  
越南 | 1个 | 0 | 129ms | 0  
马来西亚 | 4个 | 0 | 131ms | 0  
均值 | 80个 | 2个 | 189ms | 2.5%  
澳大利亚 | 2个 | 0 | 196ms | 0  
加拿大 | 4个 | 0 | 201ms | 0  
英国 | 3个 | 0 | 238ms | 0  
德国 | 1个 | 0 | 239ms | 0  
荷兰 | 2个 | 0 | 248ms | 0  
法国 | 2个 | 0 | 257ms | 0  
俄罗斯 | 1个 | 0 | 260ms | 0  
印度尼西亚 | 1个 | 0 | 325ms | 3.0%  
南非 | 1个 | 0 | 380ms | 0  
柬埔寨 | 1个 | 0 | 393ms | 33.0%  
  
**简评：** 如果你考虑在Vultr的东京[Tokyo]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于东京[Tokyo]的机房的连通状况。到此机房的ping监测点共有80个，其中超时点2个，平均响应时间为189毫秒，丢包率为2%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在50-100毫秒间的3个，在100-200毫秒间的4个，在200-300毫秒间的6个，超过300毫秒的3个；  
丢包率较高的国家/地区：柬埔寨；

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180426) 
    * [全部](https://vps123.top/pingtests/20180426 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180426 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180426 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180426 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期到Vultr _其他机房_ 的报告： 
    * [阿姆斯特丹](/vultr/idc/amsterdam/20180426-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180426")
    * [亚特兰大](/vultr/idc/atlanta/20180426-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180426")
    * [芝加哥](/vultr/idc/chicago/20180426-vultr-idc-chicago.md "多地到Vultr芝加哥机房的Ping测试 20180426")
    * [达拉斯](/vultr/idc/dallas/20180426-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180426")
    * [法兰克福](/vultr/idc/frankfurt/20180426-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180426")
    * [伦敦](/vultr/idc/london/20180426-vultr-idc-london.md "多地到Vultr伦敦机房的Ping测试 20180426")
    * [洛杉矶](/vultr/idc/losangeles/20180426-vultr-idc-losangeles.md "多地到Vultr洛杉矶机房的Ping测试 20180426")
    * [迈阿密](/vultr/idc/miami/20180426-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180426")
    * [新泽西](/vultr/idc/newjersey/20180426-vultr-idc-newjersey.md "多地到Vultr新泽西机房的Ping测试 20180426")
    * [巴黎](/vultr/idc/paris/20180426-vultr-idc-paris.md "多地到Vultr巴黎机房的Ping测试 20180426")
    * [西雅图](/vultr/idc/seattle/20180426-vultr-idc-seattle.md "多地到Vultr西雅图机房的Ping测试 20180426")
    * [硅谷](/vultr/idc/siliconvalley/20180426-vultr-idc-siliconvalley.md "多地到Vultr硅谷机房的Ping测试 20180426")
    * [新加坡](/vultr/idc/singapore/20180426-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180426")
    * [悉尼](/vultr/idc/sydney/20180426-vultr-idc-sydney.md "多地到Vultr悉尼机房的Ping测试 20180426")
  * 到Vultr东京机房的 _其他近期报告_ ： 
    * [20180514](/vultr/idc/tokyo/20180514-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180514")
    * [20180527](/vultr/idc/tokyo/20180527-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180527")
    * [20180622](/vultr/idc/tokyo/20180622-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180622")
    * [20180804](/vultr/idc/tokyo/20180804-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180804")
    * [20180918](/vultr/idc/tokyo/20180918-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180918")
  * 本期报告：在东京部署机房的 _其他VPS提供商_ ： 
    * [Linode](/linode/idc/tokyo/20180426-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180426")



本文最初发表于[多地到Vultr东京[Tokyo]机房的Ping测试（20180426）](https://vps123.top/pingtest/20180426-vultr-idc-tokyo.html)
