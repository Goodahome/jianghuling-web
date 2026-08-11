# 江湖令 · 前端静态站（GitHub Pages）

本仓库**仅含 Vite 编译产物**，用 Actions 的 `static.yml` 发布。

## 站点

- 前端：https://goodahome.github.io/jianghuling-web/
- 后端 API：https://jianghu.kssrol.com/api/v1/

## 必做设置（打不开网站时先看这里）

1. 打开仓库 **Settings → Pages**
2. **Build and deployment → Source** 选 **GitHub Actions**（不要选 “Deploy from a branch”）
3. 打开 **Actions**，确认 workflow **Deploy static content to Pages** 成功（绿色）
4. **不要**启用 `jekyll-gh-pages.yml`（Jekyll 会破坏本站）

## 本地更新站点文件后

```bash
git add -A
git commit -m "update site"
git push origin main
```

推送后等待 Actions 部署完成再访问。
