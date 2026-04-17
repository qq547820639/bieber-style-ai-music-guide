# Bieber-Style AI Music Guide

> 将 Justin Bieber 全部时期音乐风格提炼为可精确量化的 AI 生成指令体系的工业标准。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Suno Compatible](https://img.shields.io/badge/Suno-v5.5-blue)](https://suno.ai)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## 📖 项目简介

本项目提供了一套完整的、经过实战验证的 Justin Bieber 风格 AI 音乐创作工业标准。无论是使用 Suno、Udio 还是其他 AI 音乐生成工具，你都可以通过本手册中的量化参数和 Style Prompt 模板稳定产出具备 Bieber 声乐特质、制作美学与情感内核的原创作品。

**核心特性**：
- 覆盖 5 大时期风格分支（Tropical Pop EDM、Alternative R&B、Acoustic Pop、Afrobeat/Pop、Dark Pop R&B）
- 量化评估公式（综合得分、Hook 记忆度、第一人称密度）
- Suno 专属防串味与混音优化标签
- 可直接复制粘贴的一键生成 Prompt 模板
- 丰富的歌词示例与变体建议

## 🚀 快速开始

### 1. 选择风格分支
从下方选择你想要创作的风格：

| 分支 | 代表曲目 | BPM | 调性 |
| :--- | :--- | :--- | :--- |
| Tropical Pop EDM | *Sorry*, *What Do You Mean?* | 100 | 小调 |
| Alternative R&B | *Intentions*, *Changes* | 75 | 小调 |
| Acoustic Pop | *Be Alright* | 92 | 大调 |
| Afrobeat/Pop | *Peaches*, *Hold On* | 90 | 大调 |
| Dark Pop R&B | *Honest*, *Stay* | 88 | 小调 |

### 2. 复制对应的 Style Prompt
进入 `examples/prompts/` 目录，复制对应风格的 Prompt 模板。

### 3. 粘贴到 Suno 中生成
将 Prompt 与你的原创歌词粘贴到 Suno Custom Mode 中，点击生成。

**推荐设置**：
- 每次生成 3-5 个变体
- 使用 `exactly [BPM]` 锁定速度
- 添加防串味标签防止风格跑偏

## 📚 文档

完整手册位于 [`docs/handbook.md`](docs/handbook.md)，包含：
- 核心量化体系
- 五大风格参数矩阵
- 融合风格方法论
- Suno 专属增强标签集
- 歌词工业化标准
- 完整实战案例

## 📂 示例

`examples/lyrics/` 目录下提供了多个已通过量化验证的原创歌词示例：
- `tropical-pop-edm_one-more-night.txt` —— Purpose 时期风格
- `dark-pop-rnb_lost-without-your-love.txt` —— 2023-2026 最新风格
- `acoustic-rnb_hold-me-close.txt` —— Acoustic R&B 融合风格
- `minimalist-rnb_alone-tonight.txt` —— 极简叙事风格

## 🤝 贡献

欢迎贡献新的风格分支、歌词示例或 Prompt 优化建议。请阅读 [`CONTRIBUTING.md`](CONTRIBUTING.md) 了解详情。

## 📄 许可证

本项目采用 MIT 许可证，详见 [`LICENSE`](LICENSE) 文件。示例歌词均为原创，可免费用于商业或非商业用途。

## ⚠️ 免责声明

本项目为独立创作，与 Justin Bieber 或其关联公司无关。所有标签旨在描述音乐风格特征，不侵犯任何版权。

---

**Star ⭐ 这个项目，让更多人用 AI 创作出高质量的流行音乐！**
