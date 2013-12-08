# 《PHP扩展开发及内核应用》目录
   
   > 上一节: [《PHP扩展开发及内核应用》](</book/index.md>)
   > 下一节: [PHP的生命周期](</book/chapt01/1.md>)

目录中汉字部分代表已经翻译完成的章节，带链接的表示已经发布的，未待链接的表示正在校正即将发布的。

   1. [PHP的生命周期](</book/chapt01/1.md>)
      1. [让我们从SAPI开始](</book/chapt01/1.1.md>)
	  2. [PHP的启动与终止](</book/chapt01/1.2.md>)
	  3. [PHP的生命周期](</book/chapt01/1.3.md>)
	  4. [线程安全](</book/chapt01/1.4.md>)
	  5. [小结](</book/chapt01/1.5.md>)
   2. [PHP变量在内核中的实现](</book/chapt02/2.md>)
      1. [变量的类型](</book/chapt02/2.1.md>)
	  2. [变量的值](</book/chapt02/2.2.md>)
	  3. [创建PHP变量](</book/chapt02/2.3.md>)
	  4. [变量的存储方式](</book/chapt02/2.4.md>)
	  5. [变量的检索](</book/chapt02/2.5.md>)
	  6. [类型转换](</book/chapt02/2.6.md>)
	  7. [小结](</book/chapt02/2.7.md>)
   3. [内存管理](</book/chapt03/3.md>)
      1. [内存管理](</book/chapt03/3.1.md>)
	  2. [引用计数](</book/chapt03/3.2.md>)
	  3. [总结](</book/chapt03/3.3.md>)
   4. [配置编译环境](</book/chapt04/4.md>)
      1. [编译前的准备](</book/chapt04/4.1.md>)
      2. [PHP编译前的config配置](</book/chapt04/4.2.md>)
      3. [Unix/Linux平台下的编译](</book/chapt04/4.3.md>)
      4. [在Win32平台上编译PHP](</book/chapt04/4.4.md>)
      5. [小结](</book/chapt04/4.5.md>)
   5. [第一个扩展](</book/chapt05/5.md>)
      1. [一个扩展的基本结构](</book/chapt05/5.1.md>)
      2. [编译我们的扩展](</book/chapt05/5.2.md>)
      3. [静态编译](</book/chapt05/5.3.md>)
      4. [编写函数](</book/chapt05/5.4.md>)
      5. [小结](</book/chapt05/5.5.md>)
   6. [函数的返回值](</book/chapt06/6.md>)
      1. [一个特殊的参数：return_value](</book/chapt06/6.1.md>)
      2. [引用与函数的执行结果](</book/chapt06/6.2.md>)
      3. [小结](</book/chapt06/6.3.md>)
   7. [函数的参数](</book/chapt07/7.md>)
      1. [zend_parse_parameters](</book/chapt07/7.1.md>)
      2. [Arg Info 与类型绑定](</book/chapt07/7.2.md>)
      3. [小结](</book/chapt07/7.3.md>)
   8. [Array与HashTable](</book/chapt08/8.md>)
      1. [数组(C中的)与链表](</book/chapt08/8.1.md>)
      2. [操作HashTable的API](</book/chapt08/8.2.md>)
      3. [在内核中操作PHP语言中数组](</book/chapt08/8.3.md>)
      3. [小结](</book/chapt08/8.4.md>)
   9. [PHP中的资源类型](</book/chapt09/9.md>)
      1. [复合类型的数据——资源](</book/chapt09/9.1.md>)
      2. [Persistent Resources](</book/chapt09/9.2.md>)
      3. [资源自有的引用计数](</book/chapt09/9.3.md>)
      4. [小结](</book/chapt09/9.4.md>)
   10. [PHP中的面向对象（一）](</book/chapt10/10.md>)
      1. [zend_class_entry](</book/chapt10/10.1.md>)
      2. [定义一个类](</book/chapt10/10.2.md>)
      3. [定义一个接口](</book/chapt10/10.3.md>)
      4. [类的继承与接口的实现](</book/chapt10/10.4.md>)
      5. [小结](</book/chapt10/10.5.md>)
   11. [PHP中的面向对象（二）](</book/chapt11/11.md>)
      1. [生成对象的实例与调用方法](</book/chapt11/11.1.md>)
      2. [读写对象的属性](</book/chapt11/11.2.md>)
      3. [小结](</book/chapt11/11.3.md>)
   12. [启动与终止的那点事](</book/chapt12/12.md>)
      1. [关于生命周期](</book/chapt12/12.1.md>)
      2. [MINFO与phpinfo](</book/chapt12/12.2.md>)
      3. [常量](</book/chapt12/12.3.md>)
      4. [PHP扩展中的全局变量](</book/chapt12/12.4.md>)
      5. [PHP语言中的超级全局变量](</book/chapt12/12.5.md>)
      6. [小结](</book/chapt12/12.6.md>)
   13. [ini配置文件](</book/chapt13/13.md>)
      1. [读写ini配置](</book/chapt13/13.1.md>)
      2. [小结](</book/chapt13/13.2.md>)
   14. [流式访问](</book/chapt14/14.md>)
      1. [流的概览](</book/chapt14/14.1.md>)
      2. [打开与读写流](</book/chapt14/14.3.md>)
      3. [Static Stream Operations](</book/chapt14/14.3.md>)
      4. [小结](</book/chapt14/14.4.md>)
   15. [流的实现](</book/chapt15/15.md>)
      1. [PHP Streams的本质](</book/chapt15/15.1.md>)
      2. [流的封装——wrapper](</book/chapt15/15.2.md>)
      3. [实现wrapper](</book/chapt15/15.3.md>)
      4. [Manipulation](</book/chapt15/15.4.md>)
      5. [状态与属性读取](</book/chapt15/15.5.md>)
      6. [小结](</book/chapt15/15.6.md>)
   16. [有趣的流](</book/chapt16/16.md>)
      1. [流的上下文](</book/chapt16/16.1.md>)
      2. [流的过滤器](</book/chapt16/16.2.md>)
      3. [小结](</book/chapt16/16.3.md>)
   17. [配置和链接](</book/chapt17/17.md>)
      1. [Autoconf](</book/chapt17/17.1.md>)
      2. [库的查找](</book/chapt17/17.2.md>)
      3. [强制模块依赖](</book/chapt17/17.3.md>)
      4. [Speaking the Windows Dialect](</book/chapt17/17.4.md>)
      5. [小结](</book/chapt17/17.5.md>)
   18. [扩展生成器](</book/chapt18/18.md>)
      1. [ext_skel生成器](</book/chapt18/18.1.md>)
      2. [PECL_Gen生成器](</book/chapt18/18.2.md>)
      3. [小结](</book/chapt18/18.3.md>)
   19. [设置宿主环境](</book/chapt19/19.md>)
      1. [嵌入式SAPI](</book/chapt19/19.1.md>)
      2. [构建并编译一个宿主应用](</book/chapt19/19.2.md>)
      3. [通过嵌入包装重新创建cli](</book/chapt19/19.3.md>)
      4. [老技术新用](</book/chapt19/19.4.md>)
      5. [小结](</book/chapt19/19.5.md>)
   20. [高级嵌入式](</book/chapt20/20.md>)
      1. [回调到php中](</book/chapt20/20.1.md>)
      2. [错误处理](</book/chapt20/20.2.md>)
      3. [初始化php](</book/chapt20/20.3.md>)
      4. [覆写INI_SYSTEM和INI_PERDIR选项](</book/chapt20/20.4.md>)
      5. [捕获输出](</book/chapt20/20.5.md>)
      6. [同时扩展和嵌入](</book/chapt20/20.6.md>)
      7. [小结](</book/chapt20/20.7.md>)