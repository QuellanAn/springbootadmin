# spring-boot-admin

我们知道项目的监控是尤为重要的，但是我们如果用jdk 自带的jconsole 和jvisualvm 的话会非常繁琐，且界面不是很友好。之前我们使用了spring boot 项目，但是都没有对项目有一个很好的监控。在spring 家族中有 spring-boot-admin 可以很好的帮我们起到监控微服务项目的作用。

spring-boot-admin 是一个针对 Spring Boot 的 Actuator 接口进行 UI 美化封装的监控工具，它可以在列表中浏览所有被监控 spring-boot 项目的基本信息、详细的 Health 信息、内存信息、JVM 信息、垃圾回收信息、各种配置信息（比如数据源、缓存列表和命中率）等，还可以直接修改 logger 的 level。

spring-boot-admin 分为服务端和客户端。服务端是一个单独的微服务，用来查看监控的项目的运行情况，客户端是我们一个个的微服务项目。所以要想让我们的项目被服务端监控到，就需要将我们的服务注册到服务端去。




原文地址：[springboot 优雅集成spring-boot-admin 实现程序监控](https://quellanan.blog.csdn.net/article/details/103805657)
