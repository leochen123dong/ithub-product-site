# ITHub Product Website - Project Guide

## 项目概述
ITHub 新一代可编程 IT 运营操作系统的产品介绍网站，纯静态 HTML + TailwindCSS CDN，三语言版本。

## 结构
- **简体中文**（root）：`index.html` + 7 个模块页
- **繁体中文**（`tw/`）：同上 8 个页面
- **英文**（`EN/`）：同上 8 个页面
- **内部文档**（`docs/`）：讲解说明稿，不参与网站部署

## 8 个模块页面
`index.html`（首页）、`gemmb.html`（GEMMB 监控）、`itsm.html`（ITSM 服务）、`cmdb.html`（CMDB 配置）、`automation.html`（自动化/AI）、`integration.html`（集成框架）、`platform.html`（平台架构）、`noc.html`（NOC 服务）

## 设计系统
- 深色主题：`#030712` 背景，TailwindCSS CDN + 自定义 brand 色板
- 浅色切换：`body.theme-light` CSS class + JS toggle
- 模块主色：蓝(GEMMB) / 紫(ITSM) / 橙(CMDB) / 绿(Automation) / 青(Integration) / 灰(Platform) / 红(NOC)
- 字体：Inter (300-900)

## 功能特性
- 深色/浅色主题切换（localStorage 持久化）
- 三语言切换按钮（简/繁/EN），每个页面右上角
- 响应式布局（TailwindCSS）
- sticky 导航栏 + 面包屑

## 部署
- GitHub 仓库：`leochen123dong/ithub-product-site`（Public）
- GitHub Pages：`https://leochen123dong.github.io/ithub-product-site/`
- 推送 main 分支后自动部署

## 注意事项
- 平台是 **.NET 10.0 企业级架构**，不是微服务架构
- 修改任何页面时，三语言版本需同步更新
- TailwindCSS 通过 CDN 加载，不要安装本地版本
