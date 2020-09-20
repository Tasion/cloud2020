# cloud2020
springcloud2020技术学习
    1.hosts文件目录：C:\Windows\System32\drivers\etc
    2.支付服务集群配置: 
        2.1: 先要启动eurekaServer 7001、7002服务
        2.2：再启动服务提供者PaymentServer 8001、8002服务
        2.3: 后启动消费服务ConsumerServer 80服务
         结果：达到负载均衡效果；8001、8002端口交替轮巡出现
        