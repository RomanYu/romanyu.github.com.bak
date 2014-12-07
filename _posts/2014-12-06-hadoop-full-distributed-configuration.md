--- 
layout: post 
title: hadoop完全分布式配置 
desc: <strong>hadoop配置有三种模式，单机，伪分布，完全分布式，本文主要介绍完全分布式。</strong> 
date: Dec 6, 2014 

permalink: /posts/hadoop-full-distributed-configuration.html 
--- 
hadoop配置有三种模式，单机，伪分布，完全分布式，本文主要介绍完全分布式。 
单机和伪分布都是在一个host上实现，单机没有尝试过，伪分布式成功过。实际上，较伪分布式而言，完全分布式多了一些步骤而已。 
 
在学习过程中，走了很多弯路，一是hadoop的版本更新很快，没有书籍是比较贴近现在的版本，由于版本更新后，hadoop以前的结构和现在又有所不一样；二是搜索出来的文档，很多并不能切实可行的适用于所有环境，linux版本太多，可能在ubuntu上可行在centos上有问题…总之，路漫漫兮其修远！ 

总得来说，步骤大概是： 

准备工作：jdk、ssh无密码等 —> hadoop配置：环境变量和xml修改 —> 启hadoop 

详细步骤见文档： 
<iframe src = "/img/hadoop_distributed_configuration.pdf" width = "100%" height = " 100%"></iframe> 

hadoop配置成功后，接下来就真正开始学习hadoop了！ 
 
转载请注明出处～ 
 

