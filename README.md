# WorldHundred.github.io

个人主页 —— [worldhundred.github.io](https://worldhundred.github.io/)

## 技术

单文件 `index.html`，零构建、零运行时依赖。字体 JetBrains Mono 自托管于 `assets/fonts/`（避免依赖 Google Fonts 在境内阻塞首屏），图标全部内联 SVG。

## 目录

```
index.html          全部结构 / 样式 / 脚本
assets/
  portrait.jpg      头像（640×640）
  ui.webp           研究助理 Agent 运行截图（1200×1356）
  og.jpg            社交分享卡片（1200×630）
  resume.pdf        简历
  fonts/            JetBrains Mono woff2（400 / 600 / 700）
```

## 本地预览

直接双击 `index.html`，或：

```bash
python -m http.server 8000
```

## 部署

推送到 `main` 分支，GitHub Pages 自动发布。

## 内容

- 精选项目：个人研究助理 Agent —— 手写 ReAct 内核，9 个工具，stdio MCP Server，端侧 llama.cpp 离线推理，29 题可复现评测
- 其他项目：Globex 跨境购物多 Agent（课程基线二次开发）、伴学喵
