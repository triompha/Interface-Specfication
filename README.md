# 接口技术规范
如果你是一名前端工程师或者后端程序员，在为约定前后端接口而伤神，可以瞄一下！

目前推出规范 A 、 B 版本，简述如下：

## A版本 ##

接口基于 `REST` 规则，优点：

- 少管理URL，通常一个实体的增删改查，给4个接口，命名上也烦心不是：edit、update、new、add、detail ... 哎!
- 通过响应码提前就做分支处理，没必要接收到 response 再做吧！系统分层！
- REST规则好处多多，原则是：客户端和服务器之间的交互在请求之间是无状态的。从客户端到服务器的每个请求都必须包含理解请求所必需的信息。如果服务器在请求之间的任何时间点重启，客户端不会得到通知。此外，无状态请求可以由任何可用服务器回答，这十分适合云计算之类的环境。客户端可以缓存数据以改进性能。


## B版本 ##

还算有点规律，凑合用！