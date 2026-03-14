# 贡献指南 / Contributing Guide

[中文](#中文) | [English](#english)

---

## 中文

感谢你对 Awesome Agent Skills 的贡献兴趣！

### 如何贡献

#### 添加新的 Skill

1. **Fork** 这个仓库
2. 在 README.md 和 README_ZH.md 中找到合适的分类
3. 按照格式添加你的 skill：

```markdown
| skill-name | 简短描述 | 支持平台 | [GitHub](URL) |
```

4. 提交 **Pull Request**

### 贡献要求

#### 必须满足

- [ ] Skill 必须是公开可访问的
- [ ] 必须包含 SKILL.md 文件（纯 MCP 服务器或 REST API 封装不符合收录标准）
- [ ] 描述必须清晰准确
- [ ] 链接必须有效
- [ ] GitHub 仓库至少 **50+ Stars**（确保一定的社区认可度）
- [ ] 必须同时更新 `README.md` 和 `README_ZH.md`（保持双语同步）
- [ ] PR 提交前请检查格式，确保不会破坏现有文档结构

#### 建议

- [ ] 优先收录开源项目（商业产品封装需要更高的社区认可度）
- [ ] 提供中英文描述
- [ ] 包含使用示例

### 格式规范

#### Skill 条目格式

```markdown
| 名称 | 描述 | 平台 | 链接 |
|------|------|------|------|
| my-skill | 做什么的简短描述（10-20字） | All | [链接](https://github.com/...) |
```

#### 平台标识

- `All` - 支持所有平台
- `Cursor` - 仅 Cursor
- `Claude` - 仅 Claude
- `Codex` - 仅 Codex
- 多个平台用 `/` 分隔：`Cursor/Claude`

### 分类说明

| 分类 | 说明 |
|------|------|
| 官方资源 | 官方维护的资源和标准 |
| Skills 合集 | 多个 skills 的集合仓库 |
| 开发工具 | 代码审查、调试、测试等 |
| 效率提升 | 通用生产力工具 |
| 写作创作 | 文档、文章相关 |
| 数据处理 | 数据分析、转换 |
| DevOps | 部署、运维相关 |
| 设计相关 | UI/UX 设计 |

如果你的 skill 不属于现有分类，可以在 PR 中建议新分类。

### PR 模板

提交 PR 时，请包含以下信息：

```markdown
## 添加 Skill

**名称**：
**链接**：
**描述**：
**分类**：

## 检查清单

- [ ] 链接有效
- [ ] 包含 SKILL.md
- [ ] GitHub 仓库 50+ Stars
- [ ] 描述准确
- [ ] 放在正确分类
- [ ] 按字母顺序排列
- [ ] 同时更新了 README.md 和 README_ZH.md
```

### 报告问题

如果发现失效链接、错误描述或分类不当，请提交 Issue 或直接 PR 修复。

### 行为准则

- 尊重所有贡献者
- 保持友好的讨论氛围
- 专注于技术内容

如有疑问，欢迎提交 Issue 讨论。

---

## English

Thanks for your interest in contributing to Awesome Agent Skills!

### How to Contribute

#### Adding a New Skill

1. **Fork** this repository
2. Find the appropriate category in both README.md and README_ZH.md
3. Add your skill following the format:

```markdown
| skill-name | Short description | Platform | [GitHub](URL) |
```

4. Submit a **Pull Request**

### Requirements

#### Must Have

- [ ] Skill must be publicly accessible
- [ ] Must contain a SKILL.md file (pure MCP servers or REST API wrappers do not qualify)
- [ ] Description must be clear and accurate
- [ ] Link must be valid
- [ ] GitHub repository must have at least **50+ Stars** (to ensure community validation)
- [ ] Must update both `README.md` and `README_ZH.md` (keep bilingual READMEs in sync)
- [ ] Please verify formatting before submitting — PRs that break existing document structure will be rejected

#### Recommended

- [ ] Open source projects preferred (commercial product wrappers require higher community validation)
- [ ] Provide bilingual description (English/Chinese)
- [ ] Include usage examples

### Format Guidelines

#### Skill Entry Format

```markdown
| Name | Description | Platform | Link |
|------|-------------|----------|------|
| my-skill | Short description of what it does (10-20 words) | All | [Link](https://github.com/...) |
```

#### Platform Labels

- `All` - Supports all platforms
- `Cursor` - Cursor only
- `Claude` - Claude only
- `Codex` - Codex only
- Multiple platforms separated by `/`: `Cursor/Claude`

### Categories

| Category | Description |
|----------|-------------|
| Official Resources | Officially maintained resources and standards |
| Skills Collections | Repositories containing multiple skills |
| Development Tools | Code review, debugging, testing, etc. |
| Productivity | General productivity tools |
| Writing | Documentation, articles |
| Data Processing | Data analysis, transformation |
| DevOps | Deployment, operations |
| Design | UI/UX design |

If your skill doesn't fit existing categories, feel free to suggest a new one in your PR.

### PR Template

Please include the following information when submitting a PR:

```markdown
## Add Skill

**Name**:
**Link**:
**Description**:
**Category**:

## Checklist

- [ ] Link is valid
- [ ] Contains SKILL.md
- [ ] GitHub repository has 50+ Stars
- [ ] Description is accurate
- [ ] Placed in correct category
- [ ] Alphabetically ordered
- [ ] Updated both README.md and README_ZH.md
```

### Report Issues

If you find broken links, incorrect descriptions, or miscategorized items, please submit an Issue or a PR to fix them.

### Code of Conduct

- Respect all contributors
- Maintain a friendly discussion atmosphere
- Focus on technical content

If you have any questions, feel free to open an Issue.

---

Thanks for contributing! 🎉
