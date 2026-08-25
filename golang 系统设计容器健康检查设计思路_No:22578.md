最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计容器健康检查设计思路
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://SZJn.yiygjdp.asia/

原标题：优化实践：多级缓存减少下游服务调用压力
简介：静态站点自动部署发布方案，配置流水线，代码更新自动构建静态站点并且部署上线，简化发布。
 | 原文链接：http://HljD.yiygjdp.asia/

原标题：记一次第三方SDK版本兼容引发线上故障
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://hBf9.yiygjdp.asia/

原标题：golang 系统设计 id 生成器选型对比
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://d7b5.yiygjdp.asia/

原标题：golang 表单文件大小限制配置
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://Z3X1.yiygjdp.asia/

原标题：CI/CD 流水线自动构建部署落地
简介：任务执行锁防止并发重复调度，增加任务执行锁，多实例环境，防止同一个定时任务并发多次运行。
 | 原文链接：http://VzTx.yiygjdp.asia/

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://QuOs.yiygjdp.asia/

原标题：golang 系统设计定时任务调度时间校准要点
简介：数据库分表路由写入分片修正，修复分表路由逻辑，保证数据写入正确分片，不会出现数据丢失错乱。
 | 原文链接：http://MqKo.yiygjdp.asia/

原标题：golang k8s 资源请求限制配置
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://5MQ4.yiygjdp.asia/

原标题：golang redis 事务 multi exec 使用
简介：golang go mod vendor 本地依赖导出，导出 vendor 目录，离线环境编译项目，无需访问外网拉依赖。
 | 原文链接：http://O2pw.yiygjdp.asia/

原标题：实战：搭建本地对象存储兼容S3协议demo
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://gAe8.yiygjdp.asia/

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang context.WithTimeout 超时上下文，WithTimeout 设置超时时间，超时自动 cancel 释放协程。
 | 原文链接：http://c64Y.yiygjdp.asia/

原标题：入门实践：简单批量处理脚本编写
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://2W0U.yiygjdp.asia/

原标题：避坑：ORM框架隐式查询产生大量慢SQL
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://ySwQ.yiygjdp.asia/

原标题：golang k8s configmap secret 配置
简介：golang 分布式锁 redis 实现，基于 Redis 实现 Go 分布式锁，解决多实例并发竞争资源问题。
 | 原文链接：http://uOsM.yiygjdp.asia/

原标题：坑点：限流计数器重置时机错误，绕过限流规则
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://qKoI.yiygjdp.asia/

原标题：golang 系统设计网络 io 模型 epoll 原理讲解
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://mGkE.yiygjdp.asia/

原标题：Issue：WSL2内存持续暴涨不自动释放
简介：golang 日志脱敏敏感字段过滤，日志打印自动脱敏敏感字段，避免日志输出手机号身份证泄露隐私。
 | 原文链接：http://iCgA.yiygjdp.asia/

原标题：实践：分布式事务本地模拟验证实践
简介：golang sync.WaitGroup 协程等待控制，WaitGroup 控制一组协程等待全部执行完成，完成批量协程任务调度。
 | 原文链接：http://e8c6.yiygjdp.asia/

原标题：前端下载导出文件功能实现
简介：golang go 调度器 GMP 模型通俗讲解，拆解 GMP 模型，理解 goroutine M P 调度原理，看懂调度状态。
 | 原文链接：http://a4Y2.yiygjdp.asia/

原标题：Practice：实现异步回调处理通用组件封装
简介：golang gin 参数绑定 query form json，掌握 Gin 多种参数绑定方式，适配不同请求格式参数读取。
 | 原文链接：http://W0Uy.yiygjdp.asia/

原标题：实战：Redis过期回调实现业务事件通知实践
简介：golang 配置热更新不重启服务，实现配置热加载，监听配置变更，更新内存配置，无需重启服务实例。
 | 原文链接：http://SQuO.yiygjdp.asia/

原标题：方案对比：几种分布式限流算法架构适用性
简介：gitignore 文件编写过滤规则，讲解 gitignore 语法，编写过滤配置，忽略缓存、编译产物、密钥文件，保持仓库整洁。
 | 原文链接：http://sMqK.yiygjdp.asia/

原标题：Practice：实现业务唯一流水号生成组件实践
简介：golang https 客户端跳过证书校验，开发测试环境跳过 tls 证书校验，仅用于内网测试禁止生产使用。
 | 原文链接：http://oImG.yiygjdp.asia/

原标题：安全笔记：请求头伪造IP漏洞防护
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://kEiC.yiygjdp.asia/

原标题：golang 系统设计雪花算法 id 原理剖析
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://gAe8.yiygjdp.asia/

原标题：对象存储上传下载权限实操
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://c6a4.yiygjdp.asia/

原标题：Security：Web常见安全漏洞原理与修复清单
简介：正则表达式优化 CPU 占满问题，优化正则表达式写法，避免回溯，防止正则运算 CPU 占用 100%。
 | 原文链接：http://Y2Vz.yiygjdp.asia/

原标题：架构复盘：多实例部署业务状态无状态改造
简介：golang sort 搜索查找切片元素，sort.Search 二分查找有序切片，快速定位元素索引位置。
 | 原文链接：http://TxRv.yiygjdp.asia/

原标题：记一次分布式锁失效引发的数据错乱问题
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://PtNr.yiygjdp.asia/

原标题：golang go test 覆盖率统计实操
简介：golang channel 缓冲无缓冲区别，缓冲 channel 与无缓冲 channel，底层行为差异业务选型参考。
 | 原文链接：http://LpJn.yiygjdp.asia/

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://lFjD.yiygjdp.asia/

原标题：golang 系统设计 tcc 事务简单原理业务示例
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://hBf9.yiygjdp.asia/

原标题：golang csv 读写批量数据处理
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://d7b5.yiygjdp.asia/

原标题：golang 系统设计 http3 quic 简单原理了解
简介：golang ip2regionIP 地址解析实战，集成 ip2region 库，根据 IP 解析归属地城市，实现 IP 地域解析。
 | 原文链接：http://Z3X1.yiygjdp.asia/

原标题：数据库连接池参数调优
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://VzTx.yiygjdp.asia/

原标题：排错：CI流水线构建失败，日志无明确报错
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://RvPt.yiygjdp.asia/

原标题：golang 系统设计日志检索排查线上问题实操技巧
简介：golang 探测文件真实内容类型，读取文件头部字节判断真实文件格式，规避后缀伪造。
 | 原文链接：http://NrLp.yiygjdp.asia/

原标题：golang 系统设计线上日志快速检索技巧
简介：golang gorm group by 分组统计，GORM 分组聚合统计，实现 count sum 等统计查询，快速完成统计业务。
 | 原文链接：http://JnHl.yiygjdp.asia/

原标题：golang 系统设计分库分表中间件思路
简介：golang context.WithCancel 手动取消上下文，WithCancel 生成可取消 ctx，手动调用 cancel 触发取消。
 | 原文链接：http://FjDh.yiygjdp.asia/


二、踩坑排错｜Troubleshooting
原标题：Practice：简易限流器分布式版本Redis实现
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://Bf9d.yiygjdp.asia/

原标题：golang 系统设计异步化改造业务流程思路
简介：golang go 二进制安全 strip 减小体积，strip 剥离二进制调试符号，缩小程序二进制文件体积。
 | 原文链接：http://b5Z3.yiygjdp.asia/

原标题：golang 系统设计 mq 消息顺序性保证思路
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://X1Vz.yiygjdp.asia/

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://TxRv.yiygjdp.asia/

原标题：排错：CI流水线构建失败，日志无明确报错
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://PtNr.yiygjdp.asia/

原标题：golang 系统设计基准测试 benchmark 编写
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://LpJn.yiygjdp.asia/

原标题：WebSocket 双向通信 demo 开发
简介：nodejs 中间件模式原理剖析，拆解 Node 中间件设计模式，理解请求逐层处理流转的底层原理。
 | 原文链接：http://HlFj.yiygjdp.asia/

原标题：安全复盘：消息队列未授权访问安全加固
简介：开发代理服务网络限制解决，搭建本地代理服务，解决开发环境网络访问受限，实现外部接口正常调用。
 | 原文链接：http://DhBf.yiygjdp.asia/

原标题：golang 系统设计本地缓存更新失效方案实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://9d7a.yiygjdp.asia/

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang go‑zero api 接口开发与路由，go‑zero 编写 api 定义文件，生成代码开发 http 接口。
 | 原文链接：http://4Y2W.yiygjdp.asia/

原标题：golang zap 日志按日期切割方案
简介：golang 字符编码转换 go 处理，iconv‑go 做编码转换 gbk utf8 互转，处理老旧系统 gbk 编码数据。
 | 原文链接：http://0Uyw.yiygjdp.asia/

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang 项目 makefile 脚本编写，编写 Makefile 脚本，封装编译、测试、构建命令，简化项目操作。
 | 原文链接：http://QuOs.yiygjdp.asia/

原标题：踩坑：环境变量未生效导致线上配置错乱
简介：golang kitex 字节微服务框架入门，kitex 开发 rpc 微服务，代码生成，服务注册发现完整流程。
 | 原文链接：http://MqKo.yiygjdp.asia/

原标题：golang k8s 基础概念 pod deployment
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://ImGk.yiygjdp.asia/

原标题：Debug：Websocket频繁断开重连根因分析
简介：golang GC 频繁 STW 停顿优化，减少小对象分配，调整 GOGC，降低 GC 停顿对接口延迟影响。
 | 原文链接：http://EiCg.yiygjdp.asia/

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://Ae8c.yiygjdp.asia/

原标题：调优方案：gzip压缩开启降低网络传输体积
简介：golang tcp 连接泄露排查定位，netstat 查看连接状态，找出未正常关闭连接，定位连接泄漏代码。
 | 原文链接：http://6a4Y.yiygjdp.asia/

原标题：golang 系统设计分布式锁可重入实现思路
简介：前端下载导出文件功能实现，前端实现文件流下载导出，处理异常，适配浏览器不同下载行为。
 | 原文链接：http://2W0U.yiygjdp.asia/

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang 消息队列实现事务消息方案，基于 kafka 实现事务消息，业务执行成功才对外投递消息。
 | 原文链接：http://ySwQ.yiygjdp.asia/

原标题：效率笔记：VSCode插件集合后端前端开发效率
简介：nestjs 全局返回格式统一处理，Nest 全局拦截器统一包装接口返回数据，对外输出标准化响应格式。
 | 原文链接：http://uOsM.yiygjdp.asia/

原标题：golang docker 网络模式桥接 host
简介：请求重试组件退避策略实现，封装重试组件，实现指数退避策略，避免大量请求同时重试压垮下游。
 | 原文链接：http://qKIm.yiygjdp.asia/

原标题：golang 系统设计 json 解析性能优化实操
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://GkEi.yiygjdp.asia/

原标题：环境变量不生效问题修复
简介：golang http 文件下载断点续传服务，服务端实现断点续传，支持大文件分段下载，提升大文件下载稳定性。
 | 原文链接：http://CgAe.yiygjdp.asia/

原标题：项目实践：MySQL读写分离本地模拟实践
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://8c6a.yiygjdp.asia/

原标题：Architecture：静态配置与动态配置架构分离
简介：文件锁正确使用避免死锁，合理使用文件锁，控制多进程访问同一个文件，规避文件锁死锁现象。
 | 原文链接：http://4Y2W.yiygjdp.asia/

原标题：golang nginx 反向代理 go 服务配置
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://0UyS.yiygjdp.asia/

原标题：系统时间同步定时任务偏移
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://wQuO.yiygjdp.asia/

原标题：Hands‑on：简易反向代理中间件实现
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://sMqK.yiygjdp.asia/

原标题：实践：接口参数自动校验业务落地实践
简介：前后端会话登录状态持久化，实现登录状态持久存储，重启服务登录状态不丢失，保障会话稳定性。
 | 原文链接：http://oImG.yiygjdp.asia/

原标题：golang 错误处理最佳实践汇总
简介：内网测试服务搭建团队调试，配置本地服务内网可访问，团队成员能够访问调试，方便前后端联调与内部演示。
 | 原文链接：http://kEiC.yiygjdp.asia/

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang go 自定义错误类型实现，自定义 error 结构体，携带错误码、堆栈信息，统一业务错误。
 | 原文链接：http://gd7b.yiygjdp.asia/

原标题：golang 系统设计消息可靠性投递实现
简介：golang gin 框架接口开发实战，Gin 框架搭建 HTTP 服务，开发增删改查接口，快速完成后端接口开发。
 | 原文链接：http://5Z3X.yiygjdp.asia/

原标题：golang 系统设计字符串拼接性能优化技巧
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://1VzT.yiygjdp.asia/

原标题：golang 系统设计依赖漏洞扫描修复流程
简介：大事务拆分防止连接池耗尽，将执行时间很长的大事务拆分为小事务，减少事务占用连接时长。
 | 原文链接：http://xRvP.yiygjdp.asia/

原标题：golang 系统设计限流熔断降级组合使用
简介：golang 微服务网关简易实现，http 反向代理、路由匹配、鉴权限流，理解网关核心原理。
 | 原文链接：http://tNrL.yiygjdp.asia/

原标题：日志敏感信息脱敏泄露防护
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://pJnH.yiygjdp.asia/

原标题：前端下载导出文件功能实现
简介：golang fasthttp 高性能 http 库使用，fasthttp 高性能 http 实现，适合超高 QPS 场景，对比 net/http 差异。
 | 原文链接：http://lFjD.yiygjdp.asia/

原标题：golang docker 部署 es 本地开发
简介：版本升级服务启动失败处理，版本更新之后服务无法启动，对比新旧版本配置、依赖差异，完成故障修复。
 | 原文链接：http://hBf9.yiygjdp.asia/

原标题：golang 简单爬虫请求防封禁
简介：golang delve 远程调试 go 线上程序，delve 远程调试，线上环境附加进程调试排查线上 bug。
 | 原文链接：http://d7b5.yiygjdp.asia/

原标题：OpenSource：开源项目README高质量编写指南
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://Z3X1.yiygjdp.asia/

三、实战开发｜Practice
原标题：golang 系统设计回调重试幂等完整处理
简介：golang yaml 解析配置加载实操，Go 解析 YAML 配置文件，读取配置参数，驱动业务运行。
 | 原文链接：http://zTxR.yiygjdp.asia/

原标题：golang consul 服务发现简单示例
简介：前端静态缓存更新生效处理，修改静态资源版本标识，处理浏览器强缓存，让更新资源生效。
 | 原文链接：http://vPtN.yiygjdp.asia/

原标题：开发记录：日志脱敏防止敏感信息输出实践
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://rLpJ.yiygjdp.asia/

原标题：golang mysql 读写分离简单实现
简介：HTTP 状态码请求头完整梳理，汇总常用 HTTP 状态码与请求头含义，帮助快速看懂网络请求，排查接口通信问题。
 | 原文链接：http://nHlF.yiygjdp.asia/

原标题：安全笔记：CORS跨域配置错误安全风险
简介：golang excel 生成导出高性能方案，excelize 流式生成 excel，百万行数据导出，规避内存溢出。
 | 原文链接：http://jDhB.yiygjdp.asia/

原标题：坑点：版本号语义化理解错误依赖版本错乱
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://f9d7.yiygjdp.asia/

原标题：开源实践：维护开源项目Issue管理经验总结
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://b5Z3.yiygjdp.asia/

原标题：设计思考：业务系统中什么时候不要用微服务
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://X1Vz.yiygjdp.asia/

原标题：Hands‑on：静态资源CDN缓存控制头配置实践
简介：ORM 隐式慢查询问题规避，识别 ORM 框架隐式查询，避免循环查询数据库，减少不必要慢 SQL 产生。
 | 原文链接：http://TxRv.yiygjdp.asia/

原标题：实践：前后端分离项目登录状态保持完整方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://PtNL.yiygjdp.asia/

原标题：实战：单元测试+集成测试完整项目落地实践
简介：golang http 服务优雅关闭完整示例，接收终止信号，停止接收新请求，等待现有请求处理完毕后退出服务。
 | 原文链接：http://pJnH.yiygjdp.asia/

原标题：实战项目：CLI批量文件处理工具开发全过程
简介：golang udp 服务端客户端开发示例，golang 实现 UDP 服务收发数据包，实现 udp 协议通信程序。
 | 原文链接：http://lFiC.yiygjdp.asia/

原标题：服务健康检查告警监控体系
简介：golang 系统信号信号量处理，Go 处理系统各类信号，SIGINT、SIGTERM，实现程序可控退出。
 | 原文链接：http://gAe8.yiygjdp.asia/

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang http 中间件洋葱模型原理，理解 go http 中间件洋葱模型，请求响应流转顺序，编写自定义中间件。
 | 原文链接：http://c6a4.yiygjdp.asia/

原标题：JWT 令牌过期异常处理
简介：大事务拆分回滚日志暴涨解决，拆分大型数据库事务，减少回滚日志生成量，避免磁盘被回滚日志占满。
 | 原文链接：http://Y2W0.yiygjdp.asia/

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：端口占用释放资源重启服务，查找占用端口进程，结束占用进程，释放端口，让服务能够正常启动监听。
 | 原文链接：http://UySw.yiygjdp.asia/

原标题：nodejs 进程间通信 IPC 实操
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://QuOs.yiygjdp.asia/

原标题：golang 系统设计版本号语义化规范讲解
简介：后端分页查询逻辑代码实现，编写后端分页接口，处理页码、每页条数参数，优化大数据量查询返回结果。
 | 原文链接：http://MqKo.yiygjdp.asia/

原标题：跨平台 uniapp 多端开发实操
简介：静态博客部署 GitHub Pages 教程，将静态博客项目部署至 GitHub Pages，完成线上访问，快速搭建个人技术博客站点。
 | 原文链接：http://ImGk.yiygjdp.asia/

原标题：golang 结构体深拷贝几种实现
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://EiCA.yiygjdp.asia/

原标题：golang etcd watch 监听配置变更
简介：golang http 客户端连接泄漏排查，http client 未读取响应体导致连接无法复用，解决连接泄漏耗尽连接池。
 | 原文链接：http://e8c6.yiygjdp.asia/

原标题：开发复盘：超时参数统一治理线上服务实践
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://a4Y2.yiygjdp.asia/

原标题：golang k8s 监控 prometheus 部署
简介：golang benchmark 减少测试干扰，benchmark 执行循环 b.N，避免循环内部做非被测逻辑干扰结果。
 | 原文链接：http://W0Uy.yiygjdp.asia/

原标题：快速入门消息通知简单实现方案
简介：nodejs 全局异常捕获进程防护，捕获未捕获异常与 Promise 拒绝，尽量保护进程不因为异常直接退出。
 | 原文链接：http://SwQu.yiygjdp.asia/

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang pprof 线上采集性能数据，线上环境采集 pprof 性能样本，不用停机，分析线上性能问题。
 | 原文链接：http://OsMq.yiygjdp.asia/

原标题：开发复盘：大数据量分页避免offset性能问题
简介：golang go 运行时获取编译信息，程序内部读取编译时间 git 版本，接口输出程序版本信息。
 | 原文链接：http://KoIm.yiygjdp.asia/

原标题：新手指南：如何读懂开源项目报错日志
简介：golang staticcheck 静态代码分析，staticcheck 深度静态检查，发现代码错误、性能问题、风格问题。
 | 原文链接：http://GkEi.yiygjdp.asia/

原标题：golang redis 缓存更新策略讲解
简介：golang go 泛型使用避坑注意点，泛型与 interface 区别，泛型性能，什么时候适合使用泛型。
 | 原文链接：http://CgAe.yiygjdp.asia/

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 分库分表简单路由实现，简易分表路由逻辑实现，根据分片 key 计算分片位置，数据路由写入。
 | 原文链接：http://8c6a.yiygjdp.asia/

原标题：架构复盘：跨机房多活架构基础概念与代价
简介：服务器 Swap 关闭提升响应速度，关闭服务器 Swap 交换分区，避免内存交换磁盘拖慢程序响应性能。
 | 原文链接：http://4YW0.yiygjdp.asia/

原标题：golang 系统设计代码仓库权限管理方案
简介：golang socket 文件描述符继承重启，父进程传递 listener fd 给子进程，实现 go 程序零停机热重启。
 | 原文链接：http://UySw.yiygjdp.asia/

原标题：golang 系统设计 docker compose 本地开发环境搭建
简介：golang 正则表达式 Go 实操案例，正则匹配提取替换，处理手机号邮箱校验，规避正则回溯 CPU 暴涨。
 | 原文链接：http://QuOs.yiygjdp.asia/

原标题：golang 系统设计第三方 sdk 二次封装技巧
简介：系统文件描述符上限调大，调高操作系统文件描述符上限，解决高并发场景打开文件报错。
 | 原文链接：http://MqKn.yiygjdp.asia/

原标题：数值类型溢出错乱问题修复
简介：golang grpc 拦截器开发鉴权日志，开发 grpc 服务端拦截器，统一做鉴权、日志打印、异常捕获处理。
 | 原文链接：http://HlFj.yiygjdp.asia/

原标题：golang 系统设计代码仓库权限管理方案
简介：进程线程并发基础概念讲解，区分进程与线程，讲解调度逻辑，理解并发执行原理，为高并发业务开发打基础。
 | 原文链接：http://DhBf.yiygjdp.asia/

原标题：Troubleshoot：DNS解析异常导致第三方调用失败
简介：前端防抖节流高频事件处理，封装防抖节流工具，处理滚动、输入框输入等高频触发事件减少执行次数。
 | 原文链接：http://9d7b.yiygjdp.asia/

原标题：文件描述符优化进程卡死修复
简介：golang 容器健康检查接口开发，Go 开发 HTTP 健康接口，供容器编排工具探测实例存活状态。
 | 原文链接：http://5Z3X.yiygjdp.asia/

原标题：golang 系统设计内存高占用排查思路
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://1VzT.yiygjdp.asia/

原标题：golang 系统设计 changelog 变更日志维护
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://xRvP.yiygjdp.asia/

原标题：Architecture：中小型后端服务整体架构设计复盘
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://trLp.yiygjdp.asia/

四、架构设计｜Architecture
原标题：数据库连接及时关闭连接泄漏
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://JnHl.yiygjdp.asia/

原标题：golang 系统设计定时任务失败重试告警实现
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://FjDh.yiygjdp.asia/

原标题：golang 系统设计配置多环境本地开发适配方案
简介：日志输出规范防止磁盘爆满，控制日志输出量，配置日志切割轮转，避免日志文件无限增长占满磁盘。
 | 原文链接：http://Bf9d.yiygjdp.asia/

原标题：golang 系统设计序列化性能选型对比
简介：golang 接口限流中间件开发，Gin 开发限流中间件，接口层实现访问频率限制，防护接口流量。
 | 原文链接：http://7b5Z.yiygjdp.asia/

原标题：golang 系统设计异步化改造业务流程思路
简介：限流组件计数器令牌桶模式实现，实现计数器、令牌桶两种限流算法，封装可复用限流组件。
 | 原文链接：http://3X1V.yiygjdp.asia/

原标题：进程线程并发基础概念讲解
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://zTxR.yiygjdp.asia/

原标题：Docker Compose 一键搭建本地栈
简介：vue pinia 状态管理实战教程，Pinia 完整实战示例，实现状态定义修改，模块拆分替代 Vuex。
 | 原文链接：http://vPtN.yiygjdp.asia/

原标题：golang 系统设计令牌桶漏桶算法对比
简介：golang 单元测试 mock http 请求，mock HTTP 外部接口，单元测试不依赖外部网络，保证用例稳定运行。
 | 原文链接：http://rLpJ.yiygjdp.asia/

原标题：golang mysql innodb 事务隔离级别
简介：消息队列消费堆积扩容处理，消息大量堆积时，扩容消费实例，优化消费逻辑，加快消息处理速度。
 | 原文链接：http://nHlF.yiygjdp.asia/

原标题：安全实践：接口错误信息不要暴露内部细节
简介：定时任务周期调度 demo 开发，实现简单定时调度程序，按时间周期执行业务逻辑，理解定时任务运行机制。
 | 原文链接：http://DhBf.yiygjdp.asia/

原标题：golang gin 静态资源访问配置
简介：golang go 程序运行时动态修改配置，运行时热加载配置结构体，原子更新保证并发读取安全。
 | 原文链接：http://0UyS.yiygjdp.asia/

原标题：实战项目：WebSocket消息广播房间分组实践
简介：golang go 终端 pty 伪终端操作，pty 启动子进程，模拟终端交互，实现交互式命令调用。
 | 原文链接：http://2W0U.yiygjdp.asia/

原标题：Debug：异步任务堆积，服务响应越来越慢
简介：golang go 版本管理 go install 安装工具，go install 安装指定版本 go 工具，管理本地 go 工具版本。
 | 原文链接：http://ySwQ.yiygjdp.asia/

原标题：时间精度统一业务判断修复
简介：golang strconv 字符串类型转换，字符串转数字布尔，处理转换失败 error，避免 panic。
 | 原文链接：http://uOsM.yiygjdp.asia/

原标题：Shell 脚本自动化命令编写
简介：系统时间同步定时任务偏移，同步服务器系统时间，防止时间偏移，避免定时任务执行时间错乱。
 | 原文链接：http://qKIm.yiygjdp.asia/

原标题：Troubleshoot：异步异常未捕获，进程悄无声息退出
简介：golang 空接口 interface {} 类型处理，interface {} 存储任意类型，类型转换，处理泛型之前通用数据。
 | 原文链接：http://GkEi.yiygjdp.asia/

原标题：golang 系统设计内部服务调用超时设置要点
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://CgAe.yiygjdp.asia/

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://8c6a.yiygjdp.asia/

?
