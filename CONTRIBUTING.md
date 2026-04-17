# 贡献指南

感谢你对 Bieber-Style AI Music Guide 项目的关注！我们欢迎任何形式的贡献，包括但不限于：

- 新增风格分支（需附 Suno 验证结果）
- 优化现有 Style Prompt 标签
- 提供新的原创歌词示例
- 修正文档错误或补充说明
- 翻译文档到其他语言

## 如何贡献

### 1. Fork 项目
点击页面右上角的 Fork 按钮，将项目复制到你的 GitHub 账户下。

### 2. 创建分支
在你 Fork 的仓库中，创建一个描述性的分支名称：

```bash
git checkout -b add-new-style-branch
```

### 3. 进行修改
请遵循以下规范：

**风格分支新增规范**
- 在 `docs/handbook.md` 中按照现有格式添加新分支章节
- 必须包含：代表曲目、参数矩阵表、标准 Style Prompt 模板
- 在 `examples/prompts/` 下添加对应的 `.prompt.txt` 文件
- 如有原创歌词示例，放入 `examples/lyrics/` 下，命名格式为 `[分支]-[简短描述].txt`

**Prompt 标签规范**
- 使用英文标签，逗号分隔
- BPM 前必须加 `exactly`
- 防串味标签以 `no` 开头

**歌词规范**
- 每行不超过 10 个单词
- 包含结构标记如 `[Verse 1]`、`[Chorus]`
- 在文件顶部用注释注明第一人称密度和情感词频

### 4. 提交更改
提交信息请使用清晰的中文或英文：

```bash
git add .
git commit -m "新增 Afrobeat Trap 融合分支及示例歌词"
```

### 5. 推送并创建 Pull Request
```bash
git push origin add-new-style-branch
```

然后在 GitHub 页面上点击 "Compare & pull request"。

## 审核标准

Pull Request 将根据以下标准审核：
- 新增分支是否包含完整的参数矩阵
- Style Prompt 是否经过 Suno 实际测试（请附上至少一次生成结果的简要描述）
- 歌词示例是否达到第一人称密度 ≥10% 的要求
- 文档格式是否与现有内容一致

## 社区行为准则

请保持友善和尊重。我们致力于为所有人提供一个无骚扰的参与环境。
