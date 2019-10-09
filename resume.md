
## 基本信息
- 姓名： 刘杰
- 邮箱： lj_soft@126.com
- 所在地： 西安
- 手机号： 18729091227
## 教育背景
> * 2011.09 ~ 2015.6 西安工业大学计算机科学与技术学院 网络工程专业
> * 主修课程： 数据结构 编译原理 操作系统 数据库系统 计算机组成原理 C语言程序设计 Java程序设计 Java组件等
## 自我介绍
> 本人有4年半软件开发工作经验，主要从事工业4.0领域自动化解决方案， 有一年项目管理经验，带领过十人的团队为公司BG、BU定制系统，负责需求讨论，系统设计以及交付。本人有非常好的技术热情，有持续关注CoolShell、Frank等具有影响力的博客， 持续深入学习Spring生态套件，对Docker、k8s等新技术都强烈的兴趣，主动积极学习并在公司项目中推广和摸索实施。学习能力强，实习生期间独立完成从未接触过的Eclipse插件开发，为公司平台级框架的使用提供及其便利的tool。获得大家的一致认可。
## 工作经验
> 本人服务于台达电子西安研究院，主要参与工业4.0智慧工厂的相关项目。致力于研发工业智慧化系统以取代生产中的人力。参与过IOT平台级研发，以及在该平台之上的Solution开发。实际上线之后确实有提高生产效能、良率以及一定程度上减少了人力。
## 项目经验
> - MES(Include SPC)微服务化
    - `时间` 2018.2 ~ 至今
    - `概述` 整合MES系统各个模块，使用Spring Cloud 进行微服务化。构建Cloud生态，对系统进行有效监控分析(spring-admin)，提供基于组件(registry, gateway, config, bus, auth-center, elk )帮助团队快速微服务系统。利用docker，gitlab-ci等实现CICD,  
    - `目标` 对MES系统进行微服务拆分
    - `细节`
        1. 构建Spring cloud 系统，搭建基础组件等
        2. 建制CICD流程
        3. 提供业务模块的auth(A&A)模块
        4. 提供业务模块写log到elk中
        5. 提供微服务trace log, 以便于业务模块可以清晰的知道微服务之间的调用逻辑
> - Statistical Process Control System
    - `时间` 2016.06 ~ 2017.12
    - `概述` 该项目主要通过借助数理统计方法对生产过程进行分析评价，根据反馈信息及时发现系统性因素出现的征兆，并采取措施消除其影响，使过程维持在仅受随机性因素影响的受控状态，以达到控制质量的目的。架构层面微服务化，验证并优化CICD的方式
    - `目标` 减少生产产线50%QC质检人员
    - `细节`
        1. 系统分为表现层、控制层、业务逻辑层、DAO层和最终数据库五层架构。
        2. 系统中采用了代理模式、单例模式、模板模式等经典设计模式。
        3. 项目WEB层采用当前流行的MVC模式，SpringMVC框架(B/S)，使用AJAX技术实现异步无刷新，使用Json实现数据异步传递, RactJs提供页面的呈现
        4. 持久层使用轻量级映射框架 Mybatis。
        5. 服务层面向接口编程，使用代理模式，由Spring托管，DAO层使用Mybatis访问数据库， POJO类由Mybatis Generaor生成，引用BeanUtils包进行DTO对象与POJO之间的转换，由Spring托管Spring的Controler，Service层 ，DAO层的接口实现类。
        6. 微服务改造， 依据业务的边缘进行拆分，用spring boot 作为微服务的载体。 使用spring cloud 提供的基础组建快速实现微服化。考虑到测试部署的方便性， 引入 docker 使得 spring boot 组建容器化，使用 kubernetes 进行容器的编排管理
> - Common Component Library  
    - `时间` 2015.03 ~ 2015.05（2016.01 ~ 至今处于维护阶段）  
该项目为公司内部打造一个代码共享的平台， 同其他子系统都有一定的交互。后期也提供了trouble tick的相关操作, 以及bug 的申报修复等功能,同maven仓库联动实现内部lib管理。
主要技术：Spring、SpringMVC、Mybatis，Mysql、WebSphere， 使用JBPM灵活的管理Component的审阅以及发布等， 采用行业最流行技术MVC分层架构模型以Restful形式对外服务采用了Mysql数据库管理系统。使用Reactjs实现前台呈现
> - Data analysis System  
    - `时间` 2015.03 ~ 2015.05  
项目主要帮助硬件团队完成测试数据的可视化分析。以便于能直观的发现产品存在的问题，从测试场机台下来的数据文件， 解析到Data analysis System的Mongodb中，然后生成统计学的相关报表。项目最终减少改BU 60%的分析人员同时精准度有了极大的提升
主要技术：Spring、SpringMVC、Spring-data，Mongodb、Jetty， 采用行业最流行技术MVC分层架构模型以Restful形式对外服务,采用了Mongodb数据库管理系统。使用html+css+jquery实现前台， 使用d3.js与mychart.js 实现报表
## 证书
* 年度优秀员工
* IBM 认证java工程师
## 技能
* Java
* C语言
* Python
* Javascript
* Spring（core, mvc, boot, cloud,jdbc ...）
* Mybatis
* Mysql Oracle Postgress
* MongoDB Redis Hbase Phoneix
* Ogsi
* Jbpm
* Gradle Maven
* Tomcat Jetty
* Centos Ubuntu
* Docker Kubernetes
