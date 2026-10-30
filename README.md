# 李朗凝 Langning Li — 个人主页

单页静态网站（`index.html` + `style.css`），没有构建步骤，可以直接部署到 GitHub Pages、Netlify 或任何静态托管服务。

## 本地预览

在仓库根目录运行：

```bash
python3 -m http.server 8000 --directory portfolio_site
```

然后打开 <http://localhost:8000>。

## 部署到 GitHub Pages

把本目录的内容推送到一个仓库（例如 `ton198.github.io`）的根目录，然后在 **Settings → Pages** 中选择 **Deploy from a branch**、默认分支和 `/ (root)`。

## 更新内容

- 页面文字以 `resume_zh.tex` 为准，简历改动后同步修改 `index.html`。
- 运行仓库根目录的 `build_resumes.sh` 重新生成 PDF，它会把 PDF 复制到 `assets/`。
- `assets/res-lib.webp` 中同事姓名已打码；替换截图时注意同样处理。
