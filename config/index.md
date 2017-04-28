# Spring Cloud Config

Spring Cloud Config 为分布式系统中的外部配置(externalized configuration)提供服务器和客户端支持。使用Config Server，您可以在所有环境中管理应用程序的外部属性。客户端和服务器映射的概念与Spring Environment和PropertySource抽象相同，因此它们与Spring应用程序非常契合，但可以与任何以任何语言运行的应用程序一起使用。

随着应用程序通过从开发到测试和生产的部署流程，您可以管理这些环境之间的配置，并确定应用程序具有迁移时需要运行的一切。服务器存储后端的默认实现使用git，因此它轻松支持标签版本的配置环境，以及可以访问用于管理内容的各种工具。可以轻松添加替代实现，并使用Spring配置将其插入。

## 信息

- [Spring Cloud Config官网](https://cloud.spring.io/spring-cloud-config/)
- [Spring Cloud Config@github](https://github.com/spring-cloud/spring-cloud-config)

## 参考资料

- [聊聊 Spring Cloud Config](https://blog.coding.net/blog/spring-cloud-config)
- [Spring Cloud Config 客户端的高可用实现](http://www.shellsec.com/news/32669.html)
