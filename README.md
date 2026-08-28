# Tnabxy-Web服务器

> Self‑hosted multi‑protocol edge gateway, alternative to Cloudflare
> Zhimo‑Network | Rust

✅ Self‑host edge gateway
✅ Reverse proxy / Virtual host / ACME SSL
✅ Custom HTTP error pages
✅ Built‑in firewall & rate‑limit
✅ Plugin‑extendable
✅ Web dashboard & tunnel client
✅ Works behind NAT, no public‑ip required



# tnabxy
> 执墨网络 Zhimo‑Network 自研，对标 Cloudflare 的自建多协议边缘网关
> 开发语言：Go

## 项目简介
**tnabxy** 是面向自建机房、NAT内网、无公网IP场景的自托管边缘网关。
摆脱对第三方CDN的依赖，将反向代理、隧道接入、WAF防护、域名路由、静态站点、插件扩展集成于单一程序。
让家用主机、边缘硬件、私有服务器，拥有完全自主可控的边缘网络能力。

## ✨ 核心特性
- **多协议支持**
HTTP / HTTPS / HTTP3‑QUIC，支持隧道接入，NAT内网设备无需公网IP即可对外暴露服务；可替代Nginx/Apache完成反向代理、虚拟主机、静态网站部署。

- **自定义错误页面**
原生支持自定义 200、403、404、500、502 等状态页面，可挂载自定义HTML，自由定制样式。

- **内置访问防护**
IP黑白名单、请求速率限制、UA过滤、请求头校验，基础WAF能力，抵御扫描与恶意访问。

- **插件化架构**
通过插件扩展鉴权、请求改写、缓存、访问审计，业务逻辑无需修改网关核心源码。

- **Web可视化控制台**
内置网页管理面板，图形化配置域名、后端上游、SSL证书、防火墙规则，支持中文界面。

- **隧道客户端**
配套轻量客户端，旧手机、边缘盒子、家庭主机可以建立隧道，安全把内网服务发布公网。

- **自动SSL证书**
对接ACME协议自动申请、续期证书，同时支持导入自定义证书文件。

## 🎯 使用场景
1. NAT环境、家庭服务器无公网IP，对外发布Web服务
2. 自建站点，不想依赖外部CDN，完全掌控全部流量
3. 私有云、小型IDC，统一流量入口，集中做访问管控
4. 内网多套服务，依靠域名路由分发至不同后端

> ⚠️ 项目定位：仅用于自托管基础设施，**不属于翻墙工具**。可搭配 VluaceOS 轻量系统部署。

## 👤 作者信息
作者：钟嘉晨（执墨网络），开发时14岁
属于执墨网络开源生态，同生态项目：VluaceOS

---
