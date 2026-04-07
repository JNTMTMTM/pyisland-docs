# Pyisland Docs

Pyisland 项目的官方文档站点，基于 [VuePress 2](https://v2.vuepress.vuejs.org/) + [vuepress-theme-hope](https://theme-hope.vuejs.press/) 构建。

## 关于 Pyisland

Pyisland 是一个用 Python 开发、运行在 Windows 上的现代灵动岛控制中心，为 Windows 用户带来 iOS 风格的灵动岛体验。

项目提供多个分支版本：

| 分支 | 技术栈 | 特点 |
|------|--------|------|
| pyislandPyside6 | Python + PySide6 | 功能完整，稳定可靠 |
| pyislandQT | Python + PyQt5 | 事件驱动，轻量高效 |
| tauri-island | Rust + Tauri 2 | 性能更强，体积更小 |
| pyisland-wanku | Python + PySide6 | 高仿真 iOS 风格 |
| eIsland | Electron + React | 现代 Web 风格 |

主仓库：[Python-island/Python-island](https://github.com/Python-island/Python-island)

## 本地开发

### 环境要求

- [Node.js](https://nodejs.org/) 18+
- npm

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run docs:dev
```

### 构建静态站点

```bash
npm run docs:build
```

构建产物位于 `src/.vuepress/dist/` 目录。

### 其他命令

```bash
# 清除缓存后启动开发服务器
npm run docs:clean-dev

# 更新 VuePress 相关依赖
npm run docs:update-package
```

## 目录结构

```
pyisland-docs/
├── .github/                # GitHub 社区文件
│   ├── CODE_OF_CONDUCT.md  # 行为准则
│   └── CONTRIBUTING.md     # 贡献指南
├── src/                    # 文档源文件
│   ├── .vuepress/          # VuePress 配置与主题
│   ├── guide/              # 使用指南
│   ├── branches/           # 分支版本详细介绍
│   ├── develop/            # 开发文档
│   └── README.md           # 站点首页
├── package.json
└── tsconfig.json
```


## 许可证

[GPL-3.0](LICENSE)
