#  多地到BandwagonHost温哥华[Vancouver]机房的Ping测试（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到BandwagonHost温哥华\[Vancouver\]机房的Ping测试（20180514）](/images/thumbnails/to_bwg_Vancouver.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[BandwagonHost](https://vps123.top/go/bwg)的[加拿大-温哥华机房](https://vps123.top/bandwagon-facilities.html#vancouver)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[BandwagonHost](https://vps123.top/go/bwg)的加拿大-温哥华机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[BandwagonHost全部机房](/bandwagon/isp/china/20180514-bandwagon-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514多地到BandwagonHost加拿大-温哥华机房的PING测试结果，连通概况如下：大陆28个省市的193个有效测试样本中，共有超时点12个；响应均值为232毫秒，最快的三地区为海南、甘肃、天津，最慢的三地区为山东、山西、新疆；浙江、陕西、江苏、广东、安徽等9处有响应超时情况；山西、新疆、辽宁、广西、湖南等10处丢包率较高。海外13个国家地区的56个有效测试样本中，无超时点；响应均值为151毫秒，最快的三地区为美国、加拿大、日本，最慢的三地区为新加坡、香港、俄罗斯。

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商BandwagonHost位于温哥华\[Vancouver\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/bwg_20180514/plot_idc_bwg_canada-vancouver_20180514_mainland.png)

**大陆各省份到BandwagonHost加拿大-温哥华机房的测速数据 [20180514]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
海南 | 1个 | 0 | 186ms | 0  
甘肃 | 1个 | 0 | 192ms | 0  
天津 | 2个 | 0 | 198ms | 0  
上海 | 3个 | 0 | 203ms | 0  
江苏 | 22个 | 1个 | 207ms | 1.7%  
广东 | 26个 | 1个 | 215ms | 2.7%  
浙江 | 24个 | 3个 | 216ms | 2.1%  
安徽 | 5个 | 1个 | 218ms | 0  
河南 | 9个 | 0 | 220ms | 2.2%  
湖南 | 7个 | 1个 | 222ms | 10.0%  
北京 | 5个 | 0 | 223ms | 0  
黑龙江 | 4个 | 0 | 226ms | 0  
均值 | 193个 | 12个 | 232ms | 4.2%  
重庆 | 6个 | 1个 | 234ms | 1.1%  
吉林 | 1个 | 0 | 235ms | 6.7%  
福建 | 15个 | 1个 | 238ms | 7.3%  
陕西 | 8个 | 2个 | 240ms | 2.5%  
湖北 | 8个 | 0 | 242ms | 0  
广西 | 4个 | 0 | 242ms | 11.1%  
云南 | 2个 | 0 | 252ms | 0  
江西 | 4个 | 0 | 254ms | 5.0%  
辽宁 | 7个 | 0 | 257ms | 13.3%  
内蒙古 | 3个 | 0 | 262ms | 2.2%  
四川 | 6个 | 0 | 268ms | 5.0%  
贵州 | 7个 | 0 | 271ms | 7.8%  
河北 | 2个 | 0 | 274ms | 8.3%  
山东 | 6个 | 1个 | 286ms | 6.7%  
山西 | 3个 | 0 | 317ms | 33.3%  
新疆 | 2个 | 0 | 353ms | 23.3%  
  
**简评：** 如果你考虑在BandwagonHost的温哥华[Vancouver]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于温哥华[Vancouver]的机房的连通状况。到此机房的ping监测点共有193个，其中超时点12个，平均响应时间为232毫秒，丢包率为4%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在100-200毫秒间的3个，在200-300毫秒间的23个，超过300毫秒的2个；  
超时点较多的省份：浙江、安徽、湖南、重庆、陕西、山东；  
丢包率较高的省份：湖南、广西、辽宁、山西、新疆；

## 海外测速点

![海外各国家地区到VPS提供商BandwagonHost位于温哥华\[Vancouver\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/bwg_20180514/plot_idc_bwg_canada-vancouver_20180514_overseas.png)

**海外线路到BandwagonHost加拿大-温哥华机房的测速数据 [20180514]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
美国 | 19个 | 0 | 34ms | 4.4%  
加拿大 | 1个 | 0 | 69ms | -  
日本 | 1个 | 0 | 85ms | 0  
英国 | 1个 | 0 | 133ms | 0  
德国 | 1个 | 0 | 151ms | 0  
均值 | 56个 | 0 | 151ms | 0.6%  
台湾 | 1个 | 0 | 157ms | -  
韩国 | 11个 | 0 | 166ms | 0  
巴西 | 1个 | 0 | 172ms | 0  
澳大利亚 | 1个 | 0 | 176ms | 0  
马来西亚 | 1个 | 0 | 179ms | 0  
新加坡 | 3个 | 0 | 198ms | 0  
香港 | 14个 | 0 | 205ms | 2.0%  
俄罗斯 | 1个 | 0 | 238ms | 0  
  
**简评：** 如果你考虑在BandwagonHost的温哥华[Vancouver]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于温哥华[Vancouver]的机房的连通状况。到此机房的ping监测点共有56个，其中超时点0个，平均响应时间为151毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的2个，在100-200毫秒间的8个，在200-300毫秒间的2个；

[注册 BandwagonHost](https://vps123.top/go/bwg/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [BandwagonHost](https://vps123.top/pingtests/idc-bandwagon/20180514 "本期BandwagonHost的全部测速报告")
    * [各地到BandwagonHost某机房](https://vps123.top/pingtests/idc-bandwagon/isp-global/20180514 "以BandwagonHost某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到BandwagonHost各机房](https://vps123.top/pingtests/idc-bandwagon/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较BandwagonHost各机房")
  * 本期到BandwagonHost _其他机房_ 的报告： 
    * [阿姆斯特丹](/bandwagon/idc/amsterdam/20180514-bandwagon-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180514")
    * [佛罗里达](/bandwagon/idc/florida/20180514-bandwagon-idc-florida.md "多地到BandwagonHost佛罗里达机房的Ping测试 20180514")
    * [佛利蒙](/bandwagon/idc/fremont/20180514-bandwagon-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180514")
    * [香港](/bandwagon/idc/hongkong/20180514-bandwagon-idc-hongkong.md "多地到BandwagonHost香港机房的Ping测试 20180514")
    * [洛杉矶](/bandwagon/idc/losangeles/20180514-bandwagon-idc-losangeles.md "多地到BandwagonHost洛杉矶机房的Ping测试 20180514")
    * [纽约](/bandwagon/idc/newyork/20180514-bandwagon-idc-newyork.md "多地到BandwagonHost纽约机房的Ping测试 20180514")
    * [凤凰城](/bandwagon/idc/phoenix/20180514-bandwagon-idc-phoenix.md "多地到BandwagonHost凤凰城机房的Ping测试 20180514")
  * 到BandwagonHost温哥华机房的 _其他近期报告_ ： 
    * [20180527](/bandwagon/idc/vancouver/20180527-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180527")
    * [20180622](/bandwagon/idc/vancouver/20180622-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180622")
    * [20180804](/bandwagon/idc/vancouver/20180804-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180804")
    * [20180918](/bandwagon/idc/vancouver/20180918-bandwagon-idc-vancouver.md "多地到BandwagonHost温哥华机房的Ping测试 20180918")



本文最初发表于[多地到BandwagonHost温哥华[Vancouver]机房的Ping测试（20180514）](https://vps123.top/pingtest/20180514-bandwagon-idc-vancouver.html)
