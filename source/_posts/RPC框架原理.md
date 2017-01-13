title: RPC框架原理
date: 2016-07-04 17:12:22
tags:
  - 分布式
---
**Remote Procedure Call**
## 原理图
![RPC框架原理图](http://7ktupt.com1.z0.glb.clouddn.com/RPC%E5%8E%9F%E7%90%86%E5%9B%BE.png)
核心概念：`远程代理对象（通过JDK动态代理的拦截机制，将本地调用封装称远程调用服务）`

扩展内容：通信协议、序列化（网络传输问题）

## 示例代码
