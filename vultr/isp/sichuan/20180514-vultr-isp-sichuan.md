#  四川到Vultr各机房的测速数据（20180514） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![四川到Vultr各机房的测速数据（20180514）](/images/thumbnails/Sichuan_to_vultr.png)

本文的数据视角为 **四川到[Vultr](https://vps123.top/go/vultr)的各机房**的PING响应值、丢包率的比较；若你在四川且打算运行[Vultr](https://vps123.top/go/vultr)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Vultr的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

本文提供20180514四川到Vultr各机房的PING测试结果，测速点的运营商线路为电信、联通、移动，有效样本点717个，其中超时点2个。连通概况如下：大陆线路响应均值为287毫秒，最快的三个机房所在地为东京、新加坡、西雅图，最慢的三个为新泽西、伦敦、亚特兰大；迈阿密、伦敦有响应超时情况；洛杉矶、达拉斯、亚特兰大、东京、新加坡等7处丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 四川图表数据

![大陆省份四川到VPS提供商Vultr各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180514](/images/pingtests/vultr_20180514/plot_isp_sichuan_vultr_20180514.png)

### 全部运营商

**四川全部运营商到Vultr各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 46个 | 0 | 150ms | 12%  
新加坡 | 49个 | 0 | 222ms | 10%  
西雅图 | 51个 | 0 | 230ms | 1%  
悉尼 | 49个 | 0 | 257ms | 2%  
硅谷 | 47个 | 0 | 270ms | 7%  
洛杉矶 | 50个 | 0 | 273ms | 14%  
均值 | 717个 | 2个 | 287ms | 6%  
芝加哥 | 47个 | 0 | 299ms | 3%  
法兰克福 | 44个 | 0 | 303ms | 4%  
巴黎 | 48个 | 0 | 306ms | 3%  
阿姆斯特丹 | 46个 | 0 | 308ms | 3%  
达拉斯 | 48个 | 0 | 321ms | 13%  
迈阿密 | 48个 | 1个 | 326ms | 2%  
新泽西 | 49个 | 0 | 327ms | 5%  
伦敦 | 48个 | 1个 | 350ms | 3%  
亚特兰大 | 47个 | 0 | 351ms | 13%  
  
**简评：** 本表展示了四川的 **电信、联通、移动** 线路到Vultr各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻四川，可从此表了解你常用的网络到Vultr各个机房的平均响应速度以及丢包率。从表中数据可以看到， **西雅图** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

**四川电信到Vultr各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 23个 | 0 | 140ms | 8%  
新加坡 | 24个 | 0 | 206ms | 8%  
西雅图 | 24个 | 0 | 256ms | 1%  
悉尼 | 24个 | 0 | 272ms | 0  
硅谷 | 22个 | 0 | 318ms | 4%  
洛杉矶 | 24个 | 0 | 296ms | 16%  
均值 | 340个 | 2个 | 297ms | 4%  
芝加哥 | 22个 | 0 | 336ms | 3%  
法兰克福 | 20个 | 0 | 262ms | 0  
巴黎 | 24个 | 0 | 263ms | 0  
阿姆斯特丹 | 19个 | 0 | 268ms | 0  
达拉斯 | 23个 | 0 | 328ms | 9%  
迈阿密 | 23个 | 1个 | 364ms | 2%  
新泽西 | 23个 | 0 | 376ms | 2%  
伦敦 | 23个 | 1个 | 374ms | 3%  
亚特兰大 | 22个 | 0 | 362ms | 7%  
  
**简评：** 如果你是来自四川的 **电信** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，请慎重选择部署在 **东京、新加坡** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_1)吧！

### 联通

**四川联通到Vultr各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 11个 | 0 | 179ms | 19%  
新加坡 | 12个 | 0 | 278ms | 15%  
西雅图 | 12个 | 0 | 216ms | 2%  
悉尼 | 11个 | 0 | 251ms | 4%  
硅谷 | 11个 | 0 | 228ms | 4%  
洛杉矶 | 11个 | 0 | 247ms | 5%  
均值 | 168个 | 0 | 289ms | 8%  
芝加哥 | 12个 | 0 | 298ms | 5%  
法兰克福 | 11个 | 0 | 363ms | 10%  
巴黎 | 9个 | 0 | 361ms | 9%  
阿姆斯特丹 | 12个 | 0 | 366ms | 7%  
达拉斯 | 11个 | 0 | 283ms | 11%  
迈阿密 | 12个 | 0 | 309ms | 5%  
新泽西 | 11个 | 0 | 296ms | 11%  
伦敦 | 12个 | 0 | 368ms | 6%  
亚特兰大 | 10个 | 0 | 299ms | 7%  
  
**简评：** 如果你是来自四川的 **联通** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **西雅图、硅谷、洛杉矶** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_2)吧！

### 移动

**四川移动到Vultr各机房的测速数据 [20180514]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 12个 | 0 | 132ms | 10%  
新加坡 | 13个 | 0 | 182ms | 7%  
西雅图 | 15个 | 0 | 218ms | 1%  
悉尼 | 14个 | 0 | 248ms | 3%  
硅谷 | 14个 | 0 | 262ms | 12%  
洛杉矶 | 15个 | 0 | 277ms | 20%  
均值 | 209个 | 0 | 276ms | 7%  
芝加哥 | 13个 | 0 | 262ms | 0  
法兰克福 | 13个 | 0 | 285ms | 3%  
巴黎 | 15个 | 0 | 293ms | 1%  
阿姆斯特丹 | 15个 | 0 | 291ms | 2%  
达拉斯 | 14个 | 0 | 351ms | 20%  
迈阿密 | 13个 | 0 | 306ms | 0  
新泽西 | 15个 | 0 | 309ms | 1%  
伦敦 | 13个 | 0 | 307ms | 1%  
亚特兰大 | 15个 | 0 | 392ms | 24%  
  
**简评：** 如果你是来自四川的 **移动** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **西雅图、悉尼** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京、新加坡** 的机房，即使这几个城市离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_3)吧！

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180514) 
    * [全部](https://vps123.top/pingtests/20180514 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180514 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180514 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180514 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期 _其他省份_ 到Vultr各机房的报告： 
    * [安徽](/vultr/isp/anhui/20180514-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180514")
    * [北京](/vultr/isp/beijing/20180514-vultr-isp-beijing.md "北京到Vultr各机房的Ping测试 20180514")
    * [大陆](/vultr/isp/china/20180514-vultr-isp-china.md "大陆到Vultr各机房的Ping测试 20180514")
    * [重庆](/vultr/isp/chongqing/20180514-vultr-isp-chongqing.md "重庆到Vultr各机房的Ping测试 20180514")
    * [福建](/vultr/isp/fujian/20180514-vultr-isp-fujian.md "福建到Vultr各机房的Ping测试 20180514")
    * [甘肃](/vultr/isp/gansu/20180514-vultr-isp-gansu.md "甘肃到Vultr各机房的Ping测试 20180514")
    * [广东](/vultr/isp/guangdong/20180514-vultr-isp-guangdong.md "广东到Vultr各机房的Ping测试 20180514")
    * [广西](/vultr/isp/guangxi/20180514-vultr-isp-guangxi.md "广西到Vultr各机房的Ping测试 20180514")
    * [贵州](/vultr/isp/guizhou/20180514-vultr-isp-guizhou.md "贵州到Vultr各机房的Ping测试 20180514")
    * [海南](/vultr/isp/hainan/20180514-vultr-isp-hainan.md "海南到Vultr各机房的Ping测试 20180514")
    * [河北](/vultr/isp/hebei/20180514-vultr-isp-hebei.md "河北到Vultr各机房的Ping测试 20180514")
    * [黑龙江](/vultr/isp/heilongjiang/20180514-vultr-isp-heilongjiang.md "黑龙江到Vultr各机房的Ping测试 20180514")
    * [河南](/vultr/isp/henan/20180514-vultr-isp-henan.md "河南到Vultr各机房的Ping测试 20180514")
    * [湖北](/vultr/isp/hubei/20180514-vultr-isp-hubei.md "湖北到Vultr各机房的Ping测试 20180514")
    * [湖南](/vultr/isp/hunan/20180514-vultr-isp-hunan.md "湖南到Vultr各机房的Ping测试 20180514")
    * [内蒙古](/vultr/isp/innermongolia/20180514-vultr-isp-innermongolia.md "内蒙古到Vultr各机房的Ping测试 20180514")
    * [江苏](/vultr/isp/jiangsu/20180514-vultr-isp-jiangsu.md "江苏到Vultr各机房的Ping测试 20180514")
    * [江西](/vultr/isp/jiangxi/20180514-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180514")
    * [吉林](/vultr/isp/jilin/20180514-vultr-isp-jilin.md "吉林到Vultr各机房的Ping测试 20180514")
    * [辽宁](/vultr/isp/liaoning/20180514-vultr-isp-liaoning.md "辽宁到Vultr各机房的Ping测试 20180514")
    * [宁夏](/vultr/isp/ningxia/20180514-vultr-isp-ningxia.md "宁夏到Vultr各机房的Ping测试 20180514")
    * [青海](/vultr/isp/qinghai/20180514-vultr-isp-qinghai.md "青海到Vultr各机房的Ping测试 20180514")
    * [山西](/vultr/isp/shan1xi/20180514-vultr-isp-shan1xi.md "山西到Vultr各机房的Ping测试 20180514")
    * [陕西](/vultr/isp/shan3xi/20180514-vultr-isp-shan3xi.md "陕西到Vultr各机房的Ping测试 20180514")
    * [山东](/vultr/isp/shandong/20180514-vultr-isp-shandong.md "山东到Vultr各机房的Ping测试 20180514")
    * [上海](/vultr/isp/shanghai/20180514-vultr-isp-shanghai.md "上海到Vultr各机房的Ping测试 20180514")
    * [天津](/vultr/isp/tianjin/20180514-vultr-isp-tianjin.md "天津到Vultr各机房的Ping测试 20180514")
    * [西藏](/vultr/isp/tibet/20180514-vultr-isp-tibet.md "西藏到Vultr各机房的Ping测试 20180514")
    * [新疆](/vultr/isp/xinjiang/20180514-vultr-isp-xinjiang.md "新疆到Vultr各机房的Ping测试 20180514")
    * [云南](/vultr/isp/yunnan/20180514-vultr-isp-yunnan.md "云南到Vultr各机房的Ping测试 20180514")
    * [浙江](/vultr/isp/zhejiang/20180514-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180514")
  * 四川到Vultr各机房的 _其他近期报告_ ： 
    * [20180527](/vultr/isp/sichuan/20180527-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180527")
    * [20180622](/vultr/isp/sichuan/20180622-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180622")
    * [20180804](/vultr/isp/sichuan/20180804-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180804")
    * [20180918](/vultr/isp/sichuan/20180918-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180918")
  * 本期报告：四川到 _其他VPS提供商_ 各机房的测速报告： 
    * [BandwagonHost](/bandwagon/isp/sichuan/20180514-bandwagon-isp-sichuan.md "四川到BandwagonHost各机房的Ping测试 20180514")
    * [Digital Ocean](/digitalocean/isp/sichuan/20180514-digitalocean-isp-sichuan.md "四川到Digital Ocean各机房的Ping测试 20180514")
    * [Linode](/linode/isp/sichuan/20180514-linode-isp-sichuan.md "四川到Linode各机房的Ping测试 20180514")



本文最初发表于[四川到Vultr各机房的测速数据（20180514）](https://vps123.top/pingtest/20180514-vultr-isp-sichuan.html)
