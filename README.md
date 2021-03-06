Mini-Refactor
=============
Introduction
-------------
从马丁·福勒的《重构》一书中，我们了解到在一些开发的项目的代码具有["糟糕的气味"](http://wiki.c2.com/?CodeSmell)，而这些会造成项目的开发、运行和维护变得复杂。<br>
>「在不改变代码外在行为的前提下，对代码做出修改，以改进程序的内部结构」。重构是一种有纪律的、经过训练的、有条不紊的程序整理方法，可以将整理过程中不小心引入错误的机率降到最低。本质上说，重构就是「在代码写好之后改进它的设计」。<br>

我们小组基于比赛要求，了解了程序的语法规则，分别对代码布局的格式化、代码内部的命名以及一些基本的流程控制语句互转在重构方面进行了探索和实现。<br>

目录介绍
------------
* Java Resource
>* RefactorController
>>*
>* RefactorService
* WebContent
>* Css
>* front
>* js
>>* jquery

快速开始
-------------
打开 `Eclipse`>>点击 `File`>>选择 `Import``WAR Import`>>在[WAR file]一栏点击'Browse...'打开文件夹后找到refactor.war>>点击`Finish`<br>
在`Servers`中配置好`Tomcat`(版本：Apache Tomcat v7.0)>>在Tomcat中运行无误后>>在浏览器中输入：http://localhost:8080/refactor<br>
点击`浏览`选择需要重构的代码(大小不超过3M)>>点击`上传`>>点击`代码重构`<br>

测试
-------------
![image](https://upload-images.jianshu.io/upload_images/16032439-89dcc4475bf16edf.gif)

开发者
-------------
靳坤<br> 
[Morty](https://github.com/KevinMorty)(汪诗雨) <br> 
田凤荣<br> 

讨论
-------------
参考资料：
[Google Java Style Guide](https://google.github.io/styleguide/javaguide.html)
[CheckStyle](https://github.com/checkstyle/checkstyle)
[集成 FindBugs、CheckStyle、Cobertura 与 Rational Team Concert 构建系统](https://www.ibm.com/developerworks/cn/rational/integration-rational-team-concert-quality-tools/index.html)
[Static program analysis](https://en.wikipedia.org/wiki/Static_code_analysis)
