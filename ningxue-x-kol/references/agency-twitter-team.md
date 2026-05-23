# agency-agents-zh X/Twitter Team

Use these roles from:

https://github.com/jnMetaCode/agency-agents-zh

## Roles

### 1. 智能体编排者

- Category: `specialized`
- File: `specialized/specialized-agent-orchestrator.md`
- Job: 总控。拆任务、分配角色、协调流程、最终复核。

### 2. 新闻情报官

- Category: `marketing`
- File: `marketing/marketing-daily-news-briefing.md`
- Job: 收集 AI、Web3、crypto、金融市场、科技热点，交叉验证信源，输出事实底稿。

### 3. 趋势研究员

- Category: `product`
- File: `product/product-trend-researcher.md`
- Job: 判断热点是否值得写，分析趋势强度、市场信号、竞品动态和长期变量。

### 4. 社交媒体策略师

- Category: `marketing`
- File: `marketing/marketing-social-media-strategist.md`
- Job: 设计账号定位、内容节奏、栏目结构、短帖/thread/quote/reply 的组合策略。

### 5. 内容创作者

- Category: `marketing`
- File: `marketing/marketing-content-creator.md`
- Job: 把选题写成 X/Twitter 原生内容，包括短帖、thread、hook、标题和多版本草稿。

### 6. Twitter 互动官

- Category: `marketing`
- File: `marketing/marketing-twitter-engager.md`
- Job: 优化 X 语气，设计 reply、quote、KOL 互动和实时跟进策略。

## Workflow

```text
智能体编排者
→ 新闻情报官
→ 趋势研究员
→ 社交媒体策略师
→ 内容创作者
→ Twitter 互动官
→ 智能体编排者最终复核
→ ningxue-x-kol 风格校准
```

## Task Prompt For Hermes

```text
请使用 agency-agents-zh 的 6 个角色协作：
智能体编排者、新闻情报官、趋势研究员、社交媒体策略师、内容创作者、Twitter 互动官。

任务：为我的中文 X/Twitter 账号 @ningxueSamA 做今日内容生产。

流程：
1. 智能体编排者先拆解任务。
2. 新闻情报官收集今日 AI/Web3/crypto/市场热点。
3. 趋势研究员筛选最值得写的 3-5 个选题。
4. 社交媒体策略师决定内容组合：短帖、thread、quote、reply。
5. 内容创作者产出推文草稿。
6. Twitter 互动官改成 X 原生语气，并补充互动建议。
7. 智能体编排者最后复核事实、风格、节奏、风险。
8. 最后使用 ningxue-x-kol 做人设和语气校准。

输出：
1. 今日最值得写的 3-5 个选题。
2. 每个选题的判断理由。
3. 3-5 条可直接发布的中文 X 短帖。
4. 1 个 thread 大纲。
5. 5-10 条 reply/quote 草稿。
6. 发布优先级和风险提醒。

风格：
中文 X 原生表达，短句、强 hook、有判断、有数据感。
不要写成公众号长文。
不要喊单，不承诺收益，不给直接投资建议。
表达要像一个实战型趋势观察者：冷静、锋利、自嘲、边割边学。
```
