# ETWeather
中国天气网提供的 API 接口早已经无法调用，此项目调用聚合数据，功能得以实现。

本篇系学习酷欧天气项目，做出小项目－未来天气，后续依情况或许再添加些许功能。

**一.功能需求及技术可行性分析**

搜杰天气应具备的功能：

* 可以罗列出全国所有的省市县。
* 可以查看全国任意城市的天气信息。
* 可以自由顺利地切换城市，查看其他城市的天气。
* 可以手动更新及后台更新天气。 

主要用到 UI ，网络，定位，数据存储和服务等技术。

**二.如何使用聚合数据**

1.聚合数据官网地址：[https://www.juhe.cn](https://www.juhe.cn)。

2.注册完账号－申请数据－天气预报－全国天气预报－点击申请－进入我的数据－点击操作中的查看－记下 AppKey ，如我的 AppKey ：`af2af1996d54696346d66504710ddcf5`，代码中用上。

3.其余的根据开发文档学习。

***4.新手注意，具体只改动以下三个地方，再 Rebuild Project ，下载代码到手机上就可以正常使用了。***
![](http://images2015.cnblogs.com/blog/839964/201602/839964-20160223231613130-745688000.png)
![](http://images2015.cnblogs.com/blog/839964/201602/839964-20160223231638115-629996875.png)
![](http://images2015.cnblogs.com/blog/839964/201602/839964-20160223231654161-1061930232.png)
这三幅图，只改动 "key＝...." ，换成你按1-3步骤完成后生成的 AppKey 即可，完毕。
