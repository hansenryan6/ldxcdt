最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计日志级别业务使用原则梳理
简介：序列化版本不一致解析失败，保证序列化对象版本对齐，修复版本不匹配导致对象反序列化失败。
 | 原文链接：http://wiki.7h0liu.asia/arts/490575.Doc

原标题：接口压测定位系统性能瓶颈
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.7h0liu.asia/arts/800696.Doc

原标题：快速入门消息通知简单实现方案
简介：看懂报错日志快速定位问题，讲解日志阅读方法，解析堆栈信息含义，学会从报错信息中定位代码出错位置。
 | 原文链接：http://wiki.7h0liu.asia/arts/649846.Doc

原标题：golang docker 部署 es 本地开发
简介：Git 标签版本标记发布管理，使用 Git 标签标记项目版本，打标签推送远程，用于版本发布、版本回溯。
 | 原文链接：http://wiki.7h0liu.asia/arts/722709.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://wiki.7h0liu.asia/arts/860229.Doc

原标题：API 大版本不兼容平滑迁移
简介：Nginx 丢失请求头配置修正，修复 Nginx 代理转发丢失请求头配置，保证上游服务拿到完整请求头信息。
 | 原文链接：http://wiki.7h0liu.asia/arts/677481.Doc

原标题：方案对比：轮询长轮询WebSocket推送架构选型
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.7h0liu.asia/arts/156805.Doc

原标题：Issue：连接池参数不合理，大量连接被耗尽
简介：golang net/http 超时全套配置，完整配置 Go HTTP 服务读写空闲超时，全方位防止请求挂住。
 | 原文链接：http://wiki.7h0liu.asia/arts/322881.Doc

原标题：记一次分库分表路由计算错误数据写入错误分片
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://wiki.7h0liu.asia/arts/091478.Doc

原标题：进程线程并发基础概念讲解
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.7h0liu.asia/arts/153117.Doc

原标题：优化实践：批量操作性能优化，减少数据库IO
简介：游标分页大数据查询性能提升，使用游标分页替代偏移分页，解决大数据 offset 分页性能越来越差问题。
 | 原文链接：http://wiki.7h0liu.asia/arts/424046.Doc

原标题：踩坑：重试逻辑未做幂等，重复生成业务数据
简介：golang go 项目工程目录布局标准，不同规模 go 项目目录结构，小型项目中型项目大型微服务项目布局。
 | 原文链接：http://wiki.7h0liu.asia/arts/787366.Doc

原标题：golang redis pipeline 批量操作
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.7h0liu.asia/arts/694639.Doc

原标题：架构笔记：冷热数据分离架构设计与迁移
简介：golang slice 切片底层原理与坑点，切片扩容、截取、底层数组共享，规避切片修改互相影响数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/857267.Doc

原标题：踩坑记录：分页逻辑错误造成数据重复输出
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://wiki.7h0liu.asia/arts/664167.Doc

原标题：golang 系统设计日志架构采集存储检索完整链路
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/372122.Doc

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang 僵尸进程处理 go 程序，正确等待子进程退出，避免产生僵尸进程，占用系统进程表。
 | 原文链接：http://wiki.7h0liu.asia/arts/755763.Doc

原标题：优化实践：异步改造同步接口提升吞吐能力
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.7h0liu.asia/arts/988370.Doc

原标题：golang 速率限制令牌桶实现
简介：并发数据覆盖加锁安全处理，多线程并发修改同一数据，增加锁机制，防止并发覆盖丢失更新数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/734770.Doc

原标题：架构笔记：任务调度系统架构设计与可靠性
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://wiki.7h0liu.asia/arts/455185.Doc

原标题：golang 系统设计集成测试环境准备清理实操
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.7h0liu.asia/arts/582336.Doc

原标题：方案对比：同步调用vs异步消息业务选型
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.7h0liu.asia/arts/018933.Doc

原标题：CI/CD 流水线自动构建部署落地
简介：golang 钉钉企业微信告警消息推送，go 调用企业微信钉钉接口，推送告警通知、业务消息。
 | 原文链接：http://wiki.7h0liu.asia/arts/798149.Doc

原标题：不必要字符转义关闭业务异常
简介：golang mongodb go 驱动实操教程，mongo‑go‑driver 操作 mongodb，文档增删改查聚合查询。
 | 原文链接：http://wiki.7h0liu.asia/arts/608135.Doc

原标题：Practice：实现请求ID透传全链路日志实践
简介：golang io.LimitReader 限制读取字节数，LimitReader 限制最大读取，防止读取超大数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/985039.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：nodejs 读取大文件 csv 处理方案，Node 流式读取超大 CSV 文件，逐行解析，避免一次性加载全部文件。
 | 原文链接：http://wiki.7h0liu.asia/arts/672646.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang rsa 非对称加密签名验签，RSA 非对称加密与签名验签，实现非对称安全通信。
 | 原文链接：http://wiki.7h0liu.asia/arts/499287.Doc

原标题：nodejs 信号处理优雅关闭服务
简介：golang 优雅处理 http 重定向逻辑，自定义控制 http 重定向跳转次数，防止无限重定向死循环。
 | 原文链接：http://wiki.7h0liu.asia/arts/971450.Doc

原标题：排错：前端打包chunk过大浏览器加载缓慢
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/348403.Doc

原标题：分布式 ID 生成器高并发实现
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.7h0liu.asia/arts/842681.Doc

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang gorm ORM 数据库操作，GORM 实操数据库 CRUD，模型定义，关联查询，简化 Go 数据库开发。
 | 原文链接：http://wiki.7h0liu.asia/arts/974799.Doc

原标题：热更新开发环境配置教程
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.7h0liu.asia/arts/928214.Doc

原标题：nodejs 日志轮转生产环境配置
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.7h0liu.asia/arts/353730.Doc

原标题：部署复盘：蓝绿发布实现零停机业务更新
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/195655.Doc

原标题：golang 系统设计联合索引设计避坑要点
简介：golang context 超时取消实战案例，使用 context 控制协程、http 请求超时，自动终止超时任务，避免协程无限阻塞。
 | 原文链接：http://wiki.7h0liu.asia/arts/317808.Doc

原标题：实战项目：GitHubAction自动测试构建实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.7h0liu.asia/arts/518727.Doc

原标题：简易日志收集集中管理方案
简介：golang 数据库连接耗尽排查思路，监控连接池状态，定位连接未归还，解决连接耗尽报错。
 | 原文链接：http://wiki.7h0liu.asia/arts/886056.Doc

原标题：Issue：文件编码混合GBKUTF‑8乱码随机出现
简介：缓存过期打散防止缓存雪崩，对缓存过期时间增加随机偏移，避免大量缓存同时失效引发缓存雪崩。
 | 原文链接：http://wiki.7h0liu.asia/arts/418229.Doc

原标题：golang excel 简单读写操作示例
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.7h0liu.asia/arts/352046.Doc

原标题：golang 系统设计单元测试 mock 外部依赖技巧
简介：golang 任务失败重试与死信队列，异步任务失败自动重试，超过重试次数进入死信队列人工处理。
 | 原文链接：http://wiki.7h0liu.asia/arts/752814.Doc


二、踩坑排错｜Troubleshooting
原标题：golang redis set 集合去重业务
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wiki.7h0liu.asia/arts/735688.Doc

原标题：golang 系统设计接口频率限制业务落地
简介：移动端适配 rem vw 方案对比，对比 rem 与 vw 移动端适配方案，分析优缺点，给出选型建议。
 | 原文链接：http://wiki.7h0liu.asia/arts/359847.Doc

原标题：golang github actions 多平台构建
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://wiki.7h0liu.asia/arts/431468.Doc

原标题：axios 二次封装请求拦截处理
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.7h0liu.asia/arts/913346.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：golang gorm 预加载关联查询优化，GORM 预加载关联数据，避免 N+1 查询问题，提升数据库查询性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/911528.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/890364.Doc

原标题：golang 系统设计第三方接口调用封装思路
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/271412.Doc

原标题：静态博客部署 GitHub Pages 教程
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/801661.Doc

原标题：golang 优雅关闭 grpc 服务示例
简介：golang redis list 队列简易消息队列，利用 Redis List 实现简易队列，完成任务入队消费基础能力。
 | 原文链接：http://wiki.7h0liu.asia/arts/978583.Doc

原标题：性能复盘：网络IO优化减少接口等待时间
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://wiki.7h0liu.asia/arts/970605.Doc

原标题：Performance：JSON序列化性能优化实践
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.7h0liu.asia/arts/995621.Doc

原标题：golang 系统设计配置敏感信息加密存储方案
简介：项目构建脚本编译打包解析，解读项目构建脚本，理清编译、压缩、资源复制流程，理解打包后产物如何生成。
 | 原文链接：http://wiki.7h0liu.asia/arts/236365.Doc

原标题：Debug：表单自动转义特殊字符业务逻辑出错
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://wiki.7h0liu.asia/arts/807684.Doc

原标题：golang 系统设计数据库慢请求排查流程
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.7h0liu.asia/arts/009590.Doc

原标题：避坑：定时任务重复执行带来业务脏数据
简介：时间精度统一业务判断修复，统一业务使用时间戳精度，毫秒秒区分清楚，修复时间判断逻辑错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/311391.Doc

原标题：golang 系统设计技术方案评审关注点清单参考
简介：golang 响应 body 流式返回大数据，http 流式输出数据，边生成边返回，无需在内存组装完整返回结果。
 | 原文链接：http://wiki.7h0liu.asia/arts/007778.Doc

原标题：从零搭建简单的身份登录模拟示例
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://wiki.7h0liu.asia/arts/180784.Doc

原标题：Hands‑on：编写GitLabCI配置自动测试部署
简介：golang io.MultiReader MultiWriter 拼接流，多个 reader 拼接，多 writer 同时写入一份数据。
 | 原文链接：http://wiki.7h0liu.asia/arts/205845.Doc

原标题：Practice：模拟第三方接口超时服务降级验证
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.7h0liu.asia/arts/670330.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://wiki.7h0liu.asia/arts/619262.Doc

原标题：依赖安装失败全方位排错
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.7h0liu.asia/arts/006604.Doc

原标题：数据库分表路由写入分片修正
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://wiki.7h0liu.asia/arts/436707.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：SSH 密钥配置 GitHub 免密登录，分步生成配置 SSH 密钥，实现 GitHub 免密推送拉取，免去重复输入账号密码的麻烦。
 | 原文链接：http://wiki.7h0liu.asia/arts/691851.Doc

原标题：API 接口调试与异常处理实战
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://wiki.7h0liu.asia/arts/697362.Doc

原标题：GitHub 项目提交推送完整流程讲解
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.7h0liu.asia/arts/715885.Doc

原标题：golang 系统设计缓存基准测试对比方案
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.7h0liu.asia/arts/935185.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：日志切割配置防止日志丢失，配置日志切割轮转策略，日志按大小时间切割，防止日志文件丢失。
 | 原文链接：http://wiki.7h0liu.asia/arts/220852.Doc

原标题：实战项目：HTTPS本地自签名证书配置实践
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://wiki.7h0liu.asia/arts/043495.Doc

原标题：golang 系统设计 tcp keepalive 参数调优实践
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/840779.Doc

原标题：踩坑记录：乐观锁版本号处理不当更新失败
简介：golang 数据库连接池参数调优详解，最大连接空闲连接最大生命周期，结合业务合理配置避免资源浪费。
 | 原文链接：http://wiki.7h0liu.asia/arts/074121.Doc

原标题：golang redis pipeline 原子性说明
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://wiki.7h0liu.asia/arts/459588.Doc

原标题：golang 协程泄露问题排查方法
简介：golang fasthttp 服务开发完整示例，fasthttp 搭建 http 服务，路由、参数读取、响应返回完整业务。
 | 原文链接：http://wiki.7h0liu.asia/arts/196586.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：GC 垃圾回收优化降低 CPU 占用，调整 GC 参数，优化对象创建销毁，降低垃圾回收带来 CPU 开销。
 | 原文链接：http://wiki.7h0liu.asia/arts/194722.Doc

原标题：Git 分支管理多人协作实战教程
简介：WebSocket 断线重连稳定优化，增加 WebSocket 断线自动重连逻辑，处理网络抖动，维持长连接稳定。
 | 原文链接：http://wiki.7h0liu.asia/arts/312188.Doc

原标题：Hands‑on：手写简单RPC框架基础通信版本
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://wiki.7h0liu.asia/arts/949917.Doc

原标题：golang 重试退避机制代码实现
简介：Dockerfile 编写容器打包实战，讲解 Dockerfile 指令含义，编写镜像构建脚本，将本地项目打包成可分发容器镜像。
 | 原文链接：http://wiki.7h0liu.asia/arts/626444.Doc

原标题：golang 系统设计告警分级 p0‑p3 定义处理流程
简介：前端打包分包加载提速方案，前端打包做代码分包，拆分大 bundle，页面按需加载，提升首屏加载速度。
 | 原文链接：http://wiki.7h0liu.asia/arts/222823.Doc

原标题：golang 系统设计定时任务失败重试告警实现
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://wiki.7h0liu.asia/arts/939241.Doc

原标题：golang cron 定时任务防并发执行
简介：调试工具断点调试变量查看技巧，演示断点设置、变量监视、调用栈查看，借助调试工具高效排查业务逻辑错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/054878.Doc

原标题：复盘总结：技术方案文档模板架构设计文档
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://wiki.7h0liu.asia/arts/514230.Doc

三、实战开发｜Practice
原标题：golang 结构体 json 序列化坑点
简介：golang fuzz corpus 语料库使用，fuzz 语料存储历史输入，回归测试，持续复现曾经触发 bug 输入。
 | 原文链接：http://wiki.7h0liu.asia/arts/045753.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：golang embed 目录读取文件列表，embed 嵌入整个目录，读取目录下全部文件，做静态资源服务。
 | 原文链接：http://wiki.7h0liu.asia/arts/817766.Doc

原标题：golang kafka 消费者偏移量管理
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.7h0liu.asia/arts/183425.Doc

原标题：golang 系统设计分布式任务调度
简介：golang go list 双向链表使用，container/list 双向链表，频繁增删节点业务场景使用。
 | 原文链接：http://wiki.7h0liu.asia/arts/371834.Doc

原标题：零基础理解前后端简单交互流程
简介：golang go 并发模式 errgroup 使用，errgroup 结合 context，协程组，任意协程出错整体取消任务。
 | 原文链接：http://wiki.7h0liu.asia/arts/816222.Doc

原标题：golang 系统设计压测环境隔离避免影响生产
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://wiki.7h0liu.asia/arts/732251.Doc

原标题：golang 系统设计 rest 版本管理几种方案对比
简介：golang panic 崩溃日志完整收集，捕获所有 panic，打印堆栈，记录日志，方便定位崩溃根源。
 | 原文链接：http://wiki.7h0liu.asia/arts/603098.Doc

原标题：golang k8s 网络策略网络隔离设置
简介：程序信号中断退出处理逻辑，捕获系统中断信号，执行资源释放、关闭连接，实现程序优雅退出。
 | 原文链接：http://wiki.7h0liu.asia/arts/536064.Doc

原标题：golang 系统设计测试环境预发环境生产环境隔离
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.7h0liu.asia/arts/182069.Doc

原标题：全局时间标准统一逻辑错乱修复
简介：golang go‑zero 缓存自动击穿防护，go‑zero 缓存组件自带缓存击穿防护，减少缓存层故障。
 | 原文链接：http://wiki.7h0liu.asia/arts/863990.Doc

原标题：数据库读写分离性能优化
简介：前端大文件分片上传完整方案，前端分片切割大文件，配合后端分片接口，实现稳定大文件上传。
 | 原文链接：http://wiki.7h0liu.asia/arts/721863.Doc

原标题：Debug：表单提交特殊字符造成接口解析失败
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.7h0liu.asia/arts/968590.Doc

原标题：OpenSource：开源项目贡献者协作流程规范
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://wiki.7h0liu.asia/arts/102653.Doc

原标题：Nginx 请求头大小上限调整
简介：Git commit 钩子提交规范校验，配置 Git 提交钩子，提交代码自动校验提交信息格式，规范提交记录。
 | 原文链接：http://wiki.7h0liu.asia/arts/169948.Doc

原标题：Issue：本地数据库与线上数据库排序规则差异
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://wiki.7h0liu.asia/arts/711084.Doc

原标题：golang 系统设计代码评审关注点 checklist 清单
简介：golang 文件上传下载接口开发，Go 开发文件上传下载接口，校验文件，处理文件读写存储逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/208070.Doc

原标题：golang docker 部署 kafka 本地调试
简介：RPC 接口字段增减兼容处理，RPC 接口新增删除字段做好向前兼容，老版本服务不会解析报错崩溃。
 | 原文链接：http://wiki.7h0liu.asia/arts/875684.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang go decimal 定点小数金额计算，decimal 库处理金额，规避 float64 精度丢失，财务计算。
 | 原文链接：http://wiki.7h0liu.asia/arts/833084.Doc

原标题：优化实践：接口返回字段裁剪减少报文大小
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://wiki.7h0liu.asia/arts/718157.Doc

原标题：golang 系统设计消息幂等消费去重实现方案
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://wiki.7h0liu.asia/arts/977308.Doc

原标题：golang k8s configmap secret 配置
简介：WebSocket 双向通信 demo 开发，搭建简易 WebSocket 服务，实现客户端服务端双向消息推送，理解实时通信原理。
 | 原文链接：http://wiki.7h0liu.asia/arts/517583.Doc

原标题：golang 内存缓存简单实现方案
简介：golang httptest 模拟外部 http 服务，httptest.NewServer 模拟第三方 http 服务，单元测试 mock 外部接口。
 | 原文链接：http://wiki.7h0liu.asia/arts/371662.Doc

原标题：安全复盘：OAuth2授权流程安全坑点汇总
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://wiki.7h0liu.asia/arts/237998.Doc

原标题：入门实践：使用模板快速生成项目脚手架
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.7h0liu.asia/arts/602124.Doc

原标题：新手向：开源项目依赖安装失败排查
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://wiki.7h0liu.asia/arts/523257.Doc

原标题：项目实践：本地模拟缓存失效风暴验证防护
简介：golang 雪花 id 重复问题排查，排查雪花算法 ID 重复问题，时钟回拨、机器 ID 冲突，给出修复方案。
 | 原文链接：http://wiki.7h0liu.asia/arts/196857.Doc

原标题：死信队列处理消息阻塞业务
简介：hosts 配置本地回环访问修复，修改 hosts 配置，修复 127.0.0.1 解析异常，本地服务访问失败问题。
 | 原文链接：http://wiki.7h0liu.asia/arts/496510.Doc

原标题：多操作系统开发兼容处理
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://wiki.7h0liu.asia/arts/937666.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang testing.TB Helper 标记辅助函数，t.Helper 标记辅助函数，报错打印真实调用位置。
 | 原文链接：http://wiki.7h0liu.asia/arts/289222.Doc

原标题：复盘总结：分布式系统常见坑点汇总清单
简介：golang 互斥锁读写锁并发安全，互斥锁读写锁实操，保护共享变量，解决多协程并发读写数据竞争。
 | 原文链接：http://wiki.7h0liu.asia/arts/344650.Doc

原标题：Dockerfile 编写容器打包实战
简介：golang tcp_NODELAY 关闭延迟发送，设置 tcp_NODELAY，关闭 Nagle 算法，降低小包请求延迟。
 | 原文链接：http://wiki.7h0liu.asia/arts/657035.Doc

原标题：设计思考：系统限流熔断降级完整防护体系
简介：golang os 打开文件 O_APPEND O_CREATE 标志，OpenFile 标志位，控制文件创建追加截断行为。
 | 原文链接：http://wiki.7h0liu.asia/arts/336978.Doc

原标题：项目目录结构规范化最佳实践
简介：WSL 文件权限访问异常修复，处理 WSL 环境文件权限错乱，调整权限配置，实现文件正常读写访问。
 | 原文链接：http://wiki.7h0liu.asia/arts/299259.Doc

原标题：环境变量不生效问题修复
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://wiki.7h0liu.asia/arts/669176.Doc

原标题：后端大文件分片上传接口开发
简介：nodejs 数据库连接池配置调优，调优 Node 数据库连接池参数，平衡性能与资源占用，避免连接耗尽。
 | 原文链接：http://wiki.7h0liu.asia/arts/979507.Doc

原标题：数据库事务 ACID 原理讲解
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/475736.Doc

原标题：golang 系统设计缓存过期时间设置原则梳理
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://wiki.7h0liu.asia/arts/972803.Doc

原标题：入门实践：Git分支创建切换合并完整演示
简介：golang go mod exclude 排除依赖版本，exclude 排除有问题依赖版本，规避有 bug 的第三方包。
 | 原文链接：http://wiki.7h0liu.asia/arts/058730.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.7h0liu.asia/arts/382406.Doc

原标题：踩坑：Docker容器内时区不一致引发的时间BUG
简介：golang 设置 net.Conn 读写超时，每次读写设置超时，防止连接永久阻塞挂起不返回。
 | 原文链接：http://wiki.7h0liu.asia/arts/309218.Doc

四、架构设计｜Architecture
原标题：架构复盘：网关层、应用层、数据库层层限流架构
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://wiki.7h0liu.asia/arts/788352.Doc

原标题：RPC 报文大小上限调优大请求
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.7h0liu.asia/arts/909507.Doc

原标题：方案对比：几种分布式限流算法架构适用性
简介：浏览器缓存强制刷新方案，设置 HTTP 缓存头，处理浏览器缓存旧静态资源，让用户加载更新后的页面。
 | 原文链接：http://wiki.7h0liu.asia/arts/641796.Doc

原标题：nodejs 进程间通信 IPC 实操
简介：nodejs 定时任务生产环境避坑，Node 定时任务线上踩坑汇总，集群重复执行、任务阻塞等问题解决方案。
 | 原文链接：http://wiki.7h0liu.asia/arts/482404.Doc

原标题：记一次限流组件误配置把正常用户拦截
简介：DNS 解析异常第三方调用故障，排查 DNS 解析故障，修复域名解析，恢复第三方接口网络调用。
 | 原文链接：http://wiki.7h0liu.asia/arts/381096.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang channel 关闭规则与坑点，关闭已经关闭 channel 会 panic，判断 channel 是否关闭正确写法。
 | 原文链接：http://wiki.7h0liu.asia/arts/128130.Doc

原标题：vue3 组合式 API 业务开发实战
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://wiki.7h0liu.asia/arts/595530.Doc

原标题：golang k8s 资源请求限制配置
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://wiki.7h0liu.asia/arts/833229.Doc

原标题：前端大文件分片上传完整方案
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.7h0liu.asia/arts/334282.Doc

原标题：golang mongodb 事务多文档使用
简介：golang tls 证书加载配置 https 服务，加载证书密钥，搭建 golang https 服务，配置 tls 版本安全策略。
 | 原文链接：http://wiki.7h0liu.asia/arts/675887.Doc

原标题：RPC 报文大小上限调优大请求
简介：CPU 亲和性配置负载均衡调度，配置进程 CPU 亲和，均衡利用多核 CPU，优化程序调度性能。
 | 原文链接：http://wiki.7h0liu.asia/arts/719837.Doc

原标题：golang 系统设计 issue 模板 bug 反馈模板
简介：配置外部化线上部署防错误，把配置从代码剥离，外部传入配置，修改配置不需要重新打包构建。
 | 原文链接：http://wiki.7h0liu.asia/arts/699583.Doc

原标题：Troubleshooting：K8sPodOOMKilled完整排查流程
简介：定时任务重复执行分布式锁，使用分布式锁控制定时任务，保证集群环境定时任务只会执行一次。
 | 原文链接：http://wiki.7h0liu.asia/arts/520021.Doc

原标题：手写简易 RPC 服务通信原型
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://wiki.7h0liu.asia/arts/772530.Doc

原标题：快速入门容器基础概念，理解镜像与容器
简介：golang gin 路由动态注册实现方案，根据配置动态注册接口路由，无需硬编码路由，适配动态业务模块。
 | 原文链接：http://wiki.7h0liu.asia/arts/831130.Doc

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：项目目录结构规范化最佳实践，梳理源码、配置、静态资源目录划分，规范项目布局，提升代码可读性和可维护性。
 | 原文链接：http://wiki.7h0liu.asia/arts/812327.Doc

原标题：HelloCI：理解持续集成基础工作流程
简介：前端错误监控上报系统搭建，搭建前端错误监控，捕获页面 JS 错误，上报后端，快速发现线上页面 bug。
 | 原文链接：http://wiki.7h0liu.asia/arts/887137.Doc

原标题：golang 系统设计分布式事务业务选型决策思路
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.7h0liu.asia/arts/053363.Doc

?
