<div align="center">

# 🌐 个人主页

**一个关于创作、探索与日常的个人空间**

纯静态 · 零依赖 · 单文件 · 离线可用

[![在线预览](https://img.shields.io/badge/在线预览-GitHub_Pages-success?style=for-the-badge&logo=github)](https://qi0618.github.io/personal-site/)
[![部署状态](https://img.shields.io/github/actions/workflow/status/Qi0618/personal-site/deploy.yml?branch=main&style=for-the-badge&label=部署状态)](https://github.com/Qi0618/personal-site/actions)

</div>

---

## ✨ 简介

一个轻量级个人主页模板：打开 `dist/index.html` 即可使用，**无需安装依赖，也无需构建**。CSS、JavaScript、插画与图标全部内嵌于单个 HTML 文件中，支持完全离线查看。

## 🎯 特性

| 类别 | 说明 |
| :--- | :--- |
| 📱 响应式 | 桌面与移动端自适应布局，附带手机菜单 |
| 🌗 主题 | 浅色 / 深色主题一键切换，偏好保存在浏览器中 |
| 🪟 弹窗 | 项目与手记详情弹窗，纯文本写入，支持换行 |
| ✉️ 联系 | 一键复制邮箱，`mailto:` 唤起系统邮件应用 |
| ♿ 无障碍 | 键盘焦点支持、减弱动画偏好支持 |
| 🚀 轻量 | 单文件、零依赖，可离线使用 |

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/Qi0618/personal-site.git

# 直接用浏览器打开站点入口
open personal-site/dist/index.html   # macOS
```

> 无需 `npm install`，无需构建，双击 `dist/index.html` 即可预览。

## 🎨 自定义

| 搜索内容 | 说明 |
| :--- | :--- |
| `你的名字` / `YOUR NAME` | 替换为你的姓名与网站标识 |
| `hello@example.com` | 替换为你的真实邮箱（含复制按钮脚本） |
| `<title>` 与页面描述 | 修改浏览器标题与站点介绍 |
| 个人介绍 / 兴趣标签 | 替换为你自己的介绍文字 |

> 💡 两个作品与三篇手记均为示例：卡片文案位于 HTML 中，详情内容位于脚本的 `details` 对象中。

## 📁 项目结构

```
personal-site/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Pages 自动部署工作流
├── dist/
│   └── index.html          # 站点入口（单文件，开箱即用）
├── .gitignore
└── README.md
```

## 🚀 部署

项目已配置 GitHub Pages 自动部署，推送 `main` 分支即可自动更新线上站点。

- **在线地址**：<https://qi0618.github.io/personal-site/>
- **部署方式**：GitHub Actions（`.github/workflows/deploy.yml`）

## 📄 技术栈

- 原生 HTML / CSS / JavaScript
- GitHub Actions + GitHub Pages
