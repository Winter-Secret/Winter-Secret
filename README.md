# 王子睿 · 个人主页

上海交通大学本科生（日语 × 行政管理）的个人主页，单文件静态站点，可直接部署到 GitHub Pages。

## 文件结构

```
.
├── index.html      # 主页（单文件，含全部样式与脚本）
├── photo.jpg       # 个人照片
├── resume.docx     # 简历（供「下载简历」按钮使用）
└── README.md
```

## 本地预览

直接用浏览器打开 `index.html` 即可，无需任何构建或依赖。

## 部署到 GitHub Pages

1. 在 GitHub 新建一个仓库（如 `homepage`），将本目录所有文件推送上去。
2. 进入仓库 **Settings → Pages**。
3. 在 **Build and deployment** 下，Source 选择 **Deploy from a branch**，Branch 选择 **main / (root)**，保存。
4. 等待约 1 分钟，访问 `https://<用户名>.github.io/<仓库名>/` 即可。

## 自定义

- 修改个人信息：直接编辑 `index.html` 中的对应文字。
- 更换照片：替换 `photo.jpg`（圆形裁剪，建议 1:1 比例）。
- 更换配色：修改 `index.html` 顶部 `<style>` 里的 `:root` CSS 变量（如 `--accent`）。
