#  四川到Vultr各机房的测速数据（20180622） 

## 导读

本文是[TopVPS主机网络测试报告系列](https://vps123.top/pingtest)的一部分，主要提供PING测试的响应速度、丢包率等数据，关于PING指令以及响应速度、丢包率的指标意义，请看[这里](https://vps123.top/what-is-ping.html)。

![四川到Vultr各机房的测速数据（20180622）](/images/thumbnails/Sichuan_to_vultr.png)

本文的数据视角为 **四川到[Vultr](https://vps123.top/go/vultr)的各机房**的PING响应值、丢包率的比较；若你在四川且打算运行[Vultr](https://vps123.top/go/vultr)的云主机，用作代理服务器、云存储、云计算等，下面的内容很值得你深入了解。若有响应值接近、丢包率差距大的多个机房可选择，请优先选择丢包率低的；若Vultr的这些机房的数据都不理想，你可以查看本文结尾链接的其他VPS提供商的数据，发现可用性更好的机房。

**数据地图：**[我应该关注哪类VPS测速数据？](https://vps123.top/find-pingtest-data-you-need.html)

## 概要

测速点的运营商线路为电信、联通、移动，有效样本点613个，其中超时点13个。连通概况如下：大陆线路响应均值为281毫秒，最快的三个机房所在地为东京、洛杉矶、硅谷，最慢的三个为迈阿密、悉尼、阿姆斯特丹；东京、西雅图、法兰克福、新加坡、亚特兰大等7处有响应超时情况；芝加哥、迈阿密、亚特兰大、伦敦、新加坡等6处丢包率较高。

[注册 Vultr](https://vps123.top/go/vultr/_btn1)

## 四川图表数据

![大陆省份四川到VPS提供商Vultr各机房的ping测试数据统计图，包含响应值的柱状图以及丢包率的散点图，数据日期为20180622](/images/pingtests/vultr_20180622/plot_isp_sichuan_vultr_20180622.png)

### 全部运营商

**四川全部运营商到Vultr各机房的测速数据 [20180622]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 41个 | 3个 | 204ms | 6%  
洛杉矶 | 42个 | 0 | 221ms | 1%  
硅谷 | 40个 | 0 | 224ms | 1%  
西雅图 | 42个 | 3个 | 225ms | 1%  
达拉斯 | 42个 | 0 | 263ms | 1%  
新加坡 | 41个 | 1个 | 277ms | 7%  
均值 | 613个 | 13个 | 281ms | 5%  
法兰克福 | 40个 | 3个 | 283ms | 0  
巴黎 | 41个 | 0 | 284ms | 0  
亚特兰大 | 40个 | 1个 | 296ms | 15%  
芝加哥 | 41个 | 0 | 301ms | 17%  
新泽西 | 40个 | 1个 | 312ms | 2%  
伦敦 | 40个 | 0 | 313ms | 9%  
迈阿密 | 40个 | 0 | 323ms | 15%  
悉尼 | 40个 | 1个 | 339ms | 4%  
阿姆斯特丹 | 43个 | 0 | 343ms | 0  
  
**简评：** 本表展示了四川的 **电信、联通、移动** 线路到Vultr各机房的平均测速数据，这些数据绘制在前面柱状图的 **绿色** 柱位上；如果你常驻四川，可从此表了解你常用的网络到Vultr各个机房的平均响应速度以及丢包率。从表中数据可以看到， **洛杉矶、硅谷、西雅图** 的响应速度小于250ms，且丢包率在5%以内，值得关注；如果你多数时间只使用某运营商的网络，后面的分运营商的表格数据对你更有参考价值。

### 电信

**四川电信到Vultr各机房的测速数据 [20180622]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 19个 | 3个 | 224ms | 8%  
洛杉矶 | 22个 | 0 | 233ms | 1%  
硅谷 | 19个 | 0 | 256ms | 3%  
西雅图 | 21个 | 2个 | 243ms | 0  
达拉斯 | 20个 | 0 | 278ms | 1%  
新加坡 | 21个 | 1个 | 304ms | 10%  
均值 | 300个 | 12个 | 292ms | 2%  
法兰克福 | 19个 | 3个 | 251ms | 0  
巴黎 | 21个 | 0 | 251ms | 0  
亚特兰大 | 18个 | 1个 | 294ms | 0  
芝加哥 | 20个 | 0 | 299ms | 0  
新泽西 | 19个 | 1个 | 338ms | 1%  
伦敦 | 19个 | 0 | 329ms | 0  
迈阿密 | 19个 | 0 | 325ms | 1%  
悉尼 | 21个 | 1个 | 389ms | 4%  
阿姆斯特丹 | 22个 | 0 | 356ms | 1%  
  
**简评：** 如果你是来自四川的 **电信** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **洛杉矶、西雅图** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_1)吧！

### 联通

**四川联通到Vultr各机房的测速数据 [20180622]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 9个 | 0 | 229ms | 7%  
洛杉矶 | 10个 | 0 | 211ms | 0  
硅谷 | 10个 | 0 | 203ms | 0  
西雅图 | 9个 | 1个 | 216ms | 0  
达拉斯 | 9个 | 0 | 247ms | 0  
新加坡 | 10个 | 0 | 300ms | 4%  
均值 | 139个 | 1个 | 284ms | 9%  
法兰克福 | 10个 | 0 | 334ms | 0  
巴黎 | 10个 | 0 | 311ms | 0  
亚特兰大 | 9个 | 0 | 288ms | 37%  
芝加哥 | 9个 | 0 | 313ms | 38%  
新泽西 | 8个 | 0 | 290ms | 0  
伦敦 | 8个 | 0 | 321ms | 22%  
迈阿密 | 9个 | 0 | 322ms | 35%  
悉尼 | 9个 | 0 | 321ms | 3%  
阿姆斯特丹 | 10个 | 0 | 344ms | 0  
  
**简评：** 如果你是来自四川的 **联通** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **硅谷、洛杉矶、西雅图、达拉斯** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **东京** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_2)吧！

### 移动

**四川移动到Vultr各机房的测速数据 [20180622]**

机房所在地 | 测速点 | 超时点 | 响应均值 | 丢包率  
---|---|---|---|---  
东京 | 13个 | 0 | 160ms | 3%  
洛杉矶 | 10个 | 0 | 220ms | 2%  
硅谷 | 11个 | 0 | 214ms | 1%  
西雅图 | 12个 | 0 | 215ms | 2%  
达拉斯 | 13个 | 0 | 265ms | 1%  
新加坡 | 10个 | 0 | 228ms | 7%  
均值 | 174个 | 0 | 267ms | 4%  
法兰克福 | 11个 | 0 | 262ms | 1%  
巴黎 | 10个 | 0 | 290ms | 1%  
亚特兰大 | 13个 | 0 | 305ms | 9%  
芝加哥 | 12个 | 0 | 290ms | 14%  
新泽西 | 13个 | 0 | 307ms | 5%  
伦敦 | 13个 | 0 | 290ms | 6%  
迈阿密 | 12个 | 0 | 322ms | 11%  
悉尼 | 10个 | 0 | 306ms | 3%  
阿姆斯特丹 | 11个 | 0 | 330ms | 0  
  
**简评：** 如果你是来自四川的 **移动** 用户，想运行Vultr的VPS产品，用作科学上网、云存储、远程任务、游戏服务器等用途，建议重点关注部署在 **东京、硅谷、西雅图、洛杉矶** 的机房；从数据看，你的网络到这几处的连通速度、丢包率都比较不错。请慎重选择部署在 **新加坡** 的机房，即使此处离你较近；因为响应均值虽然还不错，但丢包率较高。文章结尾处有本文视角的其他近期测评的链接，建议你多看几期以提升判断的准确度；如果看好了，就果断[去让机器跑起来](https://vps123.top/go/vultr/_3)吧！

[注册 Vultr](https://vps123.top/go/vultr/_btn2)

## 相关测速报告

  * 本期测速报告归档 (20180622) 
    * [全部](https://vps123.top/pingtests/20180622 "本期各VPS提供商全部测速报告")
    * [Vultr](https://vps123.top/pingtests/idc-vultr/20180622 "本期Vultr的全部测速报告")
    * [各地到Vultr某机房](https://vps123.top/pingtests/idc-vultr/isp-global/20180622 "以Vultr某机房为关注对象的视角，横向比较大陆各省份、海外各国家地区")
    * [某地到Vultr各机房](https://vps123.top/pingtests/idc-vultr/facility-all/20180622 "以大陆某省份为关注对象的视角，横向比较Vultr各机房")
  * 本期 _其他省份_ 到Vultr各机房的报告： 
    * [安徽](/vultr/isp/anhui/20180622-vultr-isp-anhui.md "安徽到Vultr各机房的Ping测试 20180622")
    * [北京](/vultr/isp/beijing/20180622-vultr-isp-beijing.md "北京到Vultr各机房的Ping测试 20180622")
    * [大陆](/vultr/isp/china/20180622-vultr-isp-china.md "大陆到Vultr各机房的Ping测试 20180622")
    * [重庆](/vultr/isp/chongqing/20180622-vultr-isp-chongqing.md "重庆到Vultr各机房的Ping测试 20180622")
    * [福建](/vultr/isp/fujian/20180622-vultr-isp-fujian.md "福建到Vultr各机房的Ping测试 20180622")
    * [甘肃](/vultr/isp/gansu/20180622-vultr-isp-gansu.md "甘肃到Vultr各机房的Ping测试 20180622")
    * [广东](/vultr/isp/guangdong/20180622-vultr-isp-guangdong.md "广东到Vultr各机房的Ping测试 20180622")
    * [广西](/vultr/isp/guangxi/20180622-vultr-isp-guangxi.md "广西到Vultr各机房的Ping测试 20180622")
    * [贵州](/vultr/isp/guizhou/20180622-vultr-isp-guizhou.md "贵州到Vultr各机房的Ping测试 20180622")
    * [海南](/vultr/isp/hainan/20180622-vultr-isp-hainan.md "海南到Vultr各机房的Ping测试 20180622")
    * [河北](/vultr/isp/hebei/20180622-vultr-isp-hebei.md "河北到Vultr各机房的Ping测试 20180622")
    * [黑龙江](/vultr/isp/heilongjiang/20180622-vultr-isp-heilongjiang.md "黑龙江到Vultr各机房的Ping测试 20180622")
    * [河南](/vultr/isp/henan/20180622-vultr-isp-henan.md "河南到Vultr各机房的Ping测试 20180622")
    * [湖北](/vultr/isp/hubei/20180622-vultr-isp-hubei.md "湖北到Vultr各机房的Ping测试 20180622")
    * [湖南](/vultr/isp/hunan/20180622-vultr-isp-hunan.md "湖南到Vultr各机房的Ping测试 20180622")
    * [内蒙古](/vultr/isp/innermongolia/20180622-vultr-isp-innermongolia.md "内蒙古到Vultr各机房的Ping测试 20180622")
    * [江苏](/vultr/isp/jiangsu/20180622-vultr-isp-jiangsu.md "江苏到Vultr各机房的Ping测试 20180622")
    * [江西](/vultr/isp/jiangxi/20180622-vultr-isp-jiangxi.md "江西到Vultr各机房的Ping测试 20180622")
    * [吉林](/vultr/isp/jilin/20180622-vultr-isp-jilin.md "吉林到Vultr各机房的Ping测试 20180622")
    * [辽宁](/vultr/isp/liaoning/20180622-vultr-isp-liaoning.md "辽宁到Vultr各机房的Ping测试 20180622")
    * [宁夏](/vultr/isp/ningxia/20180622-vultr-isp-ningxia.md "宁夏到Vultr各机房的Ping测试 20180622")
    * [青海](/vultr/isp/qinghai/20180622-vultr-isp-qinghai.md "青海到Vultr各机房的Ping测试 20180622")
    * [山西](/vultr/isp/shan1xi/20180622-vultr-isp-shan1xi.md "山西到Vultr各机房的Ping测试 20180622")
    * [陕西](/vultr/isp/shan3xi/20180622-vultr-isp-shan3xi.md "陕西到Vultr各机房的Ping测试 20180622")
    * [山东](/vultr/isp/shandong/20180622-vultr-isp-shandong.md "山东到Vultr各机房的Ping测试 20180622")
    * [上海](/vultr/isp/shanghai/20180622-vultr-isp-shanghai.md "上海到Vultr各机房的Ping测试 20180622")
    * [天津](/vultr/isp/tianjin/20180622-vultr-isp-tianjin.md "天津到Vultr各机房的Ping测试 20180622")
    * [西藏](/vultr/isp/tibet/20180622-vultr-isp-tibet.md "西藏到Vultr各机房的Ping测试 20180622")
    * [新疆](/vultr/isp/xinjiang/20180622-vultr-isp-xinjiang.md "新疆到Vultr各机房的Ping测试 20180622")
    * [云南](/vultr/isp/yunnan/20180622-vultr-isp-yunnan.md "云南到Vultr各机房的Ping测试 20180622")
    * [浙江](/vultr/isp/zhejiang/20180622-vultr-isp-zhejiang.md "浙江到Vultr各机房的Ping测试 20180622")
  * 四川到Vultr各机房的 _其他近期报告_ ： 
    * [20180514](/vultr/isp/sichuan/20180514-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180514")
    * [20180527](/vultr/isp/sichuan/20180527-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180527")
    * [20180804](/vultr/isp/sichuan/20180804-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180804")
    * [20180918](/vultr/isp/sichuan/20180918-vultr-isp-sichuan.md "四川到Vultr各机房的Ping测试 20180918")
  * 本期报告：四川到 _其他VPS提供商_ 各机房的测速报告： 
    * [BandwagonHost](/bandwagon/isp/sichuan/20180622-bandwagon-isp-sichuan.md "四川到BandwagonHost各机房的Ping测试 20180622")
    * [Digital Ocean](/digitalocean/isp/sichuan/20180622-digitalocean-isp-sichuan.md "四川到Digital Ocean各机房的Ping测试 20180622")
    * [Linode](/linode/isp/sichuan/20180622-linode-isp-sichuan.md "四川到Linode各机房的Ping测试 20180622")



本文最初发表于[四川到Vultr各机房的测速数据（20180622）](https://vps123.top/pingtest/20180622-vultr-isp-sichuan.html)
