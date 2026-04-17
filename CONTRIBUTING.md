# Contributing to Bieber-Style AI Music Guide

感谢你对本项目感兴趣！我们欢迎任何形式的贡献，包括但不限于：

- 新增风格分支或融合分支
- 优化现有 Style Prompt 标签
- 提供新的歌词示例
- 修正文档错误或补充说明
- 分享生成经验与实测数据

## 如何贡献

### 1. 提交 Issue

如果你有想法、建议或发现了问题，请先在 [Issues](../../issues) 中搜索是否已有相关讨论。若无，可新建 Issue 并描述清楚。

### 2. Fork 与 Pull Request

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/amazing-feature`)
3. 提交你的修改 (`git commit -m 'Add some amazing feature'`)
4. 推送到远程分支 (`git push origin feature/amazing-feature`)
5. 发起 Pull Request

### 3. Pull Request 规范

- 标题清晰，简述修改内容
- 描述中说明修改原因和测试情况
- 确保与现有风格保持一致

## 贡献内容规范

### 新增风格分支

如需新增风格分支，请在 `docs/handbook.md` 中按以下模板补充：

### X.X 分支名称

**代表曲目**：*歌曲1*、*歌曲2*

| 参数 | 标准值 |
| :--- | :--- |
| BPM | XX |
| 调性 | XX |
| 核心配器 | `标签1`、`标签2` |
| 人声特征 | `标签1`、`标签2` |
| 空间效果 | `标签1` |

**Style Prompt 模板**：
\`\`\`
完整的 Style Prompt
\`\`\`
```

### 新增歌词示例

- 文件放置于 `examples/lyrics/` 目录
- 命名格式：`[分支名]_[歌名简写].txt`
- 歌词需通过量化验证（第一人称密度 ≥10%，Hook 音节数与重复次数达标）
- 文件头部可添加简短说明（风格、BPM、情感主题）

### 新增 Prompt 模板

- 文件放置于 `examples/prompts/` 目录
- 命名格式：`[分支名].prompt.txt`
- 内容为可直接复制使用的 Style Prompt

## 量化验证工具

我们建议贡献者在提交歌词示例前，运行以下简易检查：

- **第一人称密度**：计算 `I/me/my/mine` 出现次数 / 总词数 ≥ 10%
- **Hook 音节数**：理想值 4，范围 3-6
- **Hook 长元音**：至少包含一个长元音
- **Hook 重复次数**：全曲至少重复 3 次

## 行为准则

请保持友善、尊重他人。我们致力于为每位贡献者提供友好、包容的协作环境。

## 疑问？

如有任何疑问，欢迎在 Issue 区提问或联系维护者。

再次感谢你的贡献！
