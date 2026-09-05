# 柯奇画 · 学术主页

纯静态学者主页，部署于 GitHub Pages：

https://lexi-ke.github.io/hugo-theme-academic-cv/

## 结构

- `www/index.html` — 主页（简介、数据、研究方向、代表论文、项目、荣誉）
- `www/publications.html` — 论文全列表（SCI 12 + 中文核心 11）
- `www/assets/` — 样式、头像、简历 PDF
- `.github/workflows/deploy.yml` — 推送到 main 后自动部署（也可在 Actions 页手动触发）

## 更新内容

直接编辑 `www/` 下的 HTML 文件并提交即可，无需构建步骤。改动推送后
（或手动在 Actions 页点 Run workflow）约 1 分钟后线上生效。
