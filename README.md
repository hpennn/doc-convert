# 文档格式转换 (Doc Convert)

免费在线文档格式转换工具 —— 图片转PDF、PDF转图片。

## ✨ 功能特点

- 🖼️ **图片转PDF** — 支持多图合并成一个 PDF，可拖拽排序
- 📄 **PDF转图片** — 每页生成 PNG 图片，支持自定义页码范围
- 🔒 **隐私安全** — 所有文件处理均在浏览器本地完成，不会上传到任何服务器
- 📱 **响应式设计** — 手机、平板、电脑都好用
- ⚡ **纯前端实现** — 无需安装任何软件

## 🛠️ 技术栈

- 纯静态 HTML + [Tailwind CSS](https://tailwindcss.com/) CDN
- [pdf-lib](https://github.com/Hopding/pdf-lib) — 创建/修改 PDF
- [pdf.js](https://mozilla.github.io/pdf.js/) — 解析渲染 PDF

## 🚀 部署

本项目为纯静态站点，可轻松部署到以下平台：

- **Cloudflare Pages** — 连接 GitHub 仓库即可自动部署
- **Vercel** — 支持 Git 集成自动部署
- **Netlify** — 拖拽部署或 Git 集成
- **GitHub Pages** — 开启 Pages 功能即可

## 📦 项目结构

```
doc-convert/
├── index.html      # 主页面（含完整转换功能）
├── favicon.svg     # 网站图标
├── robots.txt      # 搜索引擎爬虫规则
├── sitemap.xml     # 站点地图
└── README.md       # 项目说明
```

## 📝 License

MIT
