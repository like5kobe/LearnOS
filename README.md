### LearnOS

### 信号量
 1. P操作和V操作
 2. 解决进程间的同步与互斥
 

### 分段和分页
 程序加载到内存中，由于空间不足的问题，通过分页表的索引与内存管理单元（MMU）进行调度
  （虚拟存储器与之相关联）

### 同步 异步 互斥

同步就是多个线程同时访问一块资源，而且这种访问是有序的，必须等待上一个线程请求完成，并接收到返回信息后，才可以发送请求，线程间是等待和协调的运行  

异步就是线程间彼此独立，与同步的区别就是不用等待请求返回信息，就可以发送其它请求，做其它事情，因此它的效率也要高于同步

互斥是两个线程不能同时访问同一块资源，但是互斥无法限制访问顺序，A访问完了，下一次可能是B，也可能是C，只要不是同时访问某一块资源，这个过程就是互斥。同步是有顺序的，可以理解为有顺序的互斥

### 虚拟内存与虚拟地址

  虚拟内存是计算机系统内存管理的一种技术。它使得应用程序认为它拥有连续的可用的内存（一个连续完整的地址空间），而实际上，它通常是被分隔成多个物理内存碎片，还有部分暂时存储在外部磁盘存储器上，在需要时进行数据交换

 
### 装载、链接与库

    ELF和DLL PE
    
### 计算机体系结构

### 虚拟存储器

### 核心
  cpu的体系架构、C语言、汇编语言(原理)、操作系统
  
### 系统调用
  
  系统调用的作用： 
   
1. 内核可以基于权限和规则对资源访问进行裁决，保证系统的安全性。 
2. 系统调用对资源进行抽象，提供一致性接口，避免用户在使用资源时发生错误，且编程效率大大提高。

系统调用与函数调用的区别： 
1. 调用形式和实现方式不同。功能号 VS 地址； 用户态转换到内核态 VS 用户态。 
2. 被调用代码的位置不同。 动态调用 + 操作系统 VS 静态调用 + 用户级程序。 
3. 提供方式不同。 操作系统 VS 编程语言。

    
    
