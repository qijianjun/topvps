#  多地到BandwagonHost阿姆斯特丹[Amsterdam]机房的Ping测试（20180527） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到BandwagonHost阿姆斯特丹\[Amsterdam\]机房的Ping测试（20180527）](/images/thumbnails/to_bwg_Amsterdam.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[BandwagonHost](https://vps123.top/go/bwg)的[荷兰-阿姆斯特丹机房](https://vps123.top/bandwagon-facilities.html#amsterdam)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[BandwagonHost](https://vps123.top/go/bwg)的荷兰-阿姆斯特丹机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[BandwagonHost全部机房](/bandwagon/isp/china/20180527-bandwagon-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆28个省市的168个有效测试样本中，共有超时点9个；响应均值为322毫秒，最快的三地区为山西、上海、海南，最慢的三地区为黑龙江、吉林、新疆；山东、江苏、广东、重庆、湖南等8处有响应超时情况；吉林、甘肃、黑龙江、山东、天津等17处丢包率较高。海外17个国家地区的66个有效测试样本中，无超时点；响应均值为152毫秒，最快的三地区为荷兰、英国、德国，最慢的三地区为台湾、韩国、澳大利亚。

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商BandwagonHost位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/bwg_20180527/plot_idc_bwg_netherlands-amsterdam_20180527_mainland.png)

**大陆各省份到BandwagonHost荷兰-阿姆斯特丹机房的测速数据 [20180527]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
山西 | 2个 | 0 | 228ms | 3.3%  
上海 | 2个 | 0 | 254ms | 0  
海南 | 1个 | 0 | 276ms | 0  
江苏 | 20个 | 1个 | 280ms | 0  
广东 | 25个 | 1个 | 287ms | 5.0%  
河北 | 2个 | 0 | 288ms | 0  
安徽 | 5个 | 0 | 292ms | 11.1%  
浙江 | 19个 | 0 | 296ms | 1.9%  
北京 | 5个 | 0 | 306ms | 4.0%  
云南 | 2个 | 0 | 309ms | 5.0%  
福建 | 11个 | 0 | 321ms | 17.3%  
均值 | 168个 | 9个 | 322ms | 9.7%  
甘肃 | 1个 | 0 | 328ms | 36.7%  
贵州 | 5个 | 0 | 329ms | 4.4%  
江西 | 4个 | 0 | 331ms | 10.0%  
天津 | 2个 | 0 | 332ms | 25.0%  
辽宁 | 8个 | 0 | 334ms | 1.7%  
四川 | 4个 | 0 | 339ms | 21.7%  
重庆 | 5个 | 1个 | 350ms | 8.3%  
河南 | 8个 | 0 | 356ms | 13.3%  
广西 | 4个 | 0 | 357ms | 8.9%  
湖南 | 6个 | 1个 | 364ms | 12.2%  
陕西 | 6个 | 1个 | 366ms | 23.3%  
湖北 | 5个 | 0 | 369ms | 10.0%  
山东 | 5个 | 2个 | 384ms | 30.0%  
内蒙古 | 3个 | 0 | 388ms | 12.2%  
黑龙江 | 4个 | 1个 | 389ms | 31.1%  
吉林 | 2个 | 1个 | 407ms | 43.3%  
新疆 | 2个 | 0 | 449ms | 20.0%  
  
**简评：** 如果你考虑在BandwagonHost的阿姆斯特丹[Amsterdam]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有168个，其中超时点9个，平均响应时间为322毫秒，丢包率为9%，本站评价等级为 **很差** ，十分不推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的8个，超过300毫秒的20个；  
超时点较多的省份：重庆、湖南、陕西、山东、黑龙江；  
丢包率较高的省份：安徽、福建、甘肃、江西、天津、四川、河南、湖南、陕西、湖北、山东、内蒙古、黑龙江、吉林、新疆；

## 海外测速点

![海外各国家地区到VPS提供商BandwagonHost位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180527](/images/pingtests/bwg_20180527/plot_idc_bwg_netherlands-amsterdam_20180527_overseas.png)

**海外线路到BandwagonHost荷兰-阿姆斯特丹机房的测速数据 [20180527]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
荷兰 | 1个 | 0 | 2ms | 0  
英国 | 1个 | 0 | 6ms | 0  
德国 | 2个 | 0 | 7ms | 0  
意大利 | 1个 | 0 | 8ms | -  
法国 | 1个 | 0 | 15ms | 0  
加拿大 | 1个 | 0 | 89ms | -  
俄罗斯 | 1个 | 0 | 97ms | 0  
美国 | 18个 | 0 | 142ms | 0  
均值 | 66个 | 0 | 152ms | 0  
南非 | 1个 | 0 | 169ms | 0  
马来西亚 | 1个 | 0 | 186ms | 0  
巴西 | 1个 | 0 | 206ms | 0  
新加坡 | 5个 | 0 | 208ms | 0  
日本 | 1个 | 0 | 261ms | 0  
香港 | 19个 | 0 | 290ms | 0  
台湾 | 1个 | 0 | 293ms | -  
韩国 | 10个 | 0 | 296ms | 0  
澳大利亚 | 1个 | 0 | 310ms | 0  
  
**简评：** 如果你考虑在BandwagonHost的阿姆斯特丹[Amsterdam]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有66个，其中超时点0个，平均响应时间为152毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的5个，在50-100毫秒间的2个，在100-200毫秒间的3个，在200-300毫秒间的6个，超过300毫秒的1个；

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180527) 
    * [全部](https://vps123.top/pingtests/20180527 "本期各VPS提供商全部测速报告")
    * [BandwagonHost](https://vps123.top/pingtests/idc-bandwagon/20180527 "本期BandwagonHost的全部测速报告")
    * [各地到BandwagonHost某机房](https://vps123.top/pingtests/idc-bandwagon/isp-global/20180527 "以BandwagonHost某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到BandwagonHost各机房](https://vps123.top/pingtests/idc-bandwagon/facility-all/20180527 "以大陆某省份为关注对象的视角，横向比较BandwagonHost各机房")
  * 本期到BandwagonHost _其他机房_ 的报告： 
    * [佛罗里达](/bandwagon/idc/florida/20180527-bandwagon-idc-florida.md "多地到BandwagonHost佛罗里达机房的Ping测试 20180527")
    * [佛利蒙](/bandwagon/idc/fremont/20180527-bandwagon-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180527")
    * [洛杉矶](/bandwagon/idc/losangeles/20180527-bandwagon-idc-losangeles.md "多地到BandwagonHost洛杉矶机房的Ping测试 20180527")
    * [纽约](/bandwagon/idc/newyork/20180527-bandwagon-idc-newyork.md "多地到BandwagonHost纽约机房的Ping测试 20180527")
    * [凤凰城](/bandwagon/idc/phoenix/20180527-bandwagon-idc-phoenix.md "多地到BandwagonHost凤凰城机房的Ping测试 20180527")
    * [温哥华](/bandwagon/idc/vancouver/20180527-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180527")
  * 到BandwagonHost阿姆斯特丹机房的 _其他近期报告_ ： 
    * [20180514](/bandwagon/idc/amsterdam/20180514-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180514")
    * [20180622](/bandwagon/idc/amsterdam/20180622-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180622")
    * [20180804](/bandwagon/idc/amsterdam/20180804-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180804")
    * [20180918](/bandwagon/idc/amsterdam/20180918-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180918")
  * 本期报告：在阿姆斯特丹部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/amsterdam/20180527-bwg-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180527")
    * [Digital Ocean](do/idc/amsterdam/20180527-do-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180527")
    * [Vultr](/vultr/idc/amsterdam/20180527-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180527")



本文最初发表于[多地到BandwagonHost阿姆斯特丹[Amsterdam]机房的Ping测试（20180527）](https://vps123.top/pingtest/20180527-bandwagon-idc-amsterdam.html)
