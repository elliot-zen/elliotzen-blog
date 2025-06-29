---
date: '2025-06-29T09:37:04+08:00'
title: 'Vmess'
---

* 通过 `init` 机制注册以配置为键的创建函数
	* type.go `RegisterConfig`,  注册 `CreateObject`创建;
* Dispatcher 负责从 inbound 接收数据发送到  outbound

创建配置类 `Config`时会预置Feature
* `v2ray.go`-> `Build()`
* wip: config.go -> RegisterConfigLoader
