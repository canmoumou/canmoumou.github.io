# Dennisjo · Personal Homepage

Dennisjo 的个人主页，展示开源项目、技术实践与近期构建记录。

**线上地址：** [https://canmoumou.github.io/](https://canmoumou.github.io/)

## 页面内容

- 个人简介与技术方向
- [Related Work Workflow Agent](https://github.com/canmoumou/related-work-agent)
- [碰面吧](https://github.com/canmoumou/meetup)
- GitHub Pages 自动部署

## 技术栈

- Vue 3（CDN）
- 原生 HTML / CSS / JavaScript
- GitHub Actions
- GitHub Pages

## 本地预览

该项目无需构建，可直接打开 `index.html`，也可以启动任意静态文件服务器：

```bash
python -m http.server 3000
```

然后访问 `http://localhost:3000`。

## 部署

推送到 `master` 或 `main` 分支后，`.github/workflows/deploy.yml` 会自动把静态文件发布到 GitHub Pages。

## 致谢与许可

本项目基于 [quietseek/home](https://github.com/quietseek/home) 修改，保留原项目的 MIT License 与版权声明。
