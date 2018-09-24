目前已经对接的互联网公司，金融公司，基金公司，银行等几十家企业，后端主要的技术：
服务框架：Dubbo，zookeeper，Rest服务
缓存：redis，ehcache
消息中间件：ActiveMQ，kafka
负责均衡：Nginx
分布式文件：FastDFS
安全框架：Apache shiro
任务调度：quartz
持久层框架：mybatis
日志：log4j
项目基础搭建。spring，springmvc，
环境搭建：linux下，
开发工具：eclipse。idea等
服务器：tomcat，jetty等

目前系统主流搭建：Nginx+tomcat+mybatis+redis。
针对不同的业务需求，我们会引用不同的技术。

这些主要定位于互联网企业架构

框架简介：

企业信息化系统基础功能和高效的代码生成工具，包括:

系统权限组件，数据权限组件，数据字典组件，核心工具组件，视图操作组件，工作流组件，代码生成等。采用分层设计，双重验证。提交数据安全编码，密码加密，访问验证，，数据权限验证、

平台简介：

是一个分布式的框架。提供项目模块化，服务化。热插拔的思想。高度封装安全性的java EE快速开发平台。

本身集成Dubbo服务管控，zookeeper注册中心。Redis分布式缓存技术。FastDFS分布式文件吸系统。ActiveMQ异步消息中间件，Nginx负责均衡等分布式技术。

使用maven做项目管理，项目模块化。提供项目的易开发性，扩展性。

 

以spring Framework为核心容器。SpringMVC为模型视图控制器，mybatis为数据访问层，Apache shiro为权限授权层。Ehcache对常用数据进行缓存。Activit为工作流引擎等。

 

前端集成bootstrap 框架。响应式

目前包括以下模块项目，后台系统管理系统。RestFull独立服务系统，Schedule定时调度系统，内容管理（CMS）系统，在线办公（OA）系统。我的待办（Task服务），我的收藏（bookmark服务）

提供了常用工具进行封装，包括日志工具、缓存工具、服务器端验证、数据字典、当前组织机构数据（用户、机构、区域）以及其它常用小工具等。另外 还提供一个强大的在线 代码生成 工具，此工具提供简单的单表、一对多、树结构功能的生成，如果对外观要求不是很高，生成的功能就可以用了。使用了基础框架，可以提高快速开发效 率。

内置功能(只列了一部分功能)

1.用户管理：用户是系统操作者，该功能主要完成系统用户配置。

2.机构管理：配置系统组织机构（公司、部门、小组），树结构展现，可随意调整上下级。

3.区域管理：系统城市区域模型，如：国家、省市、地市、区县的维护。

4.菜单管理：配置系统菜单，操作权限，按钮权限标识等。

5.角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。

6.字典管理：对系统中经常使用的一些较为固定的数据进行维护，如：是否、男女、类别、级别等。

7.操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。

8.连接池监视：监视当期系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。

9.工作流引擎：实现业务工单流转、在线流程设计器。

开发工具

1.Eclipse IDE：采用Maven项目管理，模块化。

2.代码生成：通过界面方式简单配置，自动生成相应代码，目前包括三种生成方式（增删改查）：单表、一对多、树结构。生成后的代码如果不需要注意美观程度，生成后即可用。

技术选型（只列了一部分技术）

1、后端

服务框架：Dubbo、zookeeper、Rest服务

缓存：Redis、ehcache

消息中间件：ActiveMQ

负载均衡：Nginx

分布式文件：FastDFS

数据库连接池：Alibaba Druid 1.0

核心框架：Spring framework

安全框架：Apache Shiro 1.2

视图框架：Spring MVC 4.0

服务端验证：Hibernate Validator 5.1

布局框架：SiteMesh 2.4

工作流引擎：Activiti 5.15

任务调度：quartz 1.8.5

持久层框架：MyBatis 3.2

日志管理：SLF4J 1.7、Log4j

工具类：Apache Commons、Jackson 2.2、Xstream 1.4、Dozer 5.3、POI

2、前端

JS框架：JQuery 1.9。

CSS框架： Bootstrap 4 metronic

客户端验证：JQuery Validation Plugin。

富文本：CKEcitor

文件管理：CKFinder

动态页签：Jerichotab

数据表格：jqGrid

对话框：jQuery jBox

树结构控件：jQuery zTree

其他组件：Bootstrap 4 metronic

3、支持

服务器中间件：Tomcat 6、7、Jboss 7、WebLogic 10、WebSphere 8

数据库支持：目前仅提供mysql数据库的支持，但不限于数据库，下个版本升级多数据源切换和数据库读写分离： 如：Oracle、SqlServer、H2等

支持开发环境：Eclipse、MyEclipse、Ras、Idea等

![img](https://upload-images.jianshu.io/upload_images/5712789-0d98f0f88087c840.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)