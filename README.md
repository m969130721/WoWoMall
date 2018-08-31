# WoWoMall
一个基于springboot框架搭建的分布式商城(当前版本1.0,最终实现微服务架构)

<h2>环境</h2>
JDK版本：8<br/>
数据库：MySQL5.7<br/>
技术栈：SpringBoot2.0.2/MyBatis3.4.6/Guava/Joda<br/>
Nginx版本：1.15.0<br/>
Maven版本：3.5.3<br/>

<h2>当前版本功能说明</h2>

<h3>用户模块</h3>
横向越权、纵向越权、<br/>
MD5明文加密、guava缓存<br/>
高复用服务响应对象的设计思想和封装<br/>

<h3>分类模块</h3>
递归算法<br/>
复杂对象排重<br/>
无限层级树结构设计<br/>

<h3>商品模块</h3>
POJO、BO、VO抽象模型<br/>
高效分页及动态排序<br/>
FTP服务对接、富文本上传<br/>

<h3>购物车模块</h3>
商品总价计算复用封装<br/>
高复用的逻辑方法封装思想<br/>
解决商业运算丢失精度的坑<br/>

<h3>订单模块</h3>
安全漏洞解决方案<br/>
订单号生成规则<br/>
强大的常量、枚举设计<br/>
收货地址<br/>
同步获取自增主键<br/>
数据绑定的对象绑定<br/>
越权问题升级巩固<br/>

<h3>支付模块</h3>
支付宝SDK源码解析<br/>
支付宝支付流程与集成<br/>
二维码生成，扫码支付<br/>

<h3>线上部署</h3>
云服务器vsftpd、nginx等配置<br/>
云服务器的配置与域名解析<br/>
