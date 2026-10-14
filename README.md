# 化学课程与学术英语导师

大学化学学习技能，覆盖有机、无机、物理、分析化学及相关数学。版本 **1.1.0**，更新于 2026-10-15。

保留英文专业术语，按需要用中文拆解复杂机制。先检查课件文字、原图和 speaker notes，再结合提供的录播转写。所有教学规则都在一个 SKILL.md 中，不依赖额外的教学偏好文件。

## 四种模式

| 模式 | 教学方式 |
| --- | --- |
| 跟课 | 通常 3–5 句，连接当前概念与前文，不出题 |
| 预习 | 简短地图、关键新词、带着听课的问题 |
| 深度学习 | 一个模块、一个主要问题、等待回答、针对性反馈 |
| 复习 | 先凭记忆作答，再讲薄弱点，结束提供自测卡 |

学生明确要求直接解释、不提问或完整总结时，优先遵守。不会把一次答对当作长期掌握，不会假装读过未提供的课件。

## 发给同学

把本仓库链接发给同学即可查看完整规则和安装方式。本版本不包含原作者的学校、成绩或英语水平设定；根据使用者实际背景调整。

## 在支持技能安装的 Codex 中使用

把下面这句话发送给 Codex：

> 使用 skill-installer，从 GitHub 仓库 zhuzeming161-cell/chemistry-tutor 的 plugins/chemistry-tutor/skills/chemistry-course-tutor 路径安装 chemistry-course-tutor 技能。

安装后可说：

> 用 chemistry-course-tutor 根据我的化学课件和 speaker notes，图文结合带我学习。

具体环境是否支持安装由该环境提供的功能决定。仓库链接是源文件入口，不是已经安装到某个 ChatGPT 账户的证明。

## 普通 ChatGPT 或其他 AI 中使用

打开 [完整教学规则](plugins/chemistry-tutor/skills/chemistry-course-tutor/SKILL.md)，复制全部内容到新对话，说明“请按这套规则教学”，然后上传课件。这样可在当前对话使用规则；是否能保存为长期技能取决于产品的功能。

## 文件结构

- plugins/chemistry-tutor/.codex-plugin/plugin.json：插件配置。
- plugins/chemistry-tutor/skills/chemistry-course-tutor/SKILL.md：完整规则。
- plugins/chemistry-tutor/skills/chemistry-course-tutor/agents/openai.yaml：技能显示名称与入口提示。
- .agents/plugins/marketplace.json：插件目录配置。

## 已完成的检查

- 技能 frontmatter、名称与目录结构检查。
- 配置路径及不含原作者个人背景的检查。
- 跟课样例：catalyst 与 equilibrium，保持四句、不提问、不假称读取了 PPT。
- 深度学习样例：nucleophile 与 electrophile，一个模块后只问一个主要问题。
- 使用官方 GitHub skill-installer 成功下载并安装到隔离测试目录，安装后的 SKILL.md 与发布源文件逐字一致，元数据检查通过。
- 尚未在接收同学的账户完成安装验证。

## 学生背景

仅在当前教学需要时询问课程层次、已有基础和语言偏好。使用者可随时覆盖默认方式，无需沿用原作者背景。
