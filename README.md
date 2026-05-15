# SSV Nexus · 讨论页 v1.2 Demo

> 基于 Figma 设计稿「nesux讨论页迭代」还原的交互 Demo。

## 在线预览

**🌐 https://onlyys.github.io/nexus-discussion-v12-demo/**

## 这个 Demo 演示了什么

### 1. 静态还原
- 1:1 还原 Figma Design Token（颜色 / 字号 / 圆角 / 间距）
- Topbar + Sidebar (ALL/MY/TOOLS/ADMIN) + Main + Rightbar（Topic 概览 + AI 洞察）
- Topic「SSV Nexus 产品进展」+ #1/#2 折叠 Event + #3 EventArticle「v1.1 上线观察 + 后续 v1.2 规划」
- 完整讨论区：2 条主评论 + 2 个 RepliesCard 灰底块 + 富媒体（ImagePreview / PDFChip / LinkPreview）

### 2. 完整可交互
- **附件上传链路**：点击 📎 → 仿 macOS 访达样式的文件选择器 → 多选 PDF/PPT/TXT/MD → 上传进度条 → chip 出现在输入框下方 → 发送后挂在评论下方可下载
- **图片图文混排**：点击 🖼 → 选 PNG → 上传后图片以原比例缩略图嵌入到 contenteditable 编辑器光标位置 → 可继续在前后输入文字 → 支持退格删除 → 发送后图片和文字混排展示
- **键位**：Enter 发送，Ctrl/Cmd/Shift + Enter 换行
- **@提及**：工具栏 @ 一键插入；正文中 `@xxx` 自动高亮蓝色
- **链接**：工具栏 🔗 弹窗输入 URL

## 设计系统

| Token | 值 |
|---|---|
| `--paper` | `#F5F6F8` 页面底色 |
| `--ink` | `#1A1918` / `#1F2328` 主文字 |
| `--brand` | `#2463EB` / `#2563EB` 品牌蓝 |
| `--replies-bg` | `#F9FAFC` 回复块底色 |
| 字体 | Inter + Noto Sans SC |

## 与上一版 Demo 的差异

| 维度 | thread-demo（旧） | discussion-v12（本版） |
|---|---|---|
| 概念 | Thread 卡片 + 转子任务 | 主评论 + RepliesCard 灰块（取消 Thread） |
| 富媒体 | 基础图片 | PDFChip / LinkPreview / 内联图片 |
| 输入 | textarea | contenteditable 图文混排 |
| 侧栏 | 简单导航 | ALL/MY/TOOLS/ADMIN + 右侧 Topic 概览 + AI 洞察 |

## 关联

- 设计稿: `LVCugwrk5rVDoL1XG8Z3BY` / node `14:2`
- 旧版 Thread Demo: https://github.com/onlyys/nexus-thread-demo
