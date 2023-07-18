 <center>
     <h1>求职简历</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             15651011752
         </span>
         ·
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             2099769588@qq.com
         </span>
         ·
         <span>
             <img src="assets/github-brands.svg" width="18px">
             <a href="https://github.com/CyC2018">My github</a>
         </span>
         ·
         <span>
             <img src="assets/rss-solid.svg" width="18px">
             <a href="#">My Blog</a>
         </span>
     </div>
 </center>


 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男，2003 年出生
 - 求职意向：Java 开发工程师
 - 工作经验：0 年（校招可不填）
 - 期望薪资：0k（校招可不填）

## <img src="assets/graduation-cap-solid.svg" width="30px"> 教育经历

- 本科，金陵科技学院，计算机科学与技术专业，2021.9~2025.7

## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **XXXX 公司，XXXX 部门，XXXX 工程师，2010.1~2010.9**

   负责 XXX

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **seckill项目**

  *springboot+mybatisplus+redis+rabbitmq+canal+resilience4j*

  本项目主要是为了实现并发秒杀功能
  
  核心功能及问题的解决：
  
  1、使用了redis+rabbitmq实现并发下单功能
  
  2、用Redission的分布式锁解决了超卖的问题
  
  3、用resilience4j实现了接口限流，防止有人恶意刷单
  
  4、使用了canal+rabbitmq实现了mysql中的秒杀信息数据同步到redis缓存中。
  
  github地址：https://github.com/6greenhand/seckill
  
- **学成教育平台项目**

  redis+nginx+jwt+springsecurity+oauth2.0+minio+ffmpeg+springboot+mybaitsplus+rabbitmq+SrpingCloud+SpringCloudAlibaba+elasticsearch+xxl_job

  这是一个分布式的教育平台的项目

  核心功能及问题的解决：

  1、为了解决视频传到一半上传失败又要重新上传的问题，所以采用了断点续传机制，将视频分片上传到minio然后再合并一个完整的视频。

  2、使用了ffmpeg将所有上传的avi格式的视频转化成mp4格式的视频

  3、采用了xxl_job分布式任务调度平台来制定定时任务，异步进行一些操作，比如上面的视频格式转换就是

  4、oauth2.0实现第三方登陆(微信登陆)

  5、为了使得搜索速度大幅度提升，所以采用了elasticsearch

  6、使用了springsecurity+jwt+ouath2.0实现了单点登陆，本项目使用oauth2.0实现了微信扫码登陆

  7、将数据分别保存到redis、mysql、elasticsearch中，为了防止数据不一致，采用了分布式事务seata

  github地址：https://github.com/6greenhand/xuecheng

## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- 熟练掌握Java基础知识，理解常用集合类源码，能使用Stream流高效操作集合类，熟练使用SSM，Spring Boot，SpringCloud，SpringCloudAlibaba等开源框架。
- 了解JVM和GC调优和JUC，知道类加载过程和垃圾回收原理, 会使用Arthas解决一些JVM的问题
- 熟悉Java并发工具包的基本使用(如CountDownLatch、Atomic、Executors)，能够使用CAS的16个原子类解决并发问题，了解AQS,CAS , synchronized与锁升级的基本原理，了解ThreadLocal的原理，并能够使用它解决一些并发场景(如计数，卖票最后汇总等)。
- 熟练使用Redis, 并可以解决Redis持久化和数据一致性，知道雪崩、击穿和穿透等问题的原因并能够解决这些问题，Redis 过期策略和内存淘汰策略，了解Redssion的原理，并能够使用Redssion分布式锁解决分布式环境下的并发安全问题, 熟悉布隆过滤器的原理，并能够使用它解决问题，如击穿, 了解redis主从哨兵集群和redis_clustor集群的原理和不同点。
- 熟练使用rabbitmq, 会使用死信队列和延迟队列实现延迟订单操作，并且能够使用rabbitmq+canal实现数据同步操作。
- 熟练使用security和shiro安全框架, 能够使用security整合jwt使用，也能够使用Spring Security+oauth2+jwt实现SSO
- 熟练使用nginx，可以部署前端页面到nginx上，能够实现负载均衡和反向和正向代理和动静结合，可以将nginx和gateway结合使用。