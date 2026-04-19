# Blog Writer Skill

> Write blogs indistinguishable from the work of a skilled human. Not SEO-optimized — human-first.

A prompt skill for AI assistants, developed and iterated across four versions using a three-model LLM ensemble evaluation. The current version, **V4**, scores **8.97/10** across 10 writing quality parameters and wins 7 of 10 outright.

Compatible with GitHub Copilot, Claude Code, Cursor, Windsurf, Cline, Codex CLI, Gemini CLI, and any AI tool that accepts a system prompt.

---

## What This Is

Most AI-generated blogs fail in three predictable ways.

**Clichés and corporate tone.** Every sentence sounds like it was written by a committee that polished the edges off every thought. "In today's fast-paced world..." "Let's dive in." "It's important to note."

**Statistical uniformity.** AI writing has low burstiness — uniform sentence lengths, predictable word choices, smooth paragraph structure. AI detection tools measure this. Readers feel it without naming it.

**Constructed, not lived.** Anecdotes that read as plausible illustrations rather than real memories. Arguments that advance too cleanly, lesson by lesson. The text passes as human-adjacent but not human.

This skill attacks all three. The goal is writing with both authenticity and discipline — because authenticity without discipline is a journal entry, and discipline without authenticity is a white paper.

**This is not an SEO skill.** There are no keyword density targets, no H2-every-300-words rules, no readability score requirements. If you need a blog that ranks, this isn't the right tool. If you need a blog that a real person would actually read to the end, it is.

---

## Evaluation

The skill was developed across four versions and evaluated by a three-model LLM ensemble (ChatGPT, Gemini, Grok) across 10 writing quality parameters. Each parameter scored 0–10.

### Ensemble Results

| Parameter | Alpha | V2 | V3 | V4 | Winner |
|---|---:|---:|---:|---:|:---:|
| Human-likeness | 7.53 | 8.63 | **9.03** | 9.00 | V3 |
| Natural voice | 7.77 | 8.70 | **9.10** | 8.97 | V3 |
| Emotional engagement | 7.10 | 8.27 | 8.50 | **8.67** | V4 |
| Memorability | 7.30 | 8.53 | 8.53 | **8.90** | V4 |
| Flow & rhythm | 8.10 | 8.70 | 8.73 | **8.97** | V4 |
| Clarity | 9.00 | 9.00 | 8.77 | **9.07** | V4 |
| Specificity | 7.20 | 9.07 | 8.33 | **9.20** | V4 |
| Persuasiveness | 7.90 | 8.83 | 8.47 | **9.13** | V4 |
| Conciseness | **8.73** | 7.83 | 8.27 | 8.67 | Alpha |
| Overall impact | 7.80 | 8.83 | 8.80 | **9.13** | V4 |
| **Ensemble avg** | **7.84** | **8.64** | **8.65** | **8.97** | **V4** |

### Per-Model Rankings

| Evaluator | Alpha | V2 | V3 | V4 | Ranked #1 |
|---|---:|---:|---:|---:|:---:|
| ChatGPT | 7.92 | 8.61 | 8.84 | **9.17** | V4 |
| Gemini | 7.61 | 8.31 | 8.54 | **8.88** | V4 |
| Grok | 8.00 | **9.00** | 8.58 | 8.86 | V2 ⚠️ |
| **Ensemble** | **7.84** | **8.64** | **8.65** | **8.97** | **V4** |

**Divergence note:** Grok is the only evaluator to rank V2 above V4. ChatGPT and Gemini both rank V4 first. Grok's V2 preference likely reflects stronger weighting on surface humanness markers over the calibrated precision and persuasive confidence V4 adds.

**Category champions:**
- **Overall champion:** V4 — 8.97 avg, no parameter below 8.67, wins 7 of 10
- **Most human:** V3 — 9.10 Natural Voice, 9.03 Human-likeness
- **Most concise:** Alpha — 8.73 Conciseness

Full evaluation with per-model breakdowns and visual benchmark diagrams: [`LLM-EE/alpha-vs-v2-vs-v3-vs-v4/ensemble-evaluation.md`](LLM-EE/alpha-vs-v2-vs-v3-vs-v4/ensemble-evaluation.md)

---

## Versions

| Version | Identity | Ensemble Avg |
|---|---|---:|
| Alpha | Clean, tight, minimal texture. Strong conciseness, limited depth. | 7.84 |
| V2 | Professional polish, named specifics, rhythm focus. High specificity. | 8.64 |
| V3 | Imperfect memory, lived-in texture, fuzzy context. Most human voice. | 8.65 |
| **V4** | Calibrated precision + confident conclusions. Current default. | **8.97** |

V4 synthesizes what worked from every prior version: V2's specificity, V3's lived texture, and a new principle — *confident conclusions, honest journey*. Core metrics stay precise. Context can be approximate. The main argument lands flat.

All version SKILL.md files live under [`skill/`](skill/).

---

## Installation 

### Install from Smithery

https://smithery.ai/skills/vinceshine6789/blog-writer

### Install Manually

The skill is a single Markdown file. Installation means placing it where your AI tool reads its instructions.

If your tool accepts a system prompt, custom instructions file, or project-level context:

1. Open [`skill/blog-writer-v4/SKILL.md`](skill/blog-writer-v4/SKILL.md) or whichever version you choose. 
2. Copy everything 
3. Paste into your tool's system prompt or instructions field

The skill is plain Markdown and works in any context the AI can read.

---

## Usage

The skill handles two modes automatically based on what you give it.

### Mode A — From a topic

Give it a subject. The skill derives the angle, voice, structure, and length.

```
Write a blog post about why most SaaS onboarding flows lose users in the first 90 seconds.
```

```
Blog post: the mistake engineers make when they estimate for the first time.
```

```
Write something about why async-first teams are misunderstood.
```

The skill infers voice, audience, and length from context. If anything fundamental is ambiguous it asks one targeted question; otherwise it writes.

**What it will not do:**
- Open with "In today's fast-paced world..."
- Pad word count with keyword-stuffed introductions
- Produce a bulleted listicle pretending to be prose
- Hedge every claim into meaninglessness
- Restate the blog in a "Conclusion" section

**What it will do:**
- Drop you mid-scene or mid-argument in the first line
- Make a point and hold it
- Write with the rhythm of a person who has actually thought about this
- End forward — on a provocation, an image, or a quiet observation — not a recap

---

### Mode B — From a draft, skeleton, or vomit draft

Paste your rough notes, skeleton, outline, or stream-of-consciousness draft. The skill:

1. Finds your actual argument (often buried)
2. Preserves your specific examples, anecdotes, and data — these are treated as sacred
3. Extracts your voice from the moments where you stopped trying to write and just said the thing
4. Transforms structure without replacing your original thinking

**Example — skeleton:**

```
Here's a skeleton for a post about cold email. Please flesh it into a full blog.

Topic: Cold email response rates have collapsed
Problem: Everyone uses the same 5-sentence template formula
My take: Specificity beats personalization. Real context beats fake rapport.
Example: Got one email that referenced my actual conference talk — the only cold email I've responded to in two years
Conclusion: Templates kill trust faster than they save time
```

**Example — vomit draft:**

```
Here's a rough draft, it's messy. Turn it into a proper blog post.

[paste text]
```

The skill will not replace your numbers with generic ones, invent anecdotes you didn't provide, or soften a strong take to seem balanced.

---

## What the Output Looks Like

From V4, topic: product tours ([full post](examples/product-tour-d.md)):

> Nobody finishes your product tour.
>
> The ones who click through every tooltip, maybe 23% on a good day, will open a support ticket tomorrow asking how to do the thing the tour just showed them. That number should terrify product teams more than it does.
>
> I watched this happen up close. I was working with an analytics company, sometime in late 2022 I think, and they'd built this onboarding sequence that must have been twelve or fourteen steps long. I sat in on a session recording where a user clicked "Next" on every single tooltip without reading any of them, then closed the tab. Forty seconds, start to finish.
>
> The PM showed me their completion numbers like they were good news.

---

## Roadmap

V4 is the general-purpose, human-authentic version. Future V4 variants will target specific formats and intents:

| Planned | Focus |
|---|---|
| V4-SEO | SEO-first: structured for search indexability while maintaining readable prose |
| V4-Thought Leadership | LinkedIn / newsletter format, authority-building, professional register |
| V4-Technical | Developer audience, code-adjacent writing, high specificity on implementation details |
| V4-Conversational | Short-form, casual register, personal blog / Substack style |
| V4-Opinion | Op-ed structure, sharper takes, built for strong positions and engagement |

Each variant will be evaluated against V4 using the same three-model ensemble methodology before being designated stable.

---

## License

MIT
