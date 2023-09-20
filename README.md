# FreshDirect-Web-Application
2023.03 - 2023.07

项目内容：使用 SpringBoot + MySQL + Redis 进行生鲜电商系统的搭建，实现前台的浏览、购买商品，后台的商品、用户、订单管理功能。

主要工作：
1. 缓存机制：使用 Redis 数据库对网页静态资源进行缓存，网页加载提速；
2. 状态保存：使用 session 对用户登录状态进行保特，保证信息安全；
3. 请求过滤：使用 Aspect4 结合 log4j2 对请求对象进行过滤并记录日志；
4. 登陆验证：继承 Filter 接口拉取 Servlet 请求，获取 session 中的登录状态。
   
