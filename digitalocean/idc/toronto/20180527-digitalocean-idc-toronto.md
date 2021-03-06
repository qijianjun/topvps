#  多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Digital Ocean多伦多\[Toronto\]机房的Ping测试（20180527）](/images/thumbnails/to_do_Toronto.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Digital Ocean](https://vps123.top/go/do)的[加拿大-多伦多机房](https://vps123.top/digitalocean-facilities.html#toronto)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Digital Ocean](https://vps123.top/go/do)的加拿大-多伦多机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Digital Ocean全部机房](/digitalocean/isp/china/20180527-digitalocean-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆30个省市的965个有效测试样本中，共有超时点7个；响应均值为256毫秒，最快的三地区为上海、北京、天津，最慢的三地区为甘肃、青海、新疆；北京、江苏、河南、山东、贵州等7处有响应超时情况。海外21个国家地区的87个有效测试样本中，无超时点；响应均值为184毫秒，最快的三地区为加拿大、美国、意大利，最慢的三地区为印度尼西亚、菲律宾、柬埔寨。

[注册 Digital Ocean](https://vps123.top/go/do/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/do_20180527/plot_idc_do_canada-toronto_20180527_mainland.png)

**大陆各省份到Digital Ocean加拿大-多伦多机房的测速数据 [20180527]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 8个 | 0 | 236ms | 0  
北京 | 8个 | 1个 | 238ms | 1.0%  
天津 | 4个 | 0 | 239ms | 0  
广东 | 79个 | 0 | 240ms | 0.7%  
海南 | 14个 | 0 | 244ms | 0  
山西 | 37个 | 0 | 245ms | 2.8%  
江苏 | 60个 | 1个 | 247ms | 0.2%  
广西 | 39个 | 0 | 248ms | 1.8%  
福建 | 34个 | 0 | 249ms | 0.1%  
河北 | 34个 | 0 | 249ms | 0.1%  
河南 | 57个 | 1个 | 250ms | 0.8%  
浙江 | 51个 | 0 | 255ms | 0.3%  
吉林 | 19个 | 0 | 255ms | 0  
江西 | 25个 | 0 | 256ms | 0.2%  
安徽 | 39个 | 0 | 256ms | 0.6%  
辽宁 | 41个 | 0 | 256ms | 0.4%  
均值 | 965个 | 7个 | 256ms | 0.9%  
山东 | 51个 | 1个 | 257ms | 0.3%  
湖南 | 44个 | 0 | 257ms | 3.5%  
宁夏 | 12个 | 0 | 258ms | 0.1%  
内蒙古 | 31个 | 0 | 259ms | 0.1%  
贵州 | 28个 | 1个 | 260ms | 2.7%  
陕西 | 32个 | 1个 | 262ms | 1.4%  
重庆 | 14个 | 1个 | 262ms | 0  
云南 | 21个 | 0 | 264ms | 3.8%  
湖北 | 44个 | 0 | 268ms | 0.5%  
四川 | 46个 | 0 | 269ms | 0.6%  
黑龙江 | 39个 | 0 | 269ms | 0.7%  
甘肃 | 23个 | 0 | 269ms | 0.2%  
青海 | 3个 | 0 | 277ms | 0  
新疆 | 28个 | 0 | 304ms | 0.8%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有965个，其中超时点7个，平均响应时间为256毫秒，丢包率为0%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的29个，超过300毫秒的1个；  
超时点较多的省份：北京；

## 海外测速点

![海外各国家地区到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/do_20180527/plot_idc_do_canada-toronto_20180527_overseas.png)

**海外线路到Digital Ocean加拿大-多伦多机房的测速数据 [20180527]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
加拿大 | 3个 | 0 | 15ms | 0  
美国 | 21个 | 0 | 61ms | 3.6%  
意大利 | 1个 | 0 | 83ms | -  
法国 | 1个 | 0 | 97ms | 0  
荷兰 | 1个 | 0 | 100ms | 0  
德国 | 3个 | 0 | 108ms | 0  
英国 | 2个 | 0 | 114ms | 0  
巴西 | 1个 | 0 | 139ms | 0  
日本 | 1个 | 0 | 162ms | 0  
均值 | 87个 | 0 | 184ms | 0.4%  
台湾 | 1个 | 0 | 200ms | -  
韩国 | 12个 | 0 | 208ms | 0  
俄罗斯 | 1个 | 0 | 216ms | 0  
香港 | 21个 | 0 | 227ms | 0  
新加坡 | 6个 | 0 | 236ms | 0  
澳大利亚 | 1个 | 0 | 243ms | 1.0%  
马来西亚 | 4个 | 0 | 255ms | 0  
南非 | 2个 | 0 | 269ms | 1.0%  
越南 | 2个 | 0 | 277ms | 1.0%  
印度尼西亚 | 1个 | 0 | 286ms | 0  
菲律宾 | 1个 | 0 | 287ms | 0  
柬埔寨 | 1个 | 0 | 292ms | 1.0%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有87个，其中超时点0个，平均响应时间为184毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的4个，在100-200毫秒间的5个，在200-300毫秒间的11个；

[注册 Digital Ocean](https://vps123.top/go/do/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180527) 
    * [全部](https://vps123.top/pingtests/20180527 "本期各VPS提供商全部测速报告")
    * [Digital Ocean](https://vps123.top/pingtests/idc-digitalocean/20180527 "本期Digital Ocean的全部测速报告")
    * [各地到Digital Ocean某机房](https://vps123.top/pingtests/idc-digitalocean/isp-global/20180527 "以Digital Ocean某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Digital Ocean各机房](https://vps123.top/pingtests/idc-digitalocean/facility-all/20180527 "以大陆某省份为关注对象的视角，横向比较Digital Ocean各机房")
  * 本期到Digital Ocean _其他机房_ 的报告： 
    * [阿姆斯特丹](/digitalocean/idc/amsterdam/20180527-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180527")
    * [班加罗尔](/digitalocean/idc/bangalore/20180527-digitalocean-idc-bangalore.md "多地到Digital Ocean班加罗尔机房的Ping测试 20180527")
    * [法兰克福](/digitalocean/idc/frankfurt/20180527-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180527")
    * [伦敦](/digitalocean/idc/london/20180527-digitalocean-idc-london.md "多地到Digital Ocean伦敦机房的Ping测试 20180527")
    * [纽约](/digitalocean/idc/newyork/20180527-digitalocean-idc-newyork.md "多地到Digital Ocean纽约机房的Ping测试 20180527")
    * [旧金山](/digitalocean/idc/sanfrancisco/20180527-digitalocean-idc-sanfrancisco.md "多地到Digital Ocean旧金山机房的Ping测试 20180527")
    * [新加坡](/digitalocean/idc/singapore/20180527-digitalocean-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180527")
  * 到Digital Ocean多伦多机房的 _其他近期报告_ ： 
    * [20180514](/digitalocean/idc/toronto/20180514-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180514")
    * [20180622](/digitalocean/idc/toronto/20180622-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180622")
    * [20180804](/digitalocean/idc/toronto/20180804-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180804")
    * [20180918](/digitalocean/idc/toronto/20180918-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180918")



本文最初发表于[多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180527）](https://vps123.top/pingtest/20180527-digitalocean-idc-toronto.html)
