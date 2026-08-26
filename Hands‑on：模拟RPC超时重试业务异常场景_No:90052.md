最新前沿技术资讯

一、入门教程｜Getting Started
原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://wiki.jzt2km.asia/arts/307518.Doc

原标题：golang 系统设计会话共享多实例部署
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.jzt2km.asia/arts/636733.Doc

原标题：golang 系统设计主键 id 选型雪花自增对比
简介：全量回归测试提升代码质量，搭建全量回归测试集，版本发布执行回归测试，避免迭代引入旧 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/895233.Doc

原标题：golang 系统设计故障演练简单落地思路方法论
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/898065.Doc

原标题：内存广播本地进程消息通知
简介：golang go 线上故障排查完整流程，CPU 高、内存上涨、接口超时、goroutine 泄露一套排查处理流程。
 | 原文链接：http://wiki.jzt2km.asia/arts/864210.Doc

原标题：nodejs 项目 pm2 部署运维指南
简介：开源项目本地运行排错完整清单，汇总开源项目拉取后运行失败各类问题，给出排查思路，快速解决本地启动异常。
 | 原文链接：http://wiki.jzt2km.asia/arts/070946.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang 子进程超时杀死防止挂住，context 控制子进程超时，超时强制杀掉子进程，避免子进程僵尸。
 | 原文链接：http://wiki.jzt2km.asia/arts/087115.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：TCP 心跳检测清理僵死连接，开启 TCP 心跳机制，自动清理僵死无效连接，释放连接资源。
 | 原文链接：http://wiki.jzt2km.asia/arts/735985.Doc

原标题：golang 开发环境快速搭建指南
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://wiki.jzt2km.asia/arts/236782.Doc

原标题：Troubleshooting：依赖安装失败完整排查清单
简介：golang json omitempty 零值坑，omitempty 会忽略零值，区分业务是否需要输出零值字段。
 | 原文链接：http://wiki.jzt2km.asia/arts/727592.Doc

原标题：golang 系统设计消息队列解耦削峰
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://wiki.jzt2km.asia/arts/461799.Doc

原标题：Practice：手写简易限流组件，计数器、令牌桶实现
简介：golang 大文件 HTTP 流式上传接收，服务端流式接收上传文件，不全部加载内存，防止大文件 OOM 崩溃。
 | 原文链接：http://wiki.jzt2km.asia/arts/161036.Doc

原标题：安全复盘：CSRF跨站请求伪造防护配置
简介：Shell 脚本自动化命令编写，讲解 Shell 基础语法，编写自动化脚本，完成批量执行、文件处理，解放重复手工操作。
 | 原文链接：http://wiki.jzt2km.asia/arts/729831.Doc

原标题：开发复盘：批量任务进度持久化实现方案
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.jzt2km.asia/arts/895667.Doc

原标题：方案设计：分布式分页查询架构难点处理
简介：golang go 并发模式 or‑channel 信号合并，合并多个 done 信号，任意一个完成触发退出逻辑。
 | 原文链接：http://wiki.jzt2km.asia/arts/021215.Doc

原标题：环境变量不生效问题修复
简介：golang 灰度发布流量权重路由实现，根据权重切分流量，部分流量访问新版本服务，实现灰度发布。
 | 原文链接：http://wiki.jzt2km.asia/arts/122813.Doc

原标题：内存泄漏定位分析完整流程
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://wiki.jzt2km.asia/arts/340067.Doc

原标题：开发记录：分布式锁超时业务安全处理实践
简介：golang clickhouse go 客户端数据写入，clickhouse‑go 客户端写入查询，海量时序数据分析业务。
 | 原文链接：http://wiki.jzt2km.asia/arts/225458.Doc

原标题：缓存过期打散防止缓存雪崩
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://wiki.jzt2km.asia/arts/044776.Doc

原标题：golang 系统设计网关 ssl 证书配置更新实操
简介：golang go 测试 t.Run 子测试分组，t.Run 实现子测试，分组执行用例，输出分组测试结果。
 | 原文链接：http://wiki.jzt2km.asia/arts/318171.Doc

原标题：nodejs 日志轮转生产环境配置
简介：异步编程 Promise 执行流程解析，拆解异步执行顺序，理解回调与 Promise 差异，理清异步场景下代码执行逻辑。
 | 原文链接：http://wiki.jzt2km.asia/arts/161574.Doc

原标题：入门实践：简易导出导入文件功能实现
简介：golang http body 必须关闭的重要性，无论成功失败必须关闭 request.Body，否则连接无法复用泄漏。
 | 原文链接：http://wiki.jzt2km.asia/arts/602175.Doc

原标题：Git 误删提交代码恢复找回
简介：golang 定时任务任务持久化存储，定时任务持久化到数据库，服务重启任务不丢失，动态管理任务。
 | 原文链接：http://wiki.jzt2km.asia/arts/466542.Doc

原标题：记一次内存Swap被大量使用系统响应缓慢
简介：golang strings.Builder 字符串高效拼接，strings.Builder 做字符串拼接，比 += 性能更高，减少内存拷贝。
 | 原文链接：http://wiki.jzt2km.asia/arts/972517.Doc

原标题：golang 系统设计一致性哈希原理讲解
简介：golang goreleaser 自动版本发布打包，goreleaser 自动化打包发布，生成多平台二进制归档文件。
 | 原文链接：http://wiki.jzt2km.asia/arts/152606.Doc

原标题：golang k8s hpa 水平 pod 自动扩缩容
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://wiki.jzt2km.asia/arts/098154.Doc

原标题：线上故障：消息队列重复消费业务处理异常
简介：golang go 爬虫请求速率控制，爬虫限频、代理轮换，设置 UA，防止爬虫被目标站点封禁 IP。
 | 原文链接：http://wiki.jzt2km.asia/arts/975845.Doc

原标题：golang etcd 配置中心简单使用
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://wiki.jzt2km.asia/arts/624586.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：跨平台 uniapp 多端开发实操，uniapp 开发一套代码，编译多端，梳理多端差异处理与适配技巧。
 | 原文链接：http://wiki.jzt2km.asia/arts/377518.Doc

原标题：golang 系统设计开发环境本地调试最佳实践
简介：golang gorm 原生 SQL 执行处理，复杂场景执行原生 SQL，处理返回结果集，兼顾性能与灵活性。
 | 原文链接：http://wiki.jzt2km.asia/arts/310738.Doc

原标题：限流规则误拦截正常请求修复
简介：golang time 定时器重置 Reset 正确用法，Timer Reset 调用前提，避免 Reset 带来逻辑错误。
 | 原文链接：http://wiki.jzt2km.asia/arts/344170.Doc

原标题：部署实践：服务器SSH安全加固配置实践
简介：后端大文件分片上传接口开发，开发后端分片上传接口，接收分片，合并分片完成大文件存储。
 | 原文链接：http://wiki.jzt2km.asia/arts/776284.Doc

原标题：TCP 长连接参数优化 TIME_WAIT
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.jzt2km.asia/arts/352621.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang grafana 面板 go 业务指标可视化，prometheus 指标对接 grafana，配置监控面板可视化业务状态。
 | 原文链接：http://wiki.jzt2km.asia/arts/888223.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang word 文档生成处理 go 方案，go 生成 word 文档报表，填充文本表格，输出 docx 文件。
 | 原文链接：http://wiki.jzt2km.asia/arts/376288.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.jzt2km.asia/arts/461871.Doc

原标题：不必要字符转义关闭业务异常
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://wiki.jzt2km.asia/arts/081273.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：golang http 重定向策略自定义，CheckRedirect 自定义重定向逻辑，限制重定向次数，防止死循环。
 | 原文链接：http://wiki.jzt2km.asia/arts/687615.Doc

原标题：程序性能指标 CPU 内存监控
简介：golang websocket 服务端开发，Go 实现 WebSocket 服务端，处理连接、消息收发，实现长连接服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/835216.Doc

原标题：golang 静态文件服务搭建教程
简介：死信队列处理消息阻塞业务，配置死信队列，处理消费失败消息，避免失败消息阻塞整个队列业务。
 | 原文链接：http://wiki.jzt2km.asia/arts/409639.Doc


二、踩坑排错｜Troubleshooting
原标题：缓存穿透防护保护数据库
简介：golang net/http/httptest 服务端模拟，httptest.NewRecorder 记录 handler 响应，校验返回状态码 body。
 | 原文链接：http://wiki.jzt2km.asia/arts/257801.Doc

原标题：系统文件描述符上限调大
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/535944.Doc

原标题：方案设计：批量大数据导出系统架构拆解
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.jzt2km.asia/arts/723077.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://wiki.jzt2km.asia/arts/118553.Doc

原标题：golang jwt 过期刷新 token 实现
简介：golang go‑pg postgres 客户端实操，go‑pg 操作 PostgreSQL 数据库，CRUD 关联查询业务开发。
 | 原文链接：http://wiki.jzt2km.asia/arts/483143.Doc

原标题：golang mysql exists in 性能对比
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://wiki.jzt2km.asia/arts/731277.Doc

原标题：前端打包分包加载提速方案
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://wiki.jzt2km.asia/arts/391223.Doc

原标题：golang 大文件读取内存优化
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://wiki.jzt2km.asia/arts/012529.Doc

原标题：golang redis 主从复制哨兵原理
简介：golang go 程序抢占调度理解，理解 go 抢占式调度原理，长循环阻塞调度，造成协程调度延迟。
 | 原文链接：http://wiki.jzt2km.asia/arts/780841.Doc

原标题：golang redis zset 延时队列实现
简介：golang 漏桶算法实现接口限流，漏桶算法控制请求流出速率，平滑突发流量，削平流量峰值。
 | 原文链接：http://wiki.jzt2km.asia/arts/972952.Doc

原标题：开发复盘：海量日志轮转清理脚本实践
简介：golang go 调用动态链接库 so 文件，go 加载 so 动态库调用函数，复用编译好的 C 动态库。
 | 原文链接：http://wiki.jzt2km.asia/arts/680096.Doc

原标题：定时任务周期调度 demo 开发
简介：golang 容器 OOM 被杀死排查区分，区分业务内存泄漏、容器限制过小，定位容器 OOMKilled 原因。
 | 原文链接：http://wiki.jzt2km.asia/arts/211547.Doc

原标题：Practice：实现限流之后友好业务返回处理
简介：开发测试生产多环境配置区分，讲解三套环境配置分离思路，配置文件隔离，防止开发配置泄露到生产环境。
 | 原文链接：http://wiki.jzt2km.asia/arts/284159.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang 结构体 json 序列化坑点，梳理 Go 结构体 JSON 序列化高频坑点，字段大小写、零值处理问题。
 | 原文链接：http://wiki.jzt2km.asia/arts/741198.Doc

原标题：5分钟快速搭建个人技术文档站点
简介：集成测试业务流程编写示例，编写业务流程集成测试，覆盖完整业务链路，验证模块之间协同工作是否正常。
 | 原文链接：http://wiki.jzt2km.asia/arts/989879.Doc

原标题：优化实践：读写分离分担主库查询压力
简介：golang go http 静态文件禁止目录遍历，http.FileServer 防止../ 路径穿越，了解底层安全实现。
 | 原文链接：http://wiki.jzt2km.asia/arts/810160.Doc

原标题：Hands‑on：模拟RPC超时重试业务异常场景
简介：golang go embed 嵌入静态资源文件，使用 go embed 把静态文件编译进二进制，单文件部署携带静态资源。
 | 原文链接：http://wiki.jzt2km.asia/arts/030166.Doc

原标题：实践：API接口文档自动导出离线文档实践
简介：全平台系统环境变量配置，汇总多操作系统环境变量配置方法，统一项目读取逻辑，适配不同运行平台。
 | 原文链接：http://wiki.jzt2km.asia/arts/636636.Doc

原标题：golang 系统设计分布式锁红锁优缺点梳理
简介：vue3 组合式 API 业务开发实战，Vue3 组合式 API 业务实战示例，拆分业务逻辑组合复用，提升代码组织。
 | 原文链接：http://wiki.jzt2km.asia/arts/924465.Doc

原标题：Hands‑on：简易速率限制中间件完整实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://wiki.jzt2km.asia/arts/763599.Doc

原标题：golang 系统设计避免索引失效书写 sql 原则
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://wiki.jzt2km.asia/arts/623925.Doc

原标题：版本升级服务启动失败处理
简介：OpenAPI 自动接口文档生成，集成 OpenAPI 工具，自动扫描代码生成接口文档，减少文档维护成本。
 | 原文链接：http://wiki.jzt2km.asia/arts/596873.Doc

原标题：安全实践：防止JSON解析漏洞恶意payload
简介：golang go 时间 time.Timer time.Ticker，定时器与周期定时器，Stop Reset 正确使用，防止资源泄漏。
 | 原文链接：http://wiki.jzt2km.asia/arts/687560.Doc

原标题：多规则数据脱敏组件开发
简介：golang go 依赖漏洞检测 govulncheck，govulncheck 扫描依赖安全漏洞，发现项目供应链风险。
 | 原文链接：http://wiki.jzt2km.asia/arts/804482.Doc

原标题：Troubleshooting：Nginx缓冲区过小大文件上传失败
简介：golang nacos go 客户端配置服务发现，nacos‑go 对接 nacos，配置管理、微服务注册发现。
 | 原文链接：http://wiki.jzt2km.asia/arts/429875.Doc

原标题：golang docker compose 部署 minio
简介：接口签名验签完整安全方案，一套完整接口签名方案，包含签名生成、请求携带、服务端验签校验。
 | 原文链接：http://wiki.jzt2km.asia/arts/604686.Doc

原标题：实战项目：搭建本地Mock服务快速开发联调
简介：golang 异步任务队列 worker 池开发，任务入数据库或 redis，worker 池消费执行，异步处理耗时业务。
 | 原文链接：http://wiki.jzt2km.asia/arts/899325.Doc

原标题：golang 系统设计 api 网关核心能力梳理
简介：golang time 时间比较 Before After Equal，时间比较不要直接减，使用内置方法判断时间先后。
 | 原文链接：http://wiki.jzt2km.asia/arts/343526.Doc

原标题：方案对比：单体、微服务、模块化单体取舍
简介：Mock 接口服务快速搭建实操，搭建模拟后端接口，自定义返回数据、延迟响应，前端开发阶段无需依赖真实后端服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/015544.Doc

原标题：坑点：gitcherry‑pick引入不兼容代码
简介：golang 数据库连接池泄露检测逻辑，监控连接池状态，检测连接长时间未归还，告警连接泄漏问题。
 | 原文链接：http://wiki.jzt2km.asia/arts/986033.Doc

原标题：golang 系统设计技术方案文档模板参考
简介：golang 优雅处理 http 超时设置，Go HTTP 请求设置各类超时，防止请求无限阻塞，保护协程与连接。
 | 原文链接：http://wiki.jzt2km.asia/arts/958979.Doc

原标题：golang elasticsearch 索引设计思路
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://wiki.jzt2km.asia/arts/882545.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：golang go 单二进制文件静态编译交叉编译，交叉编译不同操作系统架构二进制文件，实现一次编译多平台运行。
 | 原文链接：http://wiki.jzt2km.asia/arts/271429.Doc

原标题：golang 简单爬虫请求防封禁
简介：golang consul 服务发现简单示例，对接 Consul 实现服务注册发现，微服务实例自动感知。
 | 原文链接：http://wiki.jzt2km.asia/arts/125243.Doc

原标题：Nginx 反向代理路由配置实战
简介：golang aes 对称加密解密示例，AES 对称加密解密实现，业务敏感数据加密存储传输。
 | 原文链接：http://wiki.jzt2km.asia/arts/423223.Doc

原标题：前端组件库按需加载性能优化
简介：golang ip 限流黑名单实现方案，基于 IP 做限流与黑名单，拦截恶意 IP 访问，保护接口服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/301736.Doc

原标题：golang prometheus 指标暴露实现
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://wiki.jzt2km.asia/arts/164968.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang 内存缓存简单实现方案，Go 实现进程内简易内存缓存，本地缓存热点数据，减少远程调用。
 | 原文链接：http://wiki.jzt2km.asia/arts/893168.Doc

原标题：入门实战：搭建简易静态网页项目
简介：WebSocket 聊天室实时通讯开发，基于 WebSocket 搭建简易聊天室，实现多人消息广播实时聊天效果。
 | 原文链接：http://wiki.jzt2km.asia/arts/543893.Doc

原标题：前端下载导出文件功能实现
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.jzt2km.asia/arts/197443.Doc

三、实战开发｜Practice
原标题：新手向：Mac/Windows开发环境差异踩坑
简介：golang rabbitmq 死信队列延迟消息，rabbitmq 实现死信、延迟消息，处理延时业务场景。
 | 原文链接：http://wiki.jzt2km.asia/arts/285765.Doc

原标题：新手教程：本地项目初始化gitignore配置
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/571146.Doc

原标题：WebSocket 聊天室实时通讯开发
简介：开发环境变量配置全平台教程，区分 Windows、macOS、Linux 系统，讲解环境变量配置、加载优先级与常见失效原因。
 | 原文链接：http://wiki.jzt2km.asia/arts/481785.Doc

原标题：golang redis stream 消息队列实践
简介：文件分片上传断点续传功能，实现文件分片上传，记录上传进度，支持断点续传大文件上传。
 | 原文链接：http://wiki.jzt2km.asia/arts/735603.Doc

原标题：golang mysql json 字段查询使用
简介：接口限流逻辑简单模拟实现，编写简易限流逻辑，限制接口访问频次，保护服务，避免短时间大量请求压垮系统。
 | 原文链接：http://wiki.jzt2km.asia/arts/881154.Doc

原标题：手写简易 MQ 理解消息存储消费
简介：文件监控服务自动重启开发，监控项目文件变更，代码修改自动重启服务，提升本地开发调试效率。
 | 原文链接：http://wiki.jzt2km.asia/arts/414653.Doc

原标题：安全复盘：Redis命令注入风险防护手段
简介：golang 信号量 semaphore 并发限制，基于 semaphore 实现并发数量控制，保护数据库、第三方接口不被打满。
 | 原文链接：http://wiki.jzt2km.asia/arts/275831.Doc

原标题：golang k8s 监控 prometheus 部署
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://wiki.jzt2km.asia/arts/065116.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：golang channel 通道并发处理，讲解 Channel 用法，协程之间通过通道传递数据，做并发同步控制。
 | 原文链接：http://wiki.jzt2km.asia/arts/725382.Doc

原标题：golang minio 存储桶权限管控配置
简介：缓存穿透击穿雪崩全套防护，完整梳理缓存三大问题，落地全套防护策略，保障缓存层稳定运行。
 | 原文链接：http://wiki.jzt2km.asia/arts/763252.Doc

原标题：踩坑记录：浮点精度错误造成业务计算错误
简介：项目语义化版本号规范管理，遵循语义化版本规范管理项目版本，明确主次版本变更含义。
 | 原文链接：http://wiki.jzt2km.asia/arts/374676.Doc

原标题：设计思考：系统幂等性整体架构层面保障
简介：golang recover 捕获 panic 使用边界，recover 只在 defer 内部生效，协程内部必须捕获本协程 panic。
 | 原文链接：http://wiki.jzt2km.asia/arts/847719.Doc

原标题：golang yaml 解析配置加载实操
简介：golang go toml 配置注释保留，toml 解析保留注释，修改配置后写回保留原有注释。
 | 原文链接：http://wiki.jzt2km.asia/arts/720062.Doc

原标题：线上异常：时间时区问题，定时任务执行偏移
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/751535.Doc

原标题：百万数据 Excel 导出内存优化
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://wiki.jzt2km.asia/arts/772305.Doc

原标题：vue pinia 状态管理实战教程
简介：依赖安装失败全方位排错，从网络、镜像源、权限、版本多角度，定位依赖安装失败，给出对应修复手段。
 | 原文链接：http://wiki.jzt2km.asia/arts/209470.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang nats jetstream 持久消息队列，nats jetstream 持久化消息，保证消息不丢失，实现可靠消费。
 | 原文链接：http://wiki.jzt2km.asia/arts/046880.Doc

原标题：Troubleshoot：跨库关联查询，性能急剧恶化
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://wiki.jzt2km.asia/arts/319531.Doc

原标题：入门实践：实现简单文件读写功能
简介：golang 命令行参数解析开发，解析命令行入参，开发自定义 CLI 程序，读取启动参数配置服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/365846.Doc

原标题：接口幂等性防重复请求实现
简介：golang grpc 客户端拦截器封装，grpc 客户端拦截器实现请求统一签名、重试、链路信息透传。
 | 原文链接：http://wiki.jzt2km.asia/arts/016529.Doc

原标题：零基础理解JSON、XML数据格式处理
简介：本地运行正常线上报错排查，对比本地与线上环境差异，从配置、系统版本、文件权限定位线上独有的 bug。
 | 原文链接：http://wiki.jzt2km.asia/arts/293258.Doc

原标题：CI 流水线超时时间延长配置
简介：Cookie 跨环境登录配置调整，调整 Cookie 域、Secure 属性，适配开发测试生产环境，修复登录失效。
 | 原文链接：http://wiki.jzt2km.asia/arts/124361.Doc

原标题：浏览器缓存强制刷新方案
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://wiki.jzt2km.asia/arts/973981.Doc

原标题：端口占用释放资源重启服务
简介：极简 API 网关路由转发实现，开发极简网关服务，完成请求路由转发，理解网关基础实现原理。
 | 原文链接：http://wiki.jzt2km.asia/arts/151140.Doc

原标题：golang 系统设计本地缓存过期淘汰策略选型
简介：golang mqtt 客户端 go 开发物联网，paho.mqtt.golang 实现 mqtt 客户端，物联网设备消息收发。
 | 原文链接：http://wiki.jzt2km.asia/arts/489583.Doc

原标题：golang kafka 死信队列业务落地
简介：webpack chunk 分包策略详解，讲解 webpack chunk 分包策略，拆分第三方包与业务代码，优化缓存复用。
 | 原文链接：http://wiki.jzt2km.asia/arts/920624.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang go http 服务器优雅关闭完整代码，http.Server Shutdown，等待现有请求处理完成关闭服务。
 | 原文链接：http://wiki.jzt2km.asia/arts/009148.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang cpu pprof 性能分析实操，使用 pprof 采集 CPU 性能数据，定位 CPU 高占用函数，做性能优化。
 | 原文链接：http://wiki.jzt2km.asia/arts/191825.Doc

原标题：复盘总结：缓存改造业务落地踩坑复盘
简介：golang go 值传递引用传递理解，go 全部为值传递，指针本质拷贝指针值，理清参数传递行为。
 | 原文链接：http://wiki.jzt2km.asia/arts/156036.Doc

原标题：设计思考：业务系统如何做故障隔离架构
简介：RPC 报文大小上限调优大请求，调大 RPC 框架报文最大限制，支持传输大体积请求报文不被截断。
 | 原文链接：http://wiki.jzt2km.asia/arts/117315.Doc

原标题：开发复盘：大事务拆分优化业务性能实践
简介：golang testify mock 模拟接口，mock 接口生成 mock 对象，单元测试模拟外部依赖行为。
 | 原文链接：http://wiki.jzt2km.asia/arts/627433.Doc

原标题：golang 系统设计缓存 key 命名规范最佳实践
简介：golang os.Exit 退出程序注意 defer 不执行，os.Exit 会直接退出，不会执行 defer，优雅退出不要直接 os.Exit。
 | 原文链接：http://wiki.jzt2km.asia/arts/903283.Doc

原标题：踩坑记录：数值溢出造成业务ID错乱异常
简介：文件读写与异常捕获代码示例，演示文件读取写入操作，增加异常捕获逻辑，规避文件不存在、权限不足导致崩溃。
 | 原文链接：http://wiki.jzt2km.asia/arts/348831.Doc

原标题：golang 系统设计消息 key 选择保证顺序性方案
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://wiki.jzt2km.asia/arts/123754.Doc

原标题：快速入门消息队列基础概念模型
简介：Nginx 请求头大小上限调整，修改 Nginx 配置，调大请求头允许最大大小，避免大 Header 请求被拒绝。
 | 原文链接：http://wiki.jzt2km.asia/arts/634049.Doc

原标题：开发复盘：避免大报文导致服务OOM优化实践
简介：golang html 模板渲染简单示例，Go HTML 模板渲染，服务端渲染页面，填充数据输出 HTML 页面。
 | 原文链接：http://wiki.jzt2km.asia/arts/960954.Doc

原标题：Debug：分页偏移量过大数据库查询性能暴跌
简介：Shell 运维脚本服务器效率提升，编写常用运维 Shell 脚本，自动化服务器运维操作，减少手工重复工作。
 | 原文链接：http://wiki.jzt2km.asia/arts/575796.Doc

原标题：golang 系统设计故障复盘模板 postmortem 参考
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://wiki.jzt2km.asia/arts/117287.Doc

原标题：Git 仓库瘦身加快克隆下载速度
简介：golang 错误栈捕获打印方案，捕获错误完整调用堆栈，线上日志输出堆栈，快速定位错误发生代码位置。
 | 原文链接：http://wiki.jzt2km.asia/arts/569075.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：配置与镜像分离防止信息泄露，业务配置不打包进镜像，外部挂载配置，避免密钥配置随镜像泄露。
 | 原文链接：http://wiki.jzt2km.asia/arts/561045.Doc

四、架构设计｜Architecture
原标题：golang 系统设计分库分表本地测试调试技巧
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://wiki.jzt2km.asia/arts/188768.Doc

原标题：安全笔记：Cookie安全属性SecureHttpOnly
简介：静态资源 404 路径打包修复，修复打包后静态资源访问 404，调整资源输出路径，保证资源正常加载。
 | 原文链接：http://wiki.jzt2km.asia/arts/444678.Doc

原标题：golang 系统设计大文件上传架构
简介：golang go test 单元测试命令参数详解，gotest 参数覆盖率，指定测试用例，跳过测试，单元测试命令实操。
 | 原文链接：http://wiki.jzt2km.asia/arts/123911.Doc

原标题：golang 分布式上下文传递方案
简介：golang go 模块迁移从 GOPATH 到 GoMod，老项目从 GOPATH 迁移 go mod，解决依赖管理混乱问题。
 | 原文链接：http://wiki.jzt2km.asia/arts/889355.Doc

原标题：golang 系统设计灰度发布流量切分实现
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://wiki.jzt2km.asia/arts/907355.Doc

原标题：入门实践：简单重试逻辑封装实现
简介：golang http 服务性能优化调参，调优 Go HTTP 服务参数，调整连接池，提升服务并发吞吐能力。
 | 原文链接：http://wiki.jzt2km.asia/arts/669467.Doc

原标题：golang 项目 makefile 脚本编写
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://wiki.jzt2km.asia/arts/155729.Doc

原标题：实践：API版本控制多种策略落地对比实践
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://wiki.jzt2km.asia/arts/424981.Doc

原标题：GitHub Markdown 文档语法汇总
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://wiki.jzt2km.asia/arts/196394.Doc

原标题：golang redis lua 脚本开发调试
简介：Git 分支管理多人协作实战教程，详解分支创建、合并、冲突处理，适配团队开发场景，规范多人协同代码工作流。
 | 原文链接：http://wiki.jzt2km.asia/arts/800220.Doc

原标题：从零编写简易 CLI 命令行工具
简介：golang redis geo 地理位置存储查询，Redis GEO 存储经纬度，查询附近点位，实现附近人业务功能。
 | 原文链接：http://wiki.jzt2km.asia/arts/111638.Doc

原标题：开发复盘：分库分表本地模拟与数据路由实践
简介：golang 换行符统一处理，文本文件读写统一换行符，规避不同系统换行符带来解析异常。
 | 原文链接：http://wiki.jzt2km.asia/arts/146778.Doc

原标题：快速入门WebSocket，实现简易双向通信demo
简介：golang rabbitmq go 客户端生产消费，streadway/amqp 实现 rabbitmq 生产者消费者，队列交换机绑定。
 | 原文链接：http://wiki.jzt2km.asia/arts/392445.Doc

原标题：浏览器本地存储安全使用技巧
简介：跨库查询性能优化处理，减少跨库关联查询，做数据冗余或者中间表，规避跨库查询性能低下。
 | 原文链接：http://wiki.jzt2km.asia/arts/899883.Doc

原标题：极简 API 网关路由转发实现
简介：golang makefile 多平台编译脚本，makefile 一键交叉编译多平台二进制，打包镜像，执行测试。
 | 原文链接：http://wiki.jzt2km.asia/arts/729718.Doc

原标题：文件锁正确使用避免死锁
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://wiki.jzt2km.asia/arts/315547.Doc

原标题：实战项目：容器健康探针配置完整实践示例
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://wiki.jzt2km.asia/arts/441175.Doc

原标题：开发记录：服务优雅关闭释放资源完整实现
简介：golang io.Copy 流式拷贝数据，io.Copy 拷贝 reader 到 writer，不用加载全部数据到内存。
 | 原文链接：http://wiki.jzt2km.asia/arts/852534.Doc

?
