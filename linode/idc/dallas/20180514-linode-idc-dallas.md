#  多地到Linode达拉斯[Dallas]机房的Ping测试（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![多地到Linode达拉斯\[Dallas\]机房的Ping测试（20180514）](/images/thumbnails/to_linode_Dallas.png)

本篇的数据视角为全国各地以及海外运营商的网络环境下，到[Linode](https://vps123.top/go/linode)的[美国-达拉斯机房](https://vps123.top/linode-facilities.html#dallas)的网络连接；若你有[主要面向大陆用户的站点](https://vps123.top/website-for-mainland-users.html)或[外贸站](https://vps123.top/website-for-internation-trade.html)运行在VPS提供商[Linode](https://vps123.top/go/linode)的美国-达拉斯机房，可以从这些数据中了解用户访问你的站点的响应速度和体验。如果你认为当前使用的主机在主要用户所在地的访问体验不佳，可以查看[Linode全部机房](/linode/isp/china/20180514-linode-isp-china.md)的数据或其他VPS提供商的机房数据（文末有链接），发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514多地到Linode美国-达拉斯机房的PING测试结果，连通概况如下：大陆30个省市的975个有效测试样本中，共有超时点14个；响应均值为260毫秒，最快的三地区为上海、天津、吉林，最慢的三地区为重庆、四川、云南；浙江、江苏、北京、陕西、山东等9处有响应超时情况；云南、安徽、四川、广东、湖北等25处丢包率较高。海外17个国家地区的79个有效测试样本中，共有超时点1个；响应均值为177毫秒，最快的三地区为美国、加拿大、法国，最慢的三地区为马来西亚、印度尼西亚、南非；日本有响应超时情况。

[注册 Linode](https://vps123.top/go/linode/_btn1)

## 大陆测速点

![大陆各省份到VPS提供商Linode位于达拉斯\[Dallas\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_idc_linode_usa-dallas_20180514_mainland.png)

**大陆各省份到Linode美国-达拉斯机房的测速数据 [20180514]**

省份 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
上海 | 8个 | 0 | 203ms | 2.8%  
天津 | 5个 | 0 | 213ms | 0.4%  
吉林 | 15个 | 0 | 219ms | 0.5%  
北京 | 7个 | 1个 | 232ms | 8.8%  
陕西 | 32个 | 1个 | 232ms | 5.8%  
江苏 | 64个 | 2个 | 234ms | 11.5%  
辽宁 | 40个 | 0 | 234ms | 8.1%  
山东 | 53个 | 1个 | 236ms | 8.9%  
福建 | 38个 | 1个 | 236ms | 3.5%  
浙江 | 53个 | 5个 | 244ms | 10.3%  
黑龙江 | 37个 | 0 | 245ms | 8.9%  
宁夏 | 12个 | 0 | 245ms | 7.3%  
安徽 | 41个 | 1个 | 245ms | 15.1%  
山西 | 37个 | 0 | 247ms | 10.5%  
内蒙古 | 35个 | 0 | 250ms | 8.8%  
青海 | 4个 | 0 | 259ms | 9.5%  
江西 | 25个 | 0 | 259ms | 12.4%  
甘肃 | 22个 | 0 | 260ms | 6.4%  
均值 | 975个 | 14个 | 260ms | 10.1%  
河南 | 59个 | 0 | 262ms | 8.3%  
海南 | 10个 | 0 | 265ms | 6.7%  
贵州 | 28个 | 1个 | 274ms | 8.0%  
广东 | 79个 | 1个 | 275ms | 14.7%  
湖南 | 43个 | 0 | 277ms | 11.5%  
河北 | 30个 | 0 | 281ms | 4.0%  
广西 | 39个 | 0 | 282ms | 10.6%  
湖北 | 45个 | 0 | 283ms | 14.3%  
新疆 | 28个 | 0 | 293ms | 11.8%  
重庆 | 15个 | 0 | 293ms | 13.3%  
四川 | 47个 | 0 | 309ms | 14.8%  
云南 | 24个 | 0 | 310ms | 15.5%  
  
**简评：** 如果你考虑在Linode的达拉斯[Dallas]机房部署[主要面向大陆访客的网站](website-for-mainland-users.html)，本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了大陆各省份的测速点到位于达拉斯[Dallas]的机房的连通状况。到此机房的ping监测点共有975个，其中超时点14个，平均响应时间为260毫秒，丢包率为10%，本站评价等级为 **较差** ，不太推荐在位于这里的机房建站。

以下是就各省份数据的统计概要：  
平均响应时间的分布：在200-300毫秒间的28个，超过300毫秒的2个；  
超时点较多的省份：北京；  
丢包率较高的省份：江苏、浙江、安徽、山西、江西、广东、湖南、广西、湖北、新疆、重庆、四川、云南；

## 海外测速点

![海外各国家地区到VPS提供商Linode位于达拉斯\[Dallas\]的机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/linode_20180514/plot_idc_linode_usa-dallas_20180514_overseas.png)

**海外线路到Linode美国-达拉斯机房的测速数据 [20180514]**

国家地区 | 测速点 | 超时点 | 响应时间 | 丢包率  
---|---|---|---|---  
美国 | 19个 | 0 | 37ms | 0  
加拿大 | 3个 | 0 | 46ms | 0.5%  
法国 | 2个 | 0 | 110ms | 0  
英国 | 2个 | 0 | 128ms | 0  
德国 | 2个 | 0 | 134ms | 0  
巴西 | 1个 | 0 | 139ms | 0  
韩国 | 13个 | 0 | 174ms | 0  
日本 | 2个 | 1个 | 174ms | 0  
均值 | 79个 | 1个 | 177ms | 0.1%  
台湾 | 1个 | 0 | 190ms | -  
澳大利亚 | 2个 | 0 | 202ms | 0  
香港 | 18个 | 0 | 203ms | 0  
菲律宾 | 1个 | 0 | 205ms | 0  
新加坡 | 6个 | 0 | 210ms | 0  
俄罗斯 | 1个 | 0 | 211ms | 0  
马来西亚 | 4个 | 0 | 245ms | 0.8%  
印度尼西亚 | 1个 | 0 | 296ms | 0  
南非 | 1个 | 0 | 314ms | 0  
  
**简评：** 如果你考虑在Linode的达拉斯[Dallas]机房部署[主要面向海外访客的网站](https://vps123.top/website-for-internation-trade.html)（例如外贸站），本表可以作为一个很好的参考，它提供了有关响应速度以及丢包率的详细数据，反映了海外各国家/地区的测速点到位于达拉斯[Dallas]的机房的连通状况。到此机房的ping监测点共有79个，其中超时点1个，平均响应时间为177毫秒，丢包率为0%，本站评价等级为 **一般** ，可以考虑在位于这里的机房建站。

以下是就各国家/地区数据的统计概要：  
平均响应时间的分布：在50毫秒以内的2个，在100-200毫秒间的7个，在200-300毫秒间的7个，超过300毫秒的1个；

[注册 Linode](https://vps123.top/go/linode/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Linode](https://vps123.top/pingtests/idc-linode/20180514 "本期Linode的全部测速报告")
    * [各地到Linode某机房](https://vps123.top/pingtests/idc-linode/isp-global/20180514 "以Linode某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Linode各机房](https://vps123.top/pingtests/idc-linode/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Linode各机房")
  * 本期到Linode _其他机房_ 的报告： 
    * [亚特兰大](/linode/idc/atlanta/20180514-linode-idc-atlanta.md "多地到Linode亚特兰大机房的Ping测试 20180514")
    * [法兰克福](/linode/idc/frankfurt/20180514-linode-idc-frankfurt.md "多地到Linode法兰克福机房的Ping测试 20180514")
    * [佛利蒙](/linode/idc/fremont/20180514-linode-idc-fremont.md "多地到Linode佛利蒙机房的Ping测试 20180514")
    * [伦敦](/linode/idc/london/20180514-linode-idc-london.md "多地到Linode伦敦机房的Ping测试 20180514")
    * [纽瓦克](/linode/idc/newark/20180514-linode-idc-newark.md "多地到Linode纽瓦克机房的Ping测试 20180514")
    * [新加坡](/linode/idc/singapore/20180514-linode-idc-singapore.md "多地到Linode新加坡机房的Ping测试 20180514")
    * [东京](/linode/idc/tokyo/20180514-linode-idc-tokyo.md "多地到Linode东京机房的Ping测试 20180514")
  * 到Linode达拉斯机房的 _其他近期报告_ ： 
    * [20180527](/linode/idc/dallas/20180527-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180527")
    * [20180622](/linode/idc/dallas/20180622-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180622")
    * [20180804](/linode/idc/dallas/20180804-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180804")
    * [20180918](/linode/idc/dallas/20180918-linode-idc-dallas.md "多地到Linode达拉斯机房的Ping测试 20180918")
  * 本期报告：在达拉斯部署机房的 _其他VPS提供商_ ： 
    * [Vultr](/vultr/idc/dallas/20180514-vultr-idc-dallas.md "多地到Vultr达拉斯机房的Ping测试 20180514")



本文最初发表于[多地到Linode达拉斯[Dallas]机房的Ping测试（20180514）](https://vps123.top/pingtest/20180514-linode-idc-dallas.html)
