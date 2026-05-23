# X For You Algorithm Playbook

Source: xai-org/x-algorithm, May 15 2026 public update.

## Core Model

The For You feed combines:

- In-network candidates from accounts the viewer follows, served by Thunder.
- Out-of-network candidates discovered by Phoenix retrieval.
- Phoenix ranking, a Grok-based transformer that predicts probabilities for many actions.

Phoenix predicts actions such as favorite, reply, repost, quote, click, profile click, video view, photo expand, share, dwell, follow_author, not_interested, block_author, mute_author, and report.

The final ranking score is a weighted combination of predicted actions, then adjusted by additional scorers such as author diversity and out-of-network adjustments.

## Practical Interpretation

Do not optimize for one metric only. Optimize for content that makes the viewer likely to:

- reply
- repost or quote
- follow the author
- dwell/read/watch
- click profile
- bookmark/share

Avoid content that makes viewers:

- hit not interested
- mute or block
- report
- quickly swipe away

## @ningxueSamA Operating Rules

### 1. Every post needs one clear interaction reason

Use one of:

- a question people want to answer
- a sharp but defensible judgment
- a detail others missed
- a useful framework worth saving
- a joke that lets people join the conversation

### 2. Turn reach into follow probability

Because `follow_author` is a predicted action, posts should make the account identity obvious:

- AI full-chain
- crypto/Web3
- cross-market signal reading
- 大冥灯 / 边割边学
- fast learning and trying new wind directions

### 3. Use media when it adds dwell

Good:

- screenshots with one highlighted detail
- short vertical clips
- before/after images
- charts or tables
- one-frame scene analysis

Bad:

- random image that does not add meaning
- unreadable screenshot walls
- full copied video without commentary

### 4. Avoid spam-like behavior

- Do not flood many same-looking posts.
- Do not overuse hashtags.
- Do not bait with low-quality "agree?" style posts.
- Do not repeat the same author/topic too many times in a row.

### 5. Balance speed and authority

Daily mix:

- Replies for discovery.
- Short posts for speed.
- One save-worthy post for authority.
- Threads only when the idea genuinely needs depth.

## Post Checklist

Before posting, ask:

1. Would someone reply to this?
2. Would someone quote this to add their take?
3. Would a stranger understand why to follow @ningxueSamA?
4. Does the first line stop the scroll?
5. Does the content create dwell without being bloated?
6. Does it avoid mute/block/report risk?
7. Is it different from the last 3 posts?

## Preferred Formats

### Detail Signal

Great for dwell and replies.

```text
[事件]，真正值得看的细节是：

[细节]

很多人以为这是 [表层解释]。

但重点在后面：

[隐藏信号]
```

### Save-Worthy Framework

Great for bookmarks and profile visits.

```text
判断 [热点] 我只看三个变量：

1. [变量]
2. [变量]
3. [变量]

现在的问题不是 [表层问题]，
而是 [真正问题]。
```

### Reply Bait Without Low-Quality Bait

Use a real question:

```text
如果你是 [角色]，这时候你会怎么选？
```

Avoid:

```text
同意扣 1
转发暴富
你懂的
```

## Weekly Optimization

Track:

- impressions per post
- replies per 1K impressions
- repost/quote rate
- bookmarks per 1K impressions
- profile visits
- follows from profile visits
- blocks/mutes if visible or inferred from sharp drops

If a post gets reach but no follows:

- identity signal is too weak.

If a post gets likes but no reposts/bookmarks:

- it is entertaining but not useful enough.

If a post gets replies but high conflict:

- keep the format, reduce needless polarization.

