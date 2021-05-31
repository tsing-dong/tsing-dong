# 基本信息
![](https://gitee.com/tsing-document/articletopics_pic/raw/master/resume/essentialinformation.png)

# 工作经历
![](https://gitee.com/tsing-document/articletopics_pic/raw/master/resume/workexperience.png)

# 教育经历
2011.09 - 2015.07 江苏南方科技专修学院 电子信息科学与技术 本科

# 项目经验

## 北京易客信息有限公司
> 1、百场汇

`项目描述：`百场汇是一个致力于广大公司的团建，年会，会议，各个地点的预定。系统前期主要订单来源是通过 SEO 进行各大网站进行需求投放，后期开启 CRM 系统维护老客户，对公司开辟一条资金链，将公司化被动为主动，大大提高了资金收入。 
后台系统自动分单系统，能够高效的处理用户询价，及时回复用户咨询信息，运营流程系统更快的跟踪订单的状态。 cms管理系统使公司的产品跟便于维护，上架下架。网站能够在不改动前端的情况下，快速上线。

`技术点：`项目中的基础架构使用的是**SpringBoot整合Dubbo（服务治理），Zookeeper作为注册中心。** 存储使用的是关系型数据库 **MySQL** 和 非关系型数据库 **Redis。** 购买亚马逊服务器做为服务托管平台。使用 **大汉三通**
作为短信通知平台。**七牛云**作为图片存储平台。

`个人职责：`
>> 1、使用redis存储热点数据，核心存储了两种数据：1、存储网站结构。2、存储源数据（项目中的关键字、支撑业务数据的底层数据）。  
>> 2、使用阿里的Seata框架做分布式事务。  
>> 3、使用Zookeeper作为分布式锁。  
>> 4、搭建jenkins自动化部署平台成一站式代码管理。  
>> 5、使用永洪系统统计数据定时发送给运营leader发送绩效，以及统计每个月的业绩。   
>> 6、前期使用普通的`ssm`架构，使用httpclient进行服务之间的调用，因为服务之间调用复杂。后期改成了SpringBoot整合Dubbo项目。  
>> 7、前期的需求调研，将核心业务调研完成，业务对应数据库表。后期进行架构的改造。   
>> 8、项目架构重构之后，整理出项目结构图和部署结构图。  
>> 9、亚马逊服务的管理（20台机器）。

## 泰豪科技信息有限公司
> 1、国调云

`项目描述：`国调云是帮助国家电网进行更好的协调各个部门之间工作指令的下发，以及设备的状态的管理。主要分为核心云和地方云，核心云分为一线城市。地方云会将数据同步到核心云上。

`技术点：`项目中使用的基础架构是**SpringBoot整合Dubbo（服务治理），Zookeeper作为注册中心。** 存储主要使用的是国内的数据库，**达梦6、达梦7、金仓、Oracl。** 利用 **Nginx** 进行前端的负载均衡。

`个人职责：`
>> 1、前期到各个地方的国家电网进行开发和需求的开发，通过和项目经理沟通，将公共业务抽取出来，用新的技术架构重新设计。  
>> 2、使用redis存储用户信息，用于session共享。   
>> 3、使用kettle进行地方云和核心云之间的数据传输。  
>> 4、因为国家电网属于企业性质的项目，将所有的页面抽取成工具，以后类似的项目可以通过配置进行快速开发和交付。  
>> 5、内部网络环境搭建（硬件）和内部服务器（2台IBM）管理，主要是安装**GitLab、禅道、文件系统、jenkins等等。**

## 北京中图信息
> 1、sage

`官网地址：`https://journals.sagepub.com/

`项目描述：`sage主要是对书籍和书刊的管理，这个项目主要是服务于英国和北大的学生。用户可以进行书刊和文章的购买和订阅。项目中可以进行了国家化的管理。

`技术点：`项目中使用的后端基础架构是普通的`SpringMVC、Spirng、MyBatis`，前端使用普通的`Jsp+Css+Js`做页面。利用 **Nginx** 进行前端和后端的负载均衡。存储使用了关系型数据库`MySQL`和非关系型数据库`Redis。` 使用`ES`存储文章。

`个人职责：`
>> 1、使用Redis实现用户的session共享和用户对文章期刊的订阅。   
>> 2、使用ES存储文章，利用`alibaba-easyexcel`进行文章的批量导入。   
>> 3、搭建后台管理平台可以维护源数据和文章的管理。

# 专业技能
- 1、项目框架的搭建：SpringBoot、Dubbo、Zookeeper并整合MySQL、Redis等等。
- 2、硬件网络的搭建，软件系统的装置。
- 3、Linux安装`FELK、GitLab、Nginx、JDK、Maven、Nexus`等服务。
- 4、Shell脚本的编写。
- 5、使用React、Vue、Ts简单的前端的开发。

# 兴趣爱好
跑步、树莓派制作游戏机、树莓派制作模型小汽车、旅游！


 
