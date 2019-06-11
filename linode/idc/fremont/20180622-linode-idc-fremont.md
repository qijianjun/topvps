#  多地到Linode佛利蒙[Fremont]机房的Ping测试（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode佛利蒙\[Fremont\]机房的Ping测试（20180622）](/images/thumbnails/to_linode_Fremont.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-佛利蒙机房](https://vps123.top/linode-facilities.html#fremont)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-佛利蒙机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180622-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的905个有效测试样本中，共有超时点16个；响应均值为196毫秒，最快的三地区为天津、广东、北京，最慢的三地区为甘肃、新疆、香港；云南、江苏、浙江、上海、安徽等7处有响应超时情况；河南、海南、青海丢包率较高。海外18个国家地区的82个有效测试样本中，无超时点；响应均值为164毫秒，最快的三地区为美国、加拿大、日本，最慢的三地区为澳大利亚、马来西亚、柬埔寨。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/linode_20180622/plot_idc_linode_usa-fremont_20180622_mainland.png)

大陆各省份到Linode美国-佛利蒙机房的测速数据 [20180622] 省份 | 测速点 | 超时点 | 响应时间 | 丢包率 | 省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
天津 | 3个 | 0 | 166ms | 0 | 河北 | 35个 | 0 | 197ms | 2.8%  
广东 | 79个 | 0 | 178ms | 0.6% | 宁夏 | 14个 | 0 | 198ms | 2.2%  
北京 | 10个 | 0 | 178ms | 1.0% | 山西 | 37个 | 0 | 198ms | 1.8%  
上海 | 8个 | 1个 | 179ms | 2.7% | 吉林 | 15个 | 0 | 199ms | 0.7%  
福建 | 30个 | 0 | 184ms | 0.3% | 山东 | 46个 | 0 | 200ms | 2.0%  
安徽 | 34个 | 1个 | 184ms | 1.9% | 贵州 | 24个 | 0 | 204ms | 3.8%  
江苏 | 66个 | 2个 | 186ms | 1.2% | 辽宁 | 32个 | 0 | 204ms | 1.8%  
广西 | 44个 | 0 | 187ms | 0.7% | 陕西 | 25个 | 1个 | 206ms | 2.0%  
湖北 | 34个 | 0 | 189ms | 0.7% | 云南 | 23个 | 8个 | 209ms | 1.6%  
江西 | 22个 | 0 | 190ms | 0.8% | 内蒙古 | 34个 | 0 | 209ms | 1.4%  
河南 | 50个 | 1个 | 191ms | 6.9% | 黑龙江 | 27个 | 0 | 213ms | 1.6%  
浙江 | 50个 | 2个 | 191ms | 0.7% | 四川 | 40个 | 0 | 220ms | 1.4%  
重庆 | 13个 | 0 | 192ms | 1.2% | 青海 | 5个 | 0 | 220ms | 5.2%  
湖南 | 37个 | 0 | 194ms | 0.4% | 甘肃 | 16个 | 0 | 220ms | 4.6%  
海南 | 10个 | 0 | 196ms | 6.3% | 新疆 | 21个 | 0 | 245ms | 2.5%  
均值 | 905个 | 16个 | 196ms | 1.9% | 香港 | 21个 | 0 | - | -  
  
简评：如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有905个，其中超时点16个，平均响应时间为196毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在100-200毫秒间的20个，在200-300毫秒间的10个；  
超时点较多的省份：上海、云南；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于佛利蒙\[Fremont\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/linode_20180622/plot_idc_linode_usa-fremont_20180622_overseas.png)

海外线路到Linode美国-佛利蒙机房的测速数据 [20180622] 国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率 | 国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---|---|---|---|---|---  
美国 | 20个 | 0 | 31ms | 0 | 韩国 | 14个 | 0 | 157ms | 0  
加拿大 | 2个 | 0 | 90ms | 0 | 英国 | 1个 | 0 | 161ms | 0  
日本 | 2个 | 0 | 131ms | 2.0% | 均值 | 82个 | 0 | 164ms | 0.2%  
台湾 | 1个 | 0 | 134ms | 0 | 南非 | 2个 | 0 | 172ms | 0  
香港 | 21个 | 0 | 137ms | 0.9% | 菲律宾 | 2个 | 0 | 184ms | 0  
巴西 | 1个 | 0 | 141ms | 0 | 越南 | 2个 | 0 | 205ms | 0  
新加坡 | 5个 | 0 | 142ms | 0 | 澳大利亚 | 1个 | 0 | 226ms | 0  
意大利 | 1个 | 0 | 144ms | - | 马来西亚 | 4个 | 0 | 265ms | 0  
德国 | 1个 | 0 | 146ms | - | 柬埔寨 | 1个 | 0 | 342ms | 0  
法国 | 1个 | 0 | 150ms | 0 |  |  |  |  |   
  
简评：如果你考虑在Linode的佛利蒙[Fremont]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于佛利蒙[Fremont]的机房的连通状况。到此机房的ping监测点共有82个，其中超时点0个，平均响应时间为164毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的1个，在100-200毫秒间的12个，在200-300毫秒间的3个，超过300毫秒的1个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180622) 
    * [全部](https://vps123.top/pingtests/20180622 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180622 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180622 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180622 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180622-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180622")
    * [达拉斯](/linode/idc/dallas/20180622-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180622")
    * [法兰克福](/linode/idc/frankfurt/20180622-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180622")
    * [伦敦](/linode/idc/london/20180622-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180622")
    * [纽瓦克](/linode/idc/newark/20180622-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180622")
    * [新加坡](/linode/idc/singapore/20180622-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180622")
    * [东京](/linode/idc/tokyo/20180622-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180622")
  * 到Linode佛利蒙机房的 _其他近期报告_ ： 
    * [20180514](/linode/idc/fremont/20180514-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180514")
    * [20180527](/linode/idc/fremont/20180527-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180527")
    * [20180804](/linode/idc/fremont/20180804-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180804")
    * [20180918](/linode/idc/fremont/20180918-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180918")
  * 本期报告：在佛利蒙部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/fremont/20180622-bwg-idc-fremont.md "多地到BandwagonHost佛利蒙机房的Ping测试 20180622")



本文最初发表于[多地到Linode佛利蒙[Fremont]机房的Ping测试（20180622）](https://vps123.top/pingtest/20180622-linode-idc-fremont.html)