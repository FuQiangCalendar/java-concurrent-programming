# 《Java并发编程由浅入深》

## 目录

- [ ] 线程基础
  - [ ] 线程创建与运行
  - [ ] 线程通知与等待
  - [ ] 线程的虚假唤醒
  - [ ] 等待线程执行终止的 join 方法
  - [ ] 让线程睡眠的 sleep 方法
  - [ ] 线程中断
  - [ ] 理解线程上下文切换
  - [ ] 线程死锁
  - [ ] 守护线程与用户线程
- [ ] 线程进阶
  - [ ] 什么是多线程并发和并行
  - [ ] 什么是线程安全问题
  - [ ] 什么是共享变量的内存可见性问题
  - [ ] 什么是Java中原子性操作
  - [ ] 什么是Java中的CAS操作
  - [ ] AtomicLong实现原理
  - [ ] 什么是Java指令重排序
  - [ ] Java中Synchronized关键字的内存语义是什么
  - [ ] Java中Volatile关键字的内存语义是什么
  - [ ] 伪共享
  - [ ] 锁
- [ ] 线程原理分析
  - [ ] ThreadLocal 的实现原理
  - [ ] InheritableThreadLocal 的实现原理
  - [ ] ThreadLocalRandom 类原理剖析
  - [ ] ThreadLocal 的使用场景
  
  
使用（Usage)
------------

目录由命令行工具 [gitbook-summary](https://github.com/imfly/gitbook-summary) 自动生成。自由写作、发布，搭建自出版平台的方法，请[点击这里](https://github.com/imfly/how-to-create-self-publishing-platform)

简要介绍如下：

(1)克隆源文

```
$ git clone https://github.com/jxzsxsp/java-concurrent-programming.git
```

(2)安装gitbook

```
$ npm install -g gitbook-cli
```

(3)安装依赖包

```
cd java-concurrent-programming
npm install
gitbook install
```

(4)写作构建

写作，并开启服务（构建）

```
$ gitbook serve
```

通过`http://localhost:4000`实时浏览

(5)生成目录

只要修改了文章标题和文件夹，就应该重新生成目录文件

```
$ npm run summary
```

(6)一键发布

```
$ npm run deploy
```

以后，只要4-6的过程就是了。
  