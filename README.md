
<p align="center">
<a href="https://github.com/Snailclimb/JavaGuide" target="_blank">
	<img src="https://pic.imgdb.cn/item/5f6572d3160a154a677dc43a.jpg" width=""/>
</a>
</p>
<p align="center">
  <a href="https://www.cnblogs.com/yuyueq"><img src="https://img.shields.io/badge/博客园-read-brightgreen.svg" alt="阅读"></a>
  <!-- <a href="#公众号"><img src="https://img.shields.io/badge/%E5%85%AC%E4%BC%97%E5%8F%B7-JavaGuide-lightgrey.svg" alt="公众号"></a> -->
  <a href="https://blog.csdn.net/Frank_dwx"><img src="https://img.shields.io/badge/CSDN-read-important.svg" alt="csdn"></a>
</p>


<h3 align="center">欢迎来到余月七的GitHub资料收藏小栈</h3>

# Java
---
## 基础

正在收集……

---
## Spring

### IOC与DI

**1.[SpringIoC&DI](docs/java/framework/spring/1/SpringIoC&DI.md)**
  
  + 1. spring概述
    - 1.1 Spring是什么（理解）
    - 1.2 Spring发展历程 （了解）
    - 1.3 Spring的优势（理解）
    - 1.4 Spring的体系结构（了解）
  + 2. spring快速入门
    - 2.1 Spring程序开发步骤 
    - 2.2 导入Spring开发的基本包坐标
    - 2.3 编写Dao接口和实现类
    - 2.4 创建Spring核心配置文件
    - 2.5 在Spring配置文件中配置UserDaoImpl
    - 2.6 使用Spring的API获得Bean实例
  + 3. Spring配置文件
    - 3.1 Bean标签基本配置 
    - 3.2 Bean标签范围配置 
    - 3.3 Bean生命周期配置
    - 3.4 Bean实例化三种方式
    - 3.5 Bean的依赖注入入门
    - 3.6 Bean的依赖注入概念
    - 3.7 Bean的依赖注入方式
    - 3.8 Bean的依赖注入的数据类型
    - 3.9 引入其他配置文件（分模块开发）
  + 4. spring相关API
    - 4.1 ApplicationContext的继承体系
    - 4.2 ApplicationContext的实现类
    - 4.3 getBean()方法使用
 


**2.[SpringIoC和DI注解开发](docs/java/framework/spring/2/SpringIoC和DI注解开发.md)**

+ 1.Spring配置数据源
  - 1.1 数据源（连接池）的作用 
  - 1.2 数据源的手动创建
  - 1.3 Spring配置数据源
  - 1.4 抽取jdbc配置文件
  - 1.5 知识要点 
+ 2. Spring注解开发
  - 2.1 Spring原始注解
  - 2.2 Spring新注解
+ 3. Spring整合Junit
  - 3.1 原始Junit测试Spring的问题
  - 3.2 上述问题解决思路
  - 3.3 Spring集成Junit步骤
  - 3.4 Spring集成Junit代码实现


### Aop

**3.[SpringAop](docs/java/framework/spring/3/SpringAop.md)**

+ 1.Spring 的 AOP 简介
  - 1.1 什么是 AOP 
  - 1.2 AOP 的作用及其优势
  - 1.3 AOP 的底层实现
  - 1.4 AOP 的动态代理技术
  - 1.5 JDK 的动态代理
  - 1.6 cglib 的动态代理
  - 1.7 AOP 相关概念
  - 1.8 AOP 开发明确的事项
    - 1)需要编写的内容
    - 2）AOP 技术实现的内容
    - 3）AOP 底层使用哪种代理方式
  - 1.9 知识要点

+ 2. 基于 XML 的 AOP 开发
  - 2.1 快速入门
  - 2.2 XML 配置 AOP 详解
    - 1) 切点表达式的写法
    - 2) 通知的类型
    - 3) 切点表达式的抽取
  - 2.3 知识要点

+ 3.基于注解的 AOP 开发
  - 3.1 快速入门
  - 3.2 注解配置 AOP 详解
    - 1) 注解通知的类型
    - 2) 切点表达式的抽取
  - 3.3 知识要点

**3.[SpringJdbcTemplate&声明式事务](docs/java/framework/spring/4/SpringJdbcTemplate&声明式事务.md)**


+ JdbcTemplate基本使用
  - 01-JdbcTemplate基本使用-概述(了解)
  - 02-JdbcTemplate基本使用-开发步骤(理解)
  - 03-JdbcTemplate基本使用-快速入门代码实现(应用)
  - 04-JdbcTemplate基本使用-spring产生模板对象分析(理解)
  - 05-JdbcTemplate基本使用-spring产生模板对象代码实现(应用)
  - 06-JdbcTemplate基本使用-spring产生模板对象代码实现（抽取jdbc.properties）(应用)
  - 07-JdbcTemplate基本使用-常用操作-更新操作(应用)
  - 08-JdbcTemplate基本使用-常用操作-查询操作(应用)
  - 09-JdbcTemplate基本使用-知识要点(理解，记忆)
  
+ 声明式事务控制
  - 1. 编程式事务控制相关对象
    - 1.1 PlatformTransactionManager 
    - 1.2 TransactionDefinition
      - 1. 事务隔离级别
      - 2. 事务传播行为
  - 1.3 TransactionStatus
  - 1.4 知识要点
+ 2 基于 XML 的声明式事务控制
  - 2.1 什么是声明式事务控制
  - 2.2 声明式事务控制的实现
  - 2.3 切点方法的事务参数的配置
  - 2.4 知识要点
 
+ 3 基于注解的声明式事务控制
  - 3.1 使用注解配置声明式事务控制
  - 3.2 注解配置声明式事务控制解析
  - 3.3 知识要点

---
## SpringMVC


**1.[Spring与Web环境集成即入门](docs/java/framework/springMVC/1/Spring与Web环境集成即入门.md)**

**2.[SpringMVC数据请求与响应](docs/java/framework/springMVC/2/SpringMVC数据请求与响应.md)**

**3.[SpringMVC的文件上传、拦截器及异常处理](docs/java/framework/springMVC/3/SpringMVC的文件上传、拦截器及异常处理.md)**


#### Spring+SpringMVC综合练习
**4.[Spring+SpringMVC综合练习](docs/java/framework/springMVC/4/Spring+SpringMVC综合练习.md)**

---

## MyBatis
**1.[Mybatis快速入门](docs/java/framework/Mybatis/1/Mybatis快速入门.md)**

**2.[Mybatis的dao层实现原理](docs/java/framework/Mybatis/2/Mybatis的dao层实现原理.md)**

**3.[Mybatis的多表操作](docs/java/framework/Mybatis/3/Mybatis的多表操作.md)**

**4.[SSM整合](docs/java/framework/Mybatis/4/SSM整合.md)**

---


















