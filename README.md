## 简介

疯狂编程10年，平均每天10小时以上，一周写代码80小时。技术经历和技术栈如下：

* j2ee（servlet、jsp、jdbc、spring、hibernate、struct2、osgi、设计模式、各种框架和自研框架）。
* 前端（css、html、js原生API包括ajax、早期库jquery、extjs、mootools、yui等）。
* js库实现css3选择器、动画引擎、兼容性事件处理。
* svn、git、nodejs、lisp、maven、mysql。
* 手游客户端（单机、网游、RPG、动作，策略、农场经营、跑酷、卡牌等）。
  * 私有引擎（java、c，2d，引擎、工具、游戏三层编写）。
  * cocos2dx（c++、lua，2d，纯c++和纯lua网游、cocos修改定制、游戏层框架）。
  * gameplay3d（c++、lua，3d，定制即时策略战斗）。
  * unity3d（c#，2d/3d，插件、游戏框架层）。
* 自研游戏引擎（c99、opengles3.x、java、swift，2d/3d）。
* unity3d插件、开箱即用gameplay框架、vulkan、metal（进行中）。
* 人工智能、区块链、操作系统内核（学习中）。
* .....

```
曾今乔布斯的Mac团队，衣服上印着: “我爱每周工作90小时。”    
作为回应，Lisa团队的印着: “一周工作70小时，但产品已经面世。”    
而AppleⅡ团队淡定地印着: “一周工作60小时——赚钱养活Lisa和Mac。”
```

>编程10年后，想的比写的多，想好了就会写的很快。认识到编程不是目的而是过程，不再挑剔编程语言，不再害怕或排斥不熟悉的技术，更不会心有余悸，而是荣辱不惊。与代码洁癖和谐相处并合作愉快，并适应各种语法格式，没有喜好与抱怨——按部就班的把思想平静地编程现实。
>
>明白没有完美——缺陷是来自于路径依赖，宇宙熵增推动着高效与混乱的转换，存在未必合理可能只是在消亡的路上。可以用代码流畅的表达想法、抽象逻辑、映射客观、架构因果、尽情地改进与迭代。发现心中没有规则与限制，就可以断点调试现实的坚硬与黑暗。
>
>人生很短，编程的道路却很长，要学习的还有更多，未来已经蜿蜒到看不到尽头的远方，我独自在黑屋子里与递归为伴，感受着毁灭后的重建，推到重来就是人生无法避役的循环。

## 社交网络

* 「微博」[分享有趣的见解和闪念（一句话纯文字）](https://weibo.com/scottcgi)
* 「知乎」[答题和专栏（同步技术和洞见思考）](https://www.zhihu.com/people/scott.cgi)
* 「豆瓣」[标记书籍和电影，日记（同步洞见思考）](https://www.douban.com/people/scottcgi)
* 「简书」[写作（同步技术和洞见思考）](https://www.jianshu.com/u/63a72cf6fff1)
* 「csdn」[纯技术分享（同步技术）](https://blog.csdn.net/tom_221x)
* 「GitHub」[代码项目](https://github.com/scottcgi)

所有的文章会随着信息的积累和认知的改变，而不断地修订（增删改），并会同步更新到不同的社交账号。

* 技术分享
  * [知乎专栏（又在写代码）](https://zhuanlan.zhihu.com/scottcgi0)
  * [简书文集（代码分类）](https://www.jianshu.com/p/6a8fa2dea3db)
  * [csdn博客](https://blog.csdn.net/tom_221x)
* 洞见思考
  * [知乎专栏（闪念与乱想）](https://zhuanlan.zhihu.com/scottcgi)
  * [简书文集（闪念与乱想）](https://www.jianshu.com/nb/13094385)
  * [豆瓣日记](https://www.douban.com/people/scottcgi/notes)
* 闪念
  * [微博](https://weibo.com/scottcgi)
  * [知乎想法](https://www.zhihu.com/people/scott.cgi/pins)

## 开源项目 

* [Mojoc](https://github.com/scottcgi/Mojoc) 自研游戏引擎（c99，opengles3.x，android/ios）。

  纯c的游戏引擎，未来会扩展到windows和mac平台，并会给渲染层添加vulkan和metal接口。接下来的一些构想：
  
  * 在渲染层之上构建一个跨平台的UI库（使用渲染层，或是封装统一的平台绘制层）。
  * 在UI库之上开发各种编辑器或是软件。
  * 剥离出一个跨平台的c语言工具库，就像jdk一样的cdk框架。
  * 使用cdk实现一个脚本语言MojoScript——lua的改进版本，然后完成高层逻辑抽象。
  * 使用cdk自举一个c的编译器。
  * 重写c标准库实现。
  * c实现操作系统内核。
  
* [MojoJS](https://github.com/scottcgi/MojoJS) 使用js实现了css3选择器、动画引擎、兼容性事件处理。

  这个项目使用业余时间在2009年完成，开始托管在google code上，后来放到github上就一直没有维护了。未来会把动画引擎继续完善做好，并加入webgl、asm.js、WebAssembly的支持。另外，会以模块形式开发，解决特定的痛点，做到小而美、开箱即用毫无负担（心理、理解、使用、性能、冗余）。
  
* [MojoUnityJson](https://github.com/scottcgi/MojoUnityJson) c#的json解析器。
  
  从unity3d的游戏框架中剥离出来的，已有的开源c# json解析器过于厚重，于是就把Mojoc的实现翻译成了c#的版本。未来会继续完善加入json的读写、与对象和字符串的转换，加密解密等等功能。
  
* 更多的开源项目和产品，以及unity3的插件正在路上……

```
乔布斯说，
工作是人生中最重要的体验，
坚持不懈地做好一件你认为具有非凡意义的工作，
能够给你带来真正的满足感，
而从事一份伟大工作唯一的方法，就是认真、敬业、执着、创新。

或许，端对端的控制，就是对有序的极致追求，就是工匠精神偏执到变态的表现。
```

## 游戏作品

* [Super Little Red（ios）](https://itunes.apple.com/cn/app/id1242353775)，测试Mojoc引擎可用性的小游戏。

## 科幻作品

* [我，斐星人（豆瓣阅读）](https://read.douban.com/ebook/36434451)  
——短篇（3.3万字），强人工智能的诞生，时间穿越，因果链，多次反转。

* [时间穿越之谜（豆瓣阅读）](https://read.douban.com/column/8581812)  
——长篇（18万字），这是关于时间旅行和宇宙的终极奥秘与构想。

## 对编程的热爱

编程的时候很开心，觉得时间过的很快，停不下来。总是知道下一步要做什么，要学什么，要实现什么。关于编程有说不完的想法，和闪闪发亮的计划。对待代码细致入微，有癖好，有固执，有坚持，有疯狂到变态般的完美主义。

从写的第一行代码，到现在，到未来，所有写过的，正在写的，和即将写的，那些零碎的，散乱的，还是整洁的，有条理的，不同角度和功能的，都是一个在不断进化的整体，可以与你的思维不断的交流融合，并和你一起发展与进步。

>刚接触编程的时候，就能感觉到编程能很好的配合自己的性格。  
>一个人很安静，对外界没有太多的依赖。  
>默默的把对事物的理解重新描述出来，也能不断校正自己原有的理解。  
>结果又是很有成就感的奖励。  
>整个过程的乐趣和愉快，在心里静静的流淌着。

```
编程天神卡马克说，
我的人生就是以知识的不断积累和学习的不断深入，来划分为不同的阶段的。
而在如今这个时代，客观障碍已经不复存在，所有的障碍都是你的主观心魔。
那么，程序员只要有了可乐披萨和一台联网的电脑，以及为之献身的决心，
就没有什么还能够阻止你去改变世界了！

对了，
唯一够阻挡你，去获取你想要的东西的事情，
就是你一直在告诉自己，为什么它不属于你！

还在等什么？
当所有的星星都能按你希望的方向连成一线的时刻么？
```
 
