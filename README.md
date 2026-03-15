# 雅思词汇闪卡 (IELTS Vocabulary Flashcards) 🚀

一个简洁、优雅且高效的雅思词汇背诵工具。专为备考雅思的同学设计，基于艾宾浩斯遗忘曲线原理（简易版），通过闪卡（Flashcards）形式帮助你快速斩获核心词汇。

## ✨ 功能特点

* 📚 **全库/分类背诵** - 预置多维度词库，支持全库混背或按特定分类精准突破。
* 🎴 **智能闪卡模式** - 隐藏释义，强制回忆。支持点击翻页、自动发音。
* 🌙 **原生夜间模式** - 深度适配暗色主题，保护视力，深夜刷词不刺眼。
* 🔊 **在线发音** - 集成浏览器原生的文字转语音（TTS）技术，支持标准美式/英式发音。
* 📊 **学习进度追踪** - 实时统计今日进度，记录每个单词的熟练度（生疏、模糊、熟悉、简单）。
* 💾 **数据备份与导出** -
* **Excel 导出**：支持一键导出 CSV 格式的学习报表，方便复盘。
* **JSON 备份**：支持导出/导入进度配置文件，换电脑也能无缝衔接。


* 📱 **全平台响应式** - 采用 Flexbox 布局，适配 PC、平板及手机屏幕。

## 🛠️ 技术栈

* **Core**: 纯原生前端开发（HTML5 + CSS3 + Vanilla JavaScript）
* **Storage**: 基于浏览器 **LocalStorage**，无需服务器，保护个人隐私。
* **Icons/Styles**: 现代化的 UI 设计，配合平滑的过渡动画。

## 🚀 快速开始

### 方案 A：本地运行（最简单）

1. 点击 [Download ZIP](https://github.com/kinsung97/IELTS-Vocab/archive/refs/heads/main.zip) 下载并解压。
2. 双击文件夹中的 `index.html`，即可在浏览器中开始使用。

### 方案 B：在线访问（推荐）

本仓库已开启 **GitHub Pages** 自动部署。你可以通过以下网址直接访问：
👉 https://kinsung97.github.io/IELTS-Vocab/

## 📖 使用指南

1. **选择词库**：在侧边栏下拉菜单选择你要攻克的目标分类。
2. **刷词流程**：
* 看到单词 -> 尝试回忆 -> **点击卡片**查看释义。
* 根据记忆程度点击：**生疏 (1d)**、**模糊 (2d)**、**熟悉 (4d)** 或 **简单 (7d)**。
* 系统会根据你的选择自动安排下一次复习时间。


3. **备份数据**：
* 建议每周通过侧边栏点击 **"备份进度"** 下载 JSON 文件。
* 如需换电脑，点击 **"恢复进度"** 上传该 JSON 文件即可。

## 📚 数据来源

词汇数据来自 [hefengxian/my-ielts](https://github.com/hefengxian/my-ielts) 项目，包含《雅思词汇真经》等优质雅思备考资料。

感谢原作者的整理和分享！

## 📦 目录结构

```text
.
├── index.html          # 主程序文件（包含样式与逻辑）
├── words.js           # 词汇数据库（可自定义扩展）
├── README.md          # 项目文档
└── LICENSE            # MIT 开源协议

```

## 🤝 参与贡献

如果你有更好的词汇数据，或者发现了代码中的 Bug，欢迎提交 **Pull Request** 或 **Issue**！

1. Fork 本仓库
2. 新建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开一个 Pull Request

## 📄 许可证

本项目采用 [MIT License](LICENSE) 许可协议。

---

**💡 备考建议：** 雅思不仅是单词量，更是逻辑与表达。愿这个小工具能陪你度过枯燥的刷词时光！
