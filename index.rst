.. gwpcn.com documentation master file, created by
   sphinx-quickstart on Sun May 14 09:15:18 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

《Go语言趣学指南》
=========================================

.. image:: image/cover.jpg
   :align: left

欢迎来到《Get Programming with Go》中文版《Go语言趣学指南》的读者服务网站！

本书将以循序渐进的方式讲解高效使用 Go 所必需的概念，并提供大量练习来磨砺你的技能。 
这是一本初学者指南，旨在从头到尾地进行阅读，并且每个课程都建立在前面课程的基础之上。 
本书虽然没有完整地描述 Go 的所有语言特性，但是却涵盖了其中的绝大部分特性，并且提及了面向对象设计以及并发等高级主题。

无论你是打算使用 Go 编写大型的并发 web 服务，还是说只想用 Go 编写小型脚本和简单的工具，本书都会帮助你打下坚实的基础。


购买
---------------

本书在以下网店或应用有售：

- 京东（\ `自营 <https://item.jd.com/12826232.html?dist=jd>`_\ 、\ `非自营 <https://search.jd.com/Search?keyword=Go%E8%AF%AD%E8%A8%80%E8%B6%A3%E5%AD%A6%E6%8C%87%E5%8D%97&enc=utf-8&qrst=1&rt=1&stop=1&vt=2&suggest=1.his.0.0&click=2>`_\ ）
- `淘宝 <https://s.taobao.com/search?initiative_id=tbindexz_20170306&ie=utf8&spm=a21bo.2017.201856-taobao-item.2&sourceId=tb.index&search_type=item&ssid=s5-e&commend=all&imgfile=&q=Go%E8%AF%AD%E8%A8%80%E8%B6%A3%E5%AD%A6%E6%8C%87%E5%8D%97&suggest=history_1&_input_charset=utf-8&wq=&suggest_query=&source=suggest>`_\ 
- 当当（\ `自营 <http://product.dangdang.com/28525763.html>`_\ 、\ `非自营 <http://search.dangdang.com/?key=Go%D3%EF%D1%D4%C8%A4%D1%A7%D6%B8%C4%CF&act=input>`_\ ）
- `异步社区 <https://www.epubit.com/bookDetails?id=UBb60129159591>`_\ （纸书&电子书）
- 人民邮电出版社官方旗舰店（\ `京东 <https://item.jd.com/66945871504.html>`_\ 、\ `天猫 <https://detail.tmall.com/item.htm?spm=a230r.1.14.68.35fd14b2UTlWmz&id=614129741187&ns=1&abbucket=19>`_\ 、\ `当当 <http://product.dangdang.com/1580063775.html>`_\ ）

目录&试读
--------------

你可以通过点击以下链接或者\ `下载 PDF 文件 <https://github.com/huangzworks/GPWG-website/raw/master/gpwgcn_preview.pdf>`_\ 来试读本书。

.. toctree::
   :maxdepth: 2

   preview/preface
   preview/foreword
   preview/ack
   preview/about_this_book
   preview/about_the_authors

:ref:`unit0`

.. toctree::
   :maxdepth: 2

   preview/lession1

:ref:`unit1`

.. toctree::
   :maxdepth: 2

   preview/lession2
   preview/lession3
   preview/lession4
   preview/lession5

**单元 2：类型**

- 第 6 章：实数

  - 6.1 声明浮点数变量
  - 6.2 打印浮点数类型
  - 6.3 浮点精确性
  - 6.4 比较浮点数
  - 6.5 课后小结

- 第 7 章：整数

  - 7.1 声明整数变量
  - 7.2 为 8 位颜色使用 uint8 类型
  - 7.3 整数回绕
  - 7.4 课后小结

- 第 8 章：大数

  - 8.1 击中天花板
  - 8.2 big 包
  - 8.3 大小非同寻常的变量
  - 8.4 课后小结

- 第 9 章：多语言文本

  - 9.1 声明字符串变量
  - 9.2 字符、代码点、符文和字节
  - 9.3 拉弦
  - 9.4 使用凯撒加密法处理字符
  - 9.5 将字符串解码为符文
  - 9.6 课后小结

- 第 10 章：类型转换

  - 10.1 类型不能混合使用
  - 10.2 数字类型转换
  - 10.3 类型转换的危险之处
  - 10.4 字符串转换
  - 10.5 转换布尔值
  - 10.6 课后小结

- 第 11 章：单元实验——维吉尼亚加密法

**单元 3：构建块**

- 第 12 章：函数

  - 12.1 函数声明
  - 12.2 编写函数
  - 12.3 课后小结

- 第 13 章：方法

  - 13.1 声明新类型
  - 13.2 引入自定义类型
  - 13.3 通过方法为类型添加行为
  - 13.4 课后小结

- 第 14 章：第一类函数

  - 14.1 将函数赋值给变量
  - 14.2 将函数传递给其他函数
  - 14.3 声明函数类型
  - 14.4 闭包和匿名函数
  - 14.5 课后总结

- 第 15 章：单元实验——温度表

**单元 4：收集器**

- 第 16 章：劳苦功高的数组
  
  - 16.1 声明数组并访问它们的元素
  - 16.2 小心越界
  - 16.3 使用复合字面量初始化数组
  - 16.4 迭代数组
  - 16.5 被复制的数组
  - 16.6 由数组组成的数组
  - 16.7 课后小结

- 第 17 章：切片——朝向数组的窗口

  - 17.1 分割数组
  - 17.2 切片的复合字面量
  - 17.3 切片的威力
  - 17.4 带有方法的切片
  - 17.5 课后小结

- 第 18 章：更大的切片

  - 18.1 ``append`` 函数
  - 18.2 长度和容量
  - 18.3 详解 ``append`` 函数
  - 18.4 三索引切片操作
  - 18.5 使用 ``make`` 对切片实行预分配
  - 18.6 声明可变参数函数
  - 18.7 课后小结

- 第 19 章：无所不能的映射

  - 19.1 声明映射
  - 19.2 映射不会被拷贝
  - 19.3 使用 ``make`` 实行映射预分配
  - 19.4 使用映射进行计数
  - 19.5 使用映射和切片实现数据分组
  - 19.6 将映射用作集合
  - 19.7 课后小结

- 第 20 章：单元实验——切片人生

  - 20.1 开天辟地
  - 20.2 适者生存
  - 20.3 平行世界

**单元 5：状态与行为**

- 第 21 章：结构

  - 21.1 声明结构
  - 21.2 通过类型重用结构
  - 21.3 通过复合字面量初始化结构
  - 21.4 结构将被复制
  - 21.5 由结构组成的切片
  - 21.6 将结构编码为 JSON
  - 21.7 使用结构标签定制 JSON
  - 21.8 课后小结

- 第 22 章：Go 没有类

  - 22.1 将方法绑定至结构
  - 22.2 构造函数
  - 22.3 类的替代品
  - 22.4 课后小结

- 第 23 章：组合与转发

  - 23.1 合并结构
  - 23.2 方法转向
  - 23.3 命名冲突
  - 23.4 课后小结

- 第 24 章：接口

  - 24.1 接口类型
  - 24.2 探索接口
  - 24.3 满足接口
  - 24.4 课后小结

- 第 25 章：单元实验——火星上的动物避难所

**单元 6：深入 Go 语言**

- 第 26 章：关于指针的二三事

  - 26.1 & 和星号
  - 26.2 指针的作用就是指向
  - 26.3 实现修改
  - 26.4 隐式指针
  - 26.5 指针和接口
  - 26.6 明智地使用指针
  - 26.7 课后小结

- 第 27 章：关于 nil 的纷纷扰扰

  - 27.1 通向惊恐的空指针
  - 27.2 保护你的方法
  - 27.3 Nil 函数值
  - 27.4 Nil 切片
  - 27.5 Nil 映射
  - 27.6 Nil 接口
  - 27.7 Nil 之外的另一个选择
  - 27.8 课后小结

- 第 28 章：孰能无过

  - 28.1 处理错误
  - 28.2 优雅地错误处理
  - 28.3 新的错误
  - 28.4 不要惊恐
  - 28.5 课后小结

- 第 29 章：单元实验——数独规则

**单元 6：并发编程**

- 第 30 章：Goroutine 与并发

  - 30.1 启动 goroutine
  - 30.2 不止一个 goroutine
  - 30.3 通道
  - 30.4 使用 SELECT 处理多个通道
  - 30.5 阻塞和死锁
  - 30.6 地鼠装配线
  - 30.7 课后小结

- 第 31 章：并发状态

  - 31.1 互斥
  - 31.2 长时间运行的工作进程
  - 31.3 课后小结

- 第 32 章：单元实验——寻找火星生命

  - 32.1 可供活动的网格
  - 32.2 报告发现

| 结语：何去何从
| 附录：参考答案
| 索引


对本书的赞誉
-----------------

*这本书的组织方式对于快速学习 Go 来说堪称完美，
它对那些没有经验的程序员尤为有用。* 
—— MARIO CARRION ，MEREDITH 公司

*这是一本注重实践的书。 
书中包含的大量示例将帮助你学习 Go 语言的核心知识， 
并教会你 Go 语言常见的惯例用法。*
—— ULISES FLYNN ，NAV 公司

*一本关于 Go 的好书。 
为初学者而写， 
但是对经验丰富的开发者也会有所帮助。*
—— MIKAËL DAUTREY ，ISITIX 公司

*成功攀登 Go 高峰的第一步。*
—— JEFF SMITH ，AGILIFY 公司


作者简介
------------------

.. image:: image/NATHAN.jpg

NATHAN YOUNGMAN （内森·扬曼）既是一位自学成才的网络开发者，也是终生学习概念的一位践行者。
他是加拿大埃德蒙顿市 Go 聚会的组织者，Canada Learning Code 机构的导师以及地鼠玩偶的狂热摄影爱好者。

.. image:: image/ROGER.jpg

ROGER PEPPÉ （罗杰·佩珀）是一位 Go 贡献者，他维护着一系列开源 Go 项目，运营着英国纽卡斯尔市的 Go 聚会，并且当前正在担任 Go 云端基础设施软件的相关工作。

译者简介
------------------

.. image:: image/HUANGZ.jpeg
   :scale: 30%

黄健宏（huangz）是一位 IT 技术图书作译者。
他著有《Redis使用手册》和《Redis设计与实现》，译有《Go Web 编程》和《Redis实战》。
关于他的更多信息请访问 `huangz.works <http://huangz.works>`_ 。



相关资源
--------------

`《Go语言趣学指南》原书在 Manning 出版社的主页 <https://www.manning.com/books/get-programming-with-go>`_

`《Go语言趣学指南》的配套源码 <https://github.com/nathany/get-programming-with-go>`_

`《Go语言趣学指南》原书试读 <https://livebook.manning.com/book/get-programming-with-go/>`_


