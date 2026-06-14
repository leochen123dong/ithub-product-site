# ITHub Product Website

ITHub 新一代可编程 IT 运营操作系统 — 产品介绍网站

## 技术栈

- **纯静态 HTML** — 无需构建工具，零依赖
- **TailwindCSS CDN** — 通过 CDN 加载，无需本地安装
- **三语言支持** — 简体中文（root）/ 繁体中文（`tw/`）/ English（`EN/`）

## 页面结构

| 模块 | 文件 | 说明 |
|------|------|------|
| 首页 | `index.html` | 产品总览与模块导航 |
| GEMMB | `gemmb.html` | 全局企业管理监控看板 |
| ITSM | `itsm.html` | IT 服务管理 |
| CMDB | `cmdb.html` | 配置管理数据库 |
| 自动化/AI | `automation.html` | 自动化引擎与 AI 智能体 |
| 集成框架 | `integration.html` | 开放生态与集成总线 |
| 平台架构 | `platform.html` | 企业级安全基座 |
| NOC 服务 | `noc.html` | 7×24 统一运营服务 |

每个模块在 `tw/` 和 `EN/` 下有对应的繁体中文和英文版本。

## 本地运行

直接浏览器打开 `index.html` 即可预览。如需本地服务器：

```bash
# Python
python3 -m http.server 8080

# Node.js
npx serve .
```

## 部署

通过 GitHub Pages 部署，Settings → Pages → Source 选择 `main` 分支 root 目录。

## 内部文档

`docs/` 目录包含产品讲解说明稿，仅供内部维护使用，不参与网站部署。
