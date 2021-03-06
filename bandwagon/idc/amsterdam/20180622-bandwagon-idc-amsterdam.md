#  多地到BandwagonHost阿姆斯特丹[Amsterdam]机房的Ping测试（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到BandwagonHost阿姆斯特丹\[Amsterdam\]机房的Ping测试（20180622）](/images/thumbnails/to_bwg_Amsterdam.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[BandwagonHost](https://vps123.top/go/bwg)的[荷兰-阿姆斯特丹机房](https://vps123.top/bandwagon-facilities.html#amsterdam)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[BandwagonHost](https://vps123.top/go/bwg)的荷兰-阿姆斯特丹机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[BandwagonHost全部机房](/bandwagon/isp/china/20180622-bandwagon-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆29个省市的223个有效测试样本中，共有超时点10个；响应均值为306毫秒，最快的三地区为山西、江苏、湖北，最慢的三地区为河南、吉林、香港；江苏、广东、浙江、上海、重庆等7处有响应超时情况；甘肃、天津、安徽、河北、河南等20处丢包率较高。海外13个国家地区的70个有效测试样本中，无超时点；响应均值为150毫秒，最快的三地区为德国、法国、意大利，最慢的三地区为日本、台湾、英国。

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商BandwagonHost位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/bwg_20180622/plot_idc_bwg_netherlands-amsterdam_20180622_mainland.png)

**大陆各省份到BandwagonHost荷兰-阿姆斯特丹机房的测速数据 [20180622]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
山西 | 4个 | 0 | 256ms | 3.3%  
江苏 | 26个 | 2个 | 258ms | 14.2%  
湖北 | 6个 | 0 | 264ms | 20.0%  
广西 | 5个 | 0 | 266ms | 22.5%  
广东 | 27个 | 2个 | 268ms | 2.5%  
海南 | 1个 | 0 | 270ms | 0  
辽宁 | 9个 | 0 | 275ms | 5.3%  
江西 | 4个 | 0 | 284ms | 21.1%  
云南 | 2个 | 0 | 292ms | 0  
贵州 | 7个 | 0 | 294ms | 15.0%  
内蒙古 | 4个 | 0 | 299ms | 0  
浙江 | 26个 | 2个 | 303ms | 20.0%  
山东 | 6个 | 0 | 306ms | 13.3%  
均值 | 223个 | 10个 | 306ms | 16.4%  
北京 | 7个 | 0 | 310ms | 0.5%  
安徽 | 6个 | 0 | 313ms | 44.2%  
新疆 | 2个 | 0 | 320ms | 6.7%  
上海 | 3个 | 1个 | 329ms | 1.7%  
福建 | 14个 | 0 | 338ms | 27.8%  
重庆 | 6个 | 1个 | 341ms | 18.9%  
黑龙江 | 3个 | 0 | 342ms | 18.9%  
陕西 | 9个 | 1个 | 343ms | 13.3%  
四川 | 5个 | 0 | 346ms | 1.7%  
河北 | 2个 | 0 | 349ms | 40.0%  
甘肃 | 1个 | 0 | 362ms | 60.0%  
天津 | 1个 | 0 | 366ms | 53.3%  
湖南 | 6个 | 1个 | 376ms | 27.8%  
河南 | 5个 | 0 | 391ms | 40.0%  
吉林 | 2个 | 0 | 414ms | 28.3%  
香港 | 24个 | 0 | - | -  
  
**简评：** 如果你考虑在BandwagonHost的阿姆斯特丹[Amsterdam]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有223个，其中超时点10个，平均响应时间为306毫秒，丢包率为16%，本站评价等级为 **很差** ，十分不推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在200-300毫秒间的11个，超过300毫秒的17个；  
超时点较多的省份：上海、重庆、陕西、湖南；  
丢包率较高的省份：江苏、湖北、广西、江西、贵州、浙江、山东、安徽、福建、重庆、黑龙江、陕西、河北、甘肃、天津、湖南、河南、吉林；

## 海外测速点

![海外各国家地区到VPS提供商BandwagonHost位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/bwg_20180622/plot_idc_bwg_netherlands-amsterdam_20180622_overseas.png)

**海外线路到BandwagonHost荷兰-阿姆斯特丹机房的测速数据 [20180622]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
德国 | 1个 | 0 | 7ms | -  
法国 | 1个 | 0 | 8ms | 0  
意大利 | 1个 | 0 | 8ms | -  
巴西 | 1个 | 0 | 15ms | 0  
加拿大 | 1个 | 0 | 88ms | -  
美国 | 19个 | 0 | 137ms | 0  
南非 | 1个 | 0 | 148ms | 0  
均值 | 70个 | 0 | 150ms | 0  
新加坡 | 5个 | 0 | 194ms | 0  
香港 | 24个 | 0 | 231ms | 0  
韩国 | 12个 | 0 | 264ms | 0  
日本 | 1个 | 0 | 264ms | -  
台湾 | 2个 | 0 | 278ms | 0  
英国 | 1个 | 0 | 307ms | 0  
  
**简评：** 如果你考虑在BandwagonHost的阿姆斯特丹[Amsterdam]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有70个，其中超时点0个，平均响应时间为150毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的4个，在50-100毫秒间的1个，在100-200毫秒间的3个，在200-300毫秒间的4个，超过300毫秒的1个；

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180622) 
    * [全部](https://vps123.top/pingtests/20180622 "本期各VPS提供商全部测速报告")
    * [BandwagonHost](https://vps123.top/pingtests/idc-bandwagon/20180622 "本期BandwagonHost的全部测速报告")
    * [各地到BandwagonHost某机房](https://vps123.top/pingtests/idc-bandwagon/isp-global/20180622 "以BandwagonHost某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到BandwagonHost各机房](https://vps123.top/pingtests/idc-bandwagon/facility-all/20180622 "以大陆某省份为关注对象的视角，横向比较BandwagonHost各机房")
  * 本期到BandwagonHost _其他机房_ 的报告： 
    * [佛罗里达](/bandwagon/idc/florida/20180622-bandwagon-idc-florida.md "多地到BandwagonHost佛罗里达机房的Ping测试 20180622")
    * [佛利蒙](/bandwagon/idc/fremont/20180622-bandwagon-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180622")
    * [香港](/bandwagon/idc/hongkong/20180622-bandwagon-idc-hongkong.md "多地到BandwagonHost香港机房的Ping测试 20180622")
    * [洛杉矶](/bandwagon/idc/losangeles/20180622-bandwagon-idc-losangeles.md "多地到BandwagonHost洛杉矶机房的Ping测试 20180622")
    * [纽约](/bandwagon/idc/newyork/20180622-bandwagon-idc-newyork.md "多地到BandwagonHost纽约机房的Ping测试 20180622")
    * [凤凰城](/bandwagon/idc/phoenix/20180622-bandwagon-idc-phoenix.md "多地到BandwagonHost凤凰城机房的Ping测试 20180622")
    * [温哥华](/bandwagon/idc/vancouver/20180622-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180622")
  * 到BandwagonHost阿姆斯特丹机房的 _其他近期报告_ ： 
    * [20180514](/bandwagon/idc/amsterdam/20180514-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180514")
    * [20180527](/bandwagon/idc/amsterdam/20180527-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180527")
    * [20180804](/bandwagon/idc/amsterdam/20180804-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180804")
    * [20180918](/bandwagon/idc/amsterdam/20180918-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180918")
  * 本期报告：在阿姆斯特丹部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/amsterdam/20180622-bwg-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180622")
    * [Digital Ocean](do/idc/amsterdam/20180622-do-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180622")
    * [Vultr](/vultr/idc/amsterdam/20180622-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180622")



本文最初发表于[多地到BandwagonHost阿姆斯特丹[Amsterdam]机房的Ping测试（20180622）](https://vps123.top/pingtest/20180622-bandwagon-idc-amsterdam.html)
