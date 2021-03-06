#  多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Digital Ocean多伦多\[Toronto\]机房的Ping测试（20180622）](/images/thumbnails/to_do_Toronto.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Digital Ocean](https://vps123.top/go/do)的[加拿大-多伦多机房](https://vps123.top/digitalocean-facilities.html#toronto)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Digital Ocean](https://vps123.top/go/do)的加拿大-多伦多机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Digital Ocean全部机房](/digitalocean/isp/china/20180622-digitalocean-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的872个有效测试样本中，共有超时点25个；响应均值为255毫秒，最快的三地区为上海、天津、广东，最慢的三地区为青海、新疆、西藏；云南、江苏、重庆、浙江、黑龙江等11处有响应超时情况。海外19个国家地区的88个有效测试样本中，无超时点；响应均值为182毫秒，最快的三地区为加拿大、美国、德国，最慢的三地区为印度尼西亚、马来西亚、柬埔寨。

[注册 Digital Ocean](https://vps123.top/go/do/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/do_20180622/plot_idc_do_canada-toronto_20180622_mainland.png)

**大陆各省份到Digital Ocean加拿大-多伦多机房的测速数据 [20180622]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 7个 | 1个 | 231ms | 0.7%  
天津 | 2个 | 0 | 234ms | 2.0%  
广东 | 74个 | 0 | 238ms | 0.4%  
江苏 | 67个 | 3个 | 240ms | 4.0%  
安徽 | 36个 | 1个 | 240ms | 0.1%  
河南 | 45个 | 1个 | 246ms | 3.0%  
广西 | 42个 | 0 | 247ms | 1.6%  
福建 | 31个 | 1个 | 248ms | 0.4%  
重庆 | 12个 | 2个 | 250ms | 0.3%  
山东 | 40个 | 0 | 251ms | 1.0%  
北京 | 10个 | 0 | 251ms | 1.3%  
河北 | 30个 | 0 | 251ms | 0.4%  
湖南 | 37个 | 0 | 251ms | 1.6%  
浙江 | 52个 | 2个 | 252ms | 0.3%  
山西 | 32个 | 0 | 254ms | 0.3%  
均值 | 872个 | 25个 | 255ms | 1.3%  
湖北 | 34个 | 0 | 256ms | 0.8%  
海南 | 12个 | 0 | 256ms | 0.1%  
江西 | 23个 | 0 | 257ms | 0.8%  
辽宁 | 36个 | 0 | 258ms | 1.4%  
宁夏 | 13个 | 0 | 259ms | 0.7%  
贵州 | 25个 | 0 | 262ms | 2.6%  
内蒙古 | 27个 | 0 | 265ms | 2.8%  
四川 | 40个 | 0 | 266ms | 0.5%  
黑龙江 | 32个 | 2个 | 267ms | 1.4%  
云南 | 23个 | 10个 | 269ms | 0.2%  
甘肃 | 15个 | 0 | 272ms | 0.8%  
吉林 | 19个 | 0 | 272ms | 1.5%  
陕西 | 26个 | 1个 | 273ms | 0.6%  
青海 | 5个 | 0 | 275ms | 0.8%  
新疆 | 24个 | 1个 | 310ms | 1.4%  
西藏 | 1个 | 0 | 390ms | 4.0%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有872个，其中超时点25个，平均响应时间为255毫秒，丢包率为1%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的29个，超过300毫秒的2个；  
超时点较多的省份：上海、重庆、云南；

## 海外测速点

![海外各国家地区到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/do_20180622/plot_idc_do_canada-toronto_20180622_overseas.png)

**海外线路到Digital Ocean加拿大-多伦多机房的测速数据 [20180622]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
加拿大 | 2个 | 0 | 15ms | 0  
美国 | 20个 | 0 | 68ms | 0  
德国 | 1个 | 0 | 84ms | -  
意大利 | 1个 | 0 | 85ms | -  
巴西 | 1个 | 0 | 97ms | 0  
法国 | 1个 | 0 | 139ms | 0  
日本 | 2个 | 0 | 180ms | 1.0%  
均值 | 88个 | 0 | 182ms | 0.3%  
英国 | 2个 | 0 | 184ms | 0  
南非 | 2个 | 0 | 188ms | 0.5%  
台湾 | 2个 | 0 | 193ms | 0  
香港 | 23个 | 0 | 196ms | 0  
新加坡 | 5个 | 0 | 205ms | 0  
韩国 | 14个 | 0 | 215ms | 0.3%  
菲律宾 | 2个 | 0 | 226ms | 0  
澳大利亚 | 1个 | 0 | 244ms | 0  
越南 | 2个 | 0 | 257ms | 0  
印度尼西亚 | 1个 | 0 | 274ms | 0  
马来西亚 | 5个 | 0 | 296ms | 2.4%  
柬埔寨 | 1个 | 0 | 317ms | 1.0%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有88个，其中超时点0个，平均响应时间为182毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的4个，在100-200毫秒间的6个，在200-300毫秒间的7个，超过300毫秒的1个；

[注册 Digital Ocean](https://vps123.top/go/do/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180622) 
    * [全部](https://vps123.top/pingtests/20180622 "本期各VPS提供商全部测速报告")
    * [Digital Ocean](https://vps123.top/pingtests/idc-digitalocean/20180622 "本期Digital Ocean的全部测速报告")
    * [各地到Digital Ocean某机房](https://vps123.top/pingtests/idc-digitalocean/isp-global/20180622 "以Digital Ocean某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Digital Ocean各机房](https://vps123.top/pingtests/idc-digitalocean/facility-all/20180622 "以大陆某省份为关注对象的视角，横向比较Digital Ocean各机房")
  * 本期到Digital Ocean _其他机房_ 的报告： 
    * [阿姆斯特丹](/digitalocean/idc/amsterdam/20180622-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180622")
    * [班加罗尔](/digitalocean/idc/bangalore/20180622-digitalocean-idc-bangalore.md "多地到Digital Ocean班加罗尔机房的Ping测试 20180622")
    * [法兰克福](/digitalocean/idc/frankfurt/20180622-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180622")
    * [伦敦](/digitalocean/idc/london/20180622-digitalocean-idc-london.md "多地到Digital Ocean伦敦机房的Ping测试 20180622")
    * [纽约](/digitalocean/idc/newyork/20180622-digitalocean-idc-newyork.md "多地到Digital Ocean纽约机房的Ping测试 20180622")
    * [旧金山](/digitalocean/idc/sanfrancisco/20180622-digitalocean-idc-sanfrancisco.md "多地到Digital Ocean旧金山机房的Ping测试 20180622")
    * [新加坡](/digitalocean/idc/singapore/20180622-digitalocean-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180622")
  * 到Digital Ocean多伦多机房的 _其他近期报告_ ： 
    * [20180514](/digitalocean/idc/toronto/20180514-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180514")
    * [20180527](/digitalocean/idc/toronto/20180527-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180527")
    * [20180804](/digitalocean/idc/toronto/20180804-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180804")
    * [20180918](/digitalocean/idc/toronto/20180918-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180918")



本文最初发表于[多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180622）](https://vps123.top/pingtest/20180622-digitalocean-idc-toronto.html)
