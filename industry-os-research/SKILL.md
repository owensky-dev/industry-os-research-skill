---
name: industry-os-research
description: >-
  Build a living Industry OS for quickly understanding unfamiliar industries:
  source discovery, industry database, competitor reverse engineering, content
  ecosystem, keyword/user pain databases, knowledge maps, monitoring, weekly
  intelligence reports, and opportunity discovery. Use when the user wants to
  research, enter, map, monitor, or understand a new industry or turn scattered
  market information into an Obsidian-ready knowledge base or repeatable research
  workflow.
---

# Industry OS Research

## Principle

Turn scattered information into a reusable industry operating system. Do not stop at a one-off answer. Build structured knowledge that can be stored, updated, compared, and used for decisions.

The target output is usually:

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

## Intake

Before researching, identify:

- Industry or niche
- Geography and language
- Time horizon, such as current year, last 90 days, or last 12 months
- User goal: learn, launch product, invest, build content, SEO, ads, ecommerce, partnerships, or monitoring
- Preferred output: chat summary, Markdown folder plan, Obsidian vault structure, report, dashboard, or recurring workflow

If the user omits details, make conservative assumptions and state them. Ask only when geography, time range, or goal would materially change the research.

For current market facts, recent players, pricing, rankings, traffic, funding, regulations, or social/content performance, verify with up-to-date sources and cite them.

## Workflow

### 1. Define the research brief

Create a short brief before building the database:

- Scope: what is included and excluded
- Core questions: who buys, who sells, who wins, why now, where growth comes from
- Source plan: official sites, marketplaces, search data, social platforms, communities, reports, filings, newsletters, and competitor pages
- Evidence rules: source every factual claim; mark estimates; include retrieval dates; separate observation from inference

### 2. Build the industry database

Create an Obsidian-friendly structure. Adapt the folders to the niche, but start with:

```text
01-Industry-Database
├── Brands
├── Products
├── Customers
├── Pain-Points
├── Keywords
├── Communities
├── Influencers
├── Channels
├── Business-Models
├── Supply-Chain
├── Regulations
├── Trends
└── Opportunities
```

For brands, capture:

- Name, website, country, positioning, hero products, price range, sales channels, traffic or scale signals, core claims, founder/company background, social accounts, and source links

For products, capture:

- Product type, ingredients/features, user jobs-to-be-done, claims, pricing, reviews, advantages, drawbacks, leading brands, channel fit, and market size signals

For pain points, prioritize community and review evidence:

- High-frequency complaints
- High-frequency desires
- Repeated objections
- Failed alternatives
- Language users use naturally
- Possible product/content/positioning opportunities

For keywords, separate:

- Commercial
- Informational
- Comparison
- Review
- Buying intent
- Platform-specific terms, such as Google, Amazon, Reddit, YouTube, TikTok, or app stores

### 3. Reverse-engineer how the industry makes money

Select representative competitors, then analyze patterns instead of isolated screenshots.

For each competitor, inspect:

- Website navigation
- Product categories
- Collections or landing pages
- Product tags and filters
- Pricing ladder and bundles
- Offers, guarantees, subscriptions, upsells, and cross-sells
- SEO structure
- Blog/content structure
- Social channels
- Ads or affiliate signals when available
- Conversion and trust elements

Then synthesize:

- Common category structure
- Repeated offers
- Repeated SEO topics
- Repeated conversion paths
- Margin or monetization clues
- What mature players are consistently doing
- Where smaller players are copying or differentiating

Recommended output:

```text
02-Competitor-Database
├── Website-Structure
├── Product-Structure
├── Collection-Structure
├── Tag-Structure
├── SEO-Structure
├── Blog-Structure
├── Social-Structure
└── Monetization-Patterns
```

### 4. Build the content ecosystem database

Do not study only a few accounts. Build a sample large enough to see repeated patterns.

Track by platform:

- YouTube
- TikTok
- Instagram
- X
- Reddit
- Newsletters
- Blogs
- Podcasts, if relevant

For each account or publisher, capture:

- Name, URL, platform, audience size, posting frequency, core topics, top-performing content, monetization model, and source link

Classify content into:

- Exposure: strong opinion, controversy, timely trend, broad reach
- Growth: resource lists, recommendations, account discovery, follow-worthy value
- Save: steps, SOPs, templates, workflows, checklists
- Conversion: case studies, results, demos, offers, proof
- Personal brand: story, origin, mistakes, reflection, behind-the-scenes

Look for repeated winners:

- Topics that repeatedly perform
- Title structures that repeatedly perform
- Formats that repeatedly perform
- Hooks that repeatedly perform
- Content gaps where demand is visible but supply is thin

### 5. Build the knowledge map

Use the database to create an industry map with levels and links.

Start with a tree:

```text
04-Knowledge-Map
├── overview.md
├── level-1-map.md
├── node-cards
├── connection-map.md
└── roadmap.md
```

Each node card should include:

- Definition
- Why it exists
- Key companies/products
- User/customer problem
- Business model
- Growth drivers
- Risks
- Related nodes
- Open questions
- Opportunities

Add connection maps where a tree is too simple. Useful relationship chains include:

- Technology -> product -> channel -> revenue
- User pain -> product claim -> content angle -> conversion path
- Regulation -> supply constraint -> positioning opportunity
- Platform trend -> content format -> customer acquisition strategy

### 6. Convert the knowledge base into an intelligence system

Move from search mode to subscription mode.

Build:

```text
05-Intelligence-System
├── Sources
├── Monitoring
├── Weekly-Reports
├── Monthly-Map-Updates
└── Decision-Log
```

Source categories:

- Official company blogs
- Industry media
- Newsletters
- Communities
- Social accounts
- Search/marketplace keywords
- Competitor websites
- Regulatory sources
- Funding or hiring signals when relevant

Weekly monitoring should answer:

- What changed this week?
- Which products, companies, or topics gained attention?
- Which competitors changed pages, offers, pricing, collections, or content?
- Which posts/videos/newsletters performed unusually well?
- Which new risks or regulations appeared?
- Which opportunities became more or less attractive?

Monthly map updates should:

- Add new nodes
- Merge stale or redundant nodes
- Update opportunity ratings
- Mark dead trends
- Record assumptions that changed

## Quality Gates

Before delivering, check:

- Scope is clear: industry, geography, audience, and timeframe are stated.
- Facts have sources or are explicitly marked as estimates.
- Recent claims use recent sources.
- Lists such as Top 50 or Top 100 are not invented when data is unavailable; use "starter sample" or "known examples" instead.
- Tables preserve fields that are useful for later filtering and comparison.
- Insights separate what was observed from what was inferred.
- The output creates reusable files, maps, or monitoring loops rather than a disposable essay.

## Useful Prompt Patterns

Create a database:

```text
帮我建立一个 {行业/地区/年份} 行业数据库。输出 Obsidian 友好的 Markdown 目录结构，并为每个目录说明应收集哪些字段、来源和更新频率。
```

Reverse-engineer competitors:

```text
分析这些竞品网站：{URLs}。请按导航结构、产品结构、Collection/分类、Product Tag、SEO、Blog、社媒、Offer、转化路径和商业模式输出 Markdown 报告，并总结共性模式。
```

Build a content system:

```text
帮我整理 {行业} 在 {平台列表} 的内容生态。输出账号样本、近 {时间范围} 高表现内容、内容类型分类、重复爆款模式、可复用选题库和内容机会。
```

Build a knowledge map:

```text
帮我拆解 {行业}。输出一级、二级、三级知识地图；为关键节点建立知识卡片；最后给出连接关系和机会地图。
```

Create weekly intelligence:

```text
基于已有 Industry OS，生成本周行业情报周报：行业变化、竞品动作、爆款内容、关键词变化、风险信号、机会变化和下周建议。
```
