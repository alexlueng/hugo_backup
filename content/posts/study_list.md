---
title: "Golang学习的一些心得体会"
date: 2019-07-22T18:22:18+08:00
draft: false
summary: 一个学习焦虑症患者的内心独白。希望能静下心来学习，找到一份心仪的工作。
---

转眼间，已经是毕业第五年的开始了。大概许多我的同学，在程序员这个行业上，已经是小有成就了。哈，不过由于历史原因，我和他们一直都很少有联系，也就无从得知他们的近况了。而我，还是停留在“入门”这个级别上。我想当一名真正的程序员，我想写一些有用的代码，能帮助到别人的代码，而不是每天都在写垃圾，写一些无用的java模板。也不想做一个运维了，那个工作太安闲，写不了代码，只能与服务器打交道。

其实这么多年来，会发现，程序语言到最后，大抵上是相通的。只要基础够好，学习一门语言是很快的，难的是要把它用到工作中，生活中。在日常中，我常常在想，到底我能用这门语言来做一些什么应用出来呢？我并不是一个追逐热门风口的人，现在的人都在推崇python吧，大数据，人工智能现在火得一塌糊涂，我对此却不是很感冒。以前我也自称自己是python程序员，但实际上，并不是说你会用python做一下数据处理，或者用pygame写一个小游戏，就能说是一个合格的python程序员。

直到4个月之前，我开始GO语言。我感觉我终于遇上了一门值得终身学习的语言，它是一个强类型的静态语言，设计的理念非常地先进。由于之前我一直用的python是一个脚本语言，我觉得十分的互补。于是便开始了漫长的学习之旅。

由于之前一直远离了开发的工作，其实学习起来还是有点吃力的。而且目前来看，这种脱产的学习方式其实是非常考验人的意志力的。首先环境带来的干扰非常大，而我又是一个意志力不坚定的人，所以学习总是断断续续的。效果非常的不好。所以前两个月的进展非常缓慢。收集了很多的学习资料，但是能坚持看完看透的并不多。直到最近两个月，自己感觉再这样下去是真的不行了，才下定决心，断舍离，先摒弃那些不重要的知识，把GO语言中一些核心的东西先掌握熟练了。

在学习GO语言时对我最重要的一本书就是《GO程序设计语言》，这本书写得真的是非常的好，感觉把这本书读透了，然后把书中的习题都弄懂，就可以去面试工作了。我的一个朋友说，要真正掌握一样东西，需要把它做三遍。目前我是第二遍在看这本书了，打算深入地去阅读一下，第一遍的时候没有做习题，这次把那些习题补上，其中感觉有些习题还是很难的。

最近在看一些GO程序员的招聘，感觉要求还是很高的。我有点担心自己的资历不够，为了让自己的简历好看一点，所以打算先做几个项目之后再去找工作，我选了四个项目，涉及了GO语言能做的各个方面。其实这篇文章也是想记录我做这些项目的进度，进而每天都能提醒自己，学如逆水行舟，不进则退。

1. 一个基于Gin框架的web项目。其实我用Gin做了三个应用，一个账号系统，一个博客系统，一个在线商店。单个的应用其实都是很简单的，无非就是一些路由的编写，还有数据的增删改查。接下来的工作是想把它们整合到一起，做一个真正功能全面的web应用。

2. 一个gRPC服务。这个项目会相对复杂一些，使用到的技术有：golang, mongodb, grpc, docker, Google Cloud, Kubernetes, NATS, CircleCI, Terraform and go-micro。毕竟RPC是互联网的未来，我想深入学习一下，所以花点时间也是值得的。

3. 一个分布式后台实现管理调度平台。这是幕课网的一个教程，讲述了使用go语言做分布式系统，使用了etcd, redis等技术，自己以前也没做过什么分布式的项目，所以觉得这个项目对自己的帮助还是很大的。

4. 最后是一个Go爬虫项目。这个项目主要是想掌握Go语言的核心：inteface和goroutine. 在学习的过程中，我始终对Go的inteface不是很理解，然后对goroutine的写法还不是很熟悉，但这正是Go最强大的地方，所以，无论花多大的力气，也是要把它啃下来的。

好了，暂时想到的就是这么多。既然选择了这条学习道路，就一直走下去吧，踏踏实实的，希望自己能学有所获。
