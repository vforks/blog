# 目录

* 第1课 杂谈
    * [1.1 聊一聊，Go 的相对路径问题](talk/golang-relatively-path.md)
    * [1.2 Go 的 fake-useragent 了解一下](talk/go-fake-useragent.md)
    * [1.3 用 Go 来了解一下 Redis 通讯协议](talk/go-redis-protocol.md)
    * [1.4 使用 Gomock 进行单元测试](talk/gomock.md)
    * [1.5 在 Go 中恰到好处的内存对齐](talk/go-memory-align.md)
    * [1.6 来，控制一下 goroutine 的并发数量](talk/control-goroutine.md)
    * [1.7 for-loop 与 json.Unmarshal 性能分析概要](talk/for-loop-json-unmarshal.md)
    * [1.8 简单围观一下有趣的 //go: 指令](talk/go-ins.md)
    * [1.9 我要在栈上。不，你应该在堆上](talk/stack-heap.md)
    * [1.10 defer 会有性能损耗，尽量不要用](talk/defer-loss.md)
    * [1.11 从实践到原理，带你参透 gRPC](talk/talking-grpc.md)
    * [1.12 Go1.13 defer 的性能是如何提高的？](talk/go1.13-defer.md)
    * [1.13 Go 应用内存占用太多，让排查？（VSZ篇）](talk/why-vsz-large.md)
    * [1.14 干货满满的 Go Modules 和 goproxy.cn](talk/goproxy-cn.md)
* 第2课 包管理
    * [2.1 Go依赖管理工具dep](module/dep.md)
    * [2.2 如此，用dep获取私有库](module/dep-private.md)
* 第3课 gin
    * [3.1 Golang 介绍与环境安装](gin/install.md)
    * [3.2 Gin搭建Blog API's （一）](gin/api-01.md)
    * [3.3 Gin搭建Blog API's （二）](gin/api-02.md)
    * [3.4 Gin搭建Blog API's （三）](gin/api-03.md)
    * [3.5 使用JWT进行身份校验](gin/jwt.md)
    * [3.6 编写一个简单的文件日志](gin/log.md)
    * [3.7 优雅的重启服务](gin/reload-http.md)
    * [3.8 为它加上Swagger](gin/swagger.md)
    * [3.9 将Golang应用部署到Docker](gin/golang-docker.md)
    * [3.10 定制 GORM Callbacks](gin/gorm-callback.md)
    * [3.11 Cron定时任务](gin/cron.md)
    * [3.12 优化配置结构及实现图片上传](gin/config-upload.md)
    * [3.13 优化你的应用结构和实现Redis缓存](gin/application-redis.md)
    * [3.14 实现导出、导入 Excel](gin/excel.md)
    * [3.15 生成二维码、合并海报](gin/image.md)
    * [3.16 在图片上绘制文字](gin/font.md)
    * [3.17 用Nginx部署Go应用](gin/nginx.md)
    * [3.18 Golang交叉编译](gin/cgo.md)
    * [3.19 请入门 Makefile](gin/makefile.md)
* 第4课 grpc
    * [4.1 gRPC及相关介绍](grpc/install.md)
    * [4.2 gRPC Client and Server](grpc/client-and-server.md)
    * [4.3 gRPC Streaming, Client and Server](grpc/stream-client-server.md)
    * [4.4 TLS 证书认证](grpc/grpc-tls.md)
    * [4.5 基于 CA 的 TLS 证书认证](grpc/ca-tls.md)
    * [4.6 Unary and Stream interceptor](grpc/interceptor.md)
    * [4.7 让你的服务同时提供 HTTP 接口](grpc/grpc-http.md)
    * [4.8 对 RPC 方法做自定义认证](grpc/per-rpc-credentials.md)
    * [4.9 gRPC Deadlines](grpc/deadlines.md)
    * [4.10 分布式链路追踪](grpc/zipkin.md)
* 第5课 grpc-gateway
    * [5.1 介绍与环境安装](grpc-gateway/install.md)
    * [5.2 Hello World](grpc-gateway/hello-world.md)
    * [5.3 Swagger了解一下](grpc-gateway/swagger.md)
    * [5.4 能不能不用证书？](grpc-gateway/grpc-gateway-tls.md)
* 第6课 常用关键字
    * [6.1 panic and recover](panic/panic-and-recover.md)
    * [6.2 defer](defer/defer.md)
* 第7课 数据结构
    * [7.1 slice](slice/slice.md)
    * [7.2 slice：最大容量大小是怎么来的](slice/why-slice-max.md)
    * [7.3 map：初始化和访问元素](map/map-access.md)
    * [7.4 map：赋值和扩容迁移](map/map-assign.md)
    * [7.5 map：为什么遍历 map 是无序的](map/why-map-no-order.md)
* 第8课 标准库
    * [8.1 fmt](pkg/fmt.md)
    * [8.2 log](pkg/log.md)
    * [8.3 unsafe](pkg/unsafe.md)
* 第9课 工具
    * [9.1 Go 大杀器之性能剖析 PProf](tools/go-tool-pprof.md)
    * [9.2 Go 大杀器之跟踪剖析 trace](tools/go-tool-trace.md)
    * [9.3 用 GODEBUG 看调度跟踪](tools/godebug-sched.md)
    * [9.4 用 GODEBUG 看GC](tools/godebug-gc.md)
* 第10课 爬虫
    * [9.1 爬取豆瓣电影 Top250](crawler/douban-top250.md)
    * [9.2 爬取汽车之家 二手车产品库](crawler/cars.md)
    * [9.3 了解一下Golang的市场行情](crawler/go2018.md)
