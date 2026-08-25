最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计 protobuf json 性能对比
简介：golang 分布式锁防死锁实现要点，锁超时、续期、锁持有者校验，避免锁死锁，保障分布式锁可靠性。
 | 原文链接：http://book.bhetgb.asia/blog/3066860.sHtMl

原标题：文件分片上传断点续传功能
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://book.bhetgb.asia/blog/3790919.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：业务接口幂等完整落地案例，完整业务场景幂等落地示例，覆盖表单提交、回调、重试各类场景。
 | 原文链接：http://book.bhetgb.asia/blog/6558657.sHtMl

原标题：golang 系统设计大文件上传架构
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.bhetgb.asia/blog/4212974.sHtMl

原标题：优化实践：LRU本地缓存优化热点访问性能
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://book.bhetgb.asia/blog/6272945.sHtMl

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.bhetgb.asia/blog/9048974.sHtMl

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://book.bhetgb.asia/blog/4610579.sHtMl

原标题：JWT 工具封装令牌刷新过期
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.bhetgb.asia/blog/7855043.sHtMl

原标题：方案对比：几种分布式限流算法架构适用性
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.bhetgb.asia/blog/2516730.sHtMl

原标题：程序日志分级输出规范实践
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://book.bhetgb.asia/blog/2087035.sHtMl

原标题：DevOps：Docker镜像优化，减小镜像体积实践
简介：golang io.Reader io.Writer 接口理解，io 读写接口，各类数据源统一抽象，适配 io 复制函数。
 | 原文链接：http://book.bhetgb.asia/blog/5808342.sHtMl

原标题：调优方案：Docker容器内核参数性能调优
简介：golang go mod tidy 依赖清理，go mod tidy 自动增删依赖，整理 go.mod go.sum 文件。
 | 原文链接：http://book.bhetgb.asia/blog/9515615.sHtMl

原标题：TLS 版本兼容 HTTPS 握手失败
简介：动态定时任务业务调度实现，实现可以动态增删启停定时任务，无需重启服务调整调度任务。
 | 原文链接：http://book.bhetgb.asia/blog/8113596.sHtMl

原标题：golang redis 计数器防超卖示例
简介：golang cobra 命令行参数配置绑定，cobra 绑定配置文件环境变量命令行参数，多源配置合并。
 | 原文链接：http://book.bhetgb.asia/blog/7130845.sHtMl

原标题：golang 跨域处理中间件编写
简介：预编译 SQL 防注入实现，使用预编译 SQL 方式，杜绝 SQL 注入风险，提升数据库访问层安全能力。
 | 原文链接：http://book.bhetgb.asia/blog/1563946.sHtMl

原标题：提交第一个开源 PR 完整流程
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.bhetgb.asia/blog/5986488.sHtMl

原标题：性能复盘：磁盘Swap大量使用系统卡顿优化
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://book.bhetgb.asia/blog/2386781.sHtMl

原标题：golang 系统设计降级策略开关配置方案
简介：服务器时钟同步任务错乱修复，配置服务器 NTP 时间同步，保证集群所有机器时间保持一致。
 | 原文链接：http://book.bhetgb.asia/blog/9408758.sHtMl

原标题：golang es 高亮搜索结果实现方案
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.bhetgb.asia/blog/8858084.sHtMl

原标题：运维笔记：备份策略数据库定时备份脚本
简介：内存溢出问题现象识别排查，识别内存溢出现象，梳理排查方向，定位内存持续上涨引发服务崩溃问题。
 | 原文链接：http://book.bhetgb.asia/blog/5287026.sHtMl

原标题：golang 系统设计定时任务分布式锁
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://book.bhetgb.asia/blog/3461086.sHtMl

原标题：坑点：gitreset误删本地代码恢复方案
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://book.bhetgb.asia/blog/7902113.sHtMl

原标题：golang 系统设计缓存预热脚本编写实操
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.bhetgb.asia/blog/8151531.sHtMl

原标题：入门实践：简单的请求封装与异常捕获
简介：JWT 令牌过期异常处理，捕获 JWT 过期、篡改异常，编写业务处理逻辑，引导用户重新获取令牌。
 | 原文链接：http://book.bhetgb.asia/blog/1571625.sHtMl

原标题：实践：消息队列死信处理业务落地实践
简介：golang go 多版本管理 gvm 使用，gvm 管理多个 go sdk 版本，快速切换不同 go 版本做项目开发。
 | 原文链接：http://book.bhetgb.asia/blog/1650954.sHtMl

原标题：golang 系统设计内部服务契约测试简单思路
简介：ORM 框架数据库增删改查实操，使用 ORM 框架完成数据库基础操作，减少手写 SQL，简化业务层数据库交互代码。
 | 原文链接：http://book.bhetgb.asia/blog/1353640.sHtMl

原标题：端口占用释放资源重启服务
简介：golang 半关闭 tcp 连接 shutdown，tcp 连接 shutdown 半关闭，单向关闭读或者写，理解 tcp 关闭流程。
 | 原文链接：http://book.bhetgb.asia/blog/4813572.sHtMl

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：golang http cookie jar 会话处理，客户端 cookie jar 自动管理 cookie，处理登录态会话。
 | 原文链接：http://book.bhetgb.asia/blog/4931657.sHtMl

原标题：golang websocket 消息广播实现
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://book.bhetgb.asia/blog/7853634.sHtMl

原标题：优化实践：多级缓存减少下游服务调用压力
简介：前端 pdf 预览渲染方案对比，对比前端 PDF 预览库，分析性能、兼容性，给出业务选型参考。
 | 原文链接：http://book.bhetgb.asia/blog/2929833.sHtMl

原标题：golang 系统设计分布式事务几种方案优缺点
简介：golang 路径处理 filepath 包规范写法，使用 filepath 处理路径拼接分割，自动适配操作系统路径分隔符。
 | 原文链接：http://book.bhetgb.asia/blog/1891149.sHtMl

原标题：TLS 版本兼容 HTTPS 握手失败
简介：CI 流水线超时时间延长配置，调大 CI 任务超时阈值，解决构建任务耗时较长被流水线强制终止。
 | 原文链接：http://book.bhetgb.asia/blog/9515203.sHtMl

原标题：golang 系统设计压测指标确定与分析
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://book.bhetgb.asia/blog/1221947.sHtMl

原标题：golang 系统设计开源项目维护简单经验分享
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.bhetgb.asia/blog/9624015.sHtMl

原标题：CDN 缓存刷新获取最新静态资源
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.bhetgb.asia/blog/9667132.sHtMl

原标题：性能笔记：操作系统文件句柄、虚拟内存调优
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://book.bhetgb.asia/blog/9491086.sHtMl

原标题：实践：大文件分片上传后端完整实现思路
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.bhetgb.asia/blog/7891051.sHtMl

原标题：部署实践：容器优雅停机配置处理信号
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://book.bhetgb.asia/blog/3420203.sHtMl

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.bhetgb.asia/blog/1329080.sHtMl

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://book.bhetgb.asia/blog/6580167.sHtMl


二、踩坑排错｜Troubleshooting
原标题：布隆过滤器误判问题修正
简介：JWT 工具封装令牌刷新过期，封装 JWT 工具类，实现令牌生成、校验、过期刷新整套令牌管理逻辑。
 | 原文链接：http://book.bhetgb.asia/blog/5316547.sHtMl

原标题：golang 系统设计开源项目依赖版本升级维护
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.bhetgb.asia/blog/4268175.sHtMl

原标题：Hands‑on：简易导出PDF后端生成demo实践
简介：golang nats 轻量消息队列 go 开发，nats 高性能轻量消息系统，发布订阅模式异步解耦业务。
 | 原文链接：http://book.bhetgb.asia/blog/1276358.sHtMl

原标题：golang elasticsearch 索引设计思路
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://book.bhetgb.asia/blog/9316825.sHtMl

原标题：看懂报错日志快速定位问题
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://book.bhetgb.asia/blog/9391494.sHtMl

原标题：坑点：依赖包内部携带恶意代码供应链风险
简介：多规则数据脱敏组件开发，封装通用脱敏组件，支持多种脱敏规则，项目多处复用脱敏逻辑。
 | 原文链接：http://book.bhetgb.asia/blog/1943591.sHtMl

原标题：golang 系统设计开源项目贡献指南 contributing
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://book.bhetgb.asia/blog/9995443.sHtMl

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang csv 百万级数据导入数据库，流式读取 csv 分批写入数据库，避免一次性加载全部数据。
 | 原文链接：http://book.bhetgb.asia/blog/9461103.sHtMl

原标题：golang redis pipeline 批量操作
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://book.bhetgb.asia/blog/7804354.sHtMl

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go work 多模块本地开发，go work 多模块本地同时开发，本地模块互相引用，无需推送仓库。
 | 原文链接：http://book.bhetgb.asia/blog/6423069.sHtMl

原标题：从零搭建本地开发环境完整教程
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://book.bhetgb.asia/blog/5105907.sHtMl

原标题：快速入门Nginx基础配置，反向代理示例
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://book.bhetgb.asia/blog/9897976.sHtMl

原标题：Practice：实现业务id生成不连续有序ID方案
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.bhetgb.asia/blog/9053520.sHtMl

原标题：golang mysql 慢查询日志开启分析
简介：golang go 程序版本号内置编译注入，编译时注入 git commit 版本号，程序运行输出版本便于排查。
 | 原文链接：http://book.bhetgb.asia/blog/7532239.sHtMl

原标题：golang 系统设计 mq 消息重复消费处理
简介：golang net.Conn 包装自定义连接，包装 net.Conn，统计读写字节，日志打印，超时控制。
 | 原文链接：http://book.bhetgb.asia/blog/4538414.sHtMl

原标题：golang 大文件 http 下载服务
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://book.bhetgb.asia/blog/7937989.sHtMl

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.bhetgb.asia/blog/4283762.sHtMl

原标题：接口压测定位系统性能瓶颈
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.bhetgb.asia/blog/4620376.sHtMl

原标题：golang http 服务性能优化调参
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://book.bhetgb.asia/blog/4273576.sHtMl

原标题：入门实践：简单重试逻辑封装实现
简介：容器软链接文件权限修复，修复容器内软链接文件权限，让程序能够正常读取软链接指向的文件。
 | 原文链接：http://book.bhetgb.asia/blog/3838107.sHtMl

原标题：设计思考：业务系统中什么时候不要用微服务
简介：内网 DNS 不稳定随机报错排查，定位内网 DNS 抖动问题，配置备选 DNS，解决偶现域名解析失败。
 | 原文链接：http://book.bhetgb.asia/blog/7208659.sHtMl

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.bhetgb.asia/blog/5798834.sHtMl

原标题：架构笔记：海量日志处理架构选型与实践
简介：缓存过期策略优化防业务故障，合理设置缓存过期策略，规避集中过期，减少缓存失效带来业务抖动。
 | 原文链接：http://book.bhetgb.asia/blog/9104589.sHtMl

原标题：golang 系统设计数据库扩容几种方式
简介：Docker 网络模式容器互通设置，选择合适 Docker 网络模式，实现容器之间网络互相访问通信。
 | 原文链接：http://book.bhetgb.asia/blog/4759935.sHtMl

原标题：Architecture：事件溯源架构模式适用业务场景
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://book.bhetgb.asia/blog/5517723.sHtMl

原标题：golang 系统设计字段命名类型选择最佳实践
简介：golang 项目目录分层规范设计，Go 后端项目目录分层规范，按领域分层，提高项目可读性可维护性。
 | 原文链接：http://book.bhetgb.asia/blog/5182033.sHtMl

原标题：golang docker compose 环境变量
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://book.bhetgb.asia/blog/5816370.sHtMl

原标题：golang 令牌桶限流中间件 gin
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.bhetgb.asia/blog/8982059.sHtMl

原标题：golang 系统设计事务消息 rocketmq 简单原理
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.bhetgb.asia/blog/5972865.sHtMl

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.bhetgb.asia/blog/9469462.sHtMl

原标题：Git 分支切换合并删除完整操作
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.bhetgb.asia/blog/2753491.sHtMl

原标题：调优方案：JVM内存参数优化，降低GC频率
简介：前端虚拟列表大数据渲染优化，实现虚拟滚动列表，只渲染可视区域 DOM，上万条数据页面流畅渲染。
 | 原文链接：http://book.bhetgb.asia/blog/7782259.sHtMl

原标题：golang redis 计数器防超卖示例
简介：golang redis 客户端业务使用，Go Redis 客户端对接，实现缓存、计数器，适配各类 Redis 业务场景。
 | 原文链接：http://book.bhetgb.asia/blog/2682762.sHtMl

原标题：HelloDocker：编写你的第一个Dockerfile
简介：golang ctx 关闭之后资源释放，context 取消后，监听 Done ()，释放 goroutine 网络 IO 资源。
 | 原文链接：http://book.bhetgb.asia/blog/6290390.sHtMl

原标题：golang 系统设计日志与 traceId 关联打印实现
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.bhetgb.asia/blog/8547547.sHtMl

原标题：golang proto 默认值坑点梳理
简介：golang goroutine 泄露常见场景汇总，channel 阻塞、context 忘记取消，导致协程无法退出发生泄露。
 | 原文链接：http://book.bhetgb.asia/blog/2550647.sHtMl

原标题：Performance：避免内存拷贝，大对象处理优化
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://book.bhetgb.asia/blog/9095398.sHtMl

原标题：Nginx 请求头大小上限调整
简介：golang go 随机数安全与非安全，math/rand 伪随机与 crypto/rand 密码学安全随机，区分业务场景。
 | 原文链接：http://book.bhetgb.asia/blog/5993842.sHtMl

原标题：golang jwt 鉴权中间件完整示例
简介：数据库连接池参数调优，调整连接池最大最小连接数，空闲超时，避免连接耗尽或者资源浪费。
 | 原文链接：http://book.bhetgb.asia/blog/7870263.sHtMl

原标题：golang 系统设计数据库基准压测简单思路
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://book.bhetgb.asia/blog/0346831.sHtMl

三、实战开发｜Practice
原标题：SourceMap 生成线上报错定位
简介：golang go 包循环导入报错解决，A 导入 B B 导入 A，循环导入报错，重构代码拆分包消除循环依赖。
 | 原文链接：http://book.bhetgb.asia/blog/7524127.sHtMl

原标题：golang k8s 基础概念 pod deployment
简介：批量异步处理系统业务落地，构建批量异步处理系统，把耗时业务异步化，提升接口响应速度。
 | 原文链接：http://book.bhetgb.asia/blog/7802562.sHtMl

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：静态网页 HTML CSS 快速入门实战，通过简单页面案例讲解标签、样式布局，从零编写页面，理解网页基础渲染原理。
 | 原文链接：http://book.bhetgb.asia/blog/1273593.sHtMl

原标题：开发记录：网关实现接口鉴权、限流、日志打印
简介：golang 参数校验业务接口处理，Go 接口入参参数校验，拦截非法入参，减少业务层参数判断代码。
 | 原文链接：http://book.bhetgb.asia/blog/7369782.sHtMl

原标题：golang 系统设计 commit 提交规范约定
简介：golang sync.Mutex 互斥锁正确模式，互斥锁 defer Unlock，锁粒度控制，避免锁范围过大。
 | 原文链接：http://book.bhetgb.asia/blog/8954025.sHtMl

原标题：nodejs 集成测试业务流程编写
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.bhetgb.asia/blog/7883467.sHtMl

原标题：golang mysql 字符集排序规则设置
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://book.bhetgb.asia/blog/8366951.sHtMl

原标题：开发记录：JWT过期刷新滑动过期实现实践
简介：布隆过滤器误判问题修正，调整布隆过滤器参数，降低误判概率，保证业务去重逻辑准确。
 | 原文链接：http://book.bhetgb.asia/blog/5951058.sHtMl

原标题：分布式任务调度集群原型开发
简介：golang go 信号处理优雅重启实现，USR2 触发程序重启，不关闭监听 socket 实现零停机升级。
 | 原文链接：http://book.bhetgb.asia/blog/1942083.sHtMl

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang testify testify 断言库使用，testify assert require 断言，简化单元测试断言代码。
 | 原文链接：http://book.bhetgb.asia/blog/0165100.sHtMl

原标题：异步编程 Promise 执行流程解析
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.bhetgb.asia/blog/4182763.sHtMl

原标题：部署复盘：容器OOM问题完整排查流程
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.bhetgb.asia/blog/3209609.sHtMl

原标题：实战：基于DockerCompose搭建本地开发栈
简介：文件批量导入导出功能实现，开发批量导入导出接口，处理大量文件数据，完成业务数据批量迁移与导出。
 | 原文链接：http://book.bhetgb.asia/blog/8211610.sHtMl

原标题：开发复盘：大JSON解析分批处理避免内存溢出
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.bhetgb.asia/blog/6436432.sHtMl

原标题：Practice：模拟第三方接口超时服务降级验证
简介：批量操作分批处理防止 OOM，大批量数据处理不一次性加载全部数据，分批循环处理，避免内存溢出。
 | 原文链接：http://book.bhetgb.asia/blog/3492702.sHtMl

原标题：golang es 查询语句 DSL 实操
简介：golang prometheus http 接口暴露指标，暴露 prometheus metrics 接口，输出业务运行指标，接入监控告警系统。
 | 原文链接：http://book.bhetgb.asia/blog/8140759.sHtMl

原标题：golang 系统设计重试退避策略业务落地
简介：正则表达式文本处理实战案例，结合业务场景演示正则匹配、提取、替换，处理手机号、邮箱等各类文本校验需求。
 | 原文链接：http://book.bhetgb.asia/blog/3763948.sHtMl

原标题：架构复盘：多级缓存架构，本地缓存+分布式缓存
简介：golang 程序崩溃 core dump 生成调试，开启 core dump，程序崩溃生成转储文件，事后分析崩溃原因。
 | 原文链接：http://book.bhetgb.asia/blog/4838940.sHtMl

原标题：服务健康检查监控接口开发
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.bhetgb.asia/blog/5651801.sHtMl

原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://book.bhetgb.asia/blog/3558790.sHtMl

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：数据库排序规则统一结果一致，统一数据库表排序规则，解决不同环境查询排序结果不一致问题。
 | 原文链接：http://book.bhetgb.asia/blog/4903487.sHtMl

原标题：golang 项目 makefile 脚本编写
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.bhetgb.asia/blog/9970001.sHtMl

原标题：图片上传预览格式大小处理
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://book.bhetgb.asia/blog/9382674.sHtMl

原标题：代理 HTTPS 证书访问异常处理
简介：golang redis pipeline 批量操作，使用 Redis Pipeline 批量执行多条命令，减少网络往返，提升批量操作性能。
 | 原文链接：http://book.bhetgb.asia/blog/6691980.sHtMl

原标题：零基础理解HTTP常用请求头与状态码
简介：golang go 泛型实现通用数据结构，泛型实现通用栈队列，复用逻辑支持多种数据类型。
 | 原文链接：http://book.bhetgb.asia/blog/9063080.sHtMl

原标题：设计思考：缓存分层架构设计与失效处理策略
简介：golang go 项目依赖冲突解决完整思路，定位冲突包，replace、exclude、升级降级解决版本冲突。
 | 原文链接：http://book.bhetgb.asia/blog/2132836.sHtMl

原标题：golang 分布式锁 redis 实现
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://book.bhetgb.asia/blog/9628433.sHtMl

原标题：golang 系统设计代码评审 checklist 清单
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://book.bhetgb.asia/blog/5671760.sHtMl

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：前端工程化 webpack 打包优化，针对 webpack 项目做打包调优，分包、压缩、Tree‑Shaking，缩减包体积。
 | 原文链接：http://book.bhetgb.asia/blog/4282446.sHtMl

原标题：golang minio 存储桶权限管控配置
简介：golang fasthttp 客户端连接池调优，fasthttp 客户端连接池配置，复用连接提升请求性能。
 | 原文链接：http://book.bhetgb.asia/blog/9680387.sHtMl

原标题：golang cpu pprof 性能分析实操
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://book.bhetgb.asia/blog/6728055.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://book.bhetgb.asia/blog/0104083.sHtMl

原标题：新手指南：读懂项目构建脚本作用
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://book.bhetgb.asia/blog/8620167.sHtMl

原标题：golang jaeger 链路追踪 go 接入
简介：golang trace 链路追踪 opentelemetry，opentelemetry 实现链路追踪，生成 traceId spanId，完整记录调用链路。
 | 原文链接：http://book.bhetgb.asia/blog/6053838.sHtMl

原标题：设计思考：消息队列重复消费架构层防御手段
简介：golang os.Signal 信号监听完整示例，signal.Notify 监听信号，缓冲 channel 防止信号丢失。
 | 原文链接：http://book.bhetgb.asia/blog/8803132.sHtMl

原标题：环境变量不生效问题修复
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.bhetgb.asia/blog/9774262.sHtMl

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：golang wasm 浏览器 js 交互，go wasm 与 js 互相调用，浏览器端 go 程序操作 dom 调用 js 函数。
 | 原文链接：http://book.bhetgb.asia/blog/1270400.sHtMl

原标题：Practice：实现请求大小限制中间件防护大报文
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.bhetgb.asia/blog/0446461.sHtMl

原标题：项目实践：Docker镜像安全扫描本地实操
简介：多线程线程安全脏数据规避，梳理多线程共享变量，做好同步控制，避免并发修改产生脏数据。
 | 原文链接：http://book.bhetgb.asia/blog/6468771.sHtMl

原标题：golang k8s 持久化 pv pvc 使用实操
简介：GET POST 接口请求参数处理，讲解两种请求方式参数传递区别，演示参数接收、解析、校验，适配不同接口调用场景。
 | 原文链接：http://book.bhetgb.asia/blog/8696207.sHtMl

四、架构设计｜Architecture
原标题：golang 互斥锁读写锁并发安全
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://book.bhetgb.asia/blog/9795903.sHtMl

原标题：快速上手调试工具定位简单代码错误
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://book.bhetgb.asia/blog/9399644.sHtMl

原标题：golang github actions 完整工作流示例
简介：golang 高并发下锁优化减少竞争，减小锁粒度，读写锁替换互斥锁，无锁编程降低锁竞争开销。
 | 原文链接：http://book.bhetgb.asia/blog/7908015.sHtMl

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://book.bhetgb.asia/blog/6786576.sHtMl

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：CI 构建缓存加速编译速度，开启 CI 流水线依赖缓存，复用上一次构建依赖包，缩短流水线构建耗时。
 | 原文链接：http://book.bhetgb.asia/blog/0194351.sHtMl

原标题：golang k8s helm chart 简单编写
简介：golang go 第三方库选型评估要点，评估库活跃度维护情况、性能、依赖数量，选择合适开源库。
 | 原文链接：http://book.bhetgb.asia/blog/7252709.sHtMl

原标题：golang k8s 监控 prometheus 部署
简介：golang gorm select 指定查询字段，指定查询字段，避免查询全部字段，减少数据传输，提升查询性能。
 | 原文链接：http://book.bhetgb.asia/blog/6501132.sHtMl

原标题：实战：Docker资源监控查看容器状态实操
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.bhetgb.asia/blog/8527866.sHtMl

原标题：golang k8s 镜像拉取密钥配置
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.bhetgb.asia/blog/0487901.sHtMl

原标题：运维笔记：系统内核参数调优生产服务器
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://book.bhetgb.asia/blog/4509941.sHtMl

原标题：golang 文件上传下载接口开发
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://book.bhetgb.asia/blog/4646299.sHtMl

原标题：HelloGitWorkflow：理解简单主干开发流程
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://book.bhetgb.asia/blog/2994981.sHtMl

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://book.bhetgb.asia/blog/7574233.sHtMl

原标题：大事务拆分防止连接池耗尽
简介：全局时间标准统一逻辑错乱修复，全服务统一使用同一时间标准，不要混用本地时间 UTC，修复时间逻辑 bug。
 | 原文链接：http://book.bhetgb.asia/blog/0138676.sHtMl

原标题：部署实践：DockerCompose管理多服务环境
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://book.bhetgb.asia/blog/8275443.sHtMl

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang nil channel 阻塞特性，nil channel 读写永久阻塞，理解 nil channel 行为做逻辑控制。
 | 原文链接：http://book.bhetgb.asia/blog/1866578.sHtMl

原标题：任务执行锁防止并发重复调度
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://book.bhetgb.asia/blog/4549422.sHtMl

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://book.bhetgb.asia/blog/6334377.sHtMl

?
