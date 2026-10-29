# FlowSkill · 中文实战 Agent Skills（免费版）

把 AI 编码助手变成**中文副业与自动化助手**的技能包。首批 3 个技能，全部免费、开源（MIT）。

> 完整版（10+ 中文实战技能 + 逐个场景文档 + 持续更新）整理中，发布时会在本页更新入口。

## 安装（Claude Code，两条命令）

在 Claude Code 里执行：

```
/plugin marketplace add https://github.com/yh1988/flowskill.git
/plugin install flowskill-free@flowskill-cn
```

> 请用上面的 **HTTPS 地址**：简写形式 `add yh1988/flowskill` 会走 SSH 克隆，没配置过 GitHub SSH 的机器会报 "host key verification failed"。如果你的机器已配好 GitHub SSH key，简写也可以用。

装好后直接说人话即可触发，例如：

- 「帮我生成一个 n8n 工作流：每天早上 8 点抓取 XX 网站更新，汇总发到飞书群」
- 「用小红书笔记工坊给我出 5 个标题，主题是二手书摊开店」
- 「我要挂一台 95 新的微单，帮我写闲鱼文案和议价话术」

## 免费版包含

| 技能 | 干什么 | 适合谁 |
|---|---|---|
| [n8n-workflow-forge](skills/n8n-workflow-forge/SKILL.md) | 需求描述 → 可导入 n8n 的 workflow JSON + 中文配置说明（含 Windows 自托管踩坑清单） | 自动化玩家、效率控 |
| [xhs-content-studio](skills/xhs-content-studio/SKILL.md) | 小红书笔记四件套（标题×5/正文/标签/封面文案）+ 选题日历 + 合规自检 | 自媒体、副业 |
| [xianyu-seller-kit](skills/xianyu-seller-kit/SKILL.md) | 闲鱼商品文案 + 买家应答话术 + 上架节奏复盘 | 闲鱼卖家、出闲置 |

## 为什么免费

这三个技能解决的是"上手"问题。生产级场景包（电商批量运营、自媒体矩阵、办公自动化流水线）需要持续维护与真实项目打磨，会以付费形式提供——免费版好用，付费版才值得买。

## 相关项目

- [flowkit-free](https://github.com/yh1988/flowkit-free)：n8n 中文工作流免费模板（3 个可直接导入的工作流）

## 支持作者

如果这两个项目对你有帮助，欢迎来 [爱发电](https://afdian.com/a/haoyard) 支持一下，也欢迎回流到 [FlowKit 完整版](https://afdian.com/a/haoyard)。

## License

MIT。技能内容为方法论与指令说明，使用产生的具体内容请自行核验合规性（广告法/平台规则）。
