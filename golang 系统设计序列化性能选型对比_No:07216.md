最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计序列化性能选型对比
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://book.5xusux.asia/blog/8613699.sHtML

原标题：架构笔记：高并发系统核心设计思路总结
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://book.5xusux.asia/blog/2683022.sHtML

原标题：复盘总结：系统压测报告模板与分析思路
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.5xusux.asia/blog/0493617.sHtML

原标题：开源实践：开源项目如何写好PullRequest
简介：golang 滑动窗口限流算法 go 实现，滑动窗口限流，解决固定窗口临界流量突增漏洞，限流更精准。
 | 原文链接：http://book.5xusux.asia/blog/7780373.sHtML

原标题：项目实践：MySQL读写分离本地模拟实践
简介：Cookie Session 会话状态管理，讲解 Cookie 与 Session 原理，理解登录状态保存，实现服务端会话管理逻辑。
 | 原文链接：http://book.5xusux.asia/blog/6636531.sHtML

原标题：优化实践：Redis管道、批量命令减少网络往返
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.5xusux.asia/blog/4644099.sHtML

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：nodejs 内存溢出问题排查修复，Node.js 程序 OOM 排查流程，定位内存泄露，调整内存限制修复崩溃。
 | 原文链接：http://book.5xusux.asia/blog/3160457.sHtML

原标题：效率笔记：调试网络请求curl命令高级用法
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.5xusux.asia/blog/9839727.sHtML

原标题：设计思考：分布式ID系统架构选型对比
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.5xusux.asia/blog/8032848.sHtML

原标题：开发生产环境资源路径统一
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.5xusux.asia/blog/3436564.sHtML

原标题：实践：Git工作流主干开发团队协作实践
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://book.5xusux.asia/blog/9060021.sHtML

原标题：跨平台 uniapp 多端开发实操
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://book.5xusux.asia/blog/7522555.sHtML

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：golang context.WithValue 传递元数据，WithValue 只传 traceId 鉴权元数据，不要传业务大对象。
 | 原文链接：http://book.5xusux.asia/blog/2386689.sHtML

原标题：简易日志收集集中管理方案
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://book.5xusux.asia/blog/3217757.sHtML

原标题：性能复盘：系统上下文切换过高性能下降调优
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://book.5xusux.asia/blog/1208456.sHtML

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.5xusux.asia/blog/1628869.sHtML

原标题：Troubleshooting：k8s镜像拉取失败镜像仓库网络问题
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://book.5xusux.asia/blog/9254931.sHtML

原标题：golang 系统设计防爬虫简单策略
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://book.5xusux.asia/blog/0194766.sHtML

原标题：Hands‑on：简易ID生成雪花算法完整实现
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://book.5xusux.asia/blog/0136945.sHtML

原标题：排错：多实例部署session共享失效登录失效
简介：golang go 并发模式 fan‑out fan‑in，fanout 分发任务 fanin 汇总结果，多协程并发处理任务。
 | 原文链接：http://book.5xusux.asia/blog/0862386.sHtML

原标题：零基础理解模块化与组件化基础思想
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.5xusux.asia/blog/8947896.sHtML

原标题：Fork 开源项目同步上游代码
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.5xusux.asia/blog/1561192.sHtML

原标题：golang 系统设计 rest http 方法使用原则
简介：golang GC 调优 GOGC 参数调整，调整 GOGC 阈值，控制 GC 触发时机，权衡内存占用与 CPU 开销。
 | 原文链接：http://book.5xusux.asia/blog/4553619.sHtML

原标题：golang 系统设计分表分页排序业务实现难点
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://book.5xusux.asia/blog/1308428.sHtML

原标题：golang 系统设计数据库版本迁移回滚方案
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://book.5xusux.asia/blog/9988278.sHtML

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://book.5xusux.asia/blog/0504347.sHtML

原标题：golang 系统设计线上日志快速检索技巧
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.5xusux.asia/blog/8902068.sHtML

原标题：不必要字符转义关闭业务异常
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.5xusux.asia/blog/5334452.sHtML

原标题：Hands‑on：shell脚本批量自动化运维小工具
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.5xusux.asia/blog/7520798.sHtML

原标题：记一次分布式锁失效引发的数据错乱问题
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.5xusux.asia/blog/7241598.sHtML

原标题：Docker 多阶段构建镜像瘦身
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.5xusux.asia/blog/6542488.sHtML

原标题：golang 系统设计 graphql 接口优缺点梳理
简介：Git 误提交撤销回退实操教程，演示多种撤销提交方式，区分已经推送远程和本地未提交场景，处理误提交代码。
 | 原文链接：http://book.5xusux.asia/blog/7720248.sHtML

原标题：golang redis 集群 hash 槽讲解
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.5xusux.asia/blog/1596481.sHtML

原标题：方案设计：高可用Redis集群架构选型对比
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.5xusux.asia/blog/6620795.sHtML

原标题：踩坑：批量MQ消费失败直接无限重试消息爆炸
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://book.5xusux.asia/blog/7106418.sHtML

原标题：golang 系统设计自动化测试 ci 流水线集成实操
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.5xusux.asia/blog/5919494.sHtML

原标题：nodejs 接口限流防刷代码实现
简介：限流规则误拦截正常请求修复，修正限流规则阈值，避免合法用户被限流拦截，兼顾防护与可用性。
 | 原文链接：http://book.5xusux.asia/blog/5891461.sHtML

原标题：golang 系统设计 http3 quic 简单原理了解
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://book.5xusux.asia/blog/1662775.sHtML

原标题：golang pprof 线上采集性能数据
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.5xusux.asia/blog/0804385.sHtML

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.5xusux.asia/blog/3775030.sHtML


二、踩坑排错｜Troubleshooting
原标题：golang 消息死信处理业务逻辑
简介：端口占用访问失败排查方案，讲解端口占用排查命令，定位占用进程，释放端口，解决服务启动端口被占用报错。
 | 原文链接：http://book.5xusux.asia/blog/4894219.sHtML

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.5xusux.asia/blog/3833023.sHtML

原标题：golang 优雅停机服务关闭实现
简介：golang etcd key 监听变更 watch 机制，watch 监听 etcd 键变化，配置变更实时感知，实现配置热更新。
 | 原文链接：http://book.5xusux.asia/blog/8392615.sHtML

原标题：golang 系统设计 lru 缓存算法实现思路
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://book.5xusux.asia/blog/8243069.sHtML

原标题：golang 系统设计 mq 消息积压解决方案
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.5xusux.asia/blog/6703859.sHtML

原标题：新手快速上手 Git 版本控制实操指南
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.5xusux.asia/blog/5102066.sHtML

原标题：开源项目构建失败排查步骤
简介：golang 制品镜像版本号规范管理，镜像版本号结合 git commit，明确每个镜像对应代码版本便于追溯。
 | 原文链接：http://book.5xusux.asia/blog/9325659.sHtML

原标题：golang 系统设计网关性能压测优化简单思路
简介：OAuth2 第三方登录服务搭建，搭建 OAuth2 服务，支持第三方账号登录，实现授权登录能力。
 | 原文链接：http://book.5xusux.asia/blog/8236163.sHtML

原标题：方案对比：本地缓存vs分布式缓存架构取舍
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://book.5xusux.asia/blog/5551513.sHtML

原标题：golang 系统设计 protobuf 枚举类型规范写法
简介：接口幂等性防重复请求实现，实现接口幂等逻辑，避免重复提交请求产生多条脏数据，保障业务数据安全。
 | 原文链接：http://book.5xusux.asia/blog/4532742.sHtML

原标题：重复提交幂等防护再次讲解
简介：golang html 模板防 xss 自动转义，理解 go html/template 自动转义，防止 XSS 攻击，处理不需要转义场景。
 | 原文链接：http://book.5xusux.asia/blog/6533163.sHtML

原标题：Practice：模拟数据库故障验证降级逻辑实践
简介：golang go 爬虫异步并发抓取，协程池控制并发抓取网页，多协程采集，提升爬虫采集速度。
 | 原文链接：http://book.5xusux.asia/blog/3779795.sHtML

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.5xusux.asia/blog/8021694.sHtML

原标题：实战：Nginx配置静态站点、反向代理、负载均衡
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.5xusux.asia/blog/4372863.sHtML

原标题：golang prometheus metrics 埋点开发
简介：golang go 服务蓝绿发布实践思路，蓝绿两套实例，流量一键切换，回滚快速降低发布风险。
 | 原文链接：http://book.5xusux.asia/blog/3016613.sHtML

原标题：golang 系统设计熔断降级架构讲解
简介：golang base64 大文件流式编解码，大文件流式 base64 转换，不用一次性加载全部文件进入内存。
 | 原文链接：http://book.5xusux.asia/blog/8913501.sHtML

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang sync.Pool 对象池复用对象，sync.Pool 复用临时对象，减少内存分配，降低 GC 频率提升性能。
 | 原文链接：http://book.5xusux.asia/blog/7365564.sHtML

原标题：安全笔记：GitHubAction密钥安全管理
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.5xusux.asia/blog/8909497.sHtML

原标题：nestjs 全局返回格式统一处理
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://book.5xusux.asia/blog/5083312.sHtML

原标题：快速入门OpenAPI文档生成基础实践
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://book.5xusux.asia/blog/7936428.sHtML

原标题：性能笔记：锁优化减少竞争提升并发吞吐
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://book.5xusux.asia/blog/0299217.sHtML

原标题：实战项目：本地模拟磁盘IO高负载观察服务行为
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://book.5xusux.asia/blog/4066895.sHtML

原标题：golang 系统设计配置敏感信息加密存储
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.5xusux.asia/blog/2232168.sHtML

原标题：golang 系统设计 http1.1 http2 核心差异讲解
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.5xusux.asia/blog/1970655.sHtML

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.5xusux.asia/blog/1158681.sHtML

原标题：Git 误删提交代码恢复找回
简介：缓存穿透防护保护数据库，实现缓存穿透防护手段，拦截不存在的数据查询，避免请求直接打穿数据库。
 | 原文链接：http://book.5xusux.asia/blog/6000233.sHtML

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：网关集成鉴权限流日志一体化，在网关层整合鉴权、限流、请求日志，统一对入口请求做管控处理。
 | 原文链接：http://book.5xusux.asia/blog/7546882.sHtML

原标题：Practice：批量异步任务处理系统设计实现
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.5xusux.asia/blog/6036502.sHtML

原标题：Debug：请求头过大Nginx拒绝连接报错
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.5xusux.asia/blog/5252421.sHtML

原标题：优化实践：分页查询性能优化解决offset问题
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://book.5xusux.asia/blog/9826434.sHtML

原标题：nodejs 项目 pm2 部署运维指南
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.5xusux.asia/blog/3346247.sHtML

原标题：golang mysql 时间类型选型避坑
简介：数值 key 浮点匹配异常规避，避免浮点数作为 Redis 等存储的 key，防止精度问题引发 key 匹配失败。
 | 原文链接：http://book.5xusux.asia/blog/6087535.sHtML

原标题：golang 表单文件大小限制配置
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.5xusux.asia/blog/1820331.sHtML

原标题：golang 结构体 json 序列化坑点
简介：golang go 程序敏感信息禁止打印日志，密钥密码禁止输出日志，防止敏感信息日志泄露。
 | 原文链接：http://book.5xusux.asia/blog/0134102.sHtML

原标题：API 接口调试与异常处理实战
简介：操作系统内核版本适配服务，针对服务运行要求，适配操作系统内核版本，规避内核兼容 bug。
 | 原文链接：http://book.5xusux.asia/blog/0415109.sHtML

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://book.5xusux.asia/blog/4676609.sHtML

原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang go 代码覆盖率线上统计，单元测试覆盖率统计，找出未测试代码分支，提升测试质量。
 | 原文链接：http://book.5xusux.asia/blog/5754088.sHtML

原标题：Practice：实现文件监控自动重启开发服务工具
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://book.5xusux.asia/blog/2082582.sHtML

原标题：磁盘 inode 耗尽文件创建失败
简介：golang map 并发读写 panic 解决方案，map 非并发安全，讲解加锁、sync.map 方案解决并发读写崩溃。
 | 原文链接：http://book.5xusux.asia/blog/9494240.sHtML

原标题：golang 系统设计定时任务分布式锁
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://book.5xusux.asia/blog/7085024.sHtML

三、实战开发｜Practice
原标题：Debug日志：生产环境偶发空指针异常排查
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.5xusux.asia/blog/0873470.sHtML

原标题：golang 系统设计网关灰度流量切分简单方案
简介：golang excel 大文件读取流式解析，流式读取大 excel 文件，逐行解析数据，不加载全部内容进内存。
 | 原文链接：http://book.5xusux.asia/blog/1950561.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 跨平台系统差异处理方案，处理 windows linux mac 路径、信号、文件权限差异，代码跨平台兼容。
 | 原文链接：http://book.5xusux.asia/blog/9654363.sHtML

原标题：golang 系统设计开源项目自动化 ci 配置示例
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://book.5xusux.asia/blog/3088010.sHtML

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.5xusux.asia/blog/3227092.sHtML

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang go xml 解析生成 xml 文档，encoding/xml 解析 xml，结构体标签映射 xml 节点属性。
 | 原文链接：http://book.5xusux.asia/blog/2397856.sHtML

原标题：新手教程：配置SSH‑Key免密访问GitHub
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.5xusux.asia/blog/3760114.sHtML

原标题：golang k8s configmap secret 配置
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.5xusux.asia/blog/1391099.sHtML

原标题：后端登录鉴权模块完整开发
简介：golang 容器时区设置镜像构建处理，镜像内部设置正确时区，解决容器时间与宿主机不一致。
 | 原文链接：http://book.5xusux.asia/blog/4886577.sHtML

原标题：Architecture：监控告警架构避免告警风暴设计
简介：golang go 符号表与调试信息取舍，区分生产环境调试符号取舍，平衡镜像体积与故障排查能力。
 | 原文链接：http://book.5xusux.asia/blog/3326267.sHtML

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang go 锁竞争导致 CPU 飙升，识别锁竞争场景，减少锁粒度，优化并发逻辑降低 CPU 开销。
 | 原文链接：http://book.5xusux.asia/blog/4225977.sHtML

原标题：开发记录：长连接连接管理自动清理僵死连接
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://book.5xusux.asia/blog/8573229.sHtML

原标题：golang 项目 go mod 依赖管理
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.5xusux.asia/blog/5981739.sHtML

原标题：零基础理解HTTP常用请求头与状态码
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.5xusux.asia/blog/6348274.sHtML

原标题：golang ci 流水线自动部署 k8s 示例
简介：TLS 版本兼容 HTTPS 握手失败，兼容老旧 TLS 协议版本，修复部分客户端 HTTPS 握手失败无法访问。
 | 原文链接：http://book.5xusux.asia/blog/0774122.sHtML

原标题：OpenSource：开源项目README高质量编写指南
简介：golang excel 简单读写操作示例，Go 实现 Excel 简单读写，业务数据导出 Excel 报表。
 | 原文链接：http://book.5xusux.asia/blog/6722863.sHtML

原标题：DevOps：CI构建产物缓存复用加速编译
简介：新手快速上手 Git 版本控制实操指南，讲解 Git 基础概念与常用命令，结合实操案例，帮助零基础用户掌握版本控制核心能力。
 | 原文链接：http://book.5xusux.asia/blog/2691376.sHtML

原标题：Debug：序列化反序列化版本不一致解析失败
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.5xusux.asia/blog/9354679.sHtML

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang go url url.Values 参数编码，url.Values 构建 url 查询参数，自动处理参数 url 编码。
 | 原文链接：http://book.5xusux.asia/blog/9256862.sHtML

原标题：golang 系统设计告警升级通知策略配置思路
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://book.5xusux.asia/blog/7857140.sHtML

原标题：Debug：时间回拨，定时任务调度逻辑错乱
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://book.5xusux.asia/blog/3929320.sHtML

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：golang go mod replace 本地模块替换，replace 替换模块为本地目录，修改第三方库本地调试。
 | 原文链接：http://book.5xusux.asia/blog/9777900.sHtML

原标题：开源实践：Fork上游项目，持续同步更新代码
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.5xusux.asia/blog/3228862.sHtML

原标题：golang mysql 索引失效常见场景
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://book.5xusux.asia/blog/6508117.sHtML

原标题：golang 系统设计定时任务分布式锁防重复执行
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.5xusux.asia/blog/3874215.sHtML

原标题：golang dockerfile 多阶段构建详解
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.5xusux.asia/blog/7501197.sHtML

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang toml 配置文件解析教程，Go 解析 Toml 格式配置，适用于项目配置管理场景。
 | 原文链接：http://book.5xusux.asia/blog/8227497.sHtML

原标题：golang 系统设计分布式事务几种方案
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.5xusux.asia/blog/7872245.sHtML

原标题：Hands‑on：模板渲染引擎最小原型实现
简介：CLI 批量处理工具文件操作开发，开发命令行批量工具，实现批量文件处理，提升重复文件处理效率。
 | 原文链接：http://book.5xusux.asia/blog/3189571.sHtML

原标题：架构笔记：多数据源架构设计事务处理难点
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.5xusux.asia/blog/1072462.sHtML

原标题：实战项目：Nginx限速、限流、防爬虫配置实践
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://book.5xusux.asia/blog/9660758.sHtML

原标题：实战：gRPC服务编写客户端服务端完整demo
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://book.5xusux.asia/blog/5210532.sHtML

原标题：多操作系统开发兼容处理
简介：golang 自定义 pprof 扩展业务指标，扩展 pprof，输出业务自定义指标，结合性能数据分析业务状态。
 | 原文链接：http://book.5xusux.asia/blog/8309069.sHtML

原标题：本地简易配置中心动态管理
简介：golang go 错误包装 fmt.Errorf % w，使用 % w 包装错误，支持 errors.Is errors.As 判断错误类型。
 | 原文链接：http://book.5xusux.asia/blog/2934317.sHtML

原标题：部署复盘：GitHubActions完整自动化配置
简介：分布式任务调度集群原型开发，开发简易分布式调度原型，集群多节点运行，保证任务只执行一次。
 | 原文链接：http://book.5xusux.asia/blog/4518686.sHtML

原标题：golang gin 框架接口开发实战
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.5xusux.asia/blog/9992649.sHtML

原标题：OpenSource：开源项目README高质量编写指南
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.5xusux.asia/blog/4917298.sHtML

原标题：golang 项目 go mod 依赖管理
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.5xusux.asia/blog/0706700.sHtML

原标题：golang 系统设计监控缺失指标补全完整流程
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://book.5xusux.asia/blog/6363162.sHtML

原标题：快速上手简单信号处理脚本编写
简介：异步任务堆积消费能力优化，处理消息任务堆积问题，提升消费处理速度，恢复队列正常处理水位。
 | 原文链接：http://book.5xusux.asia/blog/9830400.sHtML

四、架构设计｜Architecture
原标题：安全笔记：依赖包漏洞检测供应链安全
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.5xusux.asia/blog/9096382.sHtML

原标题：golang gitlab runner 部署与注册实操
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://book.5xusux.asia/blog/2070386.sHtML

原标题：前端大文件分片上传完整方案
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.5xusux.asia/blog/7727325.sHtML

原标题：golang k8s 镜像拉取密钥配置
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.5xusux.asia/blog/5325275.sHtML

原标题：实践：数据库慢查询分析与索引优化实战演练
简介：golang http3 quic 客户端服务端示例，go 实现 http3 quic 服务端客户端，体验 quic 协议低延迟特性。
 | 原文链接：http://book.5xusux.asia/blog/9651473.sHtML

原标题：golang 系统设计密钥轮换安全实践思路
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.5xusux.asia/blog/6898565.sHtML

原标题：线上异常：线程池队列拒绝策略配置错误丢任务
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://book.5xusux.asia/blog/6617508.sHtML

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang defer panic 异常处理，理解 defer 延迟执行，panic 恐慌捕获，实现函数资源释放异常保护。
 | 原文链接：http://book.5xusux.asia/blog/7718347.sHtML

原标题：Practice：JWT工具封装，刷新令牌完整逻辑
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://book.5xusux.asia/blog/8541535.sHtML

原标题：golang minio 存储桶权限管控配置
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://book.5xusux.asia/blog/7289132.sHtML

原标题：记一次升级操作系统内核引发服务不稳定
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.5xusux.asia/blog/5959428.sHtML

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://book.5xusux.asia/blog/8618727.sHtML

原标题：架构复盘：RPC框架架构超时重试设计要点
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.5xusux.asia/blog/3732946.sHtML

原标题：安全笔记：XSS跨站脚本攻击防御落地实践
简介：golang go 测试文件命名规范，_test.go 测试文件，TestXxx 单元测试函数命名规范。
 | 原文链接：http://book.5xusux.asia/blog/1538993.sHtML

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.5xusux.asia/blog/5791014.sHtML

原标题：golang 系统设计错误码体系完整设计
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://book.5xusux.asia/blog/0801177.sHtML

原标题：golang etcd 配置中心简单使用
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.5xusux.asia/blog/6424866.sHtML

原标题：新手指南：读懂项目构建脚本作用
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://book.5xusux.asia/blog/0210088.sHtML

?
