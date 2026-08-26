最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.8ai71b.asia/arts/474659.Doc

原标题：架构复盘：数据库主从架构设计与延迟应对方案
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.8ai71b.asia/arts/278629.Doc

原标题：Hands‑on：搭建OAuth2简易授权服务Demo
简介：golang os 主机名内核版本读取，os 读取主机名，内核信息，操作系统版本，获取运行环境信息。
 | 原文链接：http://wiki.8ai71b.asia/arts/976793.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：程序预加载加快服务启动速度，把高频使用资源提前预加载，减少请求阶段初始化，加快服务启动。
 | 原文链接：http://wiki.8ai71b.asia/arts/022885.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/115440.Doc

原标题：golang redis 缓存雪崩完整处理
简介：接口签名校验防篡改实现，实现请求签名验签逻辑，校验请求参数未被篡改，提升接口调用安全性。
 | 原文链接：http://wiki.8ai71b.asia/arts/314959.Doc

原标题：开发记录：搭建CI/CD流水线自动构建部署项目
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://wiki.8ai71b.asia/arts/696911.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.8ai71b.asia/arts/353177.Doc

原标题：实战：WebSocket断线重连完整业务处理实践
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/786929.Doc

原标题：golang k8s 日志收集 efk 简单架构
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.8ai71b.asia/arts/497317.Doc

原标题：前后端交互跨域问题完整处理
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.8ai71b.asia/arts/264552.Doc

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.8ai71b.asia/arts/887360.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：用户敏感数据脱敏代码实现，编写数据脱敏工具，对手机号、身份证做脱敏处理，防止敏感信息直接泄露。
 | 原文链接：http://wiki.8ai71b.asia/arts/104096.Doc

原标题：定时任务周期调度 demo 开发
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.8ai71b.asia/arts/459020.Doc

原标题：golang 多协程任务池并发控制
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://wiki.8ai71b.asia/arts/454748.Doc

原标题：新手教程：如何给开源项目提交第一个PR
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://wiki.8ai71b.asia/arts/593085.Doc

原标题：分布式事务最终一致性实现
简介：golang viper 多源配置管理实操，viper 读取配置文件环境变量命令行参数，多源配置优先级管理。
 | 原文链接：http://wiki.8ai71b.asia/arts/744562.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：golang time.Ticker 泄漏常见场景，忘记 Stop Ticker，导致协程泄漏，定时器资源无法释放。
 | 原文链接：http://wiki.8ai71b.asia/arts/361923.Doc

原标题：开发记录：短信发送服务封装，失败重试策略
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.8ai71b.asia/arts/945107.Doc

原标题：开发记录：业务错误告警邮件通知组件实践
简介：golang 服务注册 etcd 简单示例，etcd 实现服务注册发现，微服务实例注册元数据，客户端发现节点。
 | 原文链接：http://wiki.8ai71b.asia/arts/727215.Doc

原标题：golang 系统设计网关缓存静态资源实现思路
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://wiki.8ai71b.asia/arts/579606.Doc

原标题：性能笔记：DNS缓存优化减少域名解析开销
简介：express 中间件开发业务实践，开发 Express 自定义中间件，拦截请求，实现鉴权、日志记录等通用逻辑。
 | 原文链接：http://wiki.8ai71b.asia/arts/725802.Doc

原标题：前后端会话登录状态持久化
简介：golang go‑zero 分布式锁组件使用，go‑zero 内置 redis 分布式锁，业务直接调用实现并发控制。
 | 原文链接：http://wiki.8ai71b.asia/arts/875989.Doc

原标题：Debug：多线程共享可变变量产生脏数据
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://wiki.8ai71b.asia/arts/560925.Doc

原标题：golang 信号量控制并发数量
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.8ai71b.asia/arts/371022.Doc

原标题：慢查询分析索引调优数据库实战
简介：Spring 事务传播机制配置生效，理解事务传播行为，正确配置，修复事务不生效、事务失效的业务 bug。
 | 原文链接：http://wiki.8ai71b.asia/arts/381681.Doc

原标题：排错：反向代理后获取真实IP全部变成内网IP
简介：golang mysql 事务回滚异常处理，Go MySQL 事务异常捕获，正确回滚事务，保证异常场景数据回滚。
 | 原文链接：http://wiki.8ai71b.asia/arts/645244.Doc

原标题：死信队列处理消息阻塞业务
简介：golang net/url 路径拼接处理，url.ParseRequestURI 处理请求 url，正确拼接 url 路径避免拼接错误。
 | 原文链接：http://wiki.8ai71b.asia/arts/089647.Doc

原标题：无用对象回收抑制内存上涨
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://wiki.8ai71b.asia/arts/001899.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：vite 项目配置与构建提速技巧，讲解 vite 配置优化手段，提升开发热更新速度与生产构建打包效率。
 | 原文链接：http://wiki.8ai71b.asia/arts/107338.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.8ai71b.asia/arts/644964.Doc

原标题：golang 系统设计读写穿透更新缓存几种方案
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://wiki.8ai71b.asia/arts/349522.Doc

原标题：AI‑Dev：AI辅助编码高效使用提示词技巧
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://wiki.8ai71b.asia/arts/419028.Doc

原标题：设计思考：系统降级开关架构设计快速切流量
简介：golang 大内存分配 GC 抖动规避，避免瞬时大量对象创建，分批处理，防止 GC 抖动业务抖动。
 | 原文链接：http://wiki.8ai71b.asia/arts/072222.Doc

原标题：开源实践：开源Issue沟通技巧如何有效提Bug
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.8ai71b.asia/arts/888624.Doc

原标题：golang 系统设计数据脱敏架构实现
简介：golang time duration 解析时间字符串，time.ParseDuration 解析 1h30m 时间间隔字符串。
 | 原文链接：http://wiki.8ai71b.asia/arts/311817.Doc

原标题：坑点：缓存穿透，大量无效请求打穿数据库
简介：golang goroutine 泄露检测告警实现，监控 goroutine 数量，突增触发告警，提早发现协程泄露。
 | 原文链接：http://wiki.8ai71b.asia/arts/611374.Doc

原标题：golang 系统设计性能优化通用思路方法论
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.8ai71b.asia/arts/603230.Doc

原标题：开发记录：分布式ID生成器实现与压力测试
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://wiki.8ai71b.asia/arts/040074.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.8ai71b.asia/arts/078183.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://wiki.8ai71b.asia/arts/674339.Doc

原标题：Architecture：限流计数器架构时间窗口选型对比
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.8ai71b.asia/arts/902117.Doc

原标题：golang 工具函数库封装思路
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.8ai71b.asia/arts/990671.Doc

原标题：踩坑记录：UTC时间与本地时间混用逻辑错乱
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://wiki.8ai71b.asia/arts/890996.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.8ai71b.asia/arts/690612.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：文件句柄耗尽资源泄露处理，定位文件句柄泄露，修复文件忘记关闭问题，解决句柄耗尽服务报错。
 | 原文链接：http://wiki.8ai71b.asia/arts/619285.Doc

原标题：项目实践：Docker多环境镜像构建策略实践
简介：golang CPU 绑定亲和性设置 go 程序，设置进程 CPU 亲和绑定核心，减少 CPU 调度开销，提升计算性能。
 | 原文链接：http://wiki.8ai71b.asia/arts/715770.Doc

原标题：架构思考：单体应用向微服务拆分演进路径
简介：时间同步修复令牌提前过期，服务器时间不同步导致 JWT 令牌提前过期，同步系统时间解决异常。
 | 原文链接：http://wiki.8ai71b.asia/arts/321729.Doc

原标题：实战项目：搭建私有Docker镜像仓库本地实践
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.8ai71b.asia/arts/303984.Doc

原标题：golang 消息死信处理业务逻辑
简介：分布式锁失效问题排查修复，分析分布式锁失效场景，修复锁超时、续期问题，保证锁逻辑可靠。
 | 原文链接：http://wiki.8ai71b.asia/arts/452981.Doc

原标题：golang k8s 监控 prometheus 部署
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://wiki.8ai71b.asia/arts/082447.Doc

原标题：实战项目：实现简单缓存服务缓存穿透击穿防护
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://wiki.8ai71b.asia/arts/233040.Doc

原标题：环境变量不生效问题修复
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://wiki.8ai71b.asia/arts/285286.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.8ai71b.asia/arts/011982.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang atomic 原子操作整数，atomic 加减比较交换，无锁更新整型变量，简单计数器场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/031736.Doc

原标题：后端分页查询逻辑代码实现
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://wiki.8ai71b.asia/arts/196852.Doc

原标题：Hands‑on：本地模拟消息重复消费处理实践
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.8ai71b.asia/arts/762484.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：极简方式搭建个人技术文档站点，使用轻量化工具快速部署文档站点，支持 markdown 编写，实现知识沉淀与对外分享。
 | 原文链接：http://wiki.8ai71b.asia/arts/374657.Doc

原标题：效率笔记：GitWorkflow团队协作规范模板
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.8ai71b.asia/arts/264355.Doc

原标题：vite 插件开发自定义构建逻辑
简介：golang go 模板执行错误捕获，捕获模板执行错误，防止模板错误直接返回空白页面。
 | 原文链接：http://wiki.8ai71b.asia/arts/790473.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://wiki.8ai71b.asia/arts/530659.Doc

原标题：golang 系统设计 debug 远程调试 go 程序实操
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.8ai71b.asia/arts/150069.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.8ai71b.asia/arts/831059.Doc

原标题：并发数据覆盖加锁安全处理
简介：golang systemd 配置 go 服务部署，编写 systemd unit 文件管理 go 服务，开机自启、崩溃自动重启。
 | 原文链接：http://wiki.8ai71b.asia/arts/997347.Doc

原标题：极简 API 网关路由转发实现
简介：开发生产环境资源路径统一，对齐开发环境与生产环境资源路径，防止本地正常上线后资源找不到。
 | 原文链接：http://wiki.8ai71b.asia/arts/649092.Doc

原标题：运维笔记：备份策略数据库定时备份脚本
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.8ai71b.asia/arts/134729.Doc

原标题：架构笔记：分布式事务方案对比与业务取舍
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://wiki.8ai71b.asia/arts/552405.Doc

原标题：新手教程：gitrebase基础使用与风险提示
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.8ai71b.asia/arts/845915.Doc

原标题：新手参与开源社区贡献指南
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.8ai71b.asia/arts/569641.Doc

原标题：操作系统内核版本适配服务
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://wiki.8ai71b.asia/arts/962129.Doc

原标题：git cherry‑pick 规范操作防 bug
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://wiki.8ai71b.asia/arts/939587.Doc

原标题：golang docker volume 数据持久化
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://wiki.8ai71b.asia/arts/740921.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang cgo 性能开销避坑指南，cgo 调用开销，减少频繁 cgo 调用，规避 cgo 带来内存泄漏风险。
 | 原文链接：http://wiki.8ai71b.asia/arts/758786.Doc

原标题：golang 系统设计接口超时设计原则梳理
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.8ai71b.asia/arts/411757.Doc

原标题：service‑worker 离线缓存实践
简介：简易网关请求路由过滤模拟，模拟网关基础能力，实现请求路由转发、简单过滤，理解网关核心工作逻辑。
 | 原文链接：http://wiki.8ai71b.asia/arts/712945.Doc

原标题：项目实践：多环境配置管理组件设计与实现
简介：golang mock 单元测试编写技巧，单元测试 mock 外部依赖，隔离数据库网络，只测试业务逻辑本身。
 | 原文链接：http://wiki.8ai71b.asia/arts/530402.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：Nginx 静态代理负载均衡全套配置，一套 Nginx 配置示例，覆盖静态资源、反向代理、负载均衡场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/307757.Doc

原标题：golang 系统设计单元测试边界条件覆盖思路
简介：golang 自定义 http round tripper，封装 http 客户端拦截，实现请求日志、签名、重试统一处理逻辑。
 | 原文链接：http://wiki.8ai71b.asia/arts/049595.Doc

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.8ai71b.asia/arts/085506.Doc

原标题：CI 流水线超时时间延长配置
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.8ai71b.asia/arts/667404.Doc

三、实战开发｜Practice
原标题：性能复盘：接口响应从800ms优化到50ms全过程
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/892744.Doc

原标题：OpenSource：开源项目版本发布CHANGELOG编写
简介：golang defer 闭包变量捕获坑，defer 捕获循环变量引用，变量被复写，理解闭包变量捕获规则。
 | 原文链接：http://wiki.8ai71b.asia/arts/349055.Doc

原标题：运维笔记：系统文件句柄数调整生产配置
简介：golang net.Listener 包装自定义监听器，包装 Listener 做连接计数、连接拦截，扩展网络能力。
 | 原文链接：http://wiki.8ai71b.asia/arts/429185.Doc

原标题：部署实践：告警收敛避免告警风暴配置
简介：golang 分表跨表 join 查询处理方案，分表后跨分片关联查询解决方案，业务层聚合代替数据库 join。
 | 原文链接：http://wiki.8ai71b.asia/arts/897096.Doc

原标题：golang 系统设计压测工具 wrk 使用实操
简介：golang errors.Is errors.As 错误判断，判断是否为指定错误类型，提取自定义错误信息，错误处理进阶。
 | 原文链接：http://wiki.8ai71b.asia/arts/958207.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：浮点计算精度错误处理方案，讲解浮点数计算精度丢失问题，使用合适数据类型，规避金额计算出错。
 | 原文链接：http://wiki.8ai71b.asia/arts/682471.Doc

原标题：nodejs 事件循环机制完整讲解
简介：代码格式化工具团队统一风格，接入格式化工具，统一全团队代码书写风格，减少格式类 git 冲突。
 | 原文链接：http://wiki.8ai71b.asia/arts/164393.Doc

原标题：golang mock 单元测试编写技巧
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.8ai71b.asia/arts/043148.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：DNS TTL 配置域名切换生效，调整 DNS 解析 TTL，缩短缓存时间，域名变更后可以快速全网生效。
 | 原文链接：http://wiki.8ai71b.asia/arts/529586.Doc

原标题：Issue：系统fd快速上涨进程慢慢卡死
简介：Git LFS 大文件推送失败解决，配置 Git LFS，处理仓库大文件，解决大文件推送报错推送失败。
 | 原文链接：http://wiki.8ai71b.asia/arts/868716.Doc

原标题：安全复盘：环境变量密钥泄露风险与防护
简介：nodejs 进程间通信 IPC 实操，演示 Node.js 主进程子进程 IPC 通信，进程之间传递消息数据。
 | 原文链接：http://wiki.8ai71b.asia/arts/194914.Doc

原标题：Shell 脚本自动化命令编写
简介：golang wasm 性能优化与内存管理，wasm 内存分配释放，减少内存拷贝，优化浏览器端性能。
 | 原文链接：http://wiki.8ai71b.asia/arts/818494.Doc

原标题：开发记录：敏感数据加密存储解密业务实践
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://wiki.8ai71b.asia/arts/951767.Doc

原标题：Redis 大 key 拆分集群卡顿解决
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.8ai71b.asia/arts/530068.Doc

原标题：golang mysql exists in 性能对比
简介：分布式 ID 生成器高并发实现，实现高性能分布式 ID 生成器，适配高并发业务，生成全局唯一 ID。
 | 原文链接：http://wiki.8ai71b.asia/arts/756320.Doc

原标题：架构笔记：数据脱敏架构接入层与存储层方案
简介：限流窗口绕过漏洞修复方案，修复限流时间窗口漏洞，避免攻击者绕过限流规则，保障接口防护有效。
 | 原文链接：http://wiki.8ai71b.asia/arts/213695.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：eslint prettier 代码规范落地，配置 eslint 与 prettier，做代码检查格式化，统一前端团队代码风格。
 | 原文链接：http://wiki.8ai71b.asia/arts/852196.Doc

原标题：Security：密码存储哈希加盐最佳实践
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.8ai71b.asia/arts/895283.Doc

原标题：实战项目：数据导出Excel百万级大数据导出方案
简介：golang os 环境变量读取设置，os.Getenv os.Setenv os.Unsetenv 读写环境变量，环境变量多值处理。
 | 原文链接：http://wiki.8ai71b.asia/arts/385895.Doc

原标题：golang 系统设计回调签名校验防伪造实现
简介：内存泄漏定位分析完整流程，分享内存泄漏排查步骤，定位没有释放的对象，解决内存持续上涨问题。
 | 原文链接：http://wiki.8ai71b.asia/arts/016578.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：golang raw socket 底层网络报文收发，raw socket 收发原始网络报文，做网络抓包数据包处理。
 | 原文链接：http://wiki.8ai71b.asia/arts/948765.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://wiki.8ai71b.asia/arts/230088.Doc

原标题：golang 系统设计日志本地打印线上关闭调试信息
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://wiki.8ai71b.asia/arts/981514.Doc

原标题：Architecture：文件处理服务架构大文件内存规避
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.8ai71b.asia/arts/941064.Doc

原标题：OpenSource：大型仓库Git历史清理瘦身实操
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.8ai71b.asia/arts/643706.Doc

原标题：golang grafana 面板变量模板制作
简介：golang sqlx 原生 SQL 代码简化，sqlx 简化原生 SQL 结果映射结构体，兼顾性能与开发效率。
 | 原文链接：http://wiki.8ai71b.asia/arts/488497.Doc

原标题：golang 系统设计网关性能压测优化简单思路
简介：monorepo 项目多包管理最佳实践，monorepo 仓库管理多子包，统一版本管理，处理包之间互相依赖。
 | 原文链接：http://wiki.8ai71b.asia/arts/218206.Doc

原标题：golang 系统设计性能瓶颈定位完整方法论
简介：golang 内存 dump 线上堆快照采集，线上生成内存 dump 文件，线下分析，定位内存泄漏问题。
 | 原文链接：http://wiki.8ai71b.asia/arts/049027.Doc

原标题：Practice：实现业务操作日志记录中间件实践
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://wiki.8ai71b.asia/arts/045141.Doc

原标题：golang 系统设计分布式锁超时业务防死锁处理
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.8ai71b.asia/arts/784859.Doc

原标题：开源源码阅读拆解学习思路
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://wiki.8ai71b.asia/arts/598989.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.8ai71b.asia/arts/992895.Doc

原标题：部署实践：内网开发环境代理配置实践
简介：nodejs 项目 pm2 部署运维指南，使用 PM2 管理 Node 服务，进程守护、日志、重启，线上部署运维实操。
 | 原文链接：http://wiki.8ai71b.asia/arts/507063.Doc

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：golang redis 过期键监听回调，监听 key 过期事件，过期触发业务逻辑，实现过期自动处理业务场景。
 | 原文链接：http://wiki.8ai71b.asia/arts/228177.Doc

原标题：批量操作分批处理防止 OOM
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.8ai71b.asia/arts/212277.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://wiki.8ai71b.asia/arts/654566.Doc

原标题：golang 系统设计配置多环境隔离方案落地
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.8ai71b.asia/arts/445199.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.8ai71b.asia/arts/250824.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.8ai71b.asia/arts/900684.Doc

原标题：部署实践：多实例服务部署无状态改造
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.8ai71b.asia/arts/110840.Doc

四、架构设计｜Architecture
原标题：HelloEnv：多操作系统环境变量配置汇总
简介：golang 配置中心 apollo go 客户端，apollo go sdk 读取配置，配置变更自动热更新无需重启服务。
 | 原文链接：http://wiki.8ai71b.asia/arts/342221.Doc

原标题：效率笔记：Git高级命令日常开发高频使用汇总
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.8ai71b.asia/arts/386941.Doc

原标题：从零搭建简单CLI命令行工具
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.8ai71b.asia/arts/096671.Doc

原标题：golang 系统设计定时任务分片执行分布式思路
简介：Git 分支切换合并删除完整操作，实操分支全生命周期操作，包含切换、合并、删除，熟悉日常开发分支处理流程。
 | 原文链接：http://wiki.8ai71b.asia/arts/331466.Doc

原标题：新手指南：本地多版本环境共存配置
简介：Docker 容器时区错误修复方案，修复 Docker 容器内部时区偏差，解决容器内时间不对引发业务逻辑异常。
 | 原文链接：http://wiki.8ai71b.asia/arts/071437.Doc

原标题：golang 系统设计接口防刷 ip 限流实现
简介：golang make new 关键字使用区别，分清 new 与 make 适用类型，正确初始化切片 map 通道，杜绝 nil 引发 panic。
 | 原文链接：http://wiki.8ai71b.asia/arts/370368.Doc

原标题：实践：前后端时间格式统一规范落地实践
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://wiki.8ai71b.asia/arts/829674.Doc

原标题：golang 系统设计 monorepo 仓库管理方案
简介：golang 模板函数自定义拓展，自定义 template 模板函数，在 html 模板调用自定义逻辑处理数据。
 | 原文链接：http://wiki.8ai71b.asia/arts/904163.Doc

原标题：golang 参数校验业务接口处理
简介：golang go 优雅处理信号丢失场景，处理信号丢失、信号被忽略，保障程序可以正常接收终止信号。
 | 原文链接：http://wiki.8ai71b.asia/arts/752974.Doc

原标题：golang rsa 非对称加密签名验签
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.8ai71b.asia/arts/685688.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：react 状态管理方案选型对比，对比 Redux、Zustand 等 React 状态管理库，分析适用业务场景辅助选型。
 | 原文链接：http://wiki.8ai71b.asia/arts/965309.Doc

原标题：golang 大文件 http 下载服务
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.8ai71b.asia/arts/124045.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang systemd 信号与优雅退出配合，systemd 停止服务发送 SIGTERM，go 程序捕获信号优雅关闭。
 | 原文链接：http://wiki.8ai71b.asia/arts/068599.Doc

原标题：Hands‑on：本地模拟分布式锁失效场景测试
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://wiki.8ai71b.asia/arts/399907.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.8ai71b.asia/arts/714751.Doc

原标题：golang http grpc 全链路埋点示例
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.8ai71b.asia/arts/749244.Doc

原标题：golang http 服务性能优化调参
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.8ai71b.asia/arts/806058.Doc

原标题：安全复盘：定时任务权限过大风险管控
简介：golang elasticsearch 客户端 golang 实操，es 客户端文档增删改查，条件搜索聚合统计对接搜索引擎。
 | 原文链接：http://wiki.8ai71b.asia/arts/015115.Doc

?
