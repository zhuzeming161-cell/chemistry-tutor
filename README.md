# 化学课程与学术英语导师

面向大学化学课程的独立教学技能。覆盖有机、无机、物理与分析化学；保留英文专业术语，用中文解释复杂机制。根据使用者实际背景调整，不预设学校、成绩或英语水平。

## 教学方式

- 阅读课件文字、原图与 speaker notes，结合提供的录播转写。
- 图与解释一起呈现；动态过程尽量配动画或连续阶段图。
- 小模块讲清因果，通过一个问题检查理解；明确要求直接解释时不强制问答。
- 公式解释变量、单位与假设，实验区分观察、证据与结论。
- 有机机理检查电子箭头、formal charge、stereochemistry；物理化学区分 thermodynamics 与 kinetics。

## 文件

- `plugins/chemistry-tutor/.codex-plugin/plugin.json`：插件配置。
- `plugins/chemistry-tutor/skills/chemistry-course-tutor/SKILL.md`：完整教学规则，所有规则均包含在此文件，无额外引用文件。
- `.agents/plugins/marketplace.json`：插件目录配置。

## 使用

在支持 GitHub 技能安装的 Codex 环境，可要求内置 skill-installer 从本仓库的 `plugins/chemistry-tutor/skills/chemistry-course-tutor` 路径安装。支持插件的环境可按其仓库导入流程使用插件目录。

只有普通聊天功能时，也可把完整 SKILL.md 作为教学偏好提供，并上传课件。提供文本本身不等于完成技能安装。

示例：『根据我的化学课件和 speaker notes，图文结合带我学习。复杂机制用中文解释，保留英文术语。』

## 验证范围

文件结构、技能元数据格式、配置路径及移除原作者个人背景的检查已通过。此前对教学规则做过一例 catalyst 与 equilibrium 的行为测试；未在同学账户完成端到端安装验证。

仓库可见性与具体产品支持决定同学是否能访问或安装，不能把仓库链接当作已经生效的账户安装链接。
