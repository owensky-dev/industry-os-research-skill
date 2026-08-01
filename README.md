# Industry OS Research Skill

`industry-os-research` 是一个面向 Codex 的行业研究 Skill，用来把陌生行业从零散信息整理成可持续更新的 Industry OS。

它不是让 AI 临时写一篇行业分析，而是帮助你建立一套可复用、可更新、可导入 Obsidian 的行业研究系统：行业数据库、竞品数据库、内容生态、知识地图、情报周报和机会地图。

## 适合什么时候用

- 快速进入一个陌生行业或新品类
- 为某个市场建立 Obsidian 友好的知识库
- 系统拆解竞品如何赚钱
- 研究行业内容生态和重复爆款模式
- 建立关键词、用户痛点、品牌、产品、渠道数据库
- 把一次性调研升级成每周/月持续更新的行业情报系统

## 它会产出什么

典型输出结构：

```text
Industry-OS
├── 00-Research-Brief
├── 01-Industry-Database
├── 02-Competitor-Database
├── 03-Content-Database
├── 04-Knowledge-Map
├── 05-Intelligence-System
└── 06-Opportunity-Map
```

核心能力：

- 建立行业数据库：品牌、产品、用户、痛点、关键词、渠道、社区、趋势、机会
- 反向拆解竞品：网站结构、产品结构、Collection、Tag、SEO、Blog、社媒、Offer、转化路径
- 研究内容生态：YouTube、TikTok、Instagram、X、Reddit、Newsletter、Blog 等平台的账号和爆款模式
- 构建知识地图：一级/二级/三级行业地图、节点卡片、连接关系、机会地图
- 搭建情报系统：信息源、竞品监控、内容监控、周报、月度地图更新
- 强制质量门槛：明确地区/时间范围，标注来源，区分事实和推断，不虚构 Top100

## 安装方式

把 `industry-os-research` 文件夹复制到你的 Codex skills 目录：

```bash
mkdir -p ~/.codex/skills
cp -R industry-os-research ~/.codex/skills/
```

安装后重新打开 Codex 新对话，使用：

```text
用 $industry-os-research 研究美国宠物保健品 DTC 行业。
```

或者自然语言触发：

```text
帮我快速了解一个陌生行业，并建立 Obsidian 可用的行业数据库、竞品数据库、内容生态和机会地图。
```

## 推荐提示词

建立行业数据库：

```text
用 $industry-os-research 帮我建立一个 {行业/地区/年份} 行业数据库。输出 Obsidian 友好的 Markdown 目录结构，并为每个目录说明应收集哪些字段、来源和更新频率。
```

竞品拆解：

```text
用 $industry-os-research 分析这些竞品网站：{URLs}。请按导航结构、产品结构、Collection/分类、Product Tag、SEO、Blog、社媒、Offer、转化路径和商业模式输出 Markdown 报告，并总结共性模式。
```

内容生态研究：

```text
用 $industry-os-research 整理 {行业} 在 {平台列表} 的内容生态。输出账号样本、近 {时间范围} 高表现内容、内容类型分类、重复爆款模式、可复用选题库和内容机会。
```

知识地图：

```text
用 $industry-os-research 拆解 {行业}。输出一级、二级、三级知识地图；为关键节点建立知识卡片；最后给出连接关系和机会地图。
```

行业周报：

```text
用 $industry-os-research 基于已有 Industry OS，生成本周行业情报周报：行业变化、竞品动作、爆款内容、关键词变化、风险信号、机会变化和下周建议。
```

## 仓库描述

建议 GitHub repo description：

```text
A Codex skill for building a living Industry OS from industry databases, competitor research, content ecosystems, knowledge maps, monitoring, and opportunity discovery.
```

## 文件结构

```text
.
├── README.md
└── industry-os-research
    ├── SKILL.md
    └── agents
        └── openai.yaml
```

## 设计来源

这个 Skill 来自一套「用 Codex 快速了解陌生行业」的方法论蒸馏，核心思想是：不要停留在搜索和阅读，而是把信息源、数据库、知识地图、情报系统和机会发现串成一个长期增长的认知资产。

## 关注公众号

如果这个 Skill 对你有帮助，欢迎关注微信公众号 **虎皮叔叔聊跨境独立站**，获取更多独立站增长、行业研究与 AI 营销实操内容。

<p align="center">
  <img src="assets/wechat-qr.png" alt="虎皮叔叔聊跨境独立站公众号二维码" width="900">
</p>

<p align="center">微信扫码关注「虎皮叔叔聊跨境独立站」</p>
