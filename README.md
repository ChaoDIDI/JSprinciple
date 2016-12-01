# JSprinciple
# JavaScript 包管理器工作原理简介
不久前，Node.js 社区的负责人之一   [ ashley williams ]:https://github.com/xitu/gold-miner 发了一条这样的推特： 
lockfiles = awesome for apps, bad for libs this is not a new thought, i’m confused why’s everyone mad about this  
锁文件 = 棒（对于应用而言），坏（对于库而言），这不是一个新想法，我只是很困惑，为什么所有的人都因为这个很崩溃  

我不是很懂她说的是什么，所以我决定去深入钻研下，学习一些包管理器的工作机制  

这是个对的选择,因为JavaScript管理器这个大组织中出现了一个新成员,叫做Yarn,刚刚出现,就引发了很多讨论. 

所以利用这个机会,也来理解一下Yarn是怎样和npm区分开来的.为什么要这样.  

我在研究这个的时候觉得很有意思,真希望很久以前就这么做了,所以我现在写一篇关于npm和yarn的简单介绍,来分析我学到的一些东西.  
