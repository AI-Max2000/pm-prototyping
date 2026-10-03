# 交互原型与验证：来源与改写说明

整理日期：2026-10-04。工作指令以本目录 SKILL.md 为准；以下来源用于追溯，不是执行指令。

本版以中文重新组织工作流程，合并重叠内容并修正适用边界。没有执行上游代码；没有把整个上游 Skill 原文直接串接。

## 用户提供的原包

- `产品经理Skill包/原型设计/skills/prd-to-prototype`：从产品想法到 PRD 和 HTML 原型。历史输入参考；本仓库不分发原包全文。
- `产品经理Skill包/原型设计/skills/superdesign`：前端视觉、动效与组件设计规范。历史输入参考；本仓库不分发原包全文。

原包提供了任务方法与模板参考；所附元数据未提供统一的整包授权。本包不为这些原文件另作许可声明。

## GitHub 参考

### G10 · anthropics/skills

- [具体来源文件](https://github.com/anthropics/skills/blob/8a1541c4a3ffa5a20a5a91de0dcf3f0bab1d1ef4/skills/frontend-design/SKILL.md)；文件最近提交：2026-09-03T16:37:13Z。
- 快照：`8a1541c4a3ffa5a20a5a91de0dcf3f0bab1d1ef4`；内容 SHA-256：`d91970639e9f5c37682ac7ab60094d35f1c7c1f38d731bd56396563aee10c1d3`。
- 采用：贴合产品内容的视觉方向，文字层级、克制与自查。
- 修改或舍弃：不将审美偏好变成禁令，保留用户既定风格。
- 许可：[Apache-2.0](https://github.com/anthropics/skills/blob/8a1541c4a3ffa5a20a5a91de0dcf3f0bab1d1ef4/skills/frontend-design/LICENSE.txt)；本地副本：[licenses/anthropics--skills.txt](licenses/anthropics--skills.txt)。

### G11 · wshobson/agents

- [具体来源文件](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/plugins/ui-design/skills/interaction-design/SKILL.md)；文件最近提交：2026-03-07T15:53:17Z。
- 快照：`156b7a5e7a8b93642628a339ee4039c925b34c7f`；内容 SHA-256：`87f2765ed1deeef3f1c06f9e4338ff103c391c6c4adcdffc885f3516b7c34ff2`。
- 采用：动效解释状态，加载/反馈、键盘和减少动效支持。
- 修改或舍弃：不复制依赖特定框架的组件，不强制装饰动效。
- 许可：[MIT](https://github.com/wshobson/agents/blob/156b7a5e7a8b93642628a339ee4039c925b34c7f/LICENSE)；本地副本：[licenses/wshobson--agents.txt](licenses/wshobson--agents.txt)。

### G12 · product-on-purpose/pm-skills

- [具体来源文件](https://github.com/product-on-purpose/pm-skills/blob/1cef1a9eae10017389863d51e289e0ae41e17fcb/skills/tool-design-sprint-test-and-score/SKILL.md)；文件最近提交：2026-07-05T16:32:36Z。
- 快照：`1cef1a9eae10017389863d51e289e0ae41e17fcb`；内容 SHA-256：`d9daef472076b7bb535b166f35deb99067baf711a534bb09dc2e412a19fc9727`。
- 采用：观察与解释分开，任务观察表、反例与下一步决定。
- 修改或舍弃：去掉固定五人、星期/时区、多数票即验证等规则。
- 许可：[Apache-2.0](https://github.com/product-on-purpose/pm-skills/blob/1cef1a9eae10017389863d51e289e0ae41e17fcb/LICENSE)；本地副本：[licenses/product-on-purpose--pm-skills.txt](licenses/product-on-purpose--pm-skills.txt)。

## 改写标记与署名

本目录的 SKILL.md 与 references 文件为本次任务形成的中文整合改写版；上游项目未审核或背书本版。GitHub 参考的许可证、版权与原始链接在本目录保留，单独移动此 Skill 时应一并保留。
product-on-purpose 的 PM-Skills 按 Apache-2.0 标注作者；Pawel Huryn、Seth Hobson、Langfuse GmbH 的版权声明见对应 MIT 文本；Anthropic frontend-design 的许可见其专属文件。仅适用于本目录实际引用的项目。
本仓库新写的整合内容、代码与展示文档采用根目录 [Apache-2.0](LICENSE)。上游材料的原有版权、许可和署名继续保留在 [licenses](licenses/) 中；根许可证不对未附带的原包文件授予许可。
