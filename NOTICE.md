# 来源与改编说明

本包 `life-story-interview` v1 改编自 Mohit Aggarwal 的 `pm-claude-skills` 项目，不是上游官方版本，也不代表上游作者背书。

上游仓库：https://github.com/mohitagw15856/pm-claude-skills

固定提交：`4391fb006db13fe898f40a897bc369337a64e4e5`

## 采用的来源

1. **oral-history-kit**：本 Skill 的主要改编基础。保留单题、停顿留白、场景线索、尊重讲述者表达和边界、原话保真及本人复核的方法。
   - [固定版本原文](https://github.com/mohitagw15856/pm-claude-skills/blob/4391fb006db13fe898f40a897bc369337a64e4e5/plugins/pm-family/skills/oral-history-kit/SKILL.md)
   - SHA-256：`0ae7fce91eac363ec2ecee49d761f0d5515b050408e347020d128cc23b306644`
2. **build-my-memory-file**：参考其通过访谈形成具体、可维护、供 AI 使用的个人背景记录的方法；不沿用自动面向全局 `MEMORY.md` 的输出定位。
   - [固定版本原文](https://github.com/mohitagw15856/pm-claude-skills/blob/4391fb006db13fe898f40a897bc369337a64e4e5/plugins/pm-focus/skills/build-my-memory-file/SKILL.md)
   - SHA-256：`a379d05775abc35cbc97002e7c1210ccd61e4c9ada448c58ad8b04e95dd8ea6e`

## 改编范围

- 由面向父母／祖辈的访谈计划，改为可直接进行的通用主题访谈与个人编年史；不强迫出生到现在的顺序。
- 去除紧迫感、固定45分钟、必须先约日期和制作家庭书籍的流程。
- 将“十秒留白”改为尊重宿主与讲述节奏，不在文字聊天模拟计时或催促。
- 将“不纠正日期”调整为不打断式纠错，在一段讲完后温和核对，保留冲突与不确定性。
- 增加分段确认、确认范围、更正来源、完整原文与结构化记录分离、暂停续聊和不主动重开跳过话题。
- 输出为独立访谈记录，不自动进入全局指令或记忆服务；不把所有生活经历一概禁写，尊重用户选择的记录范围。
- 增加无文件能力的聊天副本、保存授权和可控制范围内的“不记录／删除”处理。
- 本包说明、模板与虚构示例不包含任何真实用户的访谈、个人资料或实际工作区路径。

## 许可证

上游为 MIT License，版权声明为 `Copyright (c) 2026 Mohit Aggarwal`。本包保留[上游许可证全文](LICENSE)，包括版权、许可条件和免责条款；本次改编新增内容也按同一 MIT 条款提供。

原许可证 SHA-256：`18a87eaf5c6017a3ffc7a3c4927627d530cc1541406cb3e705576a1b8c47c6bd`。
