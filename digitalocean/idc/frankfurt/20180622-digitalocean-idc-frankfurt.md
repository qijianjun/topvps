#  多地到Digital Ocean法兰克福[Frankfurt]机房的Ping测试（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Digital Ocean法兰克福\[Frankfurt\]机房的Ping测试（20180622）](/images/thumbnails/to_do_Frankfurt.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Digital Ocean](https://vps123.top/go/do)的[德国-法兰克福机房](https://vps123.top/digitalocean-facilities.html#frankfurt)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Digital Ocean](https://vps123.top/go/do)的德国-法兰克福机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Digital Ocean全部机房](/digitalocean/isp/china/20180622-digitalocean-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的895个有效测试样本中，共有超时点21个；响应均值为279毫秒，最快的三地区为天津、北京、安徽，最慢的三地区为贵州、新疆、香港；云南、江苏、安徽、上海、广东等12处有响应超时情况。海外17个国家地区的50个有效测试样本中，无超时点；响应均值为199毫秒，最快的三地区为法国、巴西、英国，最慢的三地区为台湾、澳大利亚、柬埔寨。

[注册 Digital Ocean](https://vps123.top/go/do/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Digital Ocean位于法兰克福\[Frankfurt\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/do_20180622/plot_idc_do_germany-frankfurt_20180622_mainland.png)

**大陆各省份到Digital Ocean德国-法兰克福机房的测速数据 [20180622]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
天津 | 3个 | 0 | 210ms | 0  
北京 | 10个 | 0 | 245ms | 1.2%  
安徽 | 37个 | 1个 | 257ms | 0.4%  
青海 | 5个 | 0 | 259ms | 1.8%  
上海 | 8个 | 1个 | 259ms | 1.6%  
江西 | 23个 | 0 | 260ms | 0.8%  
河北 | 34个 | 0 | 261ms | 1.0%  
广东 | 73个 | 1个 | 262ms | 1.5%  
浙江 | 50个 | 1个 | 263ms | 3.8%  
内蒙古 | 34个 | 0 | 263ms | 1.4%  
江苏 | 63个 | 2个 | 267ms | 0.7%  
宁夏 | 14个 | 0 | 271ms | 1.4%  
重庆 | 12个 | 0 | 272ms | 1.5%  
广西 | 44个 | 0 | 274ms | 1.7%  
甘肃 | 17个 | 1个 | 276ms | 2.4%  
海南 | 11个 | 0 | 278ms | 1.8%  
湖北 | 34个 | 0 | 279ms | 1.9%  
均值 | 895个 | 21个 | 279ms | 1.9%  
陕西 | 29个 | 0 | 282ms | 1.1%  
辽宁 | 35个 | 1个 | 283ms | 0.4%  
云南 | 23个 | 9个 | 284ms | 1.1%  
福建 | 31个 | 0 | 285ms | 0.9%  
河南 | 50个 | 1个 | 288ms | 4.4%  
黑龙江 | 31个 | 1个 | 289ms | 1.9%  
湖南 | 37个 | 0 | 291ms | 1.7%  
山西 | 35个 | 0 | 296ms | 2.2%  
吉林 | 17个 | 0 | 301ms | 3.3%  
山东 | 37个 | 0 | 303ms | 1.4%  
四川 | 42个 | 0 | 306ms | 4.5%  
贵州 | 24个 | 1个 | 306ms | 3.7%  
新疆 | 20个 | 1个 | 319ms | 1.2%  
香港 | 12个 | 0 | - | -  
  
**简评：** 如果你考虑在Digital Ocean的法兰克福[Frankfurt]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于法兰克福[Frankfurt]的机房的连通状况。到此机房的ping监测点共有895个，其中超时点21个，平均响应时间为279毫秒，丢包率为1%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在200-300毫秒间的25个，超过300毫秒的5个；  
超时点较多的省份：上海、云南；

## 海外测速点

![海外各国家地区到VPS提供商Digital Ocean位于法兰克福\[Frankfurt\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/do_20180622/plot_idc_do_germany-frankfurt_20180622_overseas.png)

**海外线路到Digital Ocean德国-法兰克福机房的测速数据 [20180622]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
法国 | 1个 | 0 | 0 | 0  
巴西 | 1个 | 0 | 10ms | 0  
英国 | 1个 | 0 | 57ms | 0  
加拿大 | 1个 | 0 | 129ms | 0  
美国 | 10个 | 0 | 141ms | 0  
新加坡 | 2个 | 0 | 160ms | 0  
印度尼西亚 | 1个 | 0 | 189ms | 0  
香港 | 12个 | 0 | 192ms | 0  
南非 | 2个 | 0 | 195ms | 0  
均值 | 50个 | 0 | 199ms | 0.4%  
菲律宾 | 2个 | 0 | 234ms | 0  
韩国 | 7个 | 0 | 242ms | 0.1%  
马来西亚 | 4个 | 0 | 264ms | 4.5%  
日本 | 1个 | 0 | 280ms | 2.0%  
越南 | 2个 | 0 | 283ms | 0  
台湾 | 1个 | 0 | 284ms | 0  
澳大利亚 | 1个 | 0 | 333ms | 0  
柬埔寨 | 1个 | 0 | 388ms | 0  
  
**简评：** 如果你考虑在Digital Ocean的法兰克福[Frankfurt]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于法兰克福[Frankfurt]的机房的连通状况。到此机房的ping监测点共有50个，其中超时点0个，平均响应时间为199毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在50-100毫秒间的1个，在100-200毫秒间的6个，在200-300毫秒间的6个，超过300毫秒的2个；

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
    * [伦敦](/digitalocean/idc/london/20180622-digitalocean-idc-london.md "多地到Digital Ocean伦敦机房的Ping测试 20180622")
    * [纽约](/digitalocean/idc/newyork/20180622-digitalocean-idc-newyork.md "多地到Digital Ocean纽约机房的Ping测试 20180622")
    * [旧金山](/digitalocean/idc/sanfrancisco/20180622-digitalocean-idc-sanfrancisco.md "多地到Digital Ocean旧金山机房的Ping测试 20180622")
    * [新加坡](/digitalocean/idc/singapore/20180622-digitalocean-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180622")
    * [多伦多](/digitalocean/idc/toronto/20180622-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180622")
  * 到Digital Ocean法兰克福机房的 _其他近期报告_ ： 
    * [20180514](/digitalocean/idc/frankfurt/20180514-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180514")
    * [20180527](/digitalocean/idc/frankfurt/20180527-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180527")
    * [20180804](/digitalocean/idc/frankfurt/20180804-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180804")
    * [20180918](/digitalocean/idc/frankfurt/20180918-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180918")
  * 本期报告：在法兰克福部署机房的 _其他VPS提供商_ ： 
    * [Digital Ocean](do/idc/frankfurt/20180622-do-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180622")
    * [Linode](/linode/idc/frankfurt/20180622-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180622")
    * [Vultr](/vultr/idc/frankfurt/20180622-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180622")



本文最初发表于[多地到Digital Ocean法兰克福[Frankfurt]机房的Ping测试（20180622）](https://vps123.top/pingtest/20180622-digitalocean-idc-frankfurt.html)
