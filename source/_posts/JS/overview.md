---
title: JavaScript简介
thumbnail: "https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1550489282456&di=e4f2ee7260c8a746a316590001179d7a&imgtype=0&src=http%3A%2F%2Fe.hiphotos.baidu.com%2Fimage%2Fpic%2Fitem%2Fbf096b63f6246b60905f18b3e6f81a4c500fa2a0.jpg"
categories: 
- JavaScript基础
tags:
- JavaScript
---

## 什么是JavaScript?

  1. JavaScript是一种轻量级的脚本语言。所谓脚本语言（script language）指的是不像C或者汇编语言一样具备开发操作系统的能力，只用来编写控制其他大型应用程序（比如：浏览器）的脚本。
  </br>
  2. JavaScript是一种嵌入式（embeded）语言。只适合嵌入大型应用程序环境，调用宿主环境提供的API。
    - 本身提供的核心语法很少，只能用来做一些数学以及逻辑运算;
    - 本身不提供任何I/O(输入/输出)相关的API，全靠宿主环境提供;
    - 目前嵌入的宿主环境：浏览器、服务器（Node）。
  </br>
  3. JavaScript是一种"对象模型"语言。各种宿主环境通过这个模型描述自己的功能和操作接口，从而通过JavaScript控制这些功能。但是又不是一种纯粹的"面向对象"的语言，还支持其他编程范式（函数式编程）。

## 核心语法

  1. 基本语法构造（操作符、控制结构、语句）
  2. 标准库（一系列具有各种功能的对象：Array、Date、Math）

## 宿主环境

  ##### 1. 浏览器
    - 浏览器控制类：操作浏览器
    - DOM类：操作网页的各种元素
    - Web类：实现互联网的各种功能

  ##### 2. 服务器（Node）
    - 各种操作系统的API（文件操作、网络通信）

## 性能
  1. 灵活的语法，表达能力强
  </br>

  2. 支持编译运行
    - JavaScript 语言本身，虽然是一种解释型语言，但是在现代浏览器中，JavaScript 都是编译后运行。程序会被高度优化，运行效率接近二进制程序。而且，JavaScript 引擎正在快速发展，性能将越来越好。

    - 还有一种 WebAssembly 格式，它是 JavaScript 引擎的中间码格式，全部都是二进制代码。由于跳过了编译步骤，可以达到接近原生二进制代码的运行速度。各种语言（主要是 C 和 C++）通过编译成 WebAssembly，就可以在浏览器里面运行
  </br>

  3. 事件驱动和非阻塞式设计
    JavaScript 程序可以采用事件驱动（event-driven）和非阻塞式（non-blocking）设计，在服务器端适合高并发环境，普通的硬件就可以承受很大的访问量。

## 发展历程

## 广泛的使用：JavaScript正在向通用系统语言发展
  - 浏览器的平台化
  - Node
  - 数据库操作（NoSQL）
  - 移动平台开发
  - 内嵌脚本语言
  - 跨平台桌面应用程序
