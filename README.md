# spring-cloud-demo
基于springboot 2.0.0.release和springcloud Finchley.M9的微服务demo  
****1.cloud-server-eureka 注册中心 注册中心集群   
****2.cloud-server-config 配置中心  
****3.cloud-service-feign 服务提供者     
****4.cloud-service-api 服务接口        
****5.cloud-service-feignconsumer 服务消费者 包含feign（ribbon,hystrix）        
****6.cloud-server-hystrix-dashboard 熔断监控单应用   
****7.cloud-server-zuul 网关 路由/校验    
****8.cloud-server-turbine 熔断监控集群应用   
****9.cloud-service-common 公共类
  
需增加 对redis/mq/mongoDB/sharding-jdbc的支持