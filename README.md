# config-clientdemo
client客户端
需要自己创建注册中心，以及rabbitmq服务
本案例关联gitlab，将配置中心的服务端，客户端都注册到eureka,修改数据后post调用http://localhost:8881/actuator/refresh  
调用配置中心服务端去更新配置文件
