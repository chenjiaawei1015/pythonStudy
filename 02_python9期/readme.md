## python知识目录

### day01

- Python2 与 Python3 区别
- 编译型,解释型语言
- 变量
- 常量
- 注释
- input
- 数据类型
- if 条件
- while 循环
- break
- continue

### day02

- 格式化输出
- while-else
- 编码
- 计算机单位换算
- 逻辑运算
  - 数字间的逻辑运算
- int 与 bool 之间的转换

### day03

- 数据类型
- int
- bool
- str

### day04

- 列表
- 元祖

### day05

- 字典

### day06

- python2 与 python3 的几点区别
- is
- id
- 小数据池
- 编码初识

### day07

- 列表,字典在遍历过程中删除元素出现的问题分析
- 集合
- 深浅拷贝
- enumerate

### day08

- 文件操作的6种方式
- With 关键字操作文件
- 解码

### day09

- 文件修改
- 函数
- 函数返回值
- 函数参数

  - 位置参数 默认参数 动态参数

  - 位置参数 默认参数 动态参数的书写顺序
- 函数注释

### day10

- 函数默认参数陷阱
- 函数命名空间
- 命名空间查找顺序
- 函数作用域
- 函数嵌套调用
- 函数嵌套定义
- 闭包

### day11

- 装饰器函数
- @语法糖
- 装饰器模板

### day12

- wraps
- 带参数的装饰器
- 多个装饰器装饰同一个函数

### day13

- 双下方法
- 可迭代协议与迭代器协议
- 迭代器
- for循环原理
- 生成器函数

### day14

- 生成器函数案例
- send
- 生成器表达式
- 列表推导式

### day15

- 生成器面试题
- 生成器取值应该采取的顺序
- 内置函数

### day16

- 内置函数
- 匿名函数

### day17

- 递归
- 二分查找算法
- 斐波那契数列

### day18

- 正则表达式
- re模块

### day19

- collections
- 时间模块
- random
- os
- sys

### day20

- 序列化
  - json
  - pickle
  - shelve
- 模块导入
  - import
  - from ... import ...

### day21

- 模块导入
  - \_\_all\_\_
- 包
- 软件开发规范
- 异常及异常处理

### day22

- 面向对象
- 类
- 对象
- 实例化
- 初始化方法
- 类属性

### day23

- 静态属性
- 动态属性(方法)
- 组合

### day24

- 单继承
- 多继承
- 新式类与经典类
- 广度优先与深度优先
- super本质

### day25

- 接口类
- 抽象类
- 多态
- 鸭子模型
- 封装
  - 私有属性
  - 私有方法

### day26

- 私有方法不能被子类继承
- property
  - setter
  - getter
  - deleter
- classmethod 类方法
- staticmethod 静态方法
- 反射
  - setattr
  - getattr
  - hasattr
  - delattr

### day27

- 包使用的注意点
- isinstance
- issubclass
- 反射
- 类的内置方法
  - \_\_str\_\_
  - \_\_repr\_\_
  - \_\_del\_\_
  - \_\_call\_\_

### day28

- 类的内置方法
  - \_\_getitem\_\_
  - \_\_setitem\_\_
  - \_\_delitem\_\_
  - \_\_eq\_\_
  - \_\_hash\_\_
- hashlib模块
  - sha系列
  - md5

### day29

- configparser 模块
- logging 模块

### day30

- 计算机网络
  - 计算机通信的历史
  - ip地址和ip协议
  - mac地址
  - arp协议
  - 子网掩码
  - tcp和udp通信过程
  - osi七层模型
- socket编程
  - 基于tcp的socket
  - 基于udp的socket

### day31

- udp案例: 时间同步服务器
- 黏包
  - 黏包的原因
  - 黏包出现的两种情况
  - 黏包的两种解决方案
- struct模块

### day33

- hmac 模块
- 验证客户端的合法性
- socketserver
- socketserver源码分析

### day35

- 操作系统知识
- 进程

### day36

- 模拟socketserver
- 守护进程
- 锁
- 信号量
- 事件
- 进程间通信
- 队列
- 生产者消费者模型

### day37

- 管道
- Manager
- 进程池

### day38

- 进程池的回调
- 线程
- 全局解释器锁 GIL
- 线程与进程的比较
  - 效率问题
  - 资源共享

### day39

- 基于线程的socket通信
- 守护线程
- 互斥锁
- 递归锁
- 死锁
- 信号量
- 事件
- 条件
- 定时器
- 线程队列
  - 先进先出
  - 先进后出
  - 优先级
- concurrent.feature模块
- 进程池与线程池

### day40

- 协程
- Greenlet模块
- Gevent模块
- 五种IO模型

### day41

- 多路复用IO模型
- select模块
- IO模型的比较
- selectors模块

### day42

- 软件安装
- 库
- 表
- 记录
- 数据
- SQL语句

### day43

- 单表查询
  - 聚合函数
  - 分组查询
  - 分页查询
  - 正则表达式
  - SQL 执行顺序
- 多表查询
  - 多表联合查询
  - 多表连接查询
    - 内连接
    - 左外连接
    - 右外连接
    - 全连接
  - 复杂条件的多表查询
  - 子查询
- 关键字

### day44

- 临时表查询
- 条件判断
- SQL查询语句执行顺序
- 外键约束
- 其他约束
  - 主键约束
  - 唯一约束
  - 默认值约束
- 表与表的关系

### day45

- 视图
- 触发器
- 存储过程
- 函数
- 事务
- 锁
- 数据库的备份和恢复

### day46

- 存储引擎
- 索引
- 查询计划
- 慢日志查询
- 大数据查询优化

### day47

- html文档结构
- 标签格式
- head常用标签及属性
- body常用标签及属性

### day48

- form表单
- input标签
- css的引入
- css选择器
- css选择器的优先级

### day49

- css属性

### day51

- js的引入
- 规范
- 变量
- 数据类型
- 操作符
- 流程控制
- 函数

### day52

- 词法分析
- 内置对象和方法

### day53

- BOM
- window对象
- DOM
- 标签节点事件的操作

### day54

- jQuery
- 选择器
- 筛选器

### day55

- 样式
- 位置
- 尺寸
- 文本
- 属性
- 文档操作

### day56

- 事件

### day59

- pymql操作mysql数据库
- sql注入问题
- 库,表的创建
- 数据的增删改查

### day60

- Django的安装

- Django工程结构
- Django配置
- 基础api(HttpResponse, render, redirect)

### day61

- shortcuts三大基础api
  - HttpResponse
  - render
  - redirect
- GET与POST请求
- Django操作sqlite3数据库

### day62

- Django连接MySQL数据库
- 创建表
- 对数据库的增删改查操作

### day63

- Django修改表的注意事项
- 外键操作
- 反向查询

### day64

- Django 多对多关系的处理
- ORM相关操作(一)
- 学生管理系统代码

### day65

- 日志中打印SQL
- Django框架
- 模板系统
- 母版
- 块
- 组件
- 静态文件

### day66

- 路由
- url配置
- url正则匹配
- 分组命名namespace
- 视图
- CBV与FBV及其装饰器
- Request
- Response
- JsonResponse
- 学生管理系统优化版(路由+正则匹配+url反向解析+CBV)

### day67

- 请求的处理过程
- 反向解析URL
- name模式
- namespace模式

### day68

- ORM介绍
- python datetime模块
- ORM字段和参数
- 元信息
- ORM相关操作(二)

### day69

- 第一部分
  - 聚合查询
  - 分组查询
  - F查询
  - Q查询
  - 锁
  - 事务
  - 执行原生SQL语句
  - QuerySet其他方法

- 第二部分
  - Cookie
  - Session
  - 分页

### day70

- AJAX使用
- AJAX优缺点
- csrf_token设置
- Django内置的serializers

### day72

- Django中间件
- 默认的中间件
- 自定义中间件
- 中间件的5个方法
  - process_request
  - process_response
  - process_view
  - process_exception
  - process_template_response
- 中间件的执行流程
- Django请求流程

### day74

- Importlib 模块导入
- session流程源码分析
- Django auth用户认证模块
- auth_user 表的字段扩展

- 项目01 博客管理系统
  - 验证码图片的生成 pillow模块
  - 模块文件的全局 request

