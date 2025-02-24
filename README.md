# 小二文档中心

## 项目简介

小二文档中心是一个基于 docsify 构建的现代化文档网站，旨在提供清晰、易用的文档管理和展示平台。本项目集成了多种功能特性，为用户提供优质的文档浏览体验。

## 功能特点

- 🚀 快速响应：基于 docsify 的无构建过程，页面加载迅速
- 📱 响应式设计：完美适配各种设备屏幕
- 🔍 全文搜索：支持文档内容快速检索
- 🎨 主题定制：可自定义的主题样式
- 🤖 AI 功能集成：智能文档处理和分析
- 🔐 权限管理：细粒度的访问控制系统

## 目录结构

```
docs/
├── _coverpage.md     # 封面页配置
├── _navbar.md        # 导航栏配置
├── _sidebar.md       # 侧边栏配置
├── index.html        # 入口文件
├── features/         # 功能特性文档
│   └── ai.md         # AI 功能说明
└── guide/           # 使用指南
    ├── access.md     # 访问指南
    └── permissions.md # 权限说明
```

## 快速开始

1. 克隆仓库
```bash
git clone https://github.com/w441499177/xiaoer-docs.git
```

2. 本地预览
```bash
# 使用任意 HTTP 服务器
python -m http.server 3000
# 或
npx http-server
```

3. 访问文档
打开浏览器访问 `http://localhost:3000` 即可查看文档

## 部署说明

本文档站点可以部署在任何静态网站托管服务上，例如：

- GitHub Pages
- Netlify
- Vercel
- 自托管服务器

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进文档。在提交之前，请确保：

1. 文档格式符合规范
2. 内容清晰准确
3. 已经测试过本地预览效果

## 技术栈

- [docsify](https://docsify.js.org/) - 文档站点生成器
- Markdown - 文档编写格式
- JavaScript - 功能实现
- CSS3 - 样式定制

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情 