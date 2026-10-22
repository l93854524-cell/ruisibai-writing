# 瑞斯拜四六级写作 Agent Skill

一个中文四六级写作辅导 Skill，依据瑞斯拜写作课八讲 AI 字幕与后续整理的 v1.2 教学模型编写。它帮助 AI 审题、搭框架、逐句练习、写范文和批改作文。

## 怎么用

在 GitHub 点击 **Code → Download ZIP**，解压后把顶层文件夹改名为 `ruisibai-writing`。

| 工具 | 把文件夹放到哪里 | 使用示例 |
|---|---|---|
| Claude Code | `~/.claude/skills/ruisibai-writing/` | `/ruisibai-writing 帮我分析这道四级作文题：……` |
| Codex | `~/.codex/skills/ruisibai-writing/` | `用 $ruisibai-writing 帮我批改这篇作文：……` |
| 普通 AI 聊天工具 | 打开 [普通AI主提示词.md](普通AI主提示词.md)，复制正文到聊天框 | 然后发送作文题目或草稿 |

装好后，确认文件夹内能看到 `SKILL.md` 和 `references/`。工具已在运行时，重新打开一次会话再试。

## 内容

- [SKILL.md](SKILL.md)：Agent Skills 入口文件。
- [teaching-method.md](references/teaching-method.md)：教学顺序与逐句示范。
- [genre-playbooks.md](references/genre-playbooks.md)：P1–P8 八种题型。
- [revision-rubric.md](references/revision-rubric.md)：作文批改流程。
- [source-provenance.md](references/source-provenance.md)：字幕依据、时间定位与规则边界。
- [普通AI主提示词.md](普通AI主提示词.md)：给普通聊天 AI 使用的单页提示词。

## 来源与边界

教学内容参考[瑞斯拜四六级写作模板课](https://www.bilibili.com/video/BV1vK4y1e7A6) P1–P8 的 AI 中文字幕，共 3,302 条。细节和时间定位见 [来源说明](references/source-provenance.md)。仓库没有收录视频、原始字幕 JSON、课件或教师原版模板。

文件中把课程明确讲解、字幕归纳和 v1.2 新增的 AI 交互／批改规则分开标注。AI 字幕可能有转写错误；本项目未经讲者认可或授权，也不代表官方四六级评分标准。使用时请核对英文表达和作文题目要求。

## 许可证

本仓库原创的 Skill 指令与说明按 [MIT License](LICENSE) 开放。第三方课程、视频、字幕及其权利仍归各自权利人。
