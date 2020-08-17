# 关于简易安卓端远控木马的编写

## 一、收获

①会想绝不等价于会做

​	当时任务布置下来，除了服务器与客户端通信那一块有点迷，其他的功能模块可谓是思路清晰。当时的想法：无非是调用各种封装好的函数，况且网上各种功能模块都直接有别人写好的demo，可以直接“敏捷开发”，将别人写好的demo拼装，然后通过简单的调试即可做完。

​	可是，后来真正动手做的时候，我发现压根不是那样，别人的代码移植过来会有各种奇葩的bug，由于本人java水平停留在学校面向考试的那种水平，所以很多bug直接改到吐血。当然，我这里绝无诋毁java移植性差的意思。哈哈哈

②让我看清自己是有多懒

​	任务布置时间是上上个星期五，结果到这个周五才完成了部分功能模块。按理说，就算是没有接触过android开发，java语言用的不熟，这个时间周期应该也可以做的差不多了。但是我却拖沓了这么久，我自己总结了两个原因：①菜是原罪 ②说得好听叫不懂得时间管理，但是说白了就是懒。在家就是忍不住想躺着休息，哪怕是无聊到刷b站也不想动手敲代码。

③了解了java的socket通信的一些基本操作

​	刚开始处理服务端和客户端通信的时候，第一想到的是通过第三方邮箱来实现。然后动手去做了，查了资料，java官方有一个邮件类包，叫jmail，在这上面花费了很长时间，虽然也确实实现了发邮件的功能，但是很容易出bug。在这个模块上耗了将近一天的时间，最终这个方案被弃用了。
