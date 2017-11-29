# 《深入理解Node.js：核心思想与源码分析》

Node.js 的源码分析，基于node v6.0.0。 

源码分析包括（libuv, v8）, 需要有一定的 C、C++基础。 Node.js 的源码到处闪烁着开发者的智慧和追求极致的精神。
包括但不限于：

- 系统架构

- 设计模式

- 性能优化

- 奇技淫巧

本书通过分析 node 核心模块的实现，向读者阐述 node 异步 IO，事件循环的核心思想。帮助开发者更好的使用 Node.js。

通过追溯 node 社区开发issue, 探讨 node 的变迁和演进，学习 node.js 的设计哲学。

# Table of content

* [惊鸿一瞥](chapter1/README.md)
  * [架构一览](chapter1/chapter1-0.md)
  * [为啥是libuv](chapter1/chapter1-1.md)
  * [V8 概念](chapter2/chapter2-0.md)
  * [C++和JS 交互](chapter2/chapter2-1.md)
* [从「hello world」讲起](chapter1/chapter1-2.md)
* [模块加载](chapter2/chapter2-2.md)
* [Global对象](chapter12/chapter12-1.md)
* [事件循环](chapter5/chapter5-1.md)
* [Timer 解读](chapter3/chapter3-1.md)
* [Yield 魔法](chapter3/chapter3-2.md)
* [Buffer](chapter6/chapter6-1.md)
* [Event](chapter7/chapter7-1.md)
* [Domain](chapter13/chapter13-2.md)
* [Stream 流](chapter8/chapter8-1.md)
* [Net 网络](chapter9/README.md)
  * [Socket](chapter9/chapter9-1.md)
  * [构建应用](chapter9/chapter9-2.md)
  * [加密](chapter9/chapter9-3.md)
* [HTTP](chapter10/README.md)
  * [HTTP Server](chapter10/chapter10-1.md)
  * [HTTP Client](chapter10/chapter10-2.md)
* [FS 文件系统](chapter11/README.md)
  * [文件系统](chapter11/chapter11-2.md)
  * [文件抽象](chapter11/chapter11-1.md)
  * [IO 那些事儿](chapter11/chapter11-3.md)
  * [libuv的选型](chapter11/chapter11-4.md)
  * [文件 IO](chapter11/chapter11-5.md)
  * [Fs 精粹](chapter11/chapter11-6.md)
* [进程](chapter13/README.md)
  * [进程](chapter13/chapter13-1.md)
  * [Cluster](chapter4/chapter4-1.md)
* [Node.js 的坑](chapter14/chapter14-5.md)
* [其他](chapter14/README.md)
  * [Node.js & Android](chapter14/chapter14-1.md)
  * [Node.js & Docker](chapter14/chapter14-2.md)
  * [Node.js 调优](chapter14/chapter14-3.md)
* [附录](chapter14/chapter14-0.md)


本书版权归作者所有，未经作者授权，禁止一切方式转载。


**如果您觉得还不错, 请我喝杯咖啡，欢迎Star,  提交PR** 


