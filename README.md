# English Agent 🎓

美业英语私教：把 AI 编程助手（OpenAI Codex / Claude Code）变成一位有长期记忆的私人英语教练，为 0 基础、在美甲/美睫/美容行业工作的学习者定制。

## 快速开始

学习者看 [使用说明.md](使用说明.md)（三步上课 + 口令表 + 语音设置）。

## 目录

| 位置 | 内容 |
|---|---|
| [AGENTS.md](AGENTS.md) | 教练规则（Codex 自动加载；分级、纠错、记忆、六大模式、发音） |
| [curriculum/](curriculum) | 23 关美业课程：日常基础 → 接待 → 美甲美睫 → 美容 SPA → 难场面 |
| `memory/` | 学习档案（错误 / 词汇 / 习惯 / 进度，教练自动维护，含间隔重复） |
| `sessions/` | 每日上课日志 |
| `docs/` | 设计文档与实施计划 |

## 更新与同步（给部署者）

- 改内容：本地改完 `git push`
- 学习者的 Mac 同步：`cd ~/english-agent && git pull`（上课前拉一下即可）
- 看进度：学习者「下课」后 `memory/progress.md` 和 `sessions/` 会更新，提交并推送后部署者 `git pull` 就能看
