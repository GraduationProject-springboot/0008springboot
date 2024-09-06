# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0008springboot月度员工绩效考核管理系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV16ia6epENY?p=9)


# 第1章 引言
## 1.1课题研究现状
如今社会是离不开计算机协助工作的社会，无论在哪个行业都可以看到计算机的身影。大到国家单位企业，小到身边小商贩，计算机技术早已与人类生活融为一体。计算机极大的方便了人类的生活，为人类的工作提供了更好的协助，在计算机技术中加入网络的技术更是现代发展的趋势。可以实现信息流通，更是复杂工程项目的得利助手。计算机技术在复杂的项目中表现更为优秀，这与信息的处理效率联系紧密。本系统就是为了给企业带来更为高效的管理而开发设计。在大多数的企业中虽然有一些企业用上了企业的办公软件，但因为这些办公软件一般都是针对企业管理人员而设计的辅助软件，员工想要进行必要的信息查询时，还需要找领导审批进行，所以这并不能减轻管理人员的工作压力，只能提高一定的工作效率，现如今的现状是急须一款既可以提高工作效率又可以减少工作量的办公系统。
## 1.2课题研究意义及背景
计算机技术的发展离不开社会的进步，同样所有的技术发展也都离不开经济的支持。如今已进入通信行业和网络发展的高潮时期，网络的速度更是更新换代的变化着，全民已进入5G时代，大街小巷也都充斥着无线网络，方便着人们的生活与办公。正是因为科技的发展，人们对办公软件的要求也越来越严格与苛刻。在现代企业中对于员工绩效考核的管理大多还是采用半人工化管理，也就是在签到中采用指纹或者人脸识别进行签到，但在考核、工资统计与审核中还是采用老式（人工进行统计审核）的管理方式，这也就促使人事工作人员在每月统计考核信息时工作非常繁忙。每条信息都需要多次核对才能保证考核的正确性。这种老式的管理方式对于小规模人数较少的企业来说还是非常好用，但是，企业如果想要具有更好的竞争力，就需要从各个角度来提高企业整体效率。想要解决问题的最好办法就是加入最新科技的支持，开发适合本企业使用的信息管理系统。

把多种复杂和不同分类的信息交由计算机来处理是现代管理工作的标志之一。计算机技术可以实现快速查询与统计分类信息的功能，其好处是有目共睹的。不仅可以减少工作压力，更可以加快工作速度，所以越来越多的人使用计算机技术来实现办公要求。计算机技术对于复杂的工作也可以有效的保证正确率，减少工作人员的核对。现如今对计算机技术的资金投入压力也非常小，综合考虑，在企业中引入计算机技术的月度员工绩效考核管理系统还是非常有好处的。
## 1.3课题的目的及设计要求
本系统的设计目的就是为企业带来更为高效的工作辅助软件，减轻企业人事工作人员的办公压力，同时降低企业的员工成本。使用月度员工绩效考核管理系统可以把多人的工作量减化到一人负责，并且员工也可以进行信息核对查询。本系统的开发包括管理员和员工两个角色，对于数据库的要求包括数据的完整性和安全性，对于功能方面要求符合实际要求和简单实用。本课题要求可以帮助企业对员工绩效考核进行完整的、系统的管理，要求可以帮助企业提高工作效率和减少工作压力。

本系统的主要内容包括部门信息、岗位信息、员工信息、绩效指标、绩效考核信息、公告信息等。管理员发布绩效指标和考核详情，员工可以在线查询。所以在数据库设计的时候需要注意表之间的关系。在系统的界面要求中需要注意友好与简洁，操作流程要适应市场需求。
## 1.4论文内容与组成部分
`     `本论文就是对月度员工绩效考核管理系统的开发进行全面的介绍，也展现了系统开发的过程。一般系统开发的过程为系统分析阶段、系统设计阶段、系统实现阶段、系统测试阶段。论文的内容在此基础上加入摘要、摘要翻译、目录和总结、致谢、参考文献等。











# ` `第2章 系统需求分析与系统开发分析
## 2.1系统的需求分析
`    `古往今来，对于企业员工绩效考核的管理一直存在，主要的管理方式就是人工加计算机结合进行管理。在签到中采用签到机进行，在数据统计中采用人工进行。这种方式的缺点就是不能用于中大型规模的公司，而且对于效益好的企业来说这种管理方式也非常的浪费时间和人力。对于每次的统计都需要多人参与和多次核对，出错率较高。在科技发展的今天，这些不同分类的信息完全可以交由计算机来进行处理，不会出错，效率还很高，计算机与网络结合的月度员工绩效考核管理系统的优点非常明显。
## 2.2现行员工绩效考核管理系统优缺点分析
现在很多的企业也都引入了计算机的员工绩效考核管理系统，这些现有的员工绩效考核管理系统的优缺点非常明显。通过本人调查发现，现有的员工绩效考核管理系统的优点有：

（1）大多数的员工绩效考核管理系统采用的是c/s结构模式，对于数据的安全非常可靠；

（2）大多数的员工绩效考核管理系统采用的是关系型的数据库进行企业数据的管理，性能非常高；

（3）大多数的员工绩效考核管理系统对于信息的更新方面，界面的设计方面都非常的成熟和完善。

缺点有：

（1）系统稳定性不高，因为采用了c/s结构进行开发，所以当依靠的计算机一旦崩溃，企业中的所有信息数据都不复存在，并且c/s结构的并发性操作非常严重，如果在代码编写中不注意将会影响系统的稳定，编码人员为了满足用户的要求需要进行代码的多次改写，c/s结构的系统在经过多次修改后，容易有并发症，造成系统不稳定；

（2）系统安全性不高，因为系统非常依赖客户机，所以在系统设计中大多采用的是脚本模式，这种模式对于安全性不可靠。
## 2.3系统设计中应注意的问题及解决方法
### 2.3.1应注意的问题
主要包括三个方面：

（1）对于数据库的选择，数据库的重要性不必多次言明，为了保证系统中的数据安全，必须选择安全性高、移植性强的数据库，并且可以和其它数据库进行完美结合，不依赖某一数据库；

（2）为了保证系统的可扩展性，可以不断的满足用户的要求，要求系统在设计中拥有良好的扩展性；

（3）为了减少系统的开发周期以及增加系统的使用寿命，需要选择好的开发语言和环境。
### 2.3.2解决办法
根据多方研究与结合本人实际能力，选择的解决办法有：

（1）对于数据库，本系统选择mysql数据库；

（2）对于系统的扩展性，本系统采用springboot模式；

（3）对于开发环境和开发技术，本系统采用java语言和myeclipse运行平台。
## 2.4系统使用技术与开发环境平台分析
### 2.4.1 Jsp技术介绍
Jsp是作为一种新兴起来的页面编程技术，主要结合在java编程使用，可以和html完美结合匹配，具有很多的优点，可以向下兼容，最大的优点就是可以全部的面向对象使用，而且可以自己选择电脑的操作系统，不论xp系统还是win7，win10都可以完美的兼容，不存在兼容问题，相较于asp语言等，具有很好的兼容性，可以自动生成网页页面代码，可以处理服务端的文件，自动更新数据，支持各种网络协议，所以是目前比较流行的web开发技术。而且支持目前市面上的大多数服务器，比如像iis tomcat等，有的甚至还支持CGI，可以作为cgi的处理器工作，同时还支持各种数据库的应用，比如像微软的sql server或者mysql数据库，都可以匹配使用。而且jsp对于刚入门的新手来说，更是比较简单，而资深的专业人士使用，也能更大发挥他的特性，所以比较受开发人员的喜爱。
### 2.4.2 Mysql数据库
Mysql是作为目前最常见也是使用率最高的一种数据库，最大的原因就是其体积小，灵活性好，功能强大。不论电脑多大内存，什么处理器，都可以很简单的就安装上，而且功能丰富，实用性更强。因为其体积小的原因，所以相对应的处理速度非常快，减缓了网站的延迟性，成本相对更低，作为目前主流网站的首选数据库应用。而且作为一款开源软件是完全免费的，可以结合java jsp  php 安卓等使用，开发人员可以不花钱就可以全部免费使用，建立自己的网站使用。Mysql数据库也经过不断的改良从5.0版本升级到现在的5.7版本了。功能也是不断的完善，使用起来也是非常的方便，也可以通过navicat for mysql直接进入可视化图形界面，进行新建和执行数据库文件，非常的方便了。Mysql最大的好处就是体积很小，所以处理速度就非常快了，可以在windiows系统上使用。扩展性和兼容性也是很好的，生成的脚本文件可以和sql数据库或者orange共用。可以在本地就实现系统管理和配置，还有数据库自动保护机制，从而保障数据存储的安全，一般情况跟java语言链接用的比较多，通过jdbc的方式实现数据库连接，从而保障系统顺利运行。因为技术以及非常的成熟，所以是目前很主流的一个数据库管理软件，使用者也是非常的多。
### 2.4.3 SpringBoot框架介绍
SpringBoot是由Pivotal团队在2013年开始研发、2014年4月发布第一个版本的全新开源的轻量级框架。它基于Spring4.0设计，不仅继承了Spring框架原有的优秀特性，而且还通过简化配置来进一步简化了Spring应用的整个搭建和开发过程。另外SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性等问题得到了很好的解决。SpringBoot框架中还有两个非常重要的策略：开箱即用和约定优于配置。开箱即用，Outofbox，是指在开发过程中，通过在MAVEN项目的pom文件中添加相关依赖包，然后使用对应注解来代替繁琐的XML配置文件以管理对象的生命周期。这个特点使得开发人员摆脱了复杂的配置工作以及依赖的管理工作，更加专注于业务逻辑。约定优于配置，Convention over configuration，是一种由SpringBoot本身来配置目标结构，由开发者在结构中添加信息的软件设计范式。这一特点虽降低了部分灵活性，增加了BUG定位的复杂性，但减少了开发人员需要做出决定的数量，同时减少了大量的XML配置，并且可以将代码编译、测试和打包等工作自动化。
### 2.4.4 tomcat服务器介绍
开发本系统所用到的服务器用的是 tomcat，因为tomcat是属于一个轻量级化的处理器，非常适合小型项目的开发，可以作为单机运行的服务器。主要是用来调试java语言开发中的jsp代码调试用的，因为他的内存很小，占用的系统资源就少，这样的话处理运行速度就非常的块，而且扩展性很好，他是由Apache和sun公司等一起联合开发的，所以兼容性也非常的强。支持好多框架的代码运行，比如mvc ,ssm，ssh等框架都可以用他来调试运行。Tomcat服务器的运行原理是，在软件里配置好tomcat以后，直接启动，就可以直接主动执行jsp的代码，然后反应到html页面访问，最后就呈现到浏览器里面向用户进行呈现出来了。所以说，开发本系统采用tomcat服务器是很好用的，内存下，效率高，也是目前程序员最受欢迎的一个小型服务器。
## 2.5系统开发可行性分析
### 2.5.1经济可行性
开发本系统硬件设备只需要一台电脑即可，在现如今的时代，相信电脑已经不是什么奢侈品，家家户户都可以使用了。有了硬件之后，只需要安装编程所需要的软件myeclipse ，mysql等，而这些软件全部都是作为开源软件免费使用，网上就可以很容易下载安装使用，所以开发本系统在经济上是可行的。
### 2.5.2技术可行性
本系统采用在windows系统上进行开发，微软的windows系统是目前市场占有率最高，使用人群最多的系统，系统非常的成熟和稳定，可以满足开发使用。服务器采用tomcat，也是可以在web开发中被大量使用的，技术是比较成熟的。用jsp创建页面，然后跟前后台进行交互，mysql数据库作为数据存储，这些技术全部是目前市面上运用了最多最成熟的技术，所以在技术上是可行的。
### 2.5.3操作可行性
本系统开发完成以后，直接在浏览器就能运行打开，以浏览网页的形式进行，只要用户懂得电脑的基本常识就可以，而且该系统设计的导航栏功能都比较直观可见，用户可以轻易的点击使用，而且点击功能都带有相应的跳转提示，比如登录界面，会提示输入账号密码的信息，用户只需要根据提示就可以简单使用，而且网站布局简单明了。所以在操作上也是完全可行的。
## 2.6系统开发功能分析
`   `本系统的功能分为管理员和员工两个角色，管理员的功能有：

（1）个人中心管理功能，添加管理员账号和修改登录密码；

（2）部门信息管理功能，对企业中的部门进行合理安排；

（3）员工信息管理功能，对企业中的员工的基本资料进行维护；

（4）绩效考核管理功能，发布员工的绩效考核，修改和删除不正确的绩效考核；

（5）岗位信息管理功能，对员工的岗位进行分配；

（6）公告信息管理功能，发布公告和管理公告；

（7）绩效绩效指标管理功能，需要考核的指标进行设置。

员工的功能有：

（1）个人资料管理功能，对本人基本信息进行维护；

（2）公告信息管理功能，实现在线查询公告；

（3）绩效考核管理功能，查询自己的考核信息；

（4）绩效指标管理功能，查询考核的指标。
## 2.7系统角色之间的用例分析
### 2.7.1管理员用例图分析
管理员的功能根据上节已进行完整的分析，根据功能画出管理员的用例图如下图2.1所示：

![](/md/blog.001.png)

图2.1管理员用例图
### 2.7.2员工用例图分析
员工的功能也已在上节进行详细的分析，本系统的员工用例图如下图2.2所示：

![](/md/blog.002.png)

图2.2员工用例图
## 2.8系统主要业务流程分析
想要系统的操作流程与逻辑正确就需要事先进行系统的流程设计分析，本系统的业务流程如下图2.3所示：

` `![](/md/blog.003.png)

图2.3系统业务流程图

本系统的使用用户包括管理员和员工两个，管理员与员工都需要先进行登录才可以进入管理系统中，管理员和员工的账号均由企业分配，不能自主申请，防止了非法人员的侵入。管理员登录后可以进行的数据管理包括绩效指标管理、绩效考核管理、部门管理，岗位管理、公告管理以及员工管理，员工登录后的功能包括个人资料管理、绩效考核管理，绩效指标管理。两种权限的数据唯一的有岗位信息、部门信息；共享的信息包括公告信息、绩效指标信息、绩效考核信息和员工个人信息。
#

#




# 第3章　系统设计
系统的设计对系统实现以及后期的维护启着重要的作用，在系统设计中要综合考虑问题，即要考虑到用户的需求也要考虑到系统本身实现的问题。
## 3.1系统体系结构设计
本系统采用的结构为b/s结构，是一种通过浏览器来进行访问和反馈的结构，b/s结构分为两部分，一部分是在前台进行请求，一部分在后台进行结果反馈。主要的表现在服务器上，b/s结构适应不断发展的应用技术，对于系统可以不断的进行扩展。
## 3.2系统功能结构设计
根据系统分析中分析出来的功能，本系统的主要功能包括部门管理、岗位管理、绩效指标管理、绩效考核管理、员工管理、通知管理等。本系统的功能结构设计如下图3.1所示：

![](/md/blog.004.png)

图3.1系统功能结构图
## 3.3数据库结构设计
对于数据库的设计包括数据库的ER图设计和数据库表的设计。数据库的ER图就是对系统中数据的实体和关键字进行设置。数据库表的设计就是把ER图转换成表格，具体的设计下两节介绍。
### 3.3.1数据库ER图设计
本系统中的主要数据有管理员信息、员工信息、绩效指标信息、绩效考核信息等，主要画出关键实体。

（1）管理员实体的Er图如下图3.2所示：

![](/md/blog.005.png)

图3.2管理员Er图

（2）管理员管理的员工信息ER图如图3.3所示。

![](/md/blog.006.png)

图3.3员工信息ER图

（3）企业中部门信息ER图如图3.4所示：

![](/md/blog.007.png)

图3.4部门信息ER图

（4）绩效考核信息ER图如下图3.5所示：

![](/md/blog.008.png)

图3.5绩效考核信息ER图
### 3.3.2数据库表设计
`  　`本系统中的数据库表有管理员信息表、员工信息表、公告信息表、绩效考核信息表、绩效指标表等，具体的表设计如下表所示：

表3.1　bumen


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||是|CURRENT\_TIMESTAMP||
|3|bumen|varchar|200|||||否|||
表3.2　config


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|name|varchar|100|||||否|||
|3|value|varchar|100|||||是|||
表3.3　gangwei


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||是|CURRENT\_TIMESTAMP||
|3|gangwei|varchar|200|||||否|||
表3.4　gonggaoxinxi


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||是|CURRENT\_TIMESTAMP||
|3|gonggaobiaoti|varchar|200|||||否|||
|4|tupian|varchar|200|||||是|||
|5|neirong|longtext||||||是|||
|6|faburiqi|date||||||是|||
表3.5　jixiaokaohe


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||是|CURRENT\_TIMESTAMP||
|3|yuangonggonghao|varchar|200|||||是|||
|4|yuangongxingming|varchar|200|||||是|||
|5|bumen|varchar|200|||||是|||
|6|gangwei|varchar|200|||||是|||
|7|jixiaoyuefen|varchar|200|||||是|||
|8|yuangongkaoqin|int|11|||||是|||
|9|gongzuotaidu|int|11|||||是|||
|10|yewujineng|int|11|||||是|||
|11|gongzuojixiao|int|11|||||是|||
|12|zongdefen|varchar|200|||||是|||
|13|jixiaodengji|varchar|200|||||是|||
表3.6　jixiaozhibiao


|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|bigint|20||是|是||否||auto\_increment|
|2|addtime|timestamp||||||是|CURRENT\_TIMESTAMP||
|3|bumen|varchar|200|||||是|||
|4|gangwei|varchar|200|||||是|||
|5|jixiaoxiangmu|varchar|200|||||是|||
|6|jixiaozhibiao1|varchar|200|||||是|||
|7|fenzhi1|int|11|||||是|||
|8|jixiaozhibiao2|varchar|200|||||是|||
|9|fenzhi2|int|11|||||是|||
|10|jixiaozhibiao3|varchar|200|||||是|||
|11|fenzhi3|int|11|||||是|||
|12|zongpingfen|varchar|200|||||是|||

#
#
#


















# 第4章 系统实现
## 4.1系统主要模块的实现
### 4.1.1系统登录模块实现
本模块界面加入了系统标题和角色的选择，在本界面中采用了图形和控件进行合理摆放的方法进行设计，还加入了合适的背景图片，使登录界面更加的直观。系统登录模块设计实现界面如下图4.1所示：

![](/md/blog.009.png)

图4.1系统登录模块界面实现
### 4.1.2个人中心管理功能模块实现
本界面主要是对管理员账号和密码进行设置，是管理员角色的操作功能，员工不能添加管理员账号，个人中心管理功能实现界面如下图4.2所示：

` `![](/md/blog.010.png)

图4.2个人中心管理模块实现界面
### 4.1.3部门信息管理模块实现
部门信息是管理员角色的功能，管理员可以为企业添加新的部门，可以查询部门的创建时间，管理员添加部门信息的实现界面如下图4.3所示：

![](/md/blog.011.png)

图4.3管理员添加部门信息实现界面

管理员添加部门信息的流程为，先进行必要字段的填写，数据库进行判定是否合法、是否为空，然后进行数据库信息的插入。
### 4.1.4部门信息管理模块实现
管理员可以在新员工招入时进行添加，对员工进行部门的安排和备注的添加。管理员添加员工信息的界面实现如下图4.4所示：

` `![](/md/blog.012.png)

图4.4管理员添加员工信息界面实现
### 4.1.5绩效指标管理模块实现
本功能是为了方便管理员对员工进行绩效考核，添加绩效指标的实现界面如下图4.5所示：

` `![](/md/blog.013.png)

图4.5添加绩效指标模块的界面实现
### 4.1.6公告信息管理模块的实现
本功能可以实现公告的发布，添加公告信息功能模块的实现界面如下图4.6所示：

` `![](/md/blog.014.png)

图4.6添加公告模块的实现界面
### 4.1.7岗位管理模块的实现
管理员可以对员工分配岗位，管理员查询岗位的实现界面如下图4.7所示：

` `![](/md/blog.015.png)

图4.7查询岗位信息的实现界面
### 4.1.8绩效考核管理模块的实现
发布员工的绩效考核，绩效考核信息的实现界面如下图4.8所示：

` `![](/md/blog.016.png)

图4.8绩效考核信息界面

4.2员工功能的界面实现

员工可以查询公告和绩效指标、绩效考核信息，也可以修改个人资料和密码。实现界面如下图4.9所示：

![](/md/blog.017.png)

图4.9员工功能的实现界面





























