最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 系统设计配置中心核心能力梳理讲解
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.ga90y7.asia/blog/653558.Doc

原标题：开发复盘：百万数据批量导入数据库优化方案
简介：golang trace 可视化分析协程阻塞，使用 trace 网页 UI，定位协程阻塞、系统调用阻塞、锁等待。
 | 原文链接：http://book.ga90y7.asia/blog/414592.Doc

原标题：nodejs 日志轮转生产环境配置
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.ga90y7.asia/blog/834163.Doc

原标题：Debug：HTTPS握手失败TLS版本兼容问题
简介：golang go 输入数据校验防御，所有外部入参严格校验长度格式，防止恶意输入造成业务异常。
 | 原文链接：http://book.ga90y7.asia/blog/888778.Doc

原标题：golang 雪花 id 重复问题排查
简介：golang sync.RWMutex 读写锁使用场景，读多写少场景读写锁，读共享写互斥，提升并发性能。
 | 原文链接：http://book.ga90y7.asia/blog/866945.Doc

原标题：golang 系统设计 canary 金丝雀部署实操
简介：服务熔断防止故障级联传播，实现服务熔断逻辑，下游故障时快速失败，阻止故障向上游链式扩散。
 | 原文链接：http://book.ga90y7.asia/blog/209148.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：golang cgo 内存管理 C 与 Go 内存，区分 Go 内存 C 堆内存，防止 cgo 内存泄漏，正确释放 C 内存。
 | 原文链接：http://book.ga90y7.asia/blog/297029.Doc

原标题：golang 结构体深拷贝几种实现
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.ga90y7.asia/blog/193896.Doc

原标题：nestjs 全局返回格式统一处理
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.ga90y7.asia/blog/285458.Doc

原标题：Architecture：灰度、蓝绿、金丝雀发布架构对比
简介：golang trace 工具采集 go 程序执行轨迹，go trace 采集程序完整调度轨迹，分析协程调度阻塞问题。
 | 原文链接：http://book.ga90y7.asia/blog/820131.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang go mod graph 查看依赖关系，go mod graph 打印依赖树，定位间接依赖来源，解决版本冲突。
 | 原文链接：http://book.ga90y7.asia/blog/351817.Doc

原标题：golang 系统设计主干开发 trunk‑based 讲解
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.ga90y7.asia/blog/644663.Doc

原标题：golang docker 部署 kafka 本地调试
简介：golang redis pipeline 与 txpipeline 区别，区分普通管道与事务管道，根据业务场景选择合适批量执行方案。
 | 原文链接：http://book.ga90y7.asia/blog/906711.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：CORS 跨域问题多种解决方案，对比 CORS、代理等不同跨域方案优缺点，根据业务场景选择合适的跨域处理方式。
 | 原文链接：http://book.ga90y7.asia/blog/224812.Doc

原标题：Debug：网关超时时间小于后端接口超时设置
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.ga90y7.asia/blog/241030.Doc

原标题：Issue：容器日志驱动配置错误日志全部丢失
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.ga90y7.asia/blog/345873.Doc

原标题：性能复盘：消息队列大量小消息性能问题优化
简介：golang 集成测试测试数据库回滚，集成测试结束自动回滚数据库，不污染测试环境数据。
 | 原文链接：http://book.ga90y7.asia/blog/164155.Doc

原标题：架构笔记：WebSocket大规模连接服务架构
简介：golang url 解析路径参数提取，url.Parse 解析 url，获取协议主机路径查询参数。
 | 原文链接：http://book.ga90y7.asia/blog/009550.Doc

原标题：golang es bool 查询条件组合技巧
简介：数据库死锁成因规避方案，讲解数据库死锁产生条件，给出业务层面规避手段，减少死锁事件发生。
 | 原文链接：http://book.ga90y7.asia/blog/128322.Doc

原标题：Debug：长连接未设置心跳，连接僵死不回收
简介：golang 结构体零值可用性原则，go 结构体尽量做到零值可用，不用初始化直接使用提升易用性。
 | 原文链接：http://book.ga90y7.asia/blog/864008.Doc

原标题：golang csv 读写批量数据处理
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.ga90y7.asia/blog/485548.Doc

原标题：安全实践：最小权限原则数据库账号管控
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.ga90y7.asia/blog/151118.Doc

原标题：golang k8s liveness readiness 探针
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.ga90y7.asia/blog/130558.Doc

原标题：数据库 utf8mb4 支持 emoji 存储
简介：golang gorm 子查询嵌套查询写法，Gorm 实现子查询、嵌套查询，复杂条件查询简化代码编写。
 | 原文链接：http://book.ga90y7.asia/blog/241187.Doc

原标题：Git 标签版本标记发布管理
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.ga90y7.asia/blog/084441.Doc

原标题：记一次字符集编码不一致乱码问题全排查
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.ga90y7.asia/blog/019366.Doc

原标题：调优方案：Nginx性能参数调优高并发配置
简介：golang http 代理客户端配置，Go HTTP Client 配置代理，通过代理服务器发起网络请求。
 | 原文链接：http://book.ga90y7.asia/blog/533551.Doc

原标题：golang 系统设计监控大盘故障快速定位思路
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.ga90y7.asia/blog/182295.Doc

原标题：golang 系统设计 traceId 全链路透传完整方案
简介：环境变量不生效问题修复，排查环境变量加载顺序、作用域问题，修复环境变量读取不到的异常。
 | 原文链接：http://book.ga90y7.asia/blog/389356.Doc

原标题：记一次第三方回调IP变动未更新防火墙拦截
简介：接口压测定位系统性能瓶颈，使用压测工具对接口施压，观察指标，定位系统性能瓶颈点。
 | 原文链接：http://book.ga90y7.asia/blog/531447.Doc

原标题：golang github actions 多平台构建
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.ga90y7.asia/blog/301785.Doc

原标题：nodejs 内存溢出问题排查修复
简介：多版本开发环境共存配置，实现同一工具多版本并存，快速切换不同版本，适配不同项目对版本的差异化需求。
 | 原文链接：http://book.ga90y7.asia/blog/488014.Doc

原标题：golang 系统设计多级缓存更新策略
简介：golang rsa 签名验签 pem 证书加载，加载 pem 格式密钥证书，rsa 签名与验签完整业务实现。
 | 原文链接：http://book.ga90y7.asia/blog/679260.Doc

原标题：程序预加载加快服务启动速度
简介：golang rate‑limiter 限流组件，封装通用 Go 限流组件，支持多算法，业务接口直接复用调用。
 | 原文链接：http://book.ga90y7.asia/blog/545470.Doc

原标题：nestjs 框架模块化项目搭建
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.ga90y7.asia/blog/956203.Doc

原标题：调优方案：前端静态资源打包性能体积优化
简介：多操作系统开发兼容处理，解决不同系统路径、换行符、权限差异，保证项目跨平台正常运行。
 | 原文链接：http://book.ga90y7.asia/blog/089392.Doc

原标题：坑点：缓存过期策略不当引发业务异常
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.ga90y7.asia/blog/741162.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang go proxy 私有代理配置，配置 go proxy 私有代理，加速依赖下载，内网环境构建项目。
 | 原文链接：http://book.ga90y7.asia/blog/727628.Doc

原标题：golang 系统设计 pr 评审合并完整流程
简介：golang mysql 慢查询日志程序采集解析，程序读取解析 mysql 慢查询日志，统计慢 SQL 做监控告警。
 | 原文链接：http://book.ga90y7.asia/blog/025906.Doc

原标题：Fork 开源项目同步上游代码
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.ga90y7.asia/blog/905948.Doc


二、踩坑排错｜Troubleshooting
原标题：golang 系统设计配置回滚版本历史记录实现
简介：文件编码统一随机乱码修复，统一项目全部文件读写编码，消除随机中文乱码，保证文本处理稳定。
 | 原文链接：http://book.ga90y7.asia/blog/936021.Doc

原标题：DevOps：Docker镜像安全扫描集成CI流程
简介：项目依赖安全扫描漏洞防范，扫描项目第三方依赖包，修复存在安全漏洞依赖，防范供应链攻击。
 | 原文链接：http://book.ga90y7.asia/blog/552736.Doc

原标题：项目实践：OpenTelemetry链路追踪本地部署实践
简介：golang go 程序守护进程实现思路，go 程序不做 daemon 化，依靠 systemd pm2 k8s 实现进程守护。
 | 原文链接：http://book.ga90y7.asia/blog/908065.Doc

原标题：golang es 批量 bulk 操作性能调优
简介：golang interface {} 类型断言类型转换，类型断言 ok 模式，避免断言失败触发 panic。
 | 原文链接：http://book.ga90y7.asia/blog/822595.Doc

原标题：优化实践：业务定时任务错开高峰避免资源争抢
简介：golang 本地消息表实现最终一致性，本地消息表 + 定时任务轮询，可靠消息实现分布式事务。
 | 原文链接：http://book.ga90y7.asia/blog/301206.Doc

原标题：golang 系统设计监控告警体系搭建思路
简介：nodejs 流处理大文件不占内存，使用 Node.js 流处理超大文件，边读边写，不需要全部加载进内存。
 | 原文链接：http://book.ga90y7.asia/blog/048512.Doc

原标题：vite 项目配置与构建提速技巧
简介：golang redis hash 结构业务实战，使用 Redis Hash 存储对象数据，适合对象字段频繁更新业务场景。
 | 原文链接：http://book.ga90y7.asia/blog/890441.Doc

原标题：手写简易 ORM 理解对象映射
简介：golang 速率限制令牌桶实现，Go 实现令牌桶限流算法，可复用限流器，控制业务调用速率。
 | 原文链接：http://book.ga90y7.asia/blog/852365.Doc

原标题：golang ci 流水线自动部署 k8s 示例
简介：golang regexp 正则捕获分组提取数据，正则捕获分组提取子匹配内容，拿到需要业务字段。
 | 原文链接：http://book.ga90y7.asia/blog/182880.Doc

原标题：golang 系统设计短链接服务实现思路
简介：golang go‑fuzz 模糊测试开发，go fuzz 模糊测试，自动构造异常输入，发现代码隐藏 bug。
 | 原文链接：http://book.ga90y7.asia/blog/776039.Doc

原标题：排错：HTTPS证书过期导致接口调用失败
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.ga90y7.asia/blog/595881.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：golang bcrypt 密码哈希加密存储，bcrypt 做用户密码哈希，加盐存储密码，保障用户密码安全。
 | 原文链接：http://book.ga90y7.asia/blog/855944.Doc

原标题：golang kafka 消息丢失重复消费
简介：golang go panic 合理使用边界，panic 只用于不可恢复程序错误，业务逻辑禁止直接 panic。
 | 原文链接：http://book.ga90y7.asia/blog/059129.Doc

原标题：Hands‑on：简易消息推送服务开发实践
简介：golang cgroup 读取容器资源限制，go 程序读取 cgroup，获取容器 cpu 内存限额，适配容器环境。
 | 原文链接：http://book.ga90y7.asia/blog/573092.Doc

原标题：golang gin 静态资源访问配置
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.ga90y7.asia/blog/795873.Doc

原标题：golang 系统设计开源 issue 处理回复沟通技巧
简介：golang k8s secret 敏感配置加载，加载 k8s secret 存储密钥密码，敏感信息不存放配置文件。
 | 原文链接：http://book.ga90y7.asia/blog/274585.Doc

原标题：golang k8s 滚动更新回滚策略
简介：golang go 种子初始化 rand 随机，rand 初始化种子，不初始化会固定序列，理解随机数种子行为。
 | 原文链接：http://book.ga90y7.asia/blog/235278.Doc

原标题：golang 系统设计 ide 配置 go 开发效率提升技巧
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.ga90y7.asia/blog/792904.Doc

原标题：OpenSource：如何高效阅读大型开源项目源码
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.ga90y7.asia/blog/569955.Doc

原标题：从零编写简易 CLI 命令行工具
简介：ServiceWorker 缓存页面更新清理，处理 ServiceWorker 缓存，实现页面新版本更新，用户可以加载最新页面。
 | 原文链接：http://book.ga90y7.asia/blog/247056.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：Docker Compose 一键搭建本地栈，使用 Compose 编排多个容器，一键拉起全套开发依赖服务。
 | 原文链接：http://book.ga90y7.asia/blog/003796.Doc

原标题：站内邮件消息通知功能开发
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.ga90y7.asia/blog/860321.Doc

原标题：golang 系统设计容器镜像安全加固要点
简介：golang 配置文件多格式兼容加载，同时支持 yaml toml json 多种格式配置文件，灵活适配不同部署环境。
 | 原文链接：http://book.ga90y7.asia/blog/193868.Doc

原标题：Hands‑on：简易连接池原型实现理解原理
简介：golang 时间时区处理避坑指南，Go 时间时区常见坑，时区转换，时间比较，规避时间逻辑错误。
 | 原文链接：http://book.ga90y7.asia/blog/194718.Doc

原标题：golang 集成测试启动测试数据库
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.ga90y7.asia/blog/801832.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：跨平台换行符统一异常修复，统一代码文件换行符，解决不同操作系统换行符不一致带来脚本执行异常。
 | 原文链接：http://book.ga90y7.asia/blog/931271.Doc

原标题：零基础理解会话、Cookie、Session基础
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.ga90y7.asia/blog/207015.Doc

原标题：Architecture：API设计RESTful最佳实践与反模式
简介：golang 压缩 zip 文件生成解压，golang 实现 zip 压缩打包，解压 zip 归档文件，处理批量文件归档。
 | 原文链接：http://book.ga90y7.asia/blog/122896.Doc

原标题：golang go test 覆盖率统计实操
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.ga90y7.asia/blog/048116.Doc

原标题：限流规则误拦截正常请求修复
简介：echarts 大数据渲染性能调优，大数据量 ECharts 图表调优，数据采样、分片渲染，解决图表卡顿。
 | 原文链接：http://book.ga90y7.asia/blog/467385.Doc

原标题：golang redis 集群 hash 槽讲解
简介：golang gif 图片帧处理操作，解析 gif 图片帧，压缩、拆分 gif 动图，处理动图业务。
 | 原文链接：http://book.ga90y7.asia/blog/189983.Doc

原标题：线上接口超时故障排查思路
简介：golang 数据库 ORM 框架选型对比，gorm xorm sqlx 对比各 ORM 优缺点，根据业务场景选型。
 | 原文链接：http://book.ga90y7.asia/blog/750461.Doc

原标题：零基础理解依赖管理与包管理器
简介：golang gin 中间件执行顺序讲解，理解 Gin 中间件注册顺序，区分前置后置逻辑，规避中间件顺序 bug。
 | 原文链接：http://book.ga90y7.asia/blog/237651.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：gRPC 服务端客户端入门示例，搭建 gRPC 服务端与调用客户端，学习 protobuf 定义，掌握 RPC 基础开发流程。
 | 原文链接：http://book.ga90y7.asia/blog/645143.Doc

原标题：Troubleshoot：批量导入数据，事务过大回滚日志暴涨
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.ga90y7.asia/blog/974625.Doc

原标题：golang 系统设计故障演练简单思路
简介：golang go 接口定义原则小接口，go 小接口设计原则，接口尽量小，只定义必要方法，提升代码灵活性。
 | 原文链接：http://book.ga90y7.asia/blog/499689.Doc

原标题：Practice：实现文件监控自动重启开发服务工具
简介：golang gin 静态资源访问配置，Gin 配置静态资源目录，直接对外提供静态文件访问服务。
 | 原文链接：http://book.ga90y7.asia/blog/978339.Doc

原标题：性能笔记：避免频繁创建销毁对象GC优化
简介：golang 优雅停机服务关闭实现，监听系统信号，关闭服务等待请求处理完毕，实现 Go 服务优雅停机。
 | 原文链接：http://book.ga90y7.asia/blog/118544.Doc

原标题：实战项目：WebSocket消息广播房间分组实践
简介：服务健康检查监控接口开发，开发健康检查接口，反馈服务运行状态，供编排工具监控服务存活状态。
 | 原文链接：http://book.ga90y7.asia/blog/160754.Doc

原标题：踩坑：大报文传输，RPC消息超过大小限制
简介：golang 模糊测试 go fuzz 基础编写，Fuzz 测试函数，自动生成随机输入，发现代码崩溃 panic。
 | 原文链接：http://book.ga90y7.asia/blog/931505.Doc

三、实战开发｜Practice
原标题：Troubleshooting：Redis大key引发集群卡顿
简介：golang os 文件目录操作大全，文件创建删除重命名，目录遍历，文件信息读取，完成各类文件系统操作。
 | 原文链接：http://book.ga90y7.asia/blog/756463.Doc

原标题：OAuth2 第三方登录服务搭建
简介：golang hertz http 框架快速上手，hertz 高性能 http 框架，路由中间件参数校验快速开发接口服务。
 | 原文链接：http://book.ga90y7.asia/blog/915893.Doc

原标题：golang docker 部署 prometheus 整套
简介：golang bytes.Buffer 字节缓冲区使用，bytes.Buffer 字节内存缓冲区，拼接字节，避免频繁内存分配。
 | 原文链接：http://book.ga90y7.asia/blog/167028.Doc

原标题：开源实践：参与开源项目从Issue到PR完整流程
简介：后端登录鉴权模块完整开发，实现完整登录模块，包含账号校验、令牌发放、接口鉴权整套能力。
 | 原文链接：http://book.ga90y7.asia/blog/891471.Doc

原标题：排错：DockerCompose依赖顺序启动顺序坑
简介：golang 信号触发配置重载实践，收到 SIGUSR1 信号重新加载配置，线上无需重启刷新配置。
 | 原文链接：http://book.ga90y7.asia/blog/374710.Doc

原标题：服务健康检查监控接口开发
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.ga90y7.asia/blog/930950.Doc

原标题：golang 项目环境变量加载方案
简介：nodejs 信号处理优雅关闭服务，监听系统信号，执行资源清理，实现 Node 服务优雅停机，拒绝粗暴杀死进程。
 | 原文链接：http://book.ga90y7.asia/blog/346938.Doc

原标题：零基础理解内存溢出基础现象与表现
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.ga90y7.asia/blog/199998.Doc

原标题：安全复盘：业务数据脱敏防止泄露实践
简介：golang go1.18 + 泛型基础实操，go 泛型基础语法，泛型函数泛型类型，实现通用工具函数。
 | 原文链接：http://book.ga90y7.asia/blog/207288.Doc

原标题：坑点：gitrebase操作失误，代码提交丢失
简介：golang gzip 压缩 http 响应，服务端开启 gzip 压缩，减小接口响应体积，降低网络传输耗时。
 | 原文链接：http://book.ga90y7.asia/blog/493646.Doc

原标题：golang 系统设计索引设计通用方法论汇总
简介：golang goroutine 协程基础实操，Goroutine 基础实操案例，启动协程执行任务，理解轻量级协程特性。
 | 原文链接：http://book.ga90y7.asia/blog/374337.Doc

原标题：部署复盘：容器OOM问题完整排查流程
简介：ICMP 放通网络丢包问题修复，放开 ICMP 协议，解决 MTU 问题导致网络丢包，修复网络不稳定现象。
 | 原文链接：http://book.ga90y7.asia/blog/352824.Doc

原标题：端口占用访问失败排查方案
简介：TCP 长连接参数优化 TIME_WAIT，调整 TCP 内核参数，优化长连接，减少大量 TIME_WAIT 连接占用资源。
 | 原文链接：http://book.ga90y7.asia/blog/938661.Doc

原标题：接口签名校验防篡改实现
简介：golang 单例模式实现几种方式，Go 单例模式多种实现对比，sync.Once 等方式，实现全局唯一实例。
 | 原文链接：http://book.ga90y7.asia/blog/412098.Doc

原标题：快速入门OpenAPI文档生成基础实践
简介：golang hertz 反向代理与负载均衡，hertz 实现反向代理，内置负载均衡，快速搭建网关类服务。
 | 原文链接：http://book.ga90y7.asia/blog/370557.Doc

原标题：HTTPS 证书过期更新操作
简介：golang influxdb 时序数据库读写操作，influxdb 存储时序指标，业务指标监控数据存取。
 | 原文链接：http://book.ga90y7.asia/blog/315449.Doc

原标题：性能复盘：数据库回滚日志过大性能影响优化
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.ga90y7.asia/blog/937024.Doc

原标题：项目实践：实现统一接口返回封装与全局异常处理
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.ga90y7.asia/blog/793816.Doc

原标题：实践：Git工作流主干开发团队协作实践
简介：前端打包产物体积压缩优化，多手段压缩前端打包产物，移除无用代码，压缩资源，提升页面加载速度。
 | 原文链接：http://book.ga90y7.asia/blog/329110.Doc

原标题：实践：实现Redis分布式锁完整可运行代码
简介：golang 工具函数库封装思路，Go 通用工具库封装思路，错误处理、类型转换，业务项目复用工具代码。
 | 原文链接：http://book.ga90y7.asia/blog/314170.Doc

原标题：效率笔记：gitlog高效查询历史提交技巧
简介：nodejs redis 缓存业务实战，Node 对接 Redis 实现业务缓存，缓存热点查询结果，减轻数据库压力。
 | 原文链接：http://book.ga90y7.asia/blog/916523.Doc

原标题：CLI 工具进度条交互效果开发
简介：分布式 ID 全局唯一生成方案，讲解分布式 ID 生成思路，实现全局唯一 ID，满足分布式系统主键生成需求。
 | 原文链接：http://book.ga90y7.asia/blog/930668.Doc

原标题：DevOps：WSL2生产环境使用风险提示
简介：golang kafka 同步异步消费对比，对比 Kafka 同步消费异步消费，分析优缺点，业务选型参考。
 | 原文链接：http://book.ga90y7.asia/blog/050697.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：API 大版本不兼容平滑迁移，API 版本迭代不兼容旧接口，设计平滑迁移方案，逐步完成版本切换。
 | 原文链接：http://book.ga90y7.asia/blog/790581.Doc

原标题：golang 系统设计数据库表设计通用规范模板
简介：golang 静态文件服务搭建教程，Go 搭建静态文件服务，托管静态资源，实现文件直接对外访问。
 | 原文链接：http://book.ga90y7.asia/blog/614243.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：本地简易配置中心动态管理，搭建轻量本地配置中心，业务动态读取配置，修改配置不重启服务。
 | 原文链接：http://book.ga90y7.asia/blog/342404.Doc

原标题：Docker 容器网络不通排查
简介：golang uuid 生成多种版本实现，生成 uuid v1 v4，生成唯一标识，业务用于单据编号场景。
 | 原文链接：http://book.ga90y7.asia/blog/759721.Doc

原标题：golang github actions 多平台构建
简介：Git 误删提交代码恢复找回，使用 Git reflog 工具找回被误删除提交记录，恢复误删除代码。
 | 原文链接：http://book.ga90y7.asia/blog/647211.Doc

原标题：零基础理解缓存基础原理与简单使用
简介：golang 链路追踪简易实现方案，简易链路追踪实现，传递 traceId，记录调用链路，方便排查慢调用。
 | 原文链接：http://book.ga90y7.asia/blog/088180.Doc

原标题：文件读写与异常捕获代码示例
简介：golang e2e 端到端测试 go 接口，编写 e2e 测试，完整模拟用户请求，校验整套业务链路正确性。
 | 原文链接：http://book.ga90y7.asia/blog/567690.Doc

原标题：开发复盘：大列表内存分批读取避免OOM实践
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.ga90y7.asia/blog/757635.Doc

原标题：Issue：本地可以访问，容器内部网络不通
简介：Git 仓库瘦身加快克隆下载速度，清理 Git 仓库历史大文件，缩减仓库体积，提升克隆拉取仓库速度。
 | 原文链接：http://book.ga90y7.asia/blog/524475.Doc

原标题：golang 系统设计读写分离延迟业务兼容
简介：golang validator 自定义校验规则，Gin Validator 自定义校验器，实现业务特殊参数校验逻辑。
 | 原文链接：http://book.ga90y7.asia/blog/304913.Doc

原标题：HTTPS 证书过期更新操作
简介：百万数据 Excel 导出内存优化，优化大 Excel 导出逻辑，流式输出，避免一次性加载全部数据造成 OOM。
 | 原文链接：http://book.ga90y7.asia/blog/248264.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：CDN 缓存刷新获取最新静态资源，调用 CDN 刷新接口，清除节点旧缓存，用户访问到更新后的静态文件。
 | 原文链接：http://book.ga90y7.asia/blog/242179.Doc

原标题：快速入门：API接口调试完整实操步骤
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.ga90y7.asia/blog/312057.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang sync.Map 适用场景与性能对比，读多写少，离散 key，对比普通 map 加锁性能差异。
 | 原文链接：http://book.ga90y7.asia/blog/672026.Doc

原标题：golang 信号量控制并发数量
简介：golang 雪花算法 workId 自动获取，自动获取机器 workId，不用手动配置，简化分布式 id 部署。
 | 原文链接：http://book.ga90y7.asia/blog/882154.Doc

原标题：实战：数据库explain执行计划分析实操演练
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.ga90y7.asia/blog/316486.Doc

原标题：配置与镜像分离防止信息泄露
简介：前端骨架屏提升页面体验，实现页面骨架屏，数据未加载完成展示占位，优化页面白屏感知体验。
 | 原文链接：http://book.ga90y7.asia/blog/215483.Doc

四、架构设计｜Architecture
原标题：golang 日志与链路 ID 关联打印
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.ga90y7.asia/blog/085075.Doc

原标题：golang 系统设计技术文档编写最佳实践
简介：golang alertmanager 告警配置实践，alertmanager 配置告警路由，告警发送邮件钉钉，异常及时通知运维。
 | 原文链接：http://book.ga90y7.asia/blog/948485.Doc

原标题：部署实践：Nginx反向代理传递真实客户端IP
简介：golang redis hyperloglog 基数统计，hyperloglog 统计 UV 基数，海量数据去重统计，极低内存开销。
 | 原文链接：http://book.ga90y7.asia/blog/919624.Doc

原标题：golang redis 热点 key 业务规避
简介：golang bufio.Scanner 缓冲区调大，Scanner 默认缓冲区大小不够，读取超长行需要扩大缓冲区。
 | 原文链接：http://book.ga90y7.asia/blog/979827.Doc

原标题：新手指南：本地多版本环境共存配置
简介：golang go 网络编程 net 包基础，net 包 tcp udp socket 编程，监听接收连接，读写数据。
 | 原文链接：http://book.ga90y7.asia/blog/052409.Doc

原标题：坑点：gitreset误删本地代码恢复方案
简介：golang grpc metadata 元数据透传，metadata 传递 traceId、鉴权信息，全链路透传上下文信息。
 | 原文链接：http://book.ga90y7.asia/blog/671362.Doc

原标题：前端 pdf 预览渲染方案对比
简介：golang http.Server 配置参数详解，ReadTimeout WriteTimeout IdleTimeout，全方位防护慢请求攻击。
 | 原文链接：http://book.ga90y7.asia/blog/208118.Doc

原标题：golang 系统设计链路数据存储选型对比讲解
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.ga90y7.asia/blog/352708.Doc

原标题：golang 系统设计单元测试编写原则最佳实践
简介：golang jwt 令牌刷新逻辑实现，实现 JWT 双令牌机制，access 短期有效 refresh 刷新令牌，实现无感续期登录。
 | 原文链接：http://book.ga90y7.asia/blog/234409.Doc

原标题：AI实践：大模型生成测试用例实践与校验
简介：golang redis scan 遍历 key 避免阻塞，使用 scan 迭代遍历 redis 键，不用 keys 命令，防止阻塞 redis 服务。
 | 原文链接：http://book.ga90y7.asia/blog/712475.Doc

原标题：golang 系统设计代码仓库权限管理方案
简介：golang 延迟队列实现方案对比，时间轮、redis zset 实现延迟队列，处理延时执行业务。
 | 原文链接：http://book.ga90y7.asia/blog/896865.Doc

原标题：项目实践：本地模拟多节点分布式系统实践
简介：Redis 热点 key 拆分降低集群压力，拆分访问量极高的热点 Key，分散请求压力，避免 Redis 节点压力过高。
 | 原文链接：http://book.ga90y7.asia/blog/370210.Doc

原标题：新手教程：Gittag版本标签打标签实操
简介：golang go 项目安全检查漏洞扫描，扫描 go 项目依赖漏洞，代码安全审计，规避安全风险。
 | 原文链接：http://book.ga90y7.asia/blog/996227.Doc

原标题：golang 系统设计网关错误重试超时处理策略
简介：golang channel 作为函数参数方向，声明 channel 入参方向，只读 channel 只写 channel 提升代码约束。
 | 原文链接：http://book.ga90y7.asia/blog/342657.Doc

原标题：golang makefile 自动化构建脚本
简介：前端图片懒加载性能优化，实现图片懒加载，页面可视区域才加载图片，减少页面初始网络请求。
 | 原文链接：http://book.ga90y7.asia/blog/960020.Doc

原标题：项目实践：搭建监控大盘查看系统关键指标
简介：轻量 API 后端接口服务快速开发，快速搭建简易 API 服务，实现基础接口能力，快速支撑小型业务需求。
 | 原文链接：http://book.ga90y7.asia/blog/490605.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang context 取消传播机制，父 ctx 取消，所有派生子 context 全部被取消，理解上下文传播。
 | 原文链接：http://book.ga90y7.asia/blog/866889.Doc

原标题：golang 系统设计 go netpoll 多路复用简单理解
简介：golang 内存持续上涨定位思路，区分内存泄漏、缓存占用、GC 参数不合理，分步定位内存持续走高。
 | 原文链接：http://book.ga90y7.asia/blog/415001.Doc

?
