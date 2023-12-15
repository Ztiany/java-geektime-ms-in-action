# geekbang-coupon-center

## 介绍

极客时间《Spring Cloud 微服务项目实战》配套源码。</br>

项目从 Spring Boot 开始，逐渐过渡到 Spring Cloud 完全体。GitHub 里每一个文件夹都包含了一个完整的组件集成过程。

源码会不断更新，大家记得随时 Pull 到本地。

整天被平台催稿，跟催命一样，写作时间比较短难免有一些 Bug，大家发现 Bug 可以给我留言提 PR 都可以。人这一辈子不搞出几个 P0 Bug 就像上学没挂过科一样，这种人生是有缺憾的。

## 软件架构

实战项目所选用的 Spring Cloud 组件如下：

1. 服务治理：Nacos
2. 负载均衡：Loadbalancer
3. 服务间调用：OpenFeign
4. 熔断降级+流量整形：Sentinel
5. 分布式配置中心：Nacos Config
6. 分布式事务：Seata
7. 调用链追踪：Sleuth + Zipkin + ELK
8. 事件驱动：Stream

## 安装教程

1. 数据库建表语句、Postman 集合都可以在"资源文件"这个 folder 里找到。
2. Nacos、Zipkin 和 ELK 的安装，请跟着专栏上的步骤来操作。
3. Sentinel 二次改造后的源码在"4-服务容错 Sentinel"的 middleware 文件夹里。
