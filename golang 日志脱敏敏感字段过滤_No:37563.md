最新前沿技术资讯

一、入门教程｜Getting Started
原标题：golang 日志脱敏敏感字段过滤
简介：golang sql 注入风险规避要点，参数化查询杜绝 sql 注入，禁止字符串拼接 SQL 语句执行。
 | 原文链接：http://book.9i77xs.asia/blog/497603.Doc

原标题：golang 配置热更新不重启服务
简介：golang sync/atomic 原子操作使用注意，理解原子操作内存顺序，规避原子操作错误使用带来 bug。
 | 原文链接：http://book.9i77xs.asia/blog/935148.Doc

原标题：运维笔记：服务器磁盘内存监控告警配置
简介：golang os/exec 安全执行外部命令，规避命令注入漏洞，参数分离，禁止拼接命令字符串执行。
 | 原文链接：http://book.9i77xs.asia/blog/411892.Doc

原标题：Practice：模拟缓存雪崩缓存击穿验证防护策略
简介：golang 文件句柄耗尽排查处理，统计进程打开文件句柄，找到未关闭文件，修复句柄泄漏问题。
 | 原文链接：http://book.9i77xs.asia/blog/070627.Doc

原标题：golang redis 过期 key 监听业务
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.9i77xs.asia/blog/162159.Doc

原标题：Hands‑on：实现服务健康检查与自动报警demo
简介：golang sync.Once 只执行一次，sync.Once 做单例初始化，保证代码只执行一次，并发安全。
 | 原文链接：http://book.9i77xs.asia/blog/964776.Doc

原标题：坑点：环境配置被打包进镜像引发安全泄露
简介：golang sort 稳定排序 Stable，稳定排序保留相等元素原有顺序，业务需要稳定排序场景。
 | 原文链接：http://book.9i77xs.asia/blog/728347.Doc

原标题：架构笔记：事件驱动架构适用场景与坑点
简介：项目脚手架模板生成工具，搭建项目模板脚手架，一键生成标准化项目骨架，减少重复初始化工作。
 | 原文链接：http://book.9i77xs.asia/blog/277718.Doc

原标题：开发记录：批量接口请求并发控制实践
简介：大文件导出内存溢出防护，流式处理大文件导出，边读边写，不把全部数据加载内存，规避 OOM。
 | 原文链接：http://book.9i77xs.asia/blog/209386.Doc

原标题：golang 系统设计配置热更新不重启服务实现
简介：golang go 变量逃逸场景汇总，切片、指针、返回局部变量引发逃逸，变量分配到堆影响 GC。
 | 原文链接：http://book.9i77xs.asia/blog/807848.Doc

原标题：性能笔记：TCP参数内核调优服务高并发场景
简介：golang arp 缓存读取操作，读取系统 arp 缓存表，获取 ip 对应的 mac 地址信息。
 | 原文链接：http://book.9i77xs.asia/blog/074792.Doc

原标题：实战项目：前端资源打包体积优化完整实操
简介：CLI 工具进度条交互效果开发，在命令行工具增加进度条展示，直观反馈任务执行进度，优化命令行体验。
 | 原文链接：http://book.9i77xs.asia/blog/931657.Doc

原标题：express 请求参数校验处理
简介：全局异常处理器接口返回统一，接入全局异常捕获，拦截业务全部异常，对外输出统一格式返回值。
 | 原文链接：http://book.9i77xs.asia/blog/566518.Doc

原标题：性能笔记：数据库表字段设计影响查询性能
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.9i77xs.asia/blog/169813.Doc

原标题：golang 系统设计 protobuf 可选字段使用技巧
简介：golang 容器信号转发处理问题修复，docker/k8s 正确转发 SIGTERM 信号，保证 go 程序收到信号优雅退出。
 | 原文链接：http://book.9i77xs.asia/blog/324043.Doc

原标题：Hands‑on：简易熔断逻辑状态机原型实现
简介：golang go 模板缓存预编译模板，预编译 html 模板，程序启动加载，避免每次请求解析模板损耗性能。
 | 原文链接：http://book.9i77xs.asia/blog/015463.Doc

原标题：golang 系统设计 io 瓶颈磁盘网络优化实践
简介：MySQL 慢查询索引优化实战，抓取慢查询 SQL，分析执行计划，新增或者调整索引，提升 SQL 执行速度。
 | 原文链接：http://book.9i77xs.asia/blog/894763.Doc

原标题：Security：限流防爬虫防恶意攻击防护体系
简介：网络读取超时设置连接挂起防护，设置网络读取超时时间，防止请求无限挂起不返回，占用连接资源。
 | 原文链接：http://book.9i77xs.asia/blog/714884.Doc

原标题：golang ci 流水线制品仓库上传下载
简介：分布式事务最终一致性实现，基于可靠消息实现最终一致性，解决跨数据库跨服务业务数据一致性。
 | 原文链接：http://book.9i77xs.asia/blog/143258.Doc

原标题：设计思考：分布式锁选型、风险、业务约束
简介：golang gorm 索引设置与优化技巧，定义数据库索引，理解索引生效条件，避免索引失效慢查询。
 | 原文链接：http://book.9i77xs.asia/blog/126851.Doc

原标题：项目实践：多租户数据隔离三种方案实操对比
简介：特殊输入字符过滤解析防护，过滤用户输入特殊字符，防止解析报错，规避恶意字符带来业务异常。
 | 原文链接：http://book.9i77xs.asia/blog/342121.Doc

原标题：golang 系统设计告警风暴抑制合并降噪方案
简介：golang 数据库慢查询监控实现，Go 封装 SQL 执行监控，记录慢 SQL，上报日志，发现数据库性能问题。
 | 原文链接：http://book.9i77xs.asia/blog/641004.Doc

原标题：调优方案：CDN优化静态资源访问延迟
简介：golang 分布式事务 seata go 客户端，seata‑go 实现分布式事务，保证跨库业务数据最终一致性。
 | 原文链接：http://book.9i77xs.asia/blog/314347.Doc

原标题：单元测试用例编写入门实操
简介：golang os 文件权限 mode，os.FileMode 文件权限，读写执行权限位，跨平台权限注意事项。
 | 原文链接：http://book.9i77xs.asia/blog/367726.Doc

原标题：git rebase 整理提交历史实操
简介：golang docker 镜像构建最佳实践，Go 项目 Docker 镜像构建最佳实践，减小镜像体积，安全构建。
 | 原文链接：http://book.9i77xs.asia/blog/411570.Doc

原标题：golang es 映射 mapping 设计避坑
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.9i77xs.asia/blog/640251.Doc

原标题：Nginx 请求头大小上限调整
简介：golang go race 竞态检测工具，‑race 检测数据竞争，编译运行检测并发读写数据竞争 bug。
 | 原文链接：http://book.9i77xs.asia/blog/343844.Doc

原标题：golang mysql exists in 性能对比
简介：golang gorm 软删除实现逻辑，Gorm 开启软删除，删除数据仅标记，数据保留可恢复，满足业务数据留存。
 | 原文链接：http://book.9i77xs.asia/blog/735084.Doc

原标题：本地运行正常线上报错排查
简介：golang 开发环境快速搭建指南，快速完成 Golang 开发环境配置，工具链安装，环境变量设置，准备开发。
 | 原文链接：http://book.9i77xs.asia/blog/901379.Doc

原标题：开发复盘：超时参数统一治理线上服务实践
简介：golang 时间轮算法实现延时调度，手写简易时间轮，高并发大量延时任务，降低轮询 CPU 消耗。
 | 原文链接：http://book.9i77xs.asia/blog/624009.Doc

原标题：实战：搭建日志收集分析简易完整演示环境
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.9i77xs.asia/blog/780495.Doc

原标题：golang 信号捕获程序退出处理
简介：golang sort 切片排序自定义 less，sort.Slice 切片快速排序，自定义 less 函数实现业务排序。
 | 原文链接：http://book.9i77xs.asia/blog/805396.Doc

原标题：设计实践：如何设计可扩展业务数据库表结构
简介：Git 混乱提交历史清理方法，针对杂乱的提交记录，使用 Git 工具整理，清理无效提交，还原整洁版本历史。
 | 原文链接：http://book.9i77xs.asia/blog/962518.Doc

原标题：跨域偶现失败配置修复
简介：golang cgo 调用 C 语言代码示例，cgo 调用 C 函数，go 与 C 互相调用，对接 C 语言库能力。
 | 原文链接：http://book.9i77xs.asia/blog/838655.Doc

原标题：nodejs 接口限流防刷代码实现
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.9i77xs.asia/blog/349666.Doc

原标题：golang 系统设计限流熔断降级组合使用
简介：服务启动依赖顺序配置正确，配置服务启动依赖关系，保证依赖服务就绪之后再启动当前业务服务。
 | 原文链接：http://book.9i77xs.asia/blog/680445.Doc

原标题：golang redis 大 key 识别处理方案
简介：接口请求重试容错机制实现，封装请求重试逻辑，遇到临时网络故障自动重试，提升第三方调用稳定性。
 | 原文链接：http://book.9i77xs.asia/blog/224357.Doc

原标题：golang 系统设计 go benchmark 性能测试实操
简介：golang go json 序列化自定义字段，json 标签控制字段名称、忽略字段、omitempty 空值忽略。
 | 原文链接：http://book.9i77xs.asia/blog/493926.Doc

原标题：golang 系统设计 protobuf 命名规范最佳实践
简介：golang json 自定义 MarshalJSON UnmarshalJSON，自定义 json 序列化反序列化逻辑，处理特殊格式字段。
 | 原文链接：http://book.9i77xs.asia/blog/858833.Doc

原标题：Issue：日志疯狂打日志快速占满磁盘空间
简介：golang 时间戳秒毫秒纳秒转换，Unix UnixMilli UnixNano 互相转换，区分单位避免时间逻辑 bug。
 | 原文链接：http://book.9i77xs.asia/blog/131407.Doc


二、踩坑排错｜Troubleshooting
原标题：nodejs 定时任务生产环境避坑
简介：golang http MaxHeaderBytes 限制请求头，设置 http 最大请求头大小，防止超大 header 攻击。
 | 原文链接：http://book.9i77xs.asia/blog/717761.Doc

原标题：Docker 容器入门镜像实操教程
简介：手写简易 MQ 理解消息存储消费，手写极简消息队列 Demo，理解消息存储、投递、消费完整流程。
 | 原文链接：http://book.9i77xs.asia/blog/019894.Doc

原标题：golang 系统设计故障应急响应完整流程梳理
简介：golang jwt 鉴权中间件完整示例，Gin JWT 鉴权中间件，令牌校验，解析用户信息，接口鉴权拦截。
 | 原文链接：http://book.9i77xs.asia/blog/262682.Doc

原标题：golang 系统设计 e2e 端到端测试简单落地思路
简介：Git 子模块更新代码不全修复，正确更新 Git 子模块，拉取子模块完整代码，解决子模块目录为空问题。
 | 原文链接：http://book.9i77xs.asia/blog/196348.Doc

原标题：WSL 内存上限限制防止资源耗尽
简介：golang 静态编译缩小镜像体积，Go 程序静态编译，不依赖系统库，产出单二进制文件，缩小镜像。
 | 原文链接：http://book.9i77xs.asia/blog/364535.Doc

原标题：golang gin 中间件执行顺序讲解
简介：golang 跨域处理中间件编写，Gin 跨域中间件开发，处理预检 OPTIONS 请求，解决浏览器跨域报错。
 | 原文链接：http://book.9i77xs.asia/blog/002518.Doc

原标题：方案对比：同步事务vs事务消息最终一致性
简介：前端权限路由动态生成实现，根据后端返回权限，动态生成前端路由菜单，实现页面权限控制。
 | 原文链接：http://book.9i77xs.asia/blog/995872.Doc

原标题：golang 系统设计开源项目 issue pr 模板编写
简介：golang go 服务压测前后性能对比，压测记录 QPS 延迟，优化前后对比，验证优化效果。
 | 原文链接：http://book.9i77xs.asia/blog/054093.Doc

原标题：实战：Nginx负载均衡多种策略配置实践
简介：多环境配置中心灵活切换方案，简易配置中心实现，支持多套环境配置，动态下发无需重启服务。
 | 原文链接：http://book.9i77xs.asia/blog/968732.Doc

原标题：golang 简易埋点日志上报实现
简介：golang 网卡 ip 读取网络信息获取，程序读取本机网卡 IP，多网卡环境筛选业务使用 IP 地址。
 | 原文链接：http://book.9i77xs.asia/blog/469625.Doc

原标题：优化实践：Redis性能调优，避免大key热key
简介：golang redis bloom 布隆过滤器 go‑redis，go‑redis 布隆过滤器，海量数据判断是否存在，减少数据库查询。
 | 原文链接：http://book.9i77xs.asia/blog/189060.Doc

原标题：新手指南：项目本地编译输出产物解析
简介：golang gorm 批量插入性能调优，GORM 批量插入优化，调整批次大小，提升大量数据插入数据库速度。
 | 原文链接：http://book.9i77xs.asia/blog/947665.Doc

原标题：Practice：实现接口mock动态返回不同响应
简介：golang go 整洁架构代码组织实践，整洁架构依赖向内，解耦业务逻辑与外部基础设施。
 | 原文链接：http://book.9i77xs.asia/blog/560915.Doc

原标题：实战：对象存储断点续传下载实践
简介：golang sync.Cond 条件变量使用，Cond 条件变量协程等待唤醒，复杂并发同步场景。
 | 原文链接：http://book.9i77xs.asia/blog/302474.Doc

原标题：golang docker 部署 mongodb 开发环境
简介：golang go 基准测试 benchmark 编写，Benchmark 性能基准测试，测量函数执行耗时内存分配情况。
 | 原文链接：http://book.9i77xs.asia/blog/441704.Doc

原标题：Nginx 透传真实客户端 IP 配置
简介：nodejs 多进程任务分发处理，多进程拆分处理 CPU 密集任务，主进程分发任务，利用多核提升处理速度。
 | 原文链接：http://book.9i77xs.asia/blog/538699.Doc

原标题：gitignore 文件编写过滤规则
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.9i77xs.asia/blog/832743.Doc

原标题：WebSocket 断线重连稳定优化
简介：站内邮件消息通知功能开发，实现站内消息、邮件通知推送，业务事件触发通知，提醒用户业务状态变更。
 | 原文链接：http://book.9i77xs.asia/blog/843222.Doc

原标题：golang 系统设计内网外网服务隔离方案
简介：golang 系统 IO 阻塞 goroutine 场景，理解系统调用阻塞 M，P 会调度其他 M，掌握 go 调度行为。
 | 原文链接：http://book.9i77xs.asia/blog/318141.Doc

原标题：golang 系统设计 commit 提交规范约定
简介：系统字符集统一乱码修复，统一数据库、程序、操作系统字符集，解决中文乱码显示异常问题。
 | 原文链接：http://book.9i77xs.asia/blog/018076.Doc

原标题：架构复盘：服务灰度发布架构设计与流量切分
简介：WSL 内存上限限制防止资源耗尽，修改 WSL 内存上限配置，避免 WSL 占用主机大量内存资源。
 | 原文链接：http://book.9i77xs.asia/blog/900404.Doc

原标题：golang k8s pod 优雅关闭流程讲解
简介：golang prometheus client 业务埋点实操，prometheus client‑go 业务埋点，计数器、仪表盘、直方图指标开发。
 | 原文链接：http://book.9i77xs.asia/blog/910144.Doc

原标题：nodejs 消息队列消费服务开发
简介：开源源码阅读拆解学习思路，分享阅读大型开源项目方法，从入口文件逐层拆解模块，降低源码学习门槛。
 | 原文链接：http://book.9i77xs.asia/blog/185574.Doc

原标题：性能复盘：热点key导致RedisCPU飙升优化
简介：golang k8s 客户端 client‑go 简单示例，client‑go 操作 k8s 资源，增删改查 pod deployment 等资源对象。
 | 原文链接：http://book.9i77xs.asia/blog/758028.Doc

原标题：golang 系统设计日志轮转切割防止磁盘占满
简介：golang tcp keepalive 参数程序配置，go 程序设置 tcp keepalive，操作系统 tcp 保活参数，清理僵死连接。
 | 原文链接：http://book.9i77xs.asia/blog/899443.Doc

原标题：复盘总结：微服务改造踩坑经验总结记录
简介：golang go 领域驱动 DDD 项目分层，go 项目 DDD 分层架构，领域层应用层基础设施层划分业务代码。
 | 原文链接：http://book.9i77xs.asia/blog/826432.Doc

原标题：开发复盘：分布式会话共享多种方案实践
简介：多套环境灵活切换配置方案，实现配置动态切换，通过环境变量、配置文件，快速切换开发测试生产环境。
 | 原文链接：http://book.9i77xs.asia/blog/949110.Doc

原标题：文件编码统一随机乱码修复
简介：golang go 项目 CI github actions 配置，github actions 实现 go 项目 ci，自动测试、代码检查、编译打包镜像。
 | 原文链接：http://book.9i77xs.asia/blog/317007.Doc

原标题：方案设计：多租户系统架构三种实现模式对比
简介：golang 字符串处理常用技巧汇总，字符串拼接、分割、替换、类型转换实操，规避字符串高频错误。
 | 原文链接：http://book.9i77xs.asia/blog/718585.Doc

原标题：golang 系统设计 webhook 回调处理架构
简介：golang 分库分表 id 路由规则设计，分库分表 id 路由算法，id 映射库表，数据均匀打散避免热点分片。
 | 原文链接：http://book.9i77xs.asia/blog/341470.Doc

原标题：Practice：实现简单信号处理优雅停机实践
简介：前端水印防信息泄露实现，实现网页水印功能，页面叠加用户信息水印，防止页面截图信息外泄。
 | 原文链接：http://book.9i77xs.asia/blog/623988.Doc

原标题：全局本地依赖隔离冲突规避
简介：程序日志分级输出规范实践，区分日志等级，规范日志打印内容，合理输出日志，方便线上问题排查定位。
 | 原文链接：http://book.9i77xs.asia/blog/375361.Doc

原标题：数据库连接及时关闭连接泄漏
简介：nestjs 框架模块化项目搭建，从零搭建 NestJS 项目，模块化拆分业务，搭建规范后端项目骨架。
 | 原文链接：http://book.9i77xs.asia/blog/197330.Doc

原标题：golang md5 sha 加密工具实现
简介：golang go 容器 heap 堆实现优先队列，实现 heap 接口，构建优先队列，任务优先级调度。
 | 原文链接：http://book.9i77xs.asia/blog/431834.Doc

原标题：调优方案：静态资源缓存头Cache‑Control优化
简介：golang context 包标准用法规范，context 传递请求元数据、超时、取消，函数第一个参数传入 ctx。
 | 原文链接：http://book.9i77xs.asia/blog/456217.Doc

原标题：golang 系统设计灰度发布实现思路
简介：批量数据处理脚本编写技巧，编写脚本批量处理大量业务数据，循环处理、分批执行，提升数据处理效率。
 | 原文链接：http://book.9i77xs.asia/blog/716527.Doc

原标题：DevOps：GitLabCI完整流水线配置示例
简介：golang crypto 密码学最佳实践，go crypto 包加密签名，规避不安全算法，使用安全密码套件。
 | 原文链接：http://book.9i77xs.asia/blog/904968.Doc

原标题：新手避坑：第一次提交GitHub项目完整流程
简介：nodejs 日志轮转生产环境配置，配置 Node 日志轮转切割，防止日志文件无限变大，适配生产环境。
 | 原文链接：http://book.9i77xs.asia/blog/780314.Doc

原标题：AI实践：大模型生成代码后审查与重构实践
简介：golang go‑zero rpc 微服务开发，go‑zero 定义 proto，生成 rpc 服务代码，实现微服务调用。
 | 原文链接：http://book.9i77xs.asia/blog/088738.Doc

原标题：golang 日志脱敏敏感字段过滤
简介：代理 HTTPS 证书访问异常处理，配置代理根证书，解决代理环境 HTTPS 证书校验失败无法访问外网。
 | 原文链接：http://book.9i77xs.asia/blog/199255.Doc

三、实战开发｜Practice
原标题：nestjs 权限守卫鉴权实现方案
简介：nodejs jwt 登录鉴权完整示例，Node 实现 JWT 登录鉴权，登录签发令牌，接口校验令牌身份。
 | 原文链接：http://book.9i77xs.asia/blog/776558.Doc

原标题：安全复盘：Redis未授权访问漏洞防护
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.9i77xs.asia/blog/933665.Doc

原标题：golang http 服务性能优化调参
简介：golang jwt jwk 公钥验证令牌，使用 jwk 公钥校验 jwt，非对称方式签发校验令牌，提升安全性。
 | 原文链接：http://book.9i77xs.asia/blog/162116.Doc

原标题：Practice：实现请求大小限制中间件防护大报文
简介：golang grpc 负载均衡客户端实现，grpc 客户端负载均衡，轮询随机权重，分发请求到多个服务实例。
 | 原文链接：http://book.9i77xs.asia/blog/127340.Doc

原标题：数据库主从延迟业务兼容处理
简介：灰度发布策略服务平滑升级，实现灰度发布逻辑，流量逐步切到新版本，出现问题快速回滚旧版本。
 | 原文链接：http://book.9i77xs.asia/blog/821454.Doc

原标题：入门实践：使用Git完成第一次代码提交与推送
简介：golang redis 事务 multi exec 使用，Redis 事务 multi exec 实现批量命令原子执行，理解 redis 事务隔离特性。
 | 原文链接：http://book.9i77xs.asia/blog/166089.Doc

原标题：DevOps：制品仓库管理二进制产物版本
简介：浏览器内存泄漏排查前端页面，梳理前端页面内存泄漏场景，讲解排查手段，修复页面内存持续上涨。
 | 原文链接：http://book.9i77xs.asia/blog/606775.Doc

原标题：性能复盘：慢查询日积月累拖垮数据库优化
简介：golang ioutil 已废弃替换方案，ioutil 废弃之后替换为 os io 包函数，更新旧项目代码。
 | 原文链接：http://book.9i77xs.asia/blog/121092.Doc

原标题：Troubleshooting：Redis大key引发集群卡顿
简介：数值类型溢出错乱问题修复，选择合适数值存储类型，处理数值溢出，避免数据存储错乱结果异常。
 | 原文链接：http://book.9i77xs.asia/blog/381239.Doc

原标题：布隆过滤器数据高效去重实现
简介：golang k8s informer 机制原理理解，informer 监听 k8s 资源变更，本地缓存，减少 apiserver 压力。
 | 原文链接：http://book.9i77xs.asia/blog/558103.Doc

原标题：方案设计：异步解耦业务架构边界识别
简介：跨域偶现失败配置修复，解决跨域问题时而复现时而正常，定位配置漏配、请求头异常等隐性问题。
 | 原文链接：http://book.9i77xs.asia/blog/670156.Doc

原标题：golang 系统设计日志脱敏敏感字段过滤处理
简介：图片上传预览格式大小处理，实现图片上传接口，校验文件格式、大小，完成上传后预览处理。
 | 原文链接：http://book.9i77xs.asia/blog/798112.Doc

原标题：新手教程：gitstash暂存工作区变更实操
简介：golang contract 契约测试微服务，微服务契约测试，保证接口变更不破坏调用方，提前发现兼容性问题。
 | 原文链接：http://book.9i77xs.asia/blog/533749.Doc

原标题：golang 系统设计结构化日志字段规范约定
简介：golang hmac 签名生成校验示例，hmac 生成消息签名，做接口请求签名，校验数据不被篡改。
 | 原文链接：http://book.9i77xs.asia/blog/080467.Doc

原标题：新手指南：虚拟机WSL开发环境入门配置
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.9i77xs.asia/blog/225509.Doc

原标题：SSH 密钥配置 GitHub 免密登录
简介：golang go 逃逸分析实操查看，go build‑gcflags=-m 查看逃逸分析，减少堆分配优化程序性能。
 | 原文链接：http://book.9i77xs.asia/blog/182481.Doc

原标题：实战：容器内执行调试排错完整实操流程
简介：golang 云存储 s3 协议对象存储，go s3 客户端，兼容 minio 阿里云 oss，实现文件上传下载签名访问。
 | 原文链接：http://book.9i77xs.asia/blog/051708.Doc

原标题：快速上手简单性能监控指标查看
简介：golang hystrix 模式简易熔断实现，简易熔断组件，错误率达到阈值触发熔断，快速失败保护下游。
 | 原文链接：http://book.9i77xs.asia/blog/167810.Doc

原标题：安全实践：接口错误信息不要暴露内部细节
简介：golang errgroup 协程组错误处理，errgroup 捕获协程错误，context 取消剩余协程，简化并发任务。
 | 原文链接：http://book.9i77xs.asia/blog/329813.Doc

原标题：模拟登录鉴权权限判断示例
简介：提交第一个开源 PR 完整流程，Fork 项目、修改代码、提交 Pull Request，讲解 PR 规范，提升合并通过率。
 | 原文链接：http://book.9i77xs.asia/blog/192416.Doc

原标题：golang 简易埋点日志上报实现
简介：golang snowflake 时钟回拨解决方案，雪花算法处理时钟回拨，防止生成重复 ID，保证 ID 全局唯一。
 | 原文链接：http://book.9i77xs.asia/blog/564693.Doc

原标题：性能笔记：RPC超时参数优化防止级联阻塞
简介：golang race 检测器性能开销，race 检测器有性能损耗，只用于测试环境，禁止生产开启 race。
 | 原文链接：http://book.9i77xs.asia/blog/206147.Doc

原标题：排错：CI缓存策略错误，每次全量重新构建
简介：golang 命令行交互 cobra 开发 cli，cobra 库开发功能完善命令行工具，子命令参数标志解析。
 | 原文链接：http://book.9i77xs.asia/blog/357518.Doc

原标题：实践：Git大仓库历史清理减小仓库体积实践
简介：golang ctx 传递规则不要存结构体，context 作为函数参数传递，禁止放入结构体字段存储。
 | 原文链接：http://book.9i77xs.asia/blog/822079.Doc

原标题：golang es 高亮搜索结果实现方案
简介：golang 系统资源限制读取 cpu 内存，读取系统容器 cpu 内存限制，程序适配容器资源配额做业务调优。
 | 原文链接：http://book.9i77xs.asia/blog/199496.Doc

原标题：Issue：浏览器缓存ServiceWorker导致旧页面常驻
简介：golang 容器内读取 k8s 配置 configmap，程序读取 k8s configmap 配置，配置与镜像分离便于运维。
 | 原文链接：http://book.9i77xs.asia/blog/103460.Doc

原标题：DevOps：多阶段构建Dockerfile最佳实践
简介：macOS 脚本执行权限开启，给 Shell 脚本添加可执行权限，解决 macOS 下脚本无法运行权限报错。
 | 原文链接：http://book.9i77xs.asia/blog/236243.Doc

原标题：golang 系统设计传输加密 tls 配置要点
简介：golang go‑zero 配置中心热更新，go‑zero 对接 etcd 配置中心，配置热更新无需重启服务。
 | 原文链接：http://book.9i77xs.asia/blog/168518.Doc

原标题：golang mysql 长连接短连接对比
简介：手写简易 RPC 服务通信原型，手写极简 RPC 原型，理解服务注册、网络传输、方法调用底层逻辑。
 | 原文链接：http://book.9i77xs.asia/blog/973428.Doc

原标题：磁盘占满服务不可用清理方案
简介：热更新开发环境配置教程，配置代码热重载，修改代码无需重启服务立即生效，大幅提升本地开发调试效率。
 | 原文链接：http://book.9i77xs.asia/blog/076398.Doc

原标题：请求工具封装统一异常处理
简介：主干开发团队代码合并策略，讲解主干开发模式，团队代码合并流程，适合高频迭代的团队协作模式。
 | 原文链接：http://book.9i77xs.asia/blog/375101.Doc

原标题：零基础理解数据库事务基础ACID概念
简介：golang 限制 multipart 内存大小，设置 MaxMemory，大文件写入磁盘临时文件防止内存暴涨。
 | 原文链接：http://book.9i77xs.asia/blog/114466.Doc

原标题：架构笔记：缓存雪崩缓存击穿架构防护方案
简介：nodejs 事件循环机制完整讲解，拆解 Node.js 事件循环各个阶段，理解异步回调执行顺序。
 | 原文链接：http://book.9i77xs.asia/blog/062003.Doc

原标题：消息队列消费堆积扩容处理
简介：GraphQL 接口查询优化实操，体验 GraphQL 查询方式，按需获取字段，减少冗余数据传输，优化接口请求效率。
 | 原文链接：http://book.9i77xs.asia/blog/906509.Doc

原标题：防火墙 IP 白名单回调接口放行
简介：golang multipart 表单文件上传解析，服务端解析 multipart 表单，获取上传文件与表单字段。
 | 原文链接：http://book.9i77xs.asia/blog/017869.Doc

原标题：Hands‑on：手写简单消息队列理解存储模型
简介：Nginx 缓冲区调优大文件上传，调大 Nginx 请求缓冲区，支持客户端上传大体积文件，避免上传被截断。
 | 原文链接：http://book.9i77xs.asia/blog/488113.Doc

原标题：golang 系统设计缓存预热脚本编写实操
简介：磁盘占满服务不可用清理方案，定位磁盘占用大文件，清理日志、缓存文件，恢复磁盘可用空间。
 | 原文链接：http://book.9i77xs.asia/blog/488143.Doc

原标题：环境变量不生效问题修复
简介：golang http client Transport 参数调优，Transport 最大连接空闲连接，TLS 配置，http 客户端调优。
 | 原文链接：http://book.9i77xs.asia/blog/839275.Doc

原标题：快速入门消息队列基础概念模型
简介：对象存储上传下载权限实操，演示对象存储文件上传、下载、访问权限设置，适配业务文件存储场景。
 | 原文链接：http://book.9i77xs.asia/blog/201290.Doc

原标题：安全实践：输入输出双向过滤安全最佳实践
简介：OOMKilled 容器被杀完整排查，排查容器被 OOM 终止完整流程，区分程序内存泄露和容器内存限制过小。
 | 原文链接：http://book.9i77xs.asia/blog/681876.Doc

四、架构设计｜Architecture
原标题：golang 系统设计开发环境本地调试最佳实践
简介：CI 流水线构建失败日志排查，阅读 CI 流水线输出日志，定位构建脚本、依赖、环境导致流水线失败问题。
 | 原文链接：http://book.9i77xs.asia/blog/560775.Doc

原标题：架构复盘：热点数据防护架构防止节点过载
简介：golang ssh 客户端远程命令执行，golang ssh 连接远程服务器，执行 shell 命令，获取命令输出结果。
 | 原文链接：http://book.9i77xs.asia/blog/956605.Doc

原标题：Security：文件上传漏洞攻击面完整防护方案
简介：golang mysql 长连接检测保活设置，配置 mysql 连接保活检测，剔除失效连接，避免拿到断开无效数据库连接。
 | 原文链接：http://book.9i77xs.asia/blog/110790.Doc

原标题：排坑：Git提交历史混乱，如何清理错误提交
简介：golang http client 连接池调优，调优 Go HTTP Client 连接池参数，复用 TCP 连接，减少连接创建开销。
 | 原文链接：http://book.9i77xs.asia/blog/088524.Doc

原标题：调优方案：容器CPU内存参数压测后调优
简介：golang go 比较运算符可比较类型，哪些类型可以直接 == 比较，map slice 函数不可直接比较。
 | 原文链接：http://book.9i77xs.asia/blog/075583.Doc

原标题：缓存过期打散防止缓存雪崩
简介：react hooks 常见陷阱避坑指南，梳理 React Hooks 高频踩坑点，依赖数组、闭包陷阱，写出稳定组件。
 | 原文链接：http://book.9i77xs.asia/blog/871149.Doc

原标题：golang 系统设计故障定位排查通用步骤方法论
简介：golang 消息队列 kafka 消费开发，Go 开发 Kafka 消费程序，消费消息执行业务，理解 Kafka 消费逻辑。
 | 原文链接：http://book.9i77xs.asia/blog/783889.Doc

原标题：nodejs redis 缓存业务实战
简介：nodejs 接口限流防刷代码实现，Node 层实现接口限流，限制 IP 访问频次，防护接口被恶意高频调用。
 | 原文链接：http://book.9i77xs.asia/blog/229218.Doc

原标题：golang 系统设计 grpc http2 多路复用讲解
简介：golang kafka 批量消费性能优化，开启批量拉取消息，调整批量大小，提升 kafka 消息消费吞吐量。
 | 原文链接：http://book.9i77xs.asia/blog/730584.Doc

原标题：golang es 查询语句 DSL 实操
简介：内存广播本地进程消息通知，实现进程内内存消息广播，进程内部模块之间事件通知解耦。
 | 原文链接：http://book.9i77xs.asia/blog/659550.Doc

原标题：golang nginx 反向代理 go 服务配置
简介：golang go cover 覆盖率报告生成，go test‑cover 生成测试覆盖率，html 可视化查看未覆盖代码行。
 | 原文链接：http://book.9i77xs.asia/blog/727156.Doc

原标题：golang 系统设计 protobuf json 性能对比
简介：golang 分页查询封装通用工具，封装 Go 通用分页工具，统一处理分页参数，简化业务分页接口开发。
 | 原文链接：http://book.9i77xs.asia/blog/893838.Doc

原标题：服务器时钟同步任务错乱修复
简介：golang 系统调用跟踪 strace 排查 go 程序，strace 跟踪系统调用，定位文件网络 IO 慢的底层原因。
 | 原文链接：http://book.9i77xs.asia/blog/494532.Doc

原标题：方案设计：接口版本管理架构向前兼容策略
简介：golang 进程信号捕获 SIGUSR 自定义信号，捕获用户自定义信号，实现线上不重启触发调试、日志切换。
 | 原文链接：http://book.9i77xs.asia/blog/358737.Doc

原标题：nodejs 跨域中间件配置细节
简介：golang 内存碎片问题识别与规避，大量小对象频繁分配产生内存碎片，通过对象池减少碎片。
 | 原文链接：http://book.9i77xs.asia/blog/379379.Doc

原标题：复盘总结：技术选型对比文档模板实践
简介：golang go yaml 解析自定义类型，yaml 自定义序列化，时间、特殊类型自定义解析逻辑。
 | 原文链接：http://book.9i77xs.asia/blog/011154.Doc

原标题：Performance：数据库分表解决单表过大性能衰减
简介：短信服务封装失败自动重试，封装短信发送组件，处理发送失败自动重试，兼容多短信服务商。
 | 原文链接：http://book.9i77xs.asia/blog/367731.Doc

原标题：性能复盘：GC停顿过长业务卡顿优化记录
简介：golang 项目 go mod 依赖管理，Go Mod 管理项目依赖，下载、升级、清理依赖，解决依赖版本管理。
 | 原文链接：http://book.9i77xs.asia/blog/896805.Doc

?
