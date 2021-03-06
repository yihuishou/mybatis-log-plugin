## 关于许可和一些想说的话
因为今天(_2020.4.10_)有个网友在issue里面提了关于开源协议的问题，让我今天很认真的从头思考这个问题，感觉挺重要的，而且有必要把一些东西说清楚。  
我从2016年开始发布第一个插件(已经废弃)，到现在将近4个年头，版本更新，bug解决，issue解答，投入的时间真的蛮多的，看着用户量上升，能帮大家提升一点开发效率，感觉还是很开心和欣慰。  
要说一个最大的收获，应该是这个仓库196个真诚的star(截止今天)，感谢各位！  
说回插件，因为jetbrains公司的IDE，每年都会有大版本以及很多的小版本更新，针对插件开发的api兼容也经常变动，每次升级版本，都可能有一些插件已经不兼容，启用失败，报错，提示你禁用插件等等。  
然后这个插件因为原本的实现机制就不好，导致经常出现一些版本兼容、注册失败以及性能的问题，(跟我之前掌握的api水平关系很大)。  
所以在intellij2020的版本发布以后，旧插件又到了需要重新大改版的时候(再次废弃)，这次我用更好的方式以及新版本的api重新实现了一个版本。  
因为旧版本只兼容到2019年的各版本，而且一直都是免费的，所以只要该插件旧版本在你机器上运行良好，并且你选择继续使用旧版本，也是完全可以的。  
然后新版本插件这次我上传到了官方的marketplace，变成了一个收费插件，目前暂时设置的价格是(**$1/year**)。  
因为插件已经收费，而且仓库目前代码对新版本IDE兼容的不好，实现的代码也有点看不下去，也没有什么学习价值，所以相关代码已经被我清理。  
保留这仓库的原因有以下几点：  
* 第一，保留一些历史数据；
* 第二，保留这些难得的star；
* 第三，issues相关处理；
* 第四，方便该插件更好的推广吧；

仓库旧有代码许可协议已经被移除，所以目前使用的是GitHub的[默认协议](https://help.github.com/cn/github/creating-cloning-and-archiving-repositories/licensing-a-repository)    
插件对新版本开启收费以后，部分用户可能难以接受，想要自己在旧有许可的源码进行改造，所以这里补充一些条款：  
* 个人用户：源码对个人用户非常友好，你想怎么修改，怎么兼容版本，怎么编译安装在自己电脑上，都没有任何限制。  
* 企业用户：修改编译后的插件不允许在相关IDE2020(含)以上版本使用。
* **绝对禁止：修改编译过的插件重新发布到仓库或共享出去。**

上面这些限制，都是出于私心，只要大家对源码的改造不进行二次发布，不影响插件的销售，原则上都是允许的。  
主要还是希望新插件能够有用户支持，产生一些收入吧，也督促自己更好的维护下去。  
当然，许可这东西防的了君子防不了小人，不排除后面可能因为一些情况关闭或删除仓库。  
目前已知有一些用户使用旧有源码进行改造并二次发布的，希望大佬们高抬贵手，低调改造。  

IntelliJ等IDE正版的用户，我周围的情况，买的比例还是不多。  
国内收入以及一些情况大家都懂的，所以大家互相理解吧，能支持正版尽量支持正版。  
国外用户的正版比例应该比较多，所以我是希望这插件能有更多的国外友人支持。  
因为特别要提的一点：**非正版IDE的用户，购买完插件，无法直接激活插件，谨慎购买！**  
为此特地增加了本地授权验证的**特殊版本**，详情查看这里 [激活失败问题处理](https://github.com/kookob/mybatis-log-plugin/blob/master/activation.md)  
最后，非常感谢大家一路上的理解和支持，谢谢大家！  





