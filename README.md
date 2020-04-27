# 1. 项目简介

本项目是一个完整的基于Spring，SpringMVC， Mybatis框架的Java web项目，项目的主要内容是实现一个网购商城，主要目的是为了巩固本人的SSM框架知识。

本项目功能齐全，完成了如下一系列典型的场景功能：

* 购物车
* 订单状态流转
* 后台的各种功能，如CRUD， 分页
* 一类产品的多属性配置，一款产品的多图片维护
* 产品展示，搜索查询
* 登录、注册、退出、登录验证
* 事务管理

# 2. 项目启动

1. 项目下载到本地后，首先执行如下SQL语句创建数据库：

   ```
   CREATE DATABASE tmall_ssm DEFAULT CHARACTER SET utf8;
   ```

2. 在cmd环境下执行SQL语句（考虑到要导入的tmall_ssm.sql文件比较大，所以通过命令行执行会更好）

   ```
   "D:\tools\MYSQL\mysql-5.1.57-win32\bin\mysql.exe" -u root -p123456 --default-character-set=utf8 tmall_ssm < d:\tmall_ssm.sql
   ```

   注：用户名和密码分别为root，123456

然后将项目导入IDEA，并配置tomcat，即可启动项目。

浏览器打开`http://127.0.0.1:8080/tmall_ssm/`可访问前台页面。

浏览器打开`http://127.0.0.1:8080/tmall_ssm/admin`可访问前台页面。