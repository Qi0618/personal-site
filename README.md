# 房诗奇 · 个人主页

一个以桌面窗口为灵感的个人介绍页面，面向 AI 产品经理相关交流。

- 在线网站：[qi0618.github.io/personal-site](https://qi0618.github.io/personal-site/)
- 页面入口：`dist/index.html`
- 原生 HTML、CSS、JavaScript，样式、图标与脚本全部内嵌，可离线打开。

## 页面内容

保留关于我、项目作品、成长经历、想法手记、联系我五个栏目，采用原始桌面窗口排版与经历双卡片布局。项目区目前展示本站的公开仓库；未提供的工作经历、其他项目及文章不虚构内容。

- 房诗奇，AI 产品经理，北京。
- 北京联合大学，视觉传达专业，本科，2024 年毕业。
- 邮箱、GitHub 与小红书入口。

支持手机布局、浅色与深色主题、栏目历史导航、快捷搜索（⌘ / Ctrl + K）、邮箱复制和键盘操作。无 JavaScript 时仍可阅读全部正文并使用栏目锚点。

## 本地预览

双击 `dist/index.html`。旧的 `dist/preview.html` 链接会保留栏目片段并跳转到同一版正式页面，避免两个版本产生差异。也可运行静态服务器：

```sh
python3 -m http.server 4173 --directory dist
```

浏览器访问 `http://localhost:4173`。

## 修改内容

直接编辑 `dist/index.html`，无需安装依赖或构建。个人信息和联系链接均位于 HTML 正文中，栏目名称与搜索关键词位于页面末尾的脚本中。

## GitHub Pages 发布

源码保存在 `main`，Pages 从 `gh-pages` 分支的根目录发布。`dist/.nojekyll` 禁用 Jekyll 处理。

修改并提交后：

```sh
git push origin main
git subtree push --prefix dist origin gh-pages
```

仓库的 Pages 设置为“Deploy from a branch”，分支 `gh-pages`、目录 `/`。`github-pages` 环境允许该分支部署。推送发布分支后，GitHub Pages 会更新在线页面。
