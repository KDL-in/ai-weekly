# AI 周刊

每周精选 AI 产品、观点与趋势（静态 HTML，托管于 GitHub Pages）。

- 在线阅读：https://kdl-in.github.io/ai-weekly/
- **统一订阅（RSS）**：https://kdl-in.github.io/ai-weekly/feed.xml
- 仓库：https://github.com/KDL-in/ai-weekly

订阅上述 RSS 后，每期发布会自动推送到阅读器。

## 目录结构

- `index.html` — 期次列表
- `issues/*.html` — 各期完整页面（与本地导出同款样式）
- `feed.xml` — RSS
- `.nojekyll` — 禁用 Jekyll，直接托管静态文件

## 如何发布新一期

从 `ai-info-sub` 数据库重新导出并覆盖站点文件后 push 即可（与本次构建同一套导出流程）。
