#  多地到Vultr迈阿密[Miami]机房的Ping测试（20180918） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Vultr迈阿密\[Miami\]机房的Ping测试（20180918）](/images/thumbnails/to_vultr_Chicago.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Vultr](https://vps123.top/go/vultr)的[美国-迈阿密机房](https://vps123.top/vultr-facilities.html#miami)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Vultr](https://vps123.top/go/vultr)的美国-迈阿密机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Vultr全部机房](/vultr/isp/china/20180918-vultr-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180918多地到Vultr美国-迈阿密机房的PING测试结果，连通概况如下：大陆31个省市的1413个有效测试样本中，共有超时点25个；响应均值为284毫秒，最快的三地区为上海、山东、江苏，最慢的三地区为甘肃、宁夏、西藏；江苏、广东、山西、浙江、湖北等11处有响应超时情况；宁夏、甘肃、湖北、上海、浙江等20处丢包率较高。海外17个国家地区的82个有效测试样本中，共有超时点39个；响应均值为202毫秒，最快的三地区为加拿大、台湾、美国，最慢的三地区为菲律宾、俄罗斯、意大利；香港、美国、韩国、新加坡、加拿大等9处有响应超时情况；菲律宾、赞比亚丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Vultr位于迈阿密\[Miami\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/vultr_20180918/plot_idc_vultr_usa-miami_20180918_mainland.png)

**大陆各省份到Vultr美国-迈阿密机房的测速数据 [20180918]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 8个 | 0 | 253ms | 8.6%  
山东 | 90个 | 0 | 263ms | 3.3%  
江苏 | 92个 | 6个 | 265ms | 6.2%  
吉林 | 20个 | 0 | 268ms | 5.8%  
辽宁 | 62个 | 1个 | 269ms | 4.3%  
安徽 | 69个 | 0 | 271ms | 5.7%  
山西 | 57个 | 3个 | 271ms | 1.8%  
河北 | 58个 | 0 | 275ms | 5.5%  
北京 | 8个 | 0 | 276ms | 5.1%  
天津 | 7个 | 0 | 277ms | 3.9%  
浙江 | 66个 | 3个 | 278ms | 8.5%  
福建 | 43个 | 1个 | 280ms | 7.6%  
江西 | 41个 | 0 | 280ms | 4.1%  
广东 | 122个 | 5个 | 280ms | 6.7%  
广西 | 60个 | 0 | 280ms | 7.3%  
均值 | 1413个 | 25个 | 284ms | 5.9%  
四川 | 76个 | 1个 | 285ms | 3.3%  
湖北 | 54个 | 2个 | 285ms | 9.7%  
青海 | 5个 | 0 | 286ms | 0  
黑龙江 | 53个 | 0 | 286ms | 1.2%  
海南 | 13个 | 0 | 287ms | 6.9%  
湖南 | 72个 | 1个 | 289ms | 6.3%  
内蒙古 | 54个 | 0 | 289ms | 4.6%  
贵州 | 43个 | 1个 | 294ms | 8.1%  
河南 | 85个 | 0 | 297ms | 4.6%  
重庆 | 8个 | 0 | 302ms | 8.3%  
陕西 | 43个 | 0 | 304ms | 6.0%  
云南 | 33个 | 0 | 306ms | 7.0%  
新疆 | 31个 | 1个 | 331ms | 8.3%  
甘肃 | 32个 | 0 | 344ms | 16.7%  
宁夏 | 7个 | 0 | 352ms | 17.6%  
西藏 | 1个 | 0 | 416ms | 2.0%  
  
**简评：** 如果你考虑在Vultr的迈阿密[Miami]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于迈阿密[Miami]的机房的连通状况。到此机房的ping监测点共有1413个，其中超时点25个，平均响应时间为284毫秒，丢包率为5%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的24个，超过300毫秒的7个；  
丢包率较高的省份：甘肃、宁夏；

## 海外测速点

![海外各国家地区到VPS提供商Vultr位于迈阿密\[Miami\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180918](/images/pingtests/vultr_20180918/plot_idc_vultr_usa-miami_20180918_overseas.png)

**海外线路到Vultr美国-迈阿密机房的测速数据 [20180918]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
加拿大 | 3个 | 2个 | 46ms | 0  
台湾 | 2个 | 1个 | 64ms | 0  
美国 | 16个 | 11个 | 139ms | 0  
德国 | 3个 | 1个 | 139ms | 0  
香港 | 20个 | 13个 | 155ms | 0  
新加坡 | 5个 | 3个 | 155ms | 0  
韩国 | 12个 | 6个 | 157ms | 0  
荷兰 | 1个 | 0 | 197ms | 0  
均值 | 82个 | 39个 | 202ms | 2.1%  
日本 | 3个 | 0 | 203ms | 1.8%  
澳大利亚 | 2个 | 0 | 246ms | 0.5%  
印度尼西亚 | 1个 | 0 | 286ms | 3.3%  
越南 | 2个 | 0 | 295ms | 0  
马来西亚 | 6个 | 0 | 302ms | 0  
赞比亚 | 2个 | 0 | 306ms | 6.5%  
菲律宾 | 2个 | 0 | 346ms | 18.8%  
俄罗斯 | 1个 | 1个 | - | -  
意大利 | 1个 | 1个 | - | -  
  
**简评：** 如果你考虑在Vultr的迈阿密[Miami]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于迈阿密[Miami]的机房的连通状况。到此机房的ping监测点共有82个，其中超时点39个，平均响应时间为202毫秒，丢包率为2%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的3个，在50-100毫秒间的1个，在100-200毫秒间的6个，在200-300毫秒间的4个，超过300毫秒的3个；  
超时点较多的国家/地区：加拿大、美国、德国、香港、新加坡、韩国；  
丢包率较高的国家/地区：菲律宾；

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180918) 
    * [全部](https://vps123.top/pingtests/20180918 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180918 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180918 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180918 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期到Vultr _其他机房_ 的报告： 
    * [阿姆斯特丹](/vultr/idc/amsterdam/20180918-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180918")
    * [亚特兰大](/vultr/idc/atlanta/20180918-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180918")
    * [芝加哥](/vultr/idc/chicago/20180918-vultr-idc-chicago.md "多地到Vultr芝加哥机房的Ping测试 20180918")
    * [达拉斯](/vultr/idc/dallas/20180918-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180918")
    * [法兰克福](/vultr/idc/frankfurt/20180918-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180918")
    * [伦敦](/vultr/idc/london/20180918-vultr-idc-london.md "多地到Vultr伦敦机房的Ping测试 20180918")
    * [洛杉矶](/vultr/idc/losangeles/20180918-vultr-idc-losangeles.md "多地到Vultr洛杉矶机房的Ping测试 20180918")
    * [新泽西](/vultr/idc/newjersey/20180918-vultr-idc-newjersey.md "多地到Vultr新泽西机房的Ping测试 20180918")
    * [巴黎](/vultr/idc/paris/20180918-vultr-idc-paris.md "多地到Vultr巴黎机房的Ping测试 20180918")
    * [西雅图](/vultr/idc/seattle/20180918-vultr-idc-seattle.md "多地到Vultr西雅图机房的Ping测试 20180918")
    * [硅谷](/vultr/idc/siliconvalley/20180918-vultr-idc-siliconvalley.md "多地到Vultr硅谷机房的Ping测试 20180918")
    * [新加坡](/vultr/idc/singapore/20180918-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180918")
    * [悉尼](/vultr/idc/sydney/20180918-vultr-idc-sydney.md "多地到Vultr悉尼机房的Ping测试 20180918")
    * [东京](/vultr/idc/tokyo/20180918-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180918")
  * 到Vultr迈阿密机房的 _其他近期报告_ ： 
    * [20180514](/vultr/idc/miami/20180514-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180514")
    * [20180527](/vultr/idc/miami/20180527-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180527")
    * [20180622](/vultr/idc/miami/20180622-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180622")
    * [20180804](/vultr/idc/miami/20180804-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180804")



本文最初发表于[多地到Vultr迈阿密[Miami]机房的Ping测试（20180918）](https://vps123.top/pingtest/20180918-vultr-idc-miami.html)
