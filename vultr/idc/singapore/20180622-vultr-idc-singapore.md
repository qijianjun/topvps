#  多地到Vultr新加坡[Singapore]机房的Ping测试（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Vultr新加坡\[Singapore\]机房的Ping测试（20180622）](/images/thumbnails/to_vultr_Singapore.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Vultr](https://vps123.top/go/vultr)的[新加坡-新加坡机房](https://vps123.top/vultr-facilities.html#singapore)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Vultr](https://vps123.top/go/vultr)的新加坡-新加坡机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Vultr全部机房](/vultr/isp/china/20180622-vultr-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

大陆31个省市的891个有效测试样本中，共有超时点36个；响应均值为235毫秒，最快的三地区为福建、湖南、河南，最慢的三地区为云南、吉林、香港；云南、浙江、江苏、辽宁、福建等16处有响应超时情况；青海、甘肃、天津、上海、浙江等30处丢包率较高。海外12个国家地区的68个有效测试样本中，共有超时点1个；响应均值为160毫秒，最快的三地区为新加坡、日本、香港，最慢的三地区为德国、意大利、加拿大；香港有响应超时情况。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Vultr位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/vultr_20180622/plot_idc_vultr_singapore-singapore_20180622_mainland.png)

**大陆各省份到Vultr新加坡-新加坡机房的测速数据 [20180622]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
福建 | 25个 | 1个 | 200ms | 8.5%  
湖南 | 33个 | 0 | 201ms | 7.6%  
河南 | 45个 | 1个 | 202ms | 12.1%  
广西 | 41个 | 1个 | 207ms | 8.3%  
安徽 | 31个 | 1个 | 208ms | 8.7%  
贵州 | 24个 | 0 | 210ms | 8.9%  
山东 | 43个 | 1个 | 210ms | 9.4%  
广东 | 78个 | 1个 | 211ms | 6.7%  
江西 | 25个 | 0 | 215ms | 10.4%  
陕西 | 25个 | 1个 | 222ms | 11.5%  
浙江 | 53个 | 6个 | 223ms | 12.8%  
海南 | 12个 | 0 | 225ms | 8.4%  
江苏 | 69个 | 6个 | 226ms | 11.9%  
均值 | 891个 | 36个 | 235ms | 9.7%  
青海 | 5个 | 1个 | 237ms | 15.0%  
湖北 | 33个 | 0 | 241ms | 11.7%  
北京 | 10个 | 0 | 242ms | 12.3%  
黑龙江 | 31个 | 0 | 243ms | 10.1%  
山西 | 33个 | 0 | 245ms | 6.0%  
宁夏 | 13个 | 0 | 248ms | 9.0%  
上海 | 7个 | 1个 | 256ms | 13.0%  
甘肃 | 14个 | 0 | 257ms | 14.2%  
河北 | 31个 | 0 | 264ms | 8.3%  
辽宁 | 36个 | 2个 | 264ms | 10.8%  
重庆 | 12个 | 0 | 273ms | 7.9%  
内蒙古 | 28个 | 0 | 278ms | 10.5%  
天津 | 2个 | 0 | 280ms | 13.3%  
四川 | 41个 | 1个 | 282ms | 8.1%  
新疆 | 25个 | 1个 | 291ms | 9.9%  
云南 | 22个 | 10个 | 291ms | 10.9%  
吉林 | 20个 | 0 | 301ms | 8.8%  
香港 | 24个 | 1个 | - | -  
  
**简评：** 如果你考虑在Vultr的新加坡[Singapore]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有891个，其中超时点36个，平均响应时间为235毫秒，丢包率为9%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在100-200毫秒间的1个，在200-300毫秒间的28个，超过300毫秒的1个；  
超时点较多的省份：浙江、青海、上海、云南；  
丢包率较高的省份：河南、江西、陕西、浙江、江苏、青海、湖北、北京、黑龙江、上海、甘肃、辽宁、内蒙古、天津、云南；

## 海外测速点

![海外各国家地区到VPS提供商Vultr位于新加坡\[Singapore\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/vultr_20180622/plot_idc_vultr_singapore-singapore_20180622_overseas.png)

**海外线路到Vultr新加坡-新加坡机房的测速数据 [20180622]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
新加坡 | 5个 | 0 | 37ms | 0  
日本 | 1个 | 0 | 66ms | -  
香港 | 24个 | 1个 | 87ms | 0  
韩国 | 12个 | 0 | 102ms | 0  
台湾 | 2个 | 0 | 130ms | 0  
南非 | 1个 | 0 | 160ms | 0  
均值 | 68个 | 1个 | 160ms | 0  
巴西 | 1个 | 0 | 183ms | 0  
美国 | 18个 | 0 | 195ms | 0  
法国 | 1个 | 0 | 209ms | 0  
德国 | 1个 | 0 | 242ms | -  
意大利 | 1个 | 0 | 254ms | -  
加拿大 | 1个 | 0 | 255ms | -  
  
**简评：** 如果你考虑在Vultr的新加坡[Singapore]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于新加坡[Singapore]的机房的连通状况。到此机房的ping监测点共有68个，其中超时点1个，平均响应时间为160毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的1个，在50-100毫秒间的2个，在100-200毫秒间的5个，在200-300毫秒间的4个；

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180622) 
    * [全部](https://vps123.top/pingtests/20180622 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180622 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180622 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180622 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期到Vultr _其他机房_ 的报告： 
    * [阿姆斯特丹](/vultr/idc/amsterdam/20180622-vultr-idc-amsterdam.md "多地到Vultr阿姆斯特丹机房的Ping测试 20180622")
    * [亚特兰大](/vultr/idc/atlanta/20180622-vultr-idc-atlanta.md "多地到Vultr亚特兰大机房的Ping测试 20180622")
    * [芝加哥](/vultr/idc/chicago/20180622-vultr-idc-chicago.md "多地到Vultr芝加哥机房的Ping测试 20180622")
    * [达拉斯](/vultr/idc/dallas/20180622-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180622")
    * [法兰克福](/vultr/idc/frankfurt/20180622-vultr-idc-frankfurt.md "多地到Vultr法兰克福机房的Ping测试 20180622")
    * [伦敦](/vultr/idc/london/20180622-vultr-idc-london.md "多地到Vultr伦敦机房的Ping测试 20180622")
    * [洛杉矶](/vultr/idc/losangeles/20180622-vultr-idc-losangeles.md "多地到Vultr洛杉矶机房的Ping测试 20180622")
    * [迈阿密](/vultr/idc/miami/20180622-vultr-idc-miami.md "多地到Vultr迈阿密机房的Ping测试 20180622")
    * [新泽西](/vultr/idc/newjersey/20180622-vultr-idc-newjersey.md "多地到Vultr新泽西机房的Ping测试 20180622")
    * [巴黎](/vultr/idc/paris/20180622-vultr-idc-paris.md "多地到Vultr巴黎机房的Ping测试 20180622")
    * [西雅图](/vultr/idc/seattle/20180622-vultr-idc-seattle.md "多地到Vultr西雅图机房的Ping测试 20180622")
    * [硅谷](/vultr/idc/siliconvalley/20180622-vultr-idc-siliconvalley.md "多地到Vultr硅谷机房的Ping测试 20180622")
    * [悉尼](/vultr/idc/sydney/20180622-vultr-idc-sydney.md "多地到Vultr悉尼机房的Ping测试 20180622")
    * [东京](/vultr/idc/tokyo/20180622-vultr-idc-tokyo.md "多地到Vultr东京机房的Ping测试 20180622")
  * 到Vultr新加坡机房的 _其他近期报告_ ： 
    * [20180514](/vultr/idc/singapore/20180514-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180514")
    * [20180527](/vultr/idc/singapore/20180527-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180527")
    * [20180804](/vultr/idc/singapore/20180804-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180804")
    * [20180918](/vultr/idc/singapore/20180918-vultr-idc-singapore.md "多地到Vultr新加坡机房的Ping测试 20180918")
  * 本期报告：在新加坡部署机房的 _其他VPS提供商_ ： 
    * [Digital Ocean](do/idc/singapore/20180622-do-idc-singapore.md "多地到Digital Ocean新加坡机房的Ping测试 20180622")
    * [Linode](/linode/idc/singapore/20180622-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180622")



本文最初发表于[多地到Vultr新加坡[Singapore]机房的Ping测试（20180622）](https://vps123.top/pingtest/20180622-vultr-idc-singapore.html)
