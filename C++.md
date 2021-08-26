# C++面试积累
### 字节序
[理解字节序](https://www.ruanyifeng.com/blog/2016/11/byte-order.html)。

字节序分为：
1. 大端字节序：符合人类阅读习惯；
2. 小端字节序：计算机电路先处理低位字节，效率较高。

所以，计算机内部处理大部分是小端字节序，而网络传输、文件存储基本上是大端字节序。硬件设备处理外部传入的数据时，必须知道数据的字节序，将其转换为符合自己操作的字节序。然后正常处理数据。处理完成后直接向外输出，其他设备自己去处理字节序问题。

### 字节对齐
[C语言字节对齐问题详解](https://www.cnblogs.com/clover-toeic/p/3853132.html)

### 函数的调用过程
[C函数调用过程原理及函数栈帧分析](https://segmentfault.com/a/1190000007977460)

### malloc的实现细节
### 内存碎片产生的细节
https://blog.csdn.net/tong5956/article/details/74937178

Linker
https://www.airs.com/blog/archives/38
https://www.airs.com/blog/archives/date/2007/08

如何编写动态库
https://www.akkadia.org/drepper/dsohowto.pdf




atoi()函数和stoi()函数
https://blog.csdn.net/zrh_CSDN/article/details/80712373