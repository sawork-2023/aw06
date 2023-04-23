# MicroPoS 


请参考spring-petclinic-rest/spring-petclinic-microserivces 将webpos项目改为微服务架构，具体要求包括：
1. 至少包含独立的产品管理服务以及discovery/gateway等微服务架构下需要的基础设施服务；
2. 请使用`RestTemplate`进行服务间访问，尝试启动服务的多实例运行确认Client-side LB可行；
2. 请注意使用断路器等机制；
3. 如有兴趣可在kubernetes或者minikube上进行部署。