# mqtt-gofly项目
`mqtt-gofly` 基于 [MQTT v3.1.1](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html) 协议，提供一个***完全基于内存*** 的 mqtt broker。



特点：完整实现 [MQTT v3.1.1](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html) 协议，不支持消息持久化。
开发：完全用Golang语言开发，不使用第三方包，轻量简单。
> **应用重启会导致 qos1, qos2 消息丢失**


### 开发文档

[mqtt-gofly开发使用文档](https://doc.goflys.cn/docview?id=18)


## 快速开始

**windows** 环境下构建：

- linux: `GOOS=linux GOARCH=amd64 go build -o mqtt-gofly`
- windows: `go build -o mqtt-gofly`

构建完成后，直接运行二进制包即可(Linux 系统需要赋与 `mqtt-gofly` 可执行权限，`chmod 744 ./mqtt-gofly`)



