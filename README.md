# submissionDEMO

主题：给老年人提供支付服务的APP

Idea来源：疫情隔离期间及隔离后线上支付交易额不断增加，而由于老年人学习能力较低等原因，且现有的支付软件往往包含较多的理财、产品推荐、广告等对老年人造成干扰的内容，据此我们希望能开发一款更加简洁、对老年人更加友好的支付软件。

一些材料：

   人民网北京11月26日电 (记者罗知之)“人民银行将引导金融机构用好智能技术，提升服务深度、广度和温度。”今天，中国人民银行科技司司长李伟在《关于切实解决老年人运用智能技术困难实施方案》国务院政策例行吹风会上表示，要让金融科技成果更好惠及包括老年人在内的广大人民群众，保证在数字普惠金融的道路上“一个都不落下”。
  
  李伟介绍，人民银行高度重视解决老年人运用智能技术困难的问题。人民银行准备从三个方面——现金管理、支付服务、普惠金融采取措施，切实提升老年人日常金融服务的可得性和满意度。
   
   “在支付服务方面，针对部分老年人不会使用移动支付、日常消费不便的问题，人民银行将指导市场机构从界面、操作等方面入手，切实提升支付产品的便利性、便捷化程度，加强对老年人移动支付的知识宣传、教育、普及推广。对利用不正当竞争手段造成商家拒收银行卡等歧视性支付行为、给老年人消费带来不便的市场机构，人民银行将开展查实处置工作，督促其落实整改。”李伟说。
   
   在普惠金融方面，李伟介绍，针对部分智能金融服务和产品主要对标青壮年客群、给老年人造成使用困难的问题，人民银行将指导金融机构，聚焦老年人日常高频金融场景，打造线上线下一体化、贴合老年人需要的“适老”金融服务。
   
   “在线上，深挖人工智能、大数据等技术优势，因人而异打造一些大字版、语音版、民族语言版和简洁版等智能金融APP，为广大老年人提供定制化、有温度、贴心的金融服务。在线下，也要通过不断优化银行实体网点、农村普惠金融服务站，切实提升老年人面对面金融服务的获得感和幸福感。”李伟表示。
  

开发计划：
在支付宝现有的功能上进行删减
保留的部分：首页的扫一扫与收付款，全部应用里的生活缴费，建议加个操作指南（viewpager）
把消息功能合并到首页，删去理财、口碑，
针对“我的”界面的修改：保留标头的个人信息，保留“账单”、“余额”、银行卡，“设置”功能建议放到界面里，要能关联亲情号，

细化的功能：
1.	支付时语音提示（有点难）
2.	设置支付限额，单次超过一定额度需要亲情号确认（能做当然好）
3.	生活缴费保留水、电、电话费就好
4.	使用前必须实名认证、绑定个人手机号和子女手机号（难搞）
5.	设置里面可设限额，能设置字号（或者直接用大字号）
6.	支付方式：密码、手势（不好弄）、指纹，应该至少有一种
7.	登录注册页面。。应该照常即可

可能用到的词：

  1.主界面 Home     
  2. 登录 login
  3.账号 account
  4.密码 password
  5.头像 profile
  6.扫一扫 scan
  7.用于计算的double余额 balance
