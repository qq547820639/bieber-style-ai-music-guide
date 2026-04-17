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

```markdown
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
