#afinal交流平台

    QQ群：192341294（群1，2000未满） 246710918（群2，1000未满） ##作者个人微信 mahua

mahua Afinal简介

    Afinal 是一个android的sqlite orm 和 ioc 框架。同时封装了android中的http框架，使其更加简单易用；
    使用finalBitmap，无需考虑bitmap在android中加载的时候oom的问题和快速滑动的时候图片加载位置错位等问题。
    Afinal的宗旨是简洁，快速。约定大于配置的方式。尽量一行代码完成所有事情。

##目前Afinal主要有四大模块：

    FinalDB模块：android中的orm框架，一行代码就可以进行增删改查。支持一对多，多对一等查询。

    FinalActivity模块：android中的ioc框架，完全注解方式就可以进行UI绑定和事件绑定。无需findViewById和setClickListener等。

    FinalHttp模块：通过httpclient进行封装http数据请求，支持ajax方式加载。

    FinalBitmap模块：通过FinalBitmap，imageview加载bitmap的时候无需考虑bitmap加载过程中出现的oom和android容器快速滑动时候出现的图片错位等现象。FinalBitmap可以配置线程加载线程数量，缓存大小，缓存路径，加载显示动画等。FinalBitmap的内存管理使用lru算法，没有使用弱引用（android2.3以后google已经不建议使用弱引用，android2.3后强行回收软引用和弱引用，详情查看android官方文档），更好的管理bitmap内存。FinalBitmap可以自定义下载器，用来扩展其他协议显示网络图片，比如ftp等。同时可以自定义bitmap显示器，在imageview显示图片的时候播放动画等（默认是渐变动画显示）。
