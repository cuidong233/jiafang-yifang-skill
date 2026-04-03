# 甲方乙方

![AI Claude Code](https://img.shields.io/badge/AI-Claude%20Code-111111?style=flat-square)
![OpenAI Codex CLI](https://img.shields.io/badge/OpenAI-Codex%20CLI-6f42c1?style=flat-square)
![Multi-Language](https://img.shields.io/badge/Multi--Language-2b6cb0?style=flat-square)
![License MIT](https://img.shields.io/badge/License-MIT-84cc16?style=flat-square)

写给乙方。

不是教你跪着服务甲方。

也不是教你逢人就硬刚。

它更像一个在项目现场见过太多翻车的人，站在你旁边提醒你：

- 这不是机会，这是坑
- 这不是需求，这是试探
- 这不是合作，这是白嫖
- 这不是难搞，这是没预算
- 这不是客户爸爸，这是采购关系

## 这个 skill 解决什么

- 这个单该不该接
- 客户值不值得长期做
- 怎么报价
- 怎么防需求失控
- 怎么设交付边界
- 怎么做验收
- 怎么催回款
- 怎么把自己从人肉耗材做成有议价权的乙方

## 适合谁

- 顾问
- 外包团队
- 代运营
- 自由职业者
- 小老板
- 一切经常要和甲方打交道的乙方

## 这个 skill 的底层判断

- 甲乙方先是交易，再谈关系
- 客户会测试边界，这是常态
- 没写进书面的东西，最后都可能不算数
- 报价不是按辛苦定，而是按价值、风险和市场定
- 真正厉害的乙方，不是更能熬，而是更会积累资产和议价权

## 安装结构

这个仓库本身就是插件根目录：

- `.codex-plugin/plugin.json`
- `.claude-plugin/plugin.json`
- `skills/jiafang-yifang/SKILL.md`
- `skills/jiafang-yifang/references/source-notes.md`
- `skills/jiafang-yifang/references/source-excerpts.md`
- `skills/jiafang-yifang/references/originals/`

如果你只是想参考写法，直接看：

- [skills/jiafang-yifang/SKILL.md](skills/jiafang-yifang/SKILL.md)

如果你想看这些规则是从什么类型的材料里提炼出来的，再看：

- [skills/jiafang-yifang/references/source-notes.md](skills/jiafang-yifang/references/source-notes.md)

如果你想直接看公开参考摘录，再看：

- [skills/jiafang-yifang/references/source-excerpts.md](skills/jiafang-yifang/references/source-excerpts.md)

如果你想直接读整篇原文文章，而不是摘录，再看：

- [skills/jiafang-yifang/references/originals/2021-11-05_除了流水线之外，绝大多数的加班就是划水而已.md](skills/jiafang-yifang/references/originals/2021-11-05_除了流水线之外，绝大多数的加班就是划水而已.md)
- [skills/jiafang-yifang/references/originals/2022-01-07_西安一码通崩了两次，崩掉一个大数据资源管理局局长.md](skills/jiafang-yifang/references/originals/2022-01-07_西安一码通崩了两次，崩掉一个大数据资源管理局局长.md)
- [skills/jiafang-yifang/references/originals/2023-06-15_让我们揭开某些生意暴利的秘密.md](skills/jiafang-yifang/references/originals/2023-06-15_让我们揭开某些生意暴利的秘密.md)
- [skills/jiafang-yifang/references/originals/2023-10-06_国内的创业者完全不是你想的那样.md](skills/jiafang-yifang/references/originals/2023-10-06_国内的创业者完全不是你想的那样.md)
- [skills/jiafang-yifang/references/originals/2024-03-18_先聊大明王朝1566，再谈邯郸未成年人谋杀案.md](skills/jiafang-yifang/references/originals/2024-03-18_先聊大明王朝1566，再谈邯郸未成年人谋杀案.md)
- [skills/jiafang-yifang/references/originals/2025-01-22_富人想要的不是钱，是说了算.md](skills/jiafang-yifang/references/originals/2025-01-22_富人想要的不是钱，是说了算.md)
- [skills/jiafang-yifang/references/originals/2025-02-10_孩子到底能不能填报工商管理志愿？.md](skills/jiafang-yifang/references/originals/2025-02-10_孩子到底能不能填报工商管理志愿？.md)
- [skills/jiafang-yifang/references/originals/2026-02-12_乔海伦是史上最牛马的小三么？.md](skills/jiafang-yifang/references/originals/2026-02-12_乔海伦是史上最牛马的小三么？.md)

## 适配结构

仓库里已经放了两套插件清单：

- `.codex-plugin/plugin.json`
- `.claude-plugin/plugin.json`

同一份 `skills/` 目录可以同时给不同 agent 工具链复用。

## 一句话总结

这不是“教你服务好甲方”的 skill。

这是“别把自己做成甲方耗材”的 skill。
