# python基础及应用

## 一 、序

### 为什么学习编程？

- 软件改变生活
- 计算机人才缺口巨大
- 网络时代的历史潮流
- 史无前例的创新时代

### 程序

- 是人与计算机对话的语言
- 发展：从机械编程到高级编程

  1957年 FORTRAN	科学计算
  1959年 COBOL 	商业领域
  1964年 BASIC		编程普及
  1972年 C语言 		操作系统底层
  1991年 Python 	面向对象
  1995年 Java 		面向对象
  1995年 PHP 		Web动态网页开发
  2009年 Go		高并发和工程化软件
  2014年 Swift 		苹果软件开发

- 计算机思维：使用计算机擅长的能力解决问题

### python语言的历史和现状

- 为什么选Python

	- 十大最流行的计算机语言之一
	- 语法简洁，极大地提高了生产力
	- 跨平台，代码可读性高
	- 软件开源，可以被自由传播和分享

- Python的特性

	- Python语言集成了多种优秀语言的特性
	- 是一种高级动态，完全面向对象的语言
	- 函数、模块、数字、字符串都是对象
	- 并且完全支持继承、重载、派生、多继承
	- 有益于增强源代码的复用性

- Python的应用领域

	- 大型网站

	  YouTube， Google， 豆瓣， 果壳网， NASA， Django

	- 图像多媒体

	  GIMP， Blender， INdustrial Light & Magic

	- 系统文件

	  Dropbox， BitTorrent， Ubuntu Software， Center

	- 科学计算/大数据

	  MySQL Workbench， Numpy， Pandas

	- 人工智能

	  tensorflow

- Python的历史

	- 1989年12月，Guido van Rossum为了打发圣诞节假期，开发了ABC语言的后继

	  Python名称来自于他喜欢的一个情景剧Montyr Python‘s Flying Circus

	- 版本1.x：支持异常处理、函数定义，开发了核心数据结构
	- 版本2.x：支持列表解析、垃圾收集器和Unicode编码
	- 版本3.x：不向后兼容2.x，扫除了编程结构和模块上的冗余和重复
	- Python3的改变

		- 修改语法：使print( )函数成为内置函数
		- 改进了Python2中input( )函数
		- 统一字符编码
		- 更新了模块：删除了部分过时的模块或函数，添加一些新的模块
		- 数据结构dict性能的优化
		- 不再区分整数和长整数，统一为int
		- 整数/整数返回得到浮点数

- Python的现状：今年来发展迅速

	- 将许多机器层面上的细节隐藏，交给编译器处理
	- 面对对象和模块设计的模式
	- Python成为数据科学和机器学习的最常用语言
	- Python被广泛应用在自动化运维、Web开发、管理工具、部署、科学建模几乎所有领域
	- 简洁高效，入门门槛低
	- 通用。满足各种需求
	- 具有最丰富的功能扩展库
	- 能与高性能的c语言程序对接

- 排行榜

	- IEEE Spectrum 第一
	- TIOBE 第三

### 开发环境

- IDLE

	- 自带的:Shell-IDLE
	- PyCharm
	- Anaconda
	- Eclipse
	- Arachno
	- Pythonwin

- 文本编辑器

	- VIM
	- Emacs、Atom、Sublime
	- Text
	- Notepad++、Visual Studio Code

- 模块库

	- 官网

	- Github

## 二、基础

### python程序设计风格

- 优雅、明确、简单

	- Python版归并排序：
	- C语言版归并排序:

- 代码强制缩进
- 写给人读的——良好的编程规范

	- 变量、函数、类命名
	- 注释和文档
	- 一些编程设计上的良好风格

- Donald Ervin Knuth——高纳德

	- Programs are meant to be read by humans and only incidentally for computers to execute.
	- 《计算机程序设计艺术》
	- TeX
	- 图灵奖

- Python哲学

  >>>import this
  The Zen of Python, by Tim Peters
  
  Beautiful is better than ugly.
  Explicit is better than implicit.
  Simple is better than complex.
  Complex is better than complicated.
  Flat is better than nested.
  Sparse is better than dense.
  Readability counts.
  Special cases aren't special enough to break the rules.
  Although practicality beats purity.
  Errors should never pass silently.
  Unless explicitly silenced.
  In the face of ambiguity, refuse the temptation to guess.
  There should be one-- and preferably only one --obvious way to do it.
  Although that way may not be obvious at first unless you're Dutch.
  Now is better than never.
  Although never is often better than *right* now.
  If the implementation is hard to explain, it's a bad idea.
  If the implementation is easy to explain, it may be a good idea.
  Namespaces are one honking great idea -- let's do more of those!

### 内容

- 数据对象与组织

	- 数据

		- 信息的表现形式和载体
		- 对现实世界实体和概念的抽象
		- 抽象就是用相对重要的的信息来代表研究对象
		- 大数据

			- Volume 数据量大
			- Velocity 数据增长快
			- Variety 来源广
			- Value 价值密度低
			- Veracity 可验证性低

	- 多种多样的数据类型

		- 描述事物大小、次序的数值类型
		- 描述事物各方面特性的文本字符串类型
		- 描述事物时间属性的日期时间类型等
		- 复杂数据类型

			- 图像
			- 音频
			- 视频

	- 数据类型归纳

		- 简单类型用来表示值

		  整数int、浮点数float、复数complex、逻辑bool、字符串str

		- 容器类型用来组织这些值

		  列表list、元组tuple、集合set、字典dict

		- 数据类型之间几乎都可以转换

	- 对数据进行组织

		- 对大量的数据进行处理的时候，需要建立各种各样的数据组织，以便提高计算效率
		- 组织方式

			- 没有组织
			- 标签式组织数据
			- 队列、栈、树、图等

- 计算和控制流

	- 计算与流程

		- 对现实世界处理和过程的抽象
		- 各种类型的数据对象，可以通过各种运算组织成复杂的表达式

	- 运算语句

		- 将表达式赋值给变量进行引用
		- 赋值语句用来实现处理与暂存

		  表达式计算
		  函数调用
		  赋值

	- 控制流语句

		- 顺序结构
		- 条件分支：if
		- 循环结构：for、while

	- 定义语句

		- 定义语句也用来组织语句，把一系列运算语句集合起来给一个名字
		- 描述了一个包含一系列处理过程的计算单元，主要为了源代码的各种复用
		- 可以定义函数def、类class等“代码”对象
		- 调用函数或类，也可以得到数据对象，Python里所有可调用的事物称为callable

### 数据类型

- 基本

	- 数值

		- 整数int

			- 不限制大小
			- 常见运算

			  运算符		功能				备注
			  m + n		加法	
			  m - n		减法
			  m * n		乘法
			  m // n		整数除法		结果是商的整数部分
			  m / n		除法				“真”除法，得到小数
			  m % n		求余数
			  divmod(m, n)	求整数除法和余数		会得到两个整数，一个是m // n,另一个是m % n
			  m ** n		求乘方		整数m的n次方
			  abs(m)		求绝对值

			- 大小比较

			  m == n		相等
			  m > n		大于
			  m >= n		大于或等于
			  m < n		小于比较
			  m <= n		小于或等于
			  m < n < k		连续比较

			- 数的进制

			  常用：
			  十进制 decimal 无前缀
			  二进制 binary 0b前缀
			  八进制 octal 0o前缀
			  十六进制 hexadecimal 0x前缀

		- 浮点数float

			- 操作与整数类似
			- 受到17位有效数字的限制
			- 科学计数法

			  1.2334442423e+12
			  0.21321313e-30

			- 进制转换导致精度误差

		- 复数

			- 1+3j
			- 支持所有常见计算
			- 只能比较是否相等
			- 两个复数取模：abs( (3 + 3j) - ( 4 + 4j) )
			- 计算模块：cmath

	- 逻辑值
	- 字符串

- 变量和引用
- 容器

	- 列表和元组
	- 字典
	- 集合

- 可变类型与不可变类型
- 建立复杂的数据结构

### 计算和控制流

- 条件分支
- 条件循环
- 迭代循环

## 四、高级特性

## 三、模块

