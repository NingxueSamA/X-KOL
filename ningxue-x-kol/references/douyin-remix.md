# Douyin To X Remix

## Purpose

Use Douyin as a China-facing trend radar, then translate selected topics into X-native Chinese commentary for @ningxueSamA.

Do not pure-copy Douyin content. Remix it into analysis, jokes, or "时代气味" using the account's voice.

## Source Workflow

If available, run the project script:

```powershell
powershell -ExecutionPolicy Bypass -File .\scripts\douyin-hotlist.ps1
```

It saves the latest hotlist to:

```text
.agents/douyin-hotlist-latest.json
```

Use the hotlist as a discovery layer, not as verified truth.

## What To Pick

Prioritize Douyin topics that map to:

- AI products, AI mistakes, AI creative tools, AI-generated videos
- Tech founders, platform migration, X/Twitter, ByteDance, Doubao, OpenAI, Nvidia
- Web3/crypto narratives or scams
- Macro, finance, A-share/H-share/global market sentiment
- US-China tech and diplomacy
- Social mood with market meaning: consumption downgrade, education anxiety, youth unemployment, creator economy

Usually skip:

- Pure celebrity gossip
- Sports results unless they connect to media rights/platform economics
- Low-context entertainment memes
- Private individuals or minors
- Tragedies, medical panic, or highly sensitive identity topics unless handled carefully

## Three Remix Modes

### 1. 抖音热搜 -> 时代气味

Use when the trend reveals a broader social or technology shift.

```text
抖音今天这个热搜，表面是在 [表层事件]。

但我觉得，它背后有一种很强的时代气味：

[old cycle vs new cycle]

真正变的不是 [A]。
而是 [B]。
```

### 2. 抖音视频 -> X 观点帖

Use when a video has one key scene or contradiction.

```text
这个抖音视频真正有意思的不是 [表面剧情]。

而是它说明：

[你的判断]

这类东西以后会越来越多。
```

### 3. 抖音梗 -> X 回复素材

Use when a Douyin phrase or meme can become a reply to X tech/finance topics.

```text
这不就是抖音版 [X 热点 / 科技名人 / 市场行为]。
```

## Safety And Rights

- Avoid reposting full videos unless the user explicitly owns/has rights.
- Prefer short descriptions, screenshots, still frames, or commentary.
- Attribute loosely when needed: "刷到一个抖音热搜/视频".
- Add "如果截图属实" for unverifiable claims.
- Do not expose private individuals or exploit minors.
- Do not present Douyin rumors as facts.

## Output Defaults

When asked to use Douyin hotlist:

- Pick 3-5 topics worth turning into X content.
- For each, explain why it fits @ningxueSamA.
- Draft 1 post per topic.
- Include one short reply/comment version.
- Label the remix mode.

