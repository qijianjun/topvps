#  多地到Digital Ocean阿姆斯特丹[Amsterdam]机房的Ping测试（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Digital Ocean阿姆斯特丹\[Amsterdam\]机房的Ping测试（20180514）](/images/thumbnails/to_do_Amsterdam.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Digital Ocean](https://vps123.top/go/do)的[荷兰-阿姆斯特丹机房](https://vps123.top/digitalocean-facilities.html#amsterdam)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Digital Ocean](https://vps123.top/go/do)的荷兰-阿姆斯特丹机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Digital Ocean全部机房](/digitalocean/isp/china/20180514-digitalocean-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514多地到Digital Ocean荷兰-阿姆斯特丹机房的PING测试结果，连通概况如下：大陆31个省市的1900个有效测试样本中，共有超时点28个；响应均值为302毫秒，最快的三地区为上海、天津、安徽，最慢的三地区为吉林、新疆、西藏；浙江、广东、山东、广西、福建等10处有响应超时情况；江苏、浙江、天津、北京丢包率较高。海外19个国家地区的163个有效测试样本中，共有超时点1个；响应均值为187毫秒，最快的三地区为荷兰、法国、德国，最慢的三地区为台湾、澳大利亚、柬埔寨；美国有响应超时情况；柬埔寨丢包率较高。

[注册 Digital Ocean](https://vps123.top/go/do/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Digital Ocean位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/do_20180514/plot_idc_do_netherlands-amsterdam_20180514_mainland.png)

**大陆各省份到Digital Ocean荷兰-阿姆斯特丹机房的测速数据 [20180514]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 16个 | 0 | 248ms | 0.1%  
天津 | 10个 | 0 | 259ms | 7.1%  
安徽 | 79个 | 1个 | 260ms | 4.1%  
重庆 | 32个 | 1个 | 278ms | 0.1%  
河北 | 66个 | 0 | 281ms | 4.3%  
广西 | 74个 | 2个 | 283ms | 1.4%  
海南 | 21个 | 0 | 283ms | 3.2%  
青海 | 8个 | 0 | 285ms | 0.4%  
福建 | 69个 | 2个 | 287ms | 3.2%  
湖北 | 83个 | 0 | 291ms | 3.7%  
江西 | 46个 | 0 | 291ms | 4.1%  
广东 | 159个 | 6个 | 291ms | 3.4%  
湖南 | 89个 | 0 | 291ms | 3.5%  
内蒙古 | 67个 | 0 | 293ms | 3.0%  
四川 | 98个 | 0 | 301ms | 2.5%  
均值 | 1900个 | 28个 | 302ms | 3.9%  
江苏 | 118个 | 2个 | 303ms | 8.6%  
云南 | 48个 | 0 | 305ms | 1.7%  
浙江 | 97个 | 8个 | 306ms | 7.8%  
甘肃 | 43个 | 0 | 306ms | 1.2%  
辽宁 | 77个 | 0 | 307ms | 4.5%  
宁夏 | 23个 | 0 | 309ms | 1.9%  
河南 | 110个 | 1个 | 312ms | 3.6%  
陕西 | 65个 | 0 | 316ms | 4.8%  
山西 | 73个 | 0 | 316ms | 4.2%  
北京 | 14个 | 2个 | 317ms | 6.5%  
山东 | 102个 | 3个 | 320ms | 4.9%  
贵州 | 55个 | 0 | 320ms | 5.0%  
黑龙江 | 74个 | 0 | 338ms | 4.6%  
吉林 | 28个 | 0 | 340ms | 4.3%  
新疆 | 54个 | 0 | 353ms | 2.2%  
西藏 | 2个 | 0 | 378ms | 0  
  
**简评：** 如果你考虑在Digital Ocean的阿姆斯特丹[Amsterdam]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有1900个，其中超时点28个，平均响应时间为302毫秒，丢包率为3%，本站评价等级为 **很差** ，十分不推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的14个，超过300毫秒的17个；  
超时点较多的省份：北京；

## 海外测速点

![海外各国家地区到VPS提供商Digital Ocean位于阿姆斯特丹\[Amsterdam\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/do_20180514/plot_idc_do_netherlands-amsterdam_20180514_overseas.png)

**海外线路到Digital Ocean荷兰-阿姆斯特丹机房的测速数据 [20180514]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
荷兰 | 2个 | 0 | 1ms | 0  
法国 | 4个 | 0 | 8ms | 0  
德国 | 4个 | 0 | 21ms | 0  
英国 | 4个 | 0 | 24ms | 0  
加拿大 | 6个 | 0 | 96ms | 0.5%  
俄罗斯 | 2个 | 0 | 102ms | 0  
美国 | 38个 | 1个 | 142ms | 0  
印度尼西亚 | 2个 | 0 | 187ms | 0.5%  
均值 | 163个 | 1个 | 187ms | 1.8%  
新加坡 | 12个 | 0 | 189ms | 0  
南非 | 4个 | 0 | 193ms | 0  
巴西 | 1个 | 0 | 197ms | 0  
马来西亚 | 6个 | 0 | 217ms | 0.2%  
菲律宾 | 2个 | 0 | 237ms | 0.5%  
日本 | 4个 | 0 | 265ms | 0.5%  
香港 | 38个 | 0 | 274ms | 0  
韩国 | 26个 | 0 | 282ms | 0  
台湾 | 2个 | 0 | 298ms | -  
澳大利亚 | 4个 | 0 | 311ms | 0  
柬埔寨 | 2个 | 0 | 514ms | 31.0%  
  
**简评：** 如果你考虑在Digital Ocean的阿姆斯特丹[Amsterdam]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于阿姆斯特丹[Amsterdam]的机房的连通状况。到此机房的ping监测点共有163个，其中超时点1个，平均响应时间为187毫秒，丢包率为1%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的4个，在50-100毫秒间的1个，在100-200毫秒间的6个，在200-300毫秒间的6个，超过300毫秒的2个；  
丢包率较高的国家/地区：柬埔寨；

[注册 Digital Ocean](https://vps123.top/go/do/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Digital Ocean](https://vps123.top/pingtests/idc-digitalocean/20180514 "本期Digital Ocean的全部测速报告")
    * [各地到Digital Ocean某机房](https://vps123.top/pingtests/idc-digitalocean/isp-global/20180514 "以Digital Ocean某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Digital Ocean各机房](https://vps123.top/pingtests/idc-digitalocean/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Digital Ocean各机房")
  * 本期到Digital Ocean _其他机房_ 的报告： 
    * [班加罗尔](/digitalocean/idc/bangalore/20180514-digitalocean-idc-bangalore.md "多地到Digital Ocean班加罗尔机房的Ping测试 20180514")
    * [法兰克福](/digitalocean/idc/frankfurt/20180514-digitalocean-idc-frankfurt.md "多地到Digital Ocean法兰克福机房的Ping测试 20180514")
    * [伦敦](/digitalocean/idc/london/20180514-digitalocean-idc-london.md "多地到Digital Ocean伦敦机房的Ping测试 20180514")
    * [纽约](/digitalocean/idc/newyork/20180514-digitalocean-idc-newyork.md "多地到Digital Ocean纽约机房的Ping测试 20180514")
    * [旧金山](/digitalocean/idc/sanfrancisco/20180514-digitalocean-idc-sanfrancisco.md "多地到Digital Ocean旧金山机房的Ping测试 20180514")
    * [新加坡](/digitalocean/idc/singapore/20180514-digitalocean-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180514")
    * [多伦多](/digitalocean/idc/toronto/20180514-digitalocean-idc-toronto.md "多地到Digital Ocean多伦多机房的Ping测试 20180514")
  * 到Digital Ocean阿姆斯特丹机房的 _其他近期报告_ ： 
    * [20180527](/digitalocean/idc/amsterdam/20180527-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180527")
    * [20180622](/digitalocean/idc/amsterdam/20180622-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180622")
    * [20180804](/digitalocean/idc/amsterdam/20180804-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180804")
    * [20180918](/digitalocean/idc/amsterdam/20180918-digitalocean-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180918")
  * 本期报告：在阿姆斯特丹部署机房的 _其他VPS提供商_ ： 
    * [BandwagonHost](/bandwagon/idc/amsterdam/20180514-bwg-idc-amsterdam.md "多地到BandwagonHost阿姆斯特丹机房的Ping测试 20180514")
    * [Digital Ocean](do/idc/amsterdam/20180514-do-idc-amsterdam.md "多地到Digital Ocean阿姆斯特丹机房的Ping测试 20180514")
    * [Vultr](/vultr/idc/amsterdam/20180514-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180514")



本文最初发表于[多地到Digital Ocean阿姆斯特丹[Amsterdam]机房的Ping测试（20180514）](https://vps123.top/pingtest/20180514-digitalocean-idc-amsterdam.html)
