---
title: "GO development tips"
date: "2021-12-28"
draft: false
description: ""
summary: "go开发中的一些技巧"
categories:
  - "golang"
tags:
  - "development"
menu: main # Optional, add page to a menu. Options: main, side, footer

# Theme-Defined params
thumbnail: "img/placeholder.jpg" # Thumbnail image
lead: "" # Lead text
comments: false 
authorbox: true 
pager: true 
toc: false
mathjax: true 
sidebar: "right" 
widgets: 
  - "search"
  - "recent"
  - "taglist"
---

平时有在reddit论坛上看外国人民是怎么使用go语言的，今天看到一个有趣的帖子，有人在论坛上发起了go开发中一些有用的技巧的讨论，还挺有意思的，因而转载过来，有些技巧是我自己都不知道的，正好可以试试，看是否能提高开发效率，也算是一份自查列表吧。

1. using Generate for creating unit tests and filling the necessary structures recursively in Goland. 在Goland中可以通过Generate来自动生成单元测试模板，然后填充核心的部分。（这个我真的不知道，一定要试试）
   
2. don't pass channel around and instead return result. Same goes for Waitgroups. Don't pass them as function parameters, instead wrap them in anonymous functions. 不要将channel和waitgroups当成参数传递，而是把它们包含在匿名函数中。


3. Don't write Java in go. 不要用java的思考方式来写go.


4. I need to learn pprof and all the tooling around. I'd like to learn more about collecting profiles. Jaegar is another tool I've never used, but would like to get some experience in.Another area I don't really get exposed to with hobby coding is unit testing with mocks. I typically just reuse the concrete types from my business logic to test. I feel like I'm not using interfaces or unit testing correctly.需要了解pprof和一些关于性能调优的工具，需要习惯mock单元测试的方式。


5. Jaeger is an amazing tool, and i highly recommend it. I never ship software without jaeger and prometheus. Jaeger是个好工具，我决不会发布没有jaeger或者prometheus的工具。


6. Vim-test makes developing TDD a breeze. vim-test让tdd像微风一样。（这是真的吗？）


7. MVC is great in certain languages and frameworks but it doesn’t work for golang. MVC是一个好的设计构架但不适合go.


8. If you're dealing with more than 1 goroutine, pass a context around as the first parameter.如果你要处理多个goroutine，传递一个context作为第一个参数。


目前觉得有用的就这些，还有一些其他的tips, 以后觉得好的话再补充吧。