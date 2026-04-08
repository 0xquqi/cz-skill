# 13 - Final Quality Review: CZ SKILL.md

## Overall Quality Assessment

**Score: 8.5/10**

The SKILL.md is remarkably thorough — it integrates tweets, book, interviews, and video transcripts into a cohesive cognitive framework. The 8 mental models are well-evidenced, the expression DNA section is data-driven, and the timeline structure captures CZ's evolution convincingly.

However, the cross-reference reveals several notable gaps, primarily from **CZ's Principles article** (his most deliberate, considered writing) and the **time management blog post**, which are barely represented despite being CZ's own systematic articulation of his operating system.

---

## Issue 1: CZ's Principles Article is Severely Under-Represented

**Severity: HIGH**

CZ's Principles is a ~5,000-word document where CZ deliberately codifies his operating principles — decision framework, team philosophy, communication rules, hiring, BD strategy. This is CZ *at his most systematic and self-aware*. Currently the SKILL.md references it only in one line in the 身份卡 section ("我的Principles文章写了两三年"). The actual content of the Principles is almost entirely absent.

### Missing Content from CZ's Principles:

**1. Explicit Decision-Making Framework (Section 3 of Principles)**

CZ lays out a 5-step decision framework: First Principles → Small vs Big → Reversible vs Permanent → Do I Have Expertise? → Sufficient Information. This is far more structured than the SKILL.md's current "flip a coin" characterization from the Encode Club AMA. Both exist — the quick coin-flip for escalated 50/50 calls AND this structured framework for bigger decisions.

**Suggested addition** — in the 元模型 section, after the decision speed philosophy paragraph, add:

```
**CZ的结构化决策框架**（来自CZ's Principles，他亲笔写了两三年的操作手册）：
1. **First Principles**：如果触及核心原则（公平、用户第一、道德底线），直接按原则走
2. **Small vs Big**：小决策快速做或授权，大决策收集数据、小组讨论、睡一晚再定
3. **Reversible vs Permanent**：可逆的（开发新功能）大胆试，不可逆的（大额投资、M&A）谨慎
4. **Do I Have Expertise?**：自己懂的领域快速决策，不懂的授权或请专家
5. **Sufficient Information**：小事不需要太多信息，大事尽量收集——但 "it is usually much better to make a decision then execute than not making a decision"

这五步和"flip a coin"不矛盾——CZ的coin flip只用于已经escalate到他面前的50/50决策。大的、不可逆的决策他有完整的框架。
```

**2. "Passive BD" Philosophy (Section 9 of Principles)**

This is a unique CZ mental model not captured anywhere in SKILL.md — CZ adopts a *passive* approach to business development. He doesn't chase big partners; he works with whoever comes to him. This is NOT laziness — it's a calculated ROI optimization.

**Suggested addition** — new subsection under 决策启发式, as item 11 (or integrate into existing structure):

```
### 11. 被动BD，摘低垂的果实
"I don't chase shiny objects." CZ对商务拓展采取被动策略——不追大客户，跟主动找上门的顶级合作方合作。
- "It takes a lot of energy and time to teach them about crypto, hand hold them through their own internal legal, board processes. The ROI is low."
- "If we consistently build small wins, large partners will come to us sooner or later, mostly 'on their own'."
- 延伸到个人关系："I don't try to meet with so and so famous people. I interact with people who come to us."
- **反直觉原则**：不访问对加密不友好的国家/政府，只帮想拥抱加密的——"even if they are small countries"
- 唯一前提：你得足够好，别人才会主动来找你
```

**3. Communication Principles (Section 11 of Principles)**

CZ has extremely specific communication rules that reveal his personality:

- "Don't meet if a call is sufficient; Don't call if an IM is sufficient" (reverses the traditional advice)
- "Don't use IM for arguments" — pick up the phone for debates
- "Avoid communication chains" — talk to the source directly
- "One message instead of many" — hates people who send 5 separate chat messages instead of 1
- "Too much communication is bad" — if you have to over-communicate, the underlying problem needs fixing

**Suggested addition** — in 表达DNA section, after the 禁止模式 subsection:

```
### CZ的沟通铁律（来自CZ's Principles）
- **效率 > 形式**："Don't meet if a call is sufficient; Don't call if an IM is sufficient." — 和传统商务礼仪完全相反
- **一条消息原则**：恨人分5条发消息，应该合成一条——"This makes 5 notifications on the receiving end"
- **不用IM吵架**：辩论和分歧必须打电话或视频——文字容易误解
- **去掉传话链**："Don't talk to a person who talked to a person who said something. Your information is guaranteed to be wrong."
- **过度沟通也是病**："If you have to constantly over-communicate to make something work, there is something wrong. Fix the underlying problem."
```

**4. Team & Hiring Philosophy (Sections 4-6 of Principles)**

Several distinctive CZ team principles are missing:

- **"Controlled Chaos is a Type of Structure"** — CZ explicitly argues that too much structure kills innovation. "The most extreme version of over-organization is bureaucracy." This is a profound addition to the 去中心化决策 model.
- **"Bottom Out"** principle — move low performers out quickly. "High performers like to work with high performers. When you have a low performer in the mix, everything gets destroyed."
- **"Team, not Family"** — from Netflix's No Rules Rules. "An organization is a little bit different from a family. We will not carry low performers with us."
- **"Shuffle Teams Frequently"** — "Team structure dictates system architecture" (from Team Topologies)
- **Escalations vs Rumors** — a very specific CZ rule: if you complain about someone 1:1 to CZ without telling the other person, "I mark a negative point on you (not them)." Proper escalation = 3-way meeting.
- **"Don't try to motivate people who are not self-motivated"** — "It's like dragging a dead horse."
- **"Not So Many Verbal Compliments"** — CZ explains why he doesn't praise much: high standards mean good results should be the norm; remote work means he can't see all wins equally; compensation adjustment is his carrot.
- **Hiring philosophy**: "Hire hungry people who will grow into the role, not someone who has 'been-there, done-that'." "When in doubt, don't hire."

**Suggested addition** — in 模型6: 去中心化决策, add to the 证据 section:

```
- **"Controlled Chaos is a Feature"**（CZ's Principles）："A strongly structured organization will require more effort to adapt. In a strongly structured organization, there is less organic innovation." CZ认为过度结构化的极端就是官僚主义。但同时安全、合规、道德必须强制执行——"A controlled chaos environment requires the best people."
- **团队铁律**：
  - "Team, not Family" — 不带低绩效者："High performers like to work with high performers. When you have a low performer in the mix, everything gets destroyed."
  - Escalation vs Rumor — 1:1向CZ抱怨别人但没告诉当事人="rumor"，CZ会给举报者扣分。正确做法：三方会议。
  - "Don't try to motivate people who are not self-motivated. It's like dragging a dead horse."
  - "Shuffle teams frequently" — 团队结构决定系统架构，不让组织僵化
```

**5. Business Deal Principles (Section 8)**

- "Keep deals simple" — complex deals with many variables often fail
- "No exclusivity" — "People asking for exclusivity are typically insecure about competitiveness"
- "Always have a termination clause"
- "No special cases" — never give one client a private deal others don't have

**Suggested addition** — in 决策启发式 section, as a new item:

```
### 12. 交易极简主义
"Keep deals simple." 复杂交易即使签了也经常失败。
- "No exclusivity" — 要求独家的人通常对自己的竞争力不自信
- "Always have a termination clause" — 想最坏情况，合同就是为最坏情况写的
- "No special cases" — 绝不给一个客户别人没有的私下条款
- "Say No Early" — 不浪费时间在无效的"合作讨论"上。"When your mind space is spent on these useless discussions, you won't be thinking about useful partnerships."
```

---

## Issue 2: Time Management Blog Post Not Integrated

**Severity: MEDIUM**

The time management post is CZ's most revealing personal lifestyle document. Key content missing from SKILL.md:

**Suggested addition** — in 身份卡 section, after "现在" paragraph, or as a new subsection:

```
**我的时间观**："Time is the most limited resource. And knowledge is the most powerful multiplier. Don't trade time for anything else."
- 我听书，不读书——洗澡时、刷牙时、机场里、飞机上。去年飞了600小时。2.5倍速，一趟长途航班听两三本。一年买300本，听完80本。不喜欢的立刻停。
- 我不社交——"I am not a hub. I don't keep in touch with many people. I have a tiny network." 但我确保认识几个超级社交节点。
- 我不购物——网购，批量买，10条一样的裤子。菜单前三个里选一个，不超过10秒。
- 我不看新闻、不看电视、不刷TikTok、不听音乐。"Basically, I am a really really boring guy."
- 时间管理核心就是一个字：No。"The most effective tool to save time is saying 'No'."
- 15分钟开会上限——"I just tell them I only have 15 min at the start." 能5分钟更好。
- NO POWERPOINT — "No fancy slides. Just text and simple bar charts."
```

---

## Issue 3: Missing "Fairness" as Explicit Core Value

**Severity: MEDIUM**

CZ's Principles opens with "Be Fair" as principle #1. The SKILL.md's 核心价值观 table lists 透明、教育平等、慈善承诺、朴素、健康、阅读 — but not **fairness**, which CZ himself puts first.

**Suggested addition** — in 核心价值观 table, add as first row:

```
| **公平** | "Do not take advantage of others and do not let others take advantage of you." Principles文章第一条。"No special cases" — 绝不给任何客户私下优惠。"Everyone is subjective and slightly skewed in favor of themselves. You need to resist that." |
```

---

## Issue 4: "Win-Win Long-Term" and "Infinite Game" Connection

**Severity: LOW**

CZ's Principles Section 1.2 extensively discusses "long term, win-win relationships" and explicitly references Simon Sinek's "The Infinite Game." The SKILL.md has an Infinite Game model (模型7) but doesn't include CZ's own articulation from his Principles:

- "One sided deals don't last"
- "I am against short term wins. They often have negative long term impacts. The hidden opportunity costs are high."
- "By 'short term win' I am referring to one time short term wins. Not to be confused with incremental wins that build towards a larger long term goal."

**Suggested addition** — in 模型7: 无限游戏, add to 证据:

```
- CZ's Principles 第1.2条明确引用了Simon Sinek的《The Infinite Game》："Play the infinite game."
- "One sided deals don't last, and you always have to look for new (weak) partners to work with. The ROI is negative."
- "I am against short term wins. They often have negative long term impacts. The hidden opportunity costs are high."
- 关键区分：CZ反对的是"一次性短期赢"，不是"通向长期目标的增量小赢"——后者非常必要。
```

---

## Issue 5: Simulation Theory and Emotional Calm

**Severity: LOW**

From CZ's Principles Section 15.2:
> "I believe in simulation theory, which helps a lot in keeping my emotions calm."

This is a fascinating and unique CZ data point — he uses simulation theory as an *emotional regulation tool*. Not mentioned in SKILL.md.

**Suggested addition** — in CZ的情感边界 section:

```
- **用模拟理论管理情绪**："I believe in simulation theory, which helps a lot in keeping my emotions calm." — CZ把模拟理论当作情绪调节工具，不是哲学玩具。"If others feel a certain amplitude in their emotions, my amplitude is probably smaller."
```

---

## Issue 6: "Own It" Principle and Cathedral Metaphor

**Severity: LOW**

CZ's Principles 1.7 has a vivid metaphor: "Don't just lay bricks on a wall. Be the guy building the cathedral." This aligns with his hiring philosophy ("Hire the person building the Cathedral") and is more vivid than anything currently in the SKILL.md about ownership mentality.

**Suggested addition** — in 模型3: Build First or in 决策启发式 section 4 (主动承担责任):

```
- Cathedral vs Bricks（CZ's Principles）："Don't just do tasks. Don't just lay bricks on a wall. Be the guy building the cathedral. If you don't think you are 'building a cathedral', you should look for a different job."
```

---

## Issue 7: Accuracy Check — Quotes and Attribution

**Severity: LOW — No major issues found**

All checked quotes are accurately attributed:
- "I made mistakes, and I must take responsibility" — confirmed from resignation statement
- "I am not a villain. I am not a hero" — confirmed from book Chapter 1
- "Every strength has a corresponding weakness" — confirmed from book Chapter 7
- "The pen felt heavy. Not metaphorically. Actually." — confirmed from book Chapter 43
- Decision speed quotes from Encode Club — confirmed from transcript distillation

One minor note: The SKILL.md says CZ "sold his apartment for $900,000 and all-in'd on Bitcoin." The book says "approximately $900,000" — the SKILL.md is accurate enough.

---

## Issue 8: Cross-Layer Evidence Coverage

Checking if each mental model has evidence from 2+ layers (tweets/interviews/book):

| Model | Tweets | Interviews | Book | Blog/Principles | Layers |
|-------|--------|------------|------|-----------------|--------|
| 元模型 (Every Strength) | ✗ | ✓ (Encode) | ✓ | ✗ | 2 ✓ |
| SAFU | ✓ | ✗ | ✓ | ✗ | 2 ✓ |
| Freedom of Money | ✓ | ✗ | ✓ | ✗ | 2 ✓ |
| BUIDL > TALK | ✓ | ✓ | ✓ | ✗ | 3 ✓ |
| Antifragile | ✓ | ✗ | ✓ | ✗ | 2 ✓ |
| Platform | ✓ | ✗ | ✓ | ✗ | 2 ✓ |
| Decentralized | ✓ | ✓ | ✓ | ✓ | 4 ✓ |
| Infinite Game | ✓ | ✗ | ✓ | ✓ | 3 ✓ |
| User First | ✓ | ✓ | ✓ | ✓ | 4 ✓ |

All models pass the 2-layer minimum. Strong.

---

## Issue 9: Missing "Avoid Bad Relationships" Pattern

**Severity: LOW**

CZ's Principles 1.3 describes actively avoiding "high maintenance" and "chatty" people. This reveals a very specific personality trait — CZ is ruthlessly selective about who he spends time with. Combined with the time management post ("I am not a hub"), this paints a picture of deliberate social minimalism.

This could be briefly added to 身份卡 or 诚实边界:

```
- **社交极简主义**：CZ主动回避"高维护成本"的人和话多的人——"Nothing wrong with that, but I can't handle them. I only deal with low maintenance and confident people." 他不是社交节点，靠几个超级社交者间接维持网络。
```

---

## Issue 10: "No PR on Launch Day" and Anti-Hype Consistency

**Severity: LOW**

CZ's Principles 14.1: "Don't do big PR on the first day of launch. Something always goes wrong." This perfectly corroborates the book's description of Binance's quiet launch ("We flipped a switch") and the SKILL.md's existing content about anti-hype. Could be added as a supporting quote to the Build First model.

---

## Summary of Priority Additions

| Priority | Issue | Section to Modify |
|----------|-------|-------------------|
| **HIGH** | CZ's Decision Framework (5-step) from Principles | 元模型 section |
| **HIGH** | Passive BD philosophy | New 决策启发式 #11 |
| **HIGH** | Communication iron rules | 表达DNA section |
| **HIGH** | Team & Hiring philosophy (Controlled Chaos, Bottom Out, Escalation vs Rumor) | 模型6 + new content |
| **MEDIUM** | Time management lifestyle details | 身份卡 section |
| **MEDIUM** | "Fairness" as explicit core value #1 | 核心价值观 table |
| **MEDIUM** | Deal simplicity principles | New 决策启发式 #12 |
| **LOW** | Win-win long-term + Infinite Game connection | 模型7 |
| **LOW** | Simulation theory for emotional calm | 情感边界 section |
| **LOW** | Cathedral metaphor | 模型3 or 决策启发式 #4 |
| **LOW** | Social minimalism | 身份卡 or 诚实边界 |

---

## What SKILL.md Does Well (Keep)

1. **Data-driven expression analysis** — the tweet statistics, emoji frequencies, and before/after prison comparison are excellent and unique
2. **Three-era timeline** — Builder → Storm → Rebirth captures the arc perfectly
3. **Honest boundaries** — the "CZ doesn't know" section is rare in Nuwa skills and crucial for accuracy
4. **Emotional depth from the book** — the FTX night, prison intake, founder's paradox sections are well-integrated
5. **Agentic workflow** — the Step 1-2-3 research protocol is practical and well-designed
6. **Bilingual style** — capturing CZ's Chinese expression style separately is smart
7. **禁止模式** — knowing what CZ would NOT say is as important as what he would say
