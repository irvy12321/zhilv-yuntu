# 展示图目录

这个目录用于存放 GitHub README 展示用的项目截图。

当前展示图：

- `01-planning.jpeg`：规划页
- `02-itinerary.jpeg`：行程生成结果页（含地图与天气）
- `03-history.jpeg`：保存与历史管理
- `04-pdf-export.png`：PDF 导出效果

根目录 `README.md` 通过 jsDelivr CDN 展示本仓库中的图片，GitHub 渲染时会使用图片代理，以改善原始图片域名无法访问时的展示。点击图片仍可打开仓库中的原图，例如：

```md
[![规划页效果](https://cdn.jsdelivr.net/gh/irvy12321/zhilv-yuntu@main/assets/showcase/01-planning.jpeg)](./assets/showcase/01-planning.jpeg)
```

当前这个目录会随项目一起上传到 GitHub，不会被 `.gitignore` 忽略。

文件名统一使用英文，避免中文路径在链接编码或复制时出现兼容问题。
