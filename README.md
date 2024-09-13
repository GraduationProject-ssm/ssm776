# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# ssm776基于SSM的的农产品线上销售网站的设计与实现+vue

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Tm8QeZE4a?p=171)


# 绪论
   1. ## 课题背景
身处网络时代，随着网络系统体系发展的不断成熟和完善，人们的生活也随之发生了很大的变化。目前，人们在追求较高物质生活的同时，也在想着如何使自身的精神内涵得到提升，而读菜就是人们获得精神享受非常重要的途径[1]。纸质版的菜籍比较沉重，携带不方便，而由于手机、平板不仅能够储存大量的菜籍信息数据，而且重量轻，可随身携带，因此现在的人们更愿意通过手机、平板等来进行在线阅读[2]。由此，开发一款农产品线上销售网站非常符合人们阅读的需求。

过去人们买菜需要到菜市场，而现在只要有网络，人们就可以通过手机、平板或电脑想什么时候买菜就可以什么时候看，想看什么样的菜就可以看什么样的菜，非常的方便，并且人们把平时的闲碎时间全部利用起来进行阅读，使阅读效率大大提高，生活也变得丰富多彩起来。另外，通过农产品线上销售网站，想要阅读哪本菜，搜索下就能够快速找到，并且还可以对菜进行归类、统计和规范管理。该农产品线上销售网站的界面非常清晰，使用简单，识字的人们都可以使用，并且它的功能齐全，能够满足各种各样的人的要求。

本文不仅从需求分析、设计分析、功能分析对该电子菜在线系统进行了全面的分析，而且还从开发背景、开发环境、目标、流程、数据库、系统维护对该农产品线上销售网站进行了总体的规划和设计。该农产品线上销售网站利用vue技术和MYSQL数据库进行开发，具有很好的稳定性和可发展性。
1. ## 研究现状
国外信息技术的发展步伐一直没有停止，源源不断的计算机应用软件被研发出来，并且软件技术也在不断迭代，目前世界各国的软件行业都已新兴了起来[3-5]。

与国外相比，我国信息技术的发展相对晚一些，不过后面，经过我们的不断追赶，我国的信息技术已经有了很大的进步，我国对现有的软件开发技术进行了细致的专研，目前我国已经能够独立的开发系统，并且也已经将这些软件系统应用于人们的生活中和各行各业中，目前，软件行业是我国非常受欢迎的行业[6-9]。

信息数字化使人们的各种信息能够快速传播，使人们的各种信息能够得到充分利用，同时，也大大宣传了信息数字化背后的软件系统[10-12]。软件开发团队的能力越来越强，开发技术功能越来越强大，软件系统大大提高了信息处理的效率，节省了处理者的处理时间。在阅读菜籍方面，人们阅读纸质版的菜籍，现在已经显得有些过时[13-14]。利用目前的软件开发技术开发出一款农产品线上销售网站能够大大的满足人们的阅读需求，人们通过该农产品线上销售网站能够快速查找、在线阅读自己喜欢的菜籍，并且也大大提高了人们阅读的效率。
1. ## 研究内容
本论文主要阐述了该农产品线上销售网站的开发技术、系统需求分析、系统设计、系统功能实现和系统测试。为了开发该系统，我在下面花费了很多功夫和心思，例如，到图菜馆阅读vue技术、MYSQL数据库等方面的编程菜籍，又在网上搜索了很多别人做的相类似的系统，将他们比较好的设计理念应用到自己的设计当中，最后才有了现在的成果。

本论文主要分为7部分，包括：

一、绪论：阐述了该系统的背景技术、研究现状和开发意义；

二、相关技术：介绍了开发该系统所用到的各种技术；

三、系统需求分析：阐述了开发该系统的可行性分析和功能需求分析；

四、系统设计：阐述了该系统的功能模块设计和数据库设计；

五、系统实现：展示了该系统的主要功能模块界面；

六、系统测试：对开发出的该系统进行测试；

七、系统总结：总结开发该系统的整个工作过程。

1. # 系统开发环境
   1. ## vue技术
Vue (读音 /vjuː/，类似于 view) 是一套用于构建[用户界面](https://baike.baidu.com/item/%E7%94%A8%E6%88%B7%E7%95%8C%E9%9D%A2/6582461)的渐进式[JavaScript](https://baike.baidu.com/item/JavaScript/321142)框架。 [5]  与其它大型框架不同的是，Vue 被设计为可以自底向上逐层应用。Vue 的核心库只关注视图层，不仅易于上手，还便于与第三方库或既有项目整合。另一方面，当与现代化的工具链以及各种支持[类库](https://baike.baidu.com/item/%E7%B1%BB%E5%BA%93/3351433)结合使用时，Vue 也完全能够为复杂的单页应用（[SPA](https://baike.baidu.com/item/SPA/17536313)）提供驱动

Vue.js目前最火的的一个前端框架，三大主流前端框架之一。
Vue.js是一套构建用户界面的框架（一套完整的解决方案，对项目侵入性大，中途     	需要跟换框架则需要重构整个项目），只关注视图层，易上手，有配套的第三方类库。提高开发效率，帮助减少不必要的dom操作；双向数据绑定，通过框架提供的指	令，前端只需要关注业务逻辑，不再关心dom如何渲染。
1. ## JAVA技术
Java编程语言具有跨平台、分布式、可移植等多种特性，很多平台Java都能运行，世界各地都能够运行Java编写的程序。1995年，开发出了JAVA编程语言。JAVA编程语言具有多种特性，例如：简单、安全、可移植、鲁棒性（Robust）、编写能效高、线程多等。在互联网飞速发展的时代，Java编程语言应用也越来越普遍[19]。它的特点具有：

一、面向对象：JAVA适用于分布式环境，JAVA能够完全面向对象，包括对象的设计及联系；

二、分布式：JAVA工作的同时，带动其他计算节点工作，只要有网络，就可以访问其他对象；

三、健壮性：JAVA能够自动处理垃圾和异常，并且机制类型强；

四、安全性：当指针和内存被删除时，非法的内存就可以避免。
1. ## MYSQL数据库
数据库在每个网站的开发中都是必不可少的，过去数据库只具有数据的保存和管理功能，但随着后来的不断更新和迭代，目前的数据库不仅能够进行数据的处理，而且还能够储存不计其数的数据[20]。

该农产品线上销售网站所使用的就是MYSQL数据库，当初是微软公司开发出的MYSQL数据库。MYSQL数据库总共建立了十几个相对应的表，它们之间独立联系，数据库和程序是密不可分的[21]。

MYSQL数据库的特点包括：能够应用于多种操作系统中；查询SQL时优化了算法，搜索速度提高的不少；还可以进行数据库的管理、控制、优化等操作；一个数据库可以记录不计其数的数据。
1. ## B/S结构
当前比较流行的网络化结构模式是B/S（浏览器/服务器）结构，它能够在服务器上面集中系统的所有核心功能，使系统开发人员的工作变得简单，并且开发出的系统也更容易使用和后期维护。用于比较熟悉的浏览器有360浏览器、谷歌浏览器、QQ浏览器等，用于比较熟悉的数据库有sqlserver、mysql数据库等，上边这些数据库和浏览器都可以安装在客户端上。B/S结构没有什么限制，并且还不需要专门的安装软件，只要笔记本、电脑有网络就能够访问系统。采用B/S结构开发的程序，比较好维护，只需要在客户端就可处理，不需要非得在服务器上处理，并且跟用户的交互性比较好，刷新浏览器就可进行数据信息的实时更新[22]。B/S架构如图2-1所示：

![](/md/blog.001.png)

图2-1 B/S模式架构图
1. ## SSM框架技术
该农产品线上销售网站是基于Spring、SpringMVC、Mybatis框架开发出来的。

2004年，Spring 框架才第一次亮相，后面也进行了很多次的更新。Spring框架包括SpringCore、Spring AOP、Spring ORM、Spring DAO、Spring Web Flow、Spring Context和Spring Web MVC等七个模块，企业应用程序就是通过这七个模块气筒不同的平台来进行开发的，Spring Web MVC中的各个元素之间形成了松散耦合[23-25]。
1. # 系统分析
   1. ## 可行性分析
开发者在进行开发系统之前，都需要进行可行性分析，保证该系统能够被成功开发出来。
1. ### 技术可行性
开发该农产品线上销售网站所采用的技术是vue和MYSQL数据库。计算机专业的学生在学校期间已经比较系统的学习了很多编程方面的知识，同时也接触了很多编程软件，所以在技术开发方面还是比较有信心的。
1. ### 操作可行性
该农产品线上销售网站的界面简洁清楚，操作简单，用户一看就会操作。操作界面上每一步都有提示，用户只要按照提示进行操作就可以了。该农产品线上销售网站具有操作可行性。
1. ### 经济可行性
我现在还是一名学生，还没有一份稳定的经济收入，所以我会将开发程序的成本控制在自己所能接受的范围内。我所使用的开发软件、数据库还有设计界面用的photoshop软件都是在网上免费下载的，另外程序编写阶段所用到的源代码也是在网上免费得到的，现在在网上能下载很多有用的、免费的东西，所以开发该系统基本不花钱，具有经济可行性。
1. ### 法律可行性
` `我是通过图菜馆、百度文库、百度网页等获得的开发该农产品线上销售网站所需要用到的资料和软件，都是采用的合法渠道，另外源代码和论文内容都是我自己一字一字写出来的，没有抄袭别人的，具有法律可行性。

通过上述的技术可行性、操作可行性、经济可行性以及法律可行性分析，可以看出，该农产品线上销售网站完全可以进行顺利开发。
1. ## 系统性能分析
1. 存储性：该农产品线上销售网站的数据库功能比较强大，能够录入很多纷繁复杂的信息，且能够保证数据的实时性；

二、易学性：该农产品线上销售网站使用起来非常简单，用户一看就会，不需要进行专门的培训，非常好上手，使用个一两次就能够熟练操作；

三、数据要求：录入的数据准确可靠，能够及时进行更新，可以独立保存，删除一些不需要的数据；

四、稳定性：该农产品线上销售网站能够稳定的运行，界面清晰明了；

五、可靠性：该农产品线上销售网站安装有拦截器，可以对病毒等进行拦截，并且还对信息进行了保护措施，用户可以放心使用。
1. ## 系统功能分析
   1. ### 角色需求
该农产品线上销售网站主要为管理员和用户两类用户角色提供需求，管理员在后台可以对系统进行全面管理，用户在前台可以进行查看系统信息，注册登录，查询菜籍，评论，下载菜籍等操作。

用户静态结构如图3-1所示。

![](/md/blog.002.png)

图3-1  用户静态结构图
1. ### 功能需求
该农产品线上销售网站具有完善的功能，界面一目了然，用户一看就会操作，管理员功能模块和用户功能模块是该系统的两大主要功能模块，其功能需求具体如下：

管理员的功能需求：

管理员在后台可以全面管理系统，管理员的功能主要包括用户管理、新闻管理、菜籍管理和评论管理等。

用户的功能需求：

用户在没有注册之前，进入网站，用户的主要功能包括查看网站首页、新闻信息、菜籍分类和菜籍信息，用户在注册登录后进入网站，用户的主要功能包括菜籍评论、加入菜架、菜籍下载、个人信息管理、我的菜架和我的留言。
1. ## 系统流程分析
   1. ### 注册流程
用户注册之后才可以登录系统，用户注册流程如图3-2所示：

![](/md/blog.003.png)

图3-2  注册流程图
1. ### 登录流程
用户需要登录系统之后，才可以进行菜籍评论、菜籍下载等操作。而管理员也只有登录系统之后，可以对系统各个方面的内容进行管理，不受任何限制。用户登录流程如图3-3所示。

![](/md/blog.004.png)

图3-3  登录流程图
1. # 系统设计
   1. ## 系统概要设计
本文通过B/S结构(Browser/Server,浏览器/服务器结构)开发的该农产品线上销售网站，B/S结构的优点很多，例如：开发容易、强的共享性、便于维护等，只要有网络，用户可以随时随地进行使用。

系统工作原理如图4-1所示。

![](/md/blog.005.png)

图4-1 系统工作原理图
1. ## 系统结构设计
系统结构设计就像一个树状结构一样，一个树干有很多分支，大任务相当于树干，小任务相当于树枝，只有需求分析信息弄清楚之后，才能保证每个小任务都能实现目标，对初步设计好的系统再进行不断优化，最终得到一个具体现实的系统结构。

管理员功能模块和用户功能模块是该农产品线上销售网站的两大部分，系统结构如图4-2所示。

农产品线上销售网站


用户信息管理

新闻信息管理

商品信息管理

商品类型管理

农户信息管理


用户信息修改

用户信息新增

农户信息添加 

农户信息删除

农户信息修改

商品类型添加

商品类型修改


商品类型删除

新闻信息添加

新闻信息删改

新闻信息删除

商品信息添加 

商品信息修改 

商品信息删除 

论坛信息管理

论坛信息修改

论坛信息删除


论坛信息添加


![](/md/blog.006.png)

图4-2 系统结构图

4.3 数据库设计

开发一个系统也需要提前设计数据库。这里的数据库是相关数据的集合，存储在一起的这些数据也是按照一定的组织方式进行的。目前，数据库能够服务于多种应用程序，则是源于它存储方式最佳，具备数据冗余率低的优势。虽然数据库为程序提供信息存储服务，但它与程序之间也可以保持较高的独立性。总而言之，数据库经历了很长一段时间的发展，从最初的不为人知，到现在的人尽皆知，其相关技术也越发成熟，同时也拥有着坚实的理论基础。

4.3.1 数据库概念设计

这部分内容需要借助数据库关系图来完成，也需要使用专门绘制数据库关系图的工具，比如Visio工具就可以设计E-R图（数据库关系图）。设计数据库，也需要按照设计的流程进行，首先还是要根据需求完成实体的确定，分析实体具有的特征，还有对实体间的关联关系进行确定。最后才是使用E-R模型的表示方法，绘制本系统的E-R图。不管是使用亿图软件，还是Visio工具，对于E-R模型的表示符号都一样，通常矩形代表实体，实体间存在的关系用菱形符号表示，实体的属性也就是实体的特征用符号椭圆表示。最后使用直线将矩形，菱形和椭圆等符号连接起来。接下来就开始对本系统的E-R图进行绘制。

（1）下图是用户实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\用户.jpg](/md/blog.007.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\用户.jpg")
图4.1 用户实体属性图

（2）下图是商品信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品信息.jpg](/md/blog.008.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品信息.jpg")
图4.2 商品信息实体属性图

（3）下图是字典表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\字典表.jpg](/md/blog.009.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\字典表.jpg")
图4.3 字典表实体属性图

（4）下图是购物车实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\购物车.jpg](/md/blog.010.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\购物车.jpg")
图4.4 购物车实体属性图

（5）下图是新闻信息实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\新闻信息.jpg](/md/blog.011.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\新闻信息.jpg")
图4.5 新闻信息实体属性图

（6）下图是论坛实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\论坛.jpg](/md/blog.012.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\论坛.jpg")
图4.6 论坛实体属性图

（7）下图是农户实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\农户.jpg](/md/blog.013.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\农户.jpg")
图4.7 农户实体属性图

（8）下图是商品评价实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品评价.jpg](/md/blog.014.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品评价.jpg")
图4.8 商品评价实体属性图

（9）下图是商品订单实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品订单.jpg](/md/blog.015.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\商品订单.jpg")
图4.9 商品订单实体属性图

（10）下图是用户表实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\用户表.jpg](/md/blog.016.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\用户表.jpg")
图4.10 用户表实体属性图

（11）下图是收货地址实体和其具备的属性。

![C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\收货地址.jpg](/md/blog.017.jpeg "C:\Users\Administrator\Desktop\img\nongchanpinxiaoshou\收货地址.jpg")
图4.11 收货地址实体属性图
1. ### 数据库表设计
采用MYSQL数据库对该农产品线上销售网站的数据进行存储，数据库中所包括的各个数据库表的详细信息如下所示：

表4.1收货地址表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|创建用户|是|
|3|address\_name|String|收货人|是|
|4|address\_phone|String|电话|是|
|5|address\_dizhi|String|地址|是|
|6|isdefault\_types|Integer|是否默认地址|是|
|7|insert\_time|Date|添加时间|是|
|8|update\_time|Date|修改时间|是|
|9|create\_time|Date|创建时间|是|
表4.2购物车表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|所属用户|是|
|3|goods\_id|Integer|商品|是|
|4|buy\_number|Integer|购买数量|是|
|5|create\_time|Date|添加时间|是|
|6|update\_time|Date|更新时间|是|
|7|insert\_time|Date|创建时间|是|
表4.3字典表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.4论坛表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|forum\_name|String|帖子标题|是|
|3|yonghu\_id|Integer|用户|是|
|4|shangjia\_id|Integer|农户|是|
|5|users\_id|Integer|管理员|是|
|6|forum\_content|String|发布内容|是|
|7|super\_ids|Integer|父id|是|
|8|forum\_state\_types|Integer|帖子状态|是|
|9|insert\_time|Date|发帖时间|是|
|10|update\_time|Date|修改时间|是|
|11|create\_time|Date|创建时间|是|
表4.5商品信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangjia\_id|Integer|农户|是|
|3|goods\_name|String|商品名称|是|
|4|goods\_types|Integer|商品类型|是|
|5|goods\_photo|String|商品照片|是|
|6|goods\_kucun\_number|Integer|商品库存|是|
|7|goods\_old\_money|BigDecimal|商品原价|是|
|8|goods\_new\_money|BigDecimal|现价|是|
|9|goods\_clicknum|Integer|点击次数|是|
|10|shangxia\_types|Integer|是否上架|是|
|11|goods\_delete|Integer|逻辑删除|是|
|12|goods\_content|String|商品简介|是|
|13|create\_time|Date|创建时间|是|
表4.6商品评价表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|goods\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|goods\_commentback\_text|String|评价内容|是|
|5|reply\_text|String|回复内容|是|
|6|insert\_time|Date|评价时间|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.7商品订单表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|goods\_order\_uuid\_number|String|订单号|是|
|3|goods\_id|Integer|商品|是|
|4|yonghu\_id|Integer|用户|是|
|5|buy\_number|Integer|购买的数量|是|
|6|goods\_order\_true\_price|BigDecimal|实付价格|是|
|7|goods\_order\_types|Integer|订单类型|是|
|8|goods\_order\_payment\_types|Integer|支付类型|是|
|9|insert\_time|Date|订单创建时间|是|
|10|create\_time|Date|创建时间|是|
表4.8新闻信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|news\_name|String|新闻名称|是|
|3|news\_photo|String|新闻图片|是|
|4|news\_types|Integer|新闻类型|是|
|5|insert\_time|Date|新闻发布时间|是|
|6|news\_content|String|新闻详情|是|
|7|create\_time|Date|创建时间|是|
表4.9农户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|shangjia\_name|String|农户名称|是|
|3|shangjia\_phone|String|联系方式|是|
|4|shangjia\_email|String|邮箱|是|
|5|shangjia\_photo|String|营业执照展示|是|
|6|shangjia\_xingji\_types|Integer|农户星级类型|是|
|7|new\_money|BigDecimal|现有余额|是|
|8|shangjia\_content|String|农户简介|是|
|9|shangjia\_delete|Integer|逻辑删除|是|
|10|create\_time|Date|创建时间|是|
表4.10用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_photo|String|头像|是|
|4|yonghu\_phone|String|用户手机号|是|
|5|yonghu\_id\_number|String|用户身份证号|是|
|6|yonghu\_email|String|邮箱|是|
|7|new\_money|BigDecimal|余额|是|
|8|yonghu\_delete|Integer|假删|是|
|9|create\_time|Date|创建时间|是|
表4.11用户表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|用户名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|



1. # 系统的实现
   1. ## 功能模块的实现
### 5.1用户信息管理
如图5.1显示的就是用户信息管理页面，此页面提供给管理员的功能有：用户信息的查询管理，可以删除用户信息、修改用户信息、新增用户信息，

还进行了对用户名称的模糊查询的条件

![](/md/blog.018.png)

![](/md/blog.019.png)

图5.1 用户信息管理页面
### 5.2 农户信息管理
如图5.2显示的就是农户信息管理页面，此页面提供给管理员的功能有：查看已发布的农户信息数据，修改农户信息，农户信息作废，即可删除，还进行了对农户信息名称的模糊查询 农户信息信息的类型查询等等一些条件。

![](/md/blog.020.png)

![](/md/blog.021.png)

图5.2 农户信息管理页面
### 5.3商品信息管理
如图5.3显示的就是商品信息管理页面，此页面提供给管理员的功能有：根据商品信息进行条件查询，还可以对商品信息进行新增、修改、查询操作等等。

![](/md/blog.022.png)

![](/md/blog.023.png)

图5.3 商品信息管理页面
### 5.1新闻信息管理
如图5.4显示的就是新闻信息管理页面，此页面提供给管理员的功能有：根据新闻信息进行新增、修改、查询操作等等。

![](/md/blog.024.png)

![](/md/blog.025.png)

图5.4 新闻信息管理页面

1. 










