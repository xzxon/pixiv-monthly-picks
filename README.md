# pixiv-monthly-picks

Pixiv 月排行榜精选画廊（静态页 + GitHub Pages 自动部署）。

- `index.html`：画廊页面，从 `data.json` 渲染
- `data.json`：榜单数据（名次 / 作品ID / 标题 / 画师 / 本地图片 / Pixiv 原作品链接）
- `images/`：榜单缩略图（著作权归原画师所有，仅作个人欣赏整理）
- `.github/workflows/pages.yml`：推送到 `main` 分支后自动部署到 GitHub Pages

## 更新榜单

1. 把新一期的数据写进 `data.json`，图片放进 `images/`
2. `git push`，工作流会自动重新部署

也可以直接喊我来刷新。
