#  多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180804） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Digital Ocean多伦多\[Toronto\]机房的Ping测试（20180804）](/images/thumbnails/to_do_Toronto.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Digital Ocean](https://vps123.top/go/do)的[加拿大-多伦多机房](https://vps123.top/digitalocean-facilities.html#toronto)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Digital Ocean](https://vps123.top/go/do)的加拿大-多伦多机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Digital Ocean全部机房](/digitalocean/isp/china/20180804-digitalocean-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的4874个有效测试样本中，共有超时点28个；响应均值为280毫秒，最快的三地区为上海、广东、重庆，最慢的三地区为甘肃、新疆、西藏；江苏、江西、浙江、上海有响应超时情况；西藏、天津、宁夏、山西丢包率较高。海外18个国家地区的225个有效测试样本中，共有超时点3个；响应均值为165毫秒，最快的三地区为加拿大、荷兰、意大利，最慢的三地区为菲律宾、印度尼西亚、马来西亚；香港有响应超时情况；美国丢包率较高。

[注册 Digital Ocean](https://vps123.top/go/do/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/do_20180804/plot_idc_do_canada-toronto_20180804_mainland.png)

**大陆各省份到Digital Ocean加拿大-多伦多机房的测速数据 [20180804]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 28个 | 4个 | 251ms | 1.7%  
广东 | 415个 | 0 | 253ms | 1.2%  
重庆 | 37个 | 0 | 259ms | 0.3%  
海南 | 32个 | 0 | 259ms | 4.0%  
山东 | 346个 | 0 | 263ms | 3.2%  
青海 | 16个 | 0 | 264ms | 0  
湖南 | 237个 | 0 | 264ms | 0.2%  
福建 | 149个 | 0 | 266ms | 2.0%  
北京 | 36个 | 0 | 266ms | 3.3%  
浙江 | 218个 | 7个 | 270ms | 1.2%  
广西 | 216个 | 0 | 270ms | 0.8%  
安徽 | 219个 | 0 | 270ms | 4.9%  
天津 | 20个 | 0 | 272ms | 8.7%  
宁夏 | 32个 | 0 | 273ms | 5.2%  
陕西 | 138个 | 0 | 278ms | 0.9%  
云南 | 119个 | 0 | 280ms | 4.6%  
均值 | 4874个 | 28个 | 280ms | 2.7%  
江西 | 131个 | 8个 | 281ms | 1.8%  
河北 | 220个 | 0 | 281ms | 3.7%  
江苏 | 331个 | 9个 | 283ms | 2.6%  
湖北 | 177个 | 0 | 285ms | 3.1%  
山西 | 177个 | 0 | 287ms | 5.1%  
河南 | 327个 | 0 | 289ms | 4.9%  
辽宁 | 218个 | 0 | 291ms | 3.3%  
四川 | 258个 | 0 | 292ms | 1.2%  
贵州 | 130个 | 0 | 292ms | 0.5%  
黑龙江 | 148个 | 0 | 296ms | 3.0%  
内蒙古 | 204个 | 0 | 301ms | 4.4%  
吉林 | 68个 | 0 | 307ms | 4.5%  
甘肃 | 104个 | 0 | 311ms | 1.6%  
新疆 | 115个 | 0 | 334ms | 2.9%  
西藏 | 8个 | 0 | 500ms | 26.5%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有4874个，其中超时点28个，平均响应时间为280毫秒，丢包率为2%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的26个，超过300毫秒的5个；  
超时点较多的省份：上海；  
丢包率较高的省份：西藏；

## 海外测速点

![海外各国家地区到VPS提供商Digital Ocean位于多伦多\[Toronto\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180804](/images/pingtests/do_20180804/plot_idc_do_canada-toronto_20180804_overseas.png)

**海外线路到Digital Ocean加拿大-多伦多机房的测速数据 [20180804]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
加拿大 | 12个 | 0 | 12ms | 0  
荷兰 | 3个 | 0 | 55ms | 0  
意大利 | 3个 | 0 | 81ms | -  
巴西 | 3个 | 0 | 86ms | 0  
美国 | 48个 | 0 | 97ms | 9.8%  
德国 | 9个 | 0 | 113ms | 0  
俄罗斯 | 3个 | 0 | 142ms | -  
英国 | 6个 | 0 | 152ms | 0.5%  
均值 | 225个 | 3个 | 165ms | 1.0%  
日本 | 3个 | 0 | 182ms | 2.0%  
新加坡 | 15个 | 0 | 203ms | 0  
香港 | 63个 | 3个 | 204ms | 0  
韩国 | 21个 | 0 | 205ms | 0  
南非 | 6个 | 0 | 206ms | 2.5%  
澳大利亚 | 6个 | 0 | 221ms | 0  
台湾 | 3个 | 0 | 237ms | 0  
菲律宾 | 3个 | 0 | 255ms | 0  
印度尼西亚 | 6个 | 0 | 260ms | 0  
马来西亚 | 12个 | 0 | 269ms | 1.8%  
  
**简评：** 如果你考虑在Digital Ocean的多伦多[Toronto]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于多伦多[Toronto]的机房的连通状况。到此机房的ping监测点共有225个，其中超时点3个，平均响应时间为165毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的4个，在100-200毫秒间的4个，在200-300毫秒间的9个；

[注册 Digital Ocean](https://vps123.top/go/do/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180804) 
    * [全部](https://vps123.top/pingtests/20180804 "本期各VPS提供商全部测速报告")
    * [Digital Ocean](https://vps123.top/pingtests/idc-digitalocean/20180804 "本期Digital Ocean的全部测速报告")
    * [各地到Digital Ocean某机房](https://vps123.top/pingtests/idc-digitalocean/isp-global/20180804 "以Digital Ocean某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Digital Ocean各机房](https://vps123.top/pingtests/idc-digitalocean/facility-all/20180804 "以大陆某省份为关注对象的视角，横向比较Digital Ocean各机房")
  * 本期到Digital Ocean _其他机房_ 的报告： 
    * [阿姆斯特丹](/digitalocean/idc/amsterdam/20180804-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180804")
    * [班加罗尔](/digitalocean/idc/bangalore/20180804-digitalocean-idc-bangalore.md "多地到Digital Ocean班加罗尔机房的Ping测试 20180804")
    * [法兰克福](/digitalocean/idc/frankfurt/20180804-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180804")
    * [伦敦](/digitalocean/idc/london/20180804-digitalocean-idc-london.md "多地到Digital Ocean伦敦机房的Ping测试 20180804")
    * [纽约](/digitalocean/idc/newyork/20180804-digitalocean-idc-newyork.md "多地到Digital Ocean纽约机房的Ping测试 20180804")
    * [旧金山](/digitalocean/idc/sanfrancisco/20180804-digitalocean-idc-sanfrancisco.md "多地到Digital Ocean旧金山机房的Ping测试 20180804")
    * [新加坡](/digitalocean/idc/singapore/20180804-digitalocean-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180804")
  * 到Digital Ocean多伦多机房的 _其他近期报告_ ： 
    * [20180514](/digitalocean/idc/toronto/20180514-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180514")
    * [20180527](/digitalocean/idc/toronto/20180527-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180527")
    * [20180622](/digitalocean/idc/toronto/20180622-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180622")
    * [20180918](/digitalocean/idc/toronto/20180918-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180918")



本文最初发表于[多地到Digital Ocean多伦多[Toronto]机房的Ping测试（20180804）](https://vps123.top/pingtest/20180804-digitalocean-idc-toronto.html)
