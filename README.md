# microservice-arch-dubbo (经过测试，不推荐。 dubbo服务和dubbo服务之间的调用，传输的对象要求；异常处理都特别麻烦。)

- Sentinel（更倾向于全面监控、动态可配置、偏运维侧）（二选一）
- Resilience4j 是一个轻量级、易于使用的熔断降级库，一般都是在应用代码集成！ （二选一）
- Nacos 服务
- Dubbo Admin 服务（类似Spring Boot Admin）
- RocketMQ 集群
- Redis 集群
- MySQL 数据库
- Tsid-creator
- JTE
- jobrunr
