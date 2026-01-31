# Stage Smart Locator

智能元素定位器调试工具 - 用于测试和调试 Chrome 扩展的专用页面。

## 🌐 在线访问

GitHub Pages: `https://<username>.github.io/stage-page/`

调试页面: `https://<username>.github.io/stage-page/smart-locator/auto-debug.html`

## 📁 项目结构

```
stage-page/
├── .github/
│   └── workflows/
│       └── deploy.yml      # GitHub Actions 自动部署配置
├── smart-locator/
│   └── auto-debug.html     # 调试页面
├── index.html              # GitHub Pages 入口页面
└── README.md               # 项目说明
```

## 🚀 自动部署

本项目使用 GitHub Actions 自动部署到 GitHub Pages：

- 推送到 `main` 或 `master` 分支时自动触发部署
- 支持手动触发 (`workflow_dispatch`)

### 首次部署设置

1. 进入仓库的 **Settings** → **Pages**
2. **Build and deployment** → **Source** 选择 **GitHub Actions**
3. 保存设置
4. 重新触发 workflow 或推送代码

## 🛠️ 本地开发

直接在浏览器中打开 `smart-locator/auto-debug.html` 文件即可进行本地调试。

## 📄 许可证

MIT License
