市面上有很多编程语言 那么编程语言安装到本地时安装的是什么呢 并且应该如何安装 

#一·安装内容

1.编译器或者解释器
对于编译型语言来说会安装编译器 解释型语言会安装解释型 因为计算机最终执行的是机器语言代码 程序员写的是源代码 需要把源代码翻译成机器语言

2·可执行工具链文件
一般在bin下

3·运行时环境
比如内存分配 垃圾回收 线程的调度

4·标准库文件
5·相关文档和相关脚本



二·安装方式

1·包管理器安装

![1741676150594](https://github.com/user-attachments/assets/e437e804-9586-4a0b-b7c9-6c3d0aa25e14)




2·官网下载

![1741676288386](https://github.com/user-attachments/assets/1f1e8923-38be-4bdb-8796-8f6da5b4f5ee)



需要注意的是使用压缩包格式文件解压后需要手动处理环境

例如tar.gz 用tar zxvf后 需要./configure 检测环境 make 编译 make install 安装环境

zip解压后需要配置环境

而安装包格式比较自动化 会自动安装



三·安装选择

![1741676315307](https://github.com/user-attachments/assets/b0f92bc9-309e-41e6-8fa4-2d0abb347ebf)
