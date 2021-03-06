## 一步一步建立起分布式系统:SOA->微服务->云原生的一套完整技术栈.

### Java8

- [x] [Lambda表达式](https://github.com/wenbin8/doc/blob/master/java8/java8的流(Stream)操作.md)
- [x] [流操作(Stream)](https://github.com/wenbin8/doc/blob/master/java8/java8的流(Stream)操作.md)
- [ ] HashMap源码分析

### 并发

- [x] [并发编程的基础](https://github.com/wenbin8/doc/blob/master/并发/01-并发编程的基础.md)
- [x] [synchronize](https://github.com/wenbin8/doc/blob/master/并发/02-synchronized.md)
- [x] [volatile](https://github.com/wenbin8/doc/blob/master/并发/03-volatile.md)
- [x] [AQS底层原理分析](https://github.com/wenbin8/doc/blob/master/并发/04-AQS底层原理分析.md)
- [x] [Condition及源码分析](https://github.com/wenbin8/doc/blob/master/并发/05-Condition及源码分析.md)
- [x] [CountDwonLatch及源码分析](https://github.com/wenbin8/doc/blob/master/并发/06-CountDwonLatch及源码分析.md)
- [x] [Semaphore及源码分析](https://github.com/wenbin8/doc/blob/master/并发/07-Semaphore及源码分析.md)
- [x] [CyclicBarrier及原理](https://github.com/wenbin8/doc/blob/master/并发/08-CyclicBarrier及原理.md)
- [x] [ConcurrentHashMap源码分析](https://github.com/wenbin8/doc/blob/master/并发/09-ConcurrentHashMap源码分析.md)
- [x] [阻塞队列、原子操作的原理分析](https://github.com/wenbin8/doc/blob/master/并发/10-阻塞队列、原子操作的原理分析.md)
- [x] [线程池、forkjoin的原理分析](https://github.com/wenbin8/doc/blob/master/并发/11-线程池、forkjoin的原理分析.md)

### IO
- [x] [BIO,NIO,AIO总结](https://github.com/wenbin8/doc/blob/master/IO/BIO%2CNIO%2CAIO总结.md)
- [x] [netty-组件与源码分析](https://github.com/wenbin8/doc/blob/master/netty/netty-组件与源码分析.md)


### JVM

- [ ] 类加载机制与编译优化
- [ ] JVM运行时数据区的内存管理机制
- [ ] 垃圾收集算法与垃圾收集器
- [ ] 性能监控与故障处理

### 常用设计模式

​	用好设计模式能帮助我们更好的解决实际问题，设计模式最重要的是解耦。设计模式天天都在用，但自己却无感知。把设计模式作为一个专题，主要是学习设计模式是如何总结经验的，把经验为自己所用。同时也为阅读框架源码打下坚实的基础。在学习设计模式之前，一定要先了解软件设计原则。

示例代码地址：git@github.com:wenbin8/design-pattern.git

- [x] [软件设计的七大原则](https://github.com/wenbin8/doc/blob/master/设计模式/01-软件设计的七大原则.md)
- [x] [工厂模式](https://github.com/wenbin8/doc/blob/master/设计模式/02-工厂模式.md)
- [x] [单例模式](https://github.com/wenbin8/doc/blob/master/设计模式/03-单例模式.md)
- [x] [原型模式](https://github.com/wenbin8/doc/blob/master/设计模式/04-原型模式.md)
- [x] [代理模式](https://github.com/wenbin8/doc/blob/master/设计模式/05-代理模式.md)
- [x] [委派模式](https://github.com/wenbin8/doc/blob/master/设计模式/06-委派模式.md)
- [x] [策略模式](https://github.com/wenbin8/doc/blob/master/设计模式/07-策略模式.md)
- [x] [模板模式](https://github.com/wenbin8/doc/blob/master/设计模式/08-模板模式.md)
- [x] [适配器模式](https://github.com/wenbin8/doc/blob/master/设计模式/09-适配器模式.md)
- [x] [装饰者模式](https://github.com/wenbin8/doc/blob/master/设计模式/10-装饰者模式.md)
- [x] [观察者模式](https://github.com/wenbin8/doc/blob/master/设计模式/11-观察者模式.md)

### 框架源码分析

Spring:

通过对Spring的核心流程总结。简化实现Spring，来加深对Spring源码的理解。如果直接看源码懵逼的话。可以先通过这个项目（https://github.com/wenbin8/myCode）来看看Spring的总体流程，该项目剥离的Spring核心（IOC\DI\AOP\MVC）之外的逻辑，帮助快速掌握理解Spring核心的设计思想与实现原理。理解了这个项目在去深入研究Spring源码就有了一定的基础。这里的代码来源都是参考《Spring 5核心原理与30个类手写实战》有兴趣深入研究的也可以参考这本书。

- [x] [Spring5的系统架构和源码构建](https://github.com/wenbin8/doc/blob/master/Spring/01-Spring核心概念与系统架构.md)
- [x] [Spring的IOC源码分析](https://github.com/wenbin8/doc/blob/master/Spring/02-Spring-IOC源码分析.md)
- [x] [Spring的DI源码分析](https://github.com/wenbin8/doc/blob/master/Spring/03-Spring-DI源码分析.md)
- [x] [Spring的AOP源码分析](https://github.com/wenbin8/doc/blob/master/Spring/04-Spring-AOP源码分析.md)
- [x] [Spring MVC源码分析](https://github.com/wenbin8/doc/blob/master/Spring/05-Spring-MVC源码分析.md)

### 数据库

- [ ] b+Tree的原理与Mysql的innoDB索引原理
- [ ] mySql数据查询性能优化

### 分布式

#### 分布式基础

- [x] [分布式架构演进](https://github.com/wenbin8/doc/blob/master/分布式/分布式基础/01-分布式架构演进.md)
- [x] [通信协议Tcp/ip](https://github.com/wenbin8/doc/blob/master/分布式/分布式基础/02-通信协议总结-TCPIP.md)
- [x] [HTTP及HTTPS协议原理](https://github.com/wenbin8/doc/blob/master/分布式/分布式基础/03-HTTP及HTTPS协议原理.md)
- [x] [序列化与反序列化](https://github.com/wenbin8/doc/blob/master/分布式/分布式基础/04-序列化和反序列化.md)

#### 微服务(Spring boot/Spring Cloud)

- [x] [微服务的发展](https://github.com/wenbin8/doc/blob/master/微服务/微服务的发展.md)

##### Spring Boot 

- [x] [Spring Boot的基本认识](https://github.com/wenbin8/doc/blob/master/微服务/SpringBoot/01-Spring%20Boot的基本认识.md)
- [ ] Spring Boot嵌入式Web容器
- [ ] Spring Boot Actuator
- [ ] Spring Boot自动装配：重新整合Spring注解编程模型，@Enable模块驱动及条件装配等Spring Framework原生特性。
- [ ] Spring Boot理解SpringApplication

#### 分布式协调服务

- [x] [分布式系统与一致性协议](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/分布式系统与一致性协议.md)
- [x] [raft协议](http://thesecretlivesofdata.com/raft/)

zookeeper:

- [x] [zookeeper的安装部署](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/01-zookeeper的安装部署.md)
- [x] [Zookeeper总结](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/02-zookeeper总结.md)
- [x] [zookeeper应用](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/03-zookeeper应用.md)
- [x] [zookeeper基于Curator实现分布式锁](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/04-zookeeper基于Curator实现分布式锁.md)
- [x] [zookeeper实现Leader选举](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/05-zookeeper实现Leader选举.md)
- [x] [zookeeper的Leader选举原理](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/06-zookeeper的Leader选举原理.md)
- [x] [zookeeper的watcher机制原理](https://github.com/wenbin8/doc/blob/master/分布式/分布式协调服务/zookeeper/07-zookeeper的watcher机制原理.md)

etcd:
- [ ] etcd安装部署

#### 分布式服务治理

##### Spring Cloud

###### alibaba:

Dubbo：

- [x] [服务治理之Apache Dubbo的基本认识](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/01-服务治理之Apache%20Dubbo的基本认识.md)
- [x] [Apache Dubbo的服务治理功能](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/02-Apache%20Dubbo的服务治理功能.md)
- [x] [Apache Dubbo内核剖析](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/03-Apache%20Dubbo内核剖析.md)
- [x] [Apache Dubbo服务发布源码分析](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/04-Apache%20Dubbo服务发布源码分析.md)
- [x] [Apache Dubbo服务注册及服务消费源码分析](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/05-Apache%20Dubbo服务注册及服务消费源码分析.md)
- [x] [Apache Dubbo服务通信及负载均衡](https://github.com/wenbin8/doc/blob/master/分布式/服务治理/dubbo/06-Apache%20Dubbo服务通信及负载均衡.md)

nacos

- [x] [nacos](https://nacos.io/zh-cn/docs/what-is-nacos.html)

Sentinel

- [x] [Sentinel](https://github.com/all4you/sentinel-tutorial)
- [x] [SentinelDoc](https://github.com/alibaba/Sentinel/wiki/介绍)

###### netfilx:

- [ ] Eureka注册中心
- [ ] Ribbon 负载均衡
- [ ] Fegin 声明式服务调用
- [ ] Hystrix 服务熔断降级方式
- [ ] Zuul 实现微服务网关
- [ ] Config 分布式统一配置中心
- [ ] Sleuth 调用链路跟踪
- [ ] BUS 消息总线
- [ ] Spring Boot 与 Spring Cloud 整合

#### 分布式消息通信

- [x] [消息中间件的背景分析](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/消息中间件的背景分析.md)

kafka

- [x] [kafka基础及安装部署](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/Kafka/01-kafka基础及安装部署.md)

- [x] [kafka应用及原理](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/Kafka/02-kafka应用及原理.md)

- [x] [kafka分区副本及消息存储原理](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/Kafka/03-kafka分区副本及消息存储原理.md)

rabbitMQ
- [x] [rabbitMQ简介及基本使用](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/RabbitMQ/01-rabbitMQ简介即基本使用.md)
- [x] [rabbitMQ进阶知识及SpringAMQP](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/RabbitMQ/02-rabbitMQ进阶知识及Spring%20AMQP.md)
- [x] [rabbitMQ可靠性投递与高可用](https://github.com/wenbin8/doc/blob/master/分布式/消息通信/RabbitMQ/03-rabbitMQ可靠性投递与高可用.md)

RocketMQ

- [ ] 占位


#### 分布式缓存

- [ ] MongoDB

Redis

- [x] [Redis安装与启动](https://github.com/wenbin8/doc/blob/master/分布式/缓存/01-Redis安装与启动.md)
- [x] [Redis基础](https://github.com/wenbin8/doc/blob/master/分布式/缓存/02-Redis基础.md)
- [x] [Redis进阶](https://github.com/wenbin8/doc/blob/master/分布式/缓存/03-Redis进阶.md)
- [x] [Redis集群](https://github.com/wenbin8/doc/blob/master/分布式/缓存/04-Redis集群.md)
- [x] [Redis实战](https://github.com/wenbin8/doc/blob/master/分布式/缓存/05-Redis实战.md)

#### 分库分表

- [x] [分库分表-总体概述](https://github.com/wenbin8/doc/blob/master/分布式/分库分表/01-分库分表-总体概述.md)

Mycat

- [x] [Mycat基础](https://github.com/wenbin8/doc/blob/master/分布式/分库分表/02-Mycat基础.md)
- [x] [Mycat进阶](https://github.com/wenbin8/doc/blob/master/分布式/分库分表/03-Mycat进阶.md)

#### 任务调度

- [x] [Quarzt](https://github.com/wenbin8/doc/blob/master/分布式/任务调度/01-Quarzt.md)

- [x] [Elastic-job](https://github.com/wenbin8/doc/blob/master/分布式/任务调度/02-Elastic-job.md)

#### Cloud Native

##### 网络基础

经过一个阶段的k8s学习后发现其实现大量使用linux中的网络知识，要想深入研究k8s这些基础知识必不可少。所以回头重新整理一下k8s在具体实现中使用到的Linux网络的基础知识。对深入理解k8s实现原理和实际应用中故障处理大有裨益。同时推荐《杜军. Kubernetes网络权威指南：基础、原理与实践》这本书来帮助我们理解k8s的网络。

- [ ] [Linux 中常用网络命令](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/网络基础/01-Linux中常用网络命令.md)
- [x] [Linux 网络基础（Network Namespase、veth pair、bridge、Iptables）](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/网络基础/02-Linux%20网络基础（Network%20Namespase、veth%20pair、bridge、Iptables）.md)
- [ ] Linux隧道网络基础（tun/tab、ipip、VXLAN、Macvlan、IPvlan）

##### Docker

他山之石：（[Docker基础](https://www.runoob.com/docker/docker-tutorial.html)，[Docker命令大全](https://www.runoob.com/docker/docker-command-manual.html)，[理解docker实现原理(Namespaces，CGroups和联合文件系统)](http://dockone.io/article/2941)）

- [x] [Docker基础及安装](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Docker/01-Docker基础及安装.md)
- [x] [镜像和容器](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Docker/02-镜像和容器.md)
- [x] [Docker网络](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Docker/03-Docker网络.md)
- [x] [Docker数据持久化与练习](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Docker/04-Docker数据持久化与练习.md)
- [x]  [Docker Compose与DockerSwarm](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Docker/05-Docker%20Compose与Docker%20Swarm.md)

##### Kubernetes

- [x] [Kubernetes集群搭建](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/01-Kubernetes集群搭建.md)
- [x] [Kubernetes入门](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/02-Kubernetes入门.md)
- [x] [Kubernetes常用资源使用及网络](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/03-Kubernetes常用资源使用及网络.md)
- [x] [Kubernetes实战](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/04-Kubernetes实战.md)
- [x] [Kubernetes存储（Volumes\PV\PVC）](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/05-Kubernetes存储（Volumes%20PV%20PVC).md)
- [x] [Kubernetes深入掌握Pod](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/06-Kubernetes深入掌握Pod.md)
- [x] [Kubernetes核心组件](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/07-Kubernetes核心组件.md)
- [x] [Kubernetes部署策略](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/08-Kubernetes部署策略.md)
- [x] [Kubernetes日志与监控](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/09-Kubernetes日志与监控.md)
- [x] [Kubernetes Trouble Shooting](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/10-Kubernetes%20Trouble%20Shooting.md)

###### 源码分析

在能独立搭建k8s环境，和熟悉基本用，学习完go语言后，开始研究k8s是怎么实现的。这里先研究kube-scheduler是因为比较好奇k8s是如何实现pod的调度。

- [x] [Kubernetes-源码调试](https://github.com/wenbin8/doc/blob/master/%E5%88%86%E5%B8%83%E5%BC%8F/CloudNative/Kubernetes/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/01-Kubernetes-%E6%BA%90%E7%A0%81%E8%B0%83%E8%AF%95.md)
- [x] [kube-scheduler-node预选-源码分析](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/源码分析/02-kube-scheduler-node预选-源码分析.md)
- [x] [kube-scheduler-node优选-源码分析](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/源码分析/03-kube-scheduler-node优选-源码分析.md)
- [x] [kube-scheduler-调度器初始化-源码分析](https://github.com/wenbin8/doc/blob/master/分布式/CloudNative/Kubernetes/源码分析/04-kube-scheduler-调度算法初始化-源码分析.md)
- [ ] kube-scheduler-抢占调度-源码分析
- [ ] kube-scheduler-亲和性调度-源码分析


##### Service Mesh

- [ ] istio基础及安装部署
- [ ] istio Sidecar机制
- [ ] istio流量治理
- [ ] istio策略和遥测
- [ ] istio服务安全

