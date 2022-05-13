# Capa RPC on AWS AppMesh

---

## 一、AWS AppMesh 最佳实践

---

## 二、AWS AppMesh 实践经验

### A、服务间通信：Backend与ALLOW_ALL概念理解

    将网状出口过滤器设置为ALLOW_ALL. 并不是说这会导致您的特定问题，但它可以掩盖问题，因为这实际上允许您的应用程序绕过 Envoy 代理以在找不到到上游主机的适当路由时发出请求。

### B、DNS解析相关问题

#### 相关文档

[使用 Envoy 的 DNS 过滤器拦截并响应虚拟服务的 DNS 查询](https://github.com/aws/aws-app-mesh-roadmap/issues/65)

[App-mesh 虚拟服务名称必须是完全限定域名 (FQDN)](https://github.com/aws/aws-app-mesh-roadmap/issues/71)

### C、监控：Envoy管理界面

#### 相关文档

[错误：导致停机的部署 - 503/504s](https://github.com/aws/aws-app-mesh-roadmap/issues/362)

[获取：上游连接错误或在标头之前断开/重置。重置原因：连接终止](https://github.com/aws/aws-app-mesh-roadmap/issues/196)

### D、Envoy配置

#### 相关文档

[Sidecars 的出口配置](https://github.com/aws/aws-app-mesh-roadmap/issues/44)

---

## 三、AWS AppMesh 社区资料

### AppMesh DNS服务发现

https://github.com/aws/aws-app-mesh-roadmap/issues/271

### AppMesh backend相关

https://github.com/aws/aws-app-mesh-roadmap/issues/60

https://github.com/aws/aws-app-mesh-roadmap/issues/113

### AppMesh 出口流量

[无法使用 ALLOW_ALL 网状出口过滤器连接到端口 443 上的目标](https://github.com/aws/aws-app-mesh-roadmap/issues/79)

### AppMesh 监控指标

[功能请求：OpenTracing/Prometheus 支持](https://github.com/aws/aws-app-mesh-roadmap/issues/127)

[功能请求：以 App Mesh 为中心的 Envoy 指标](https://github.com/aws/aws-app-mesh-roadmap/issues/217)

### AppMesh 访问日志

[Bug：当虚拟节点没有监听器时访问日志不起作用（仅出口）](https://github.com/aws/aws-app-mesh-roadmap/issues/178)

### AppMesh sidecar注入

[功能请求：sidecar 注入](https://github.com/aws/aws-app-mesh-roadmap/issues/126)

### AppMesh 服务通信 

[使用 App Mesh 进行服务到服务通信](https://github.com/aws/aws-app-mesh-roadmap/issues/152)

---

## 四、AWS AppMesh 常见问题