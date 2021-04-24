# Multiple-Files-Cloud-Transfer
## 介绍
该项目为一个分布式系统的中间件，主要用于文件的高效传输，主服务器(资源初始拥有者)接收下载请求，命令空闲客户机向资源请求者发送文件，大大降低了主服务器的负载，有效地提高了传输效率。
**1.核心为类服务发现注册的资源发现注册服务项目
2.采用资源注册中心，资源拥有者，资源请求者形式，使用 RPC（基于个人实现的 RMI
框架）实现三者的请求与响应
3.实现单一文件，多个文件的资源拆分，实现多对一发送指定部分资源，再组合成完整
资源。
4.支持自定义负载均衡策略及分发策略 支持断点续传**

## 软件架构
基于java 8开发，java11已测试运行...java8以下不保证项目的正常运行 
## 使用说明
该项目为分布式系统的中间件，用于文件传输！不是完整的一个应用
