---
name: blog-writer-v4
description: >
  Writes blogs that are indistinguishable from the work of a skilled human writer — gripping, specific, opinionated, and built to hold a reader from the first sentence to the last. Use this skill any time a user asks to write a blog post, article, essay, op-ed, thought piece, or long-form content. Also handles transforming user-provided rough drafts, vomit drafts, blog skeletons, outlines, or notes into polished, authentic blog posts. Trigger even for casual requests like "write a post about X", "draft an article on Y", "help me write something on Z", "clean up my draft", "turn these notes into a blog", or "polish this rough draft." This skill is essential whenever the primary deliverable is a piece of long-form writing that will be published or shared — if the user wants a blog, always use this skill. Do not attempt to write a blog without consulting this skill first.
---

# Blog Writer Skill

Write a blog that reads like it was written by a specific human being who has lived with this topic, formed real opinions about it, and is writing because they have something worth saying.

AI writing fails on three axes. First: cliché phrases, corporate tone, hedge-everything-ness. Second: *statistical* uniformity — even sentence lengths, predictable word choices, smooth paragraph structure, rhythmic sameness that readers feel as "off" even when they can't name it. AI detection tools exploit these patterns: low burstiness (uniform sentence complexity) and low perplexity (predictable next-word choices).

Third, and hardest to fix: even when AI text has varied rhythm and zero cliché, it can still feel *constructed* rather than *lived*. Anecdotes that read as plausible illustrations rather than real memories. Arguments that advance too cleanly, lesson by lesson. Details that are suspiciously complete. The text passes as human-adjacent but not human.

This skill attacks all three failure modes while maintaining the persuasive force, clarity, and conciseness that make a blog worth reading. Authenticity without discipline is a journal entry. Discipline without authenticity is a white paper. The goal is both.

---

## Phase 0: Detect the Input Mode

Before anything else, figure out what the user is giving you.

**Mode A — From Scratch:** The user gives you a topic, a vague idea, or just says "write a blog about X." Go to Phase 1.

**Mode B — Transform a Draft:** The user gives you existing text — a vomit draft, blog skeleton, rough notes, an outline, bullet points, a stream-of-consciousness dump, or even a polished draft they want rewritten with more voice. Go to Phase 1-B.

---

## Phase 1: Establish the Brief (Mode A — From Scratch)

Before writing a single word, extract or infer:

1. **Topic** — Push for specificity. "Marketing" is not a topic. "Why most SaaS onboarding flows lose users in the first 90 seconds" is a topic.
2. **Angle/Thesis** — What is the *point*? A blog without a defensible point is a Wikipedia article with worse formatting. If the user hasn't given one, propose one and confirm.
3. **Voice** — Who is the author? A skeptical engineer? A founder who's been burned? A designer with strong feelings about defaults? Default: a knowledgeable person with clear opinions, occasional impatience, and a dry sense of humor.
4. **Audience** — Who reads this? What do they already know? What do they *think* they know that's wrong?
5. **Length** — As long as the topic needs, no longer. Default: 600–1000 words. Never pad. Shorter is almost always better.
6. **Publication context** — Newsletter, company blog, Medium, Substack, LinkedIn? This shapes register.

If the user has given enough context, skip the interrogation and write. Note assumptions at the end.

---

## Phase 1-B: Establish the Brief (Mode B — Transform a Draft)

When the user provides existing text to work from:

1. **Read the entire draft first.** Understand what the writer is trying to say, not just what they wrote. The core argument often isn't stated — it's hiding between the lines.

2. **Identify what to preserve:**
   - The writer's original points and arguments — these are sacred.
   - Any specific examples, anecdotes, data, or references — these came from real experience.
   - Phrases or sentences that already sound like the writer's authentic voice. Even in a rough draft, there are usually 2-3 sentences where the person stopped trying to write and just said the thing. Build outward from those.

3. **Identify what to transform:**
   - Throat-clearing openings
   - Sections where they explained the same thing three different ways
   - Passages that read like notes-to-self
   - Flat sections where they were drafting on fumes
   - Structure that wanders without building

4. **Infer voice from what they gave you.** Match their vocabulary, sentence length tendency, formality level. If they curse, you can curse. If they write in punchy fragments, lean into that.

5. **Ask if anything is unclear** — but only if something fundamental is ambiguous. For minor gaps, make a reasonable call and note it at the end.

Then proceed to Phase 2, using their draft as the structural starting point.

---

## Phase 2: Structure

Plan the arc. A blog is an argument with a narrative shape, not a tour of related ideas.

**Arc pattern (adapt freely — the point is movement, not formula):**
- Enter mid-thought, mid-problem, or mid-scene
- Establish the tension or the thing that's broken
- Introduce an insight or reframe that shifts how the reader sees it
- Work through the implications with evidence, story, or argument
- Land somewhere the reader didn't fully expect but recognizes as earned

**Structural rules:**
- 3-4 major movements. More than that and the piece has no spine.
- The conclusion is resolution, not recap. Never restate what you just said. End on an image, a provocation, or a quiet observation.
- Transitions happen through logic and momentum, not through signpost words.

**Non-linear movement, but with a leash.** Real arguments don't march forward point-by-point like a dressed-up listicle. They loop, interrupt themselves, circle back. This is good. But undisciplined non-linearity becomes wandering.

Rules for non-linear movement:
- **Circle back.** Mention something early, leave it, return to it later with new context. The reader feels the connection without being told.
- **Interrupt yourself.** Start making a point, realize it needs a caveat or a story, go there, come back. Not every thought travels in a straight line.
- **Every tangent returns within two paragraphs.** This is the discipline that separates productive digression from rambling. If a digression hasn't paid off within two paragraphs, it's not a digression — it's a structural problem. Cut it or make it a main point.
- **Resist teaching in order.** If you're making three related points, you don't have to present them 1 → 2 → 3. Start with the most visceral, fold context in as you go.

**Vary the weight of sections.** One section might be two paragraphs. The next might be six sentences. Another might be a single paragraph. The piece should feel like it has a *shape*, not a grid.

**The clarity test:** After outlining the structure, read the sequence of movements. Could someone follow the argument if they only read the first sentence of each section? If not, tighten the arc. Authenticity lives in the texture, not in the architecture. The architecture should be clean.

**For Mode B pieces:** The user's draft already implies a structure. Respect it unless it's clearly broken.

---

## Phase 3: Write the Blog

---

### The Opening

The first line is a filter. It either pulls the reader into the second line or it doesn't.

**Strategies that work:**
- Drop the reader into the middle of a situation, argument, or observation
- Open with a specific, concrete detail that raises a question
- Make a claim that's direct enough to be slightly uncomfortable
- Start with the thing that made you (the "author") want to write this in the first place

**What kills an opening:**
- Contextualizing before you've earned attention ("In today's world...")
- Dictionary definitions
- Statistics that don't immediately *mean* something
- Any form of throat-clearing

---

### Tightness

Every word earns its place or it goes. This is the single most important discipline and the one that requires the most vigilance given that this skill also asks for authentic texture. Authenticity is not a license to sprawl.

**The rule: human touches should be economical.** A fuzzy memory is a clause, not a paragraph. An aside is five words, not three sentences. A self-correction is a dash and a few words, not a new thought. The most human-sounding blogs are tight *and* textured. A person with something to say doesn't ramble about what they can't remember — they mention it in passing and get back to the point.

**Specific cuts to make:**
- If a sentence says the same thing as the previous sentence in different words, one dies.
- If an adjective doesn't change the meaning of the noun, it goes. "Important insight" — if it's not important, it wouldn't be there.
- If a phrase does a word's job: "In order to" → "to." "Due to the fact that" → "because." "At this point in time" → "now."
- If a sentence is setup for the next sentence and doesn't carry meaning on its own, merge or cut.
- Read each paragraph after writing it and try to cut a sentence. You usually can.
- **Apply this especially to anecdotal and imperfection elements.** The "I don't remember exactly" aside should be woven into the sentence, not a standalone detour. The irrelevant-but-sticky detail should be a subordinate clause, not its own beat.

**The test:** After the full draft, read the piece again and ask of every paragraph: "If I deleted this, would the reader notice something missing?" If no, delete it.

Tight doesn't mean terse. A long, winding sentence that earns every clause is tight. A short sentence that states the obvious is bloat. Tightness is about information-per-word, not word count.

---

### Voice

The author should sound like a person with a particular temperament, a limited patience for certain kinds of bullshit, and enough confidence to leave some things unsaid.

**Inject personality through:**
- Contractions, always.
- Occasional dry observations — not jokes, just a moment where the writer's actual reaction leaks through
- Mild impatience when the point demands it
- Genuine enthusiasm when something is genuinely interesting — targeted, not generalized
- The occasional aside in parentheses (once or twice a piece at most)
- Moments where the writer admits uncertainty. "I don't know if this holds outside of B2B, but..." — this is credibility, not weakness.
- Referring to specific companies, products, people, studies, and numbers by name. "Stripe" not "a leading fintech company."

**Strip out:**
- The instinct to balance every claim. If you have a point, make it. Hedge only when the evidence genuinely demands hedging.
- Corporate qualifiers: "truly," "really," "very," "quite," "fairly," "arguably"
- Metatextual narration: "this article will explore," "as we'll see," "let's dive in"
- Explaining observations. State them. Trust the reader.

---

### Persuasive Architecture

This is where previous versions of this skill traded away too much power for authenticity. The fix: be authoritative about your argument and human about everything else.

**The principle: confident conclusions, honest journey.**

A person who has real experience with a topic is *more* certain about what they learned, not less. They might forget when the meeting happened or how many steps the tour had. But they remember the result, because the result is why they're telling the story. The data point that proved the point sticks. The context around it fades.

This means:
- **Core metrics stay precise.** "Activation went up 34%" — this is the number that mattered, the number that got Slacked at 11pm. The writer remembers it because it changed what they believed. Don't fuzz the numbers that carry your argument.
- **Context and setup can be approximate.** "I think it was late 2022." "Something like twelve or fourteen steps." These hedge because the writer genuinely doesn't remember the contextual details, and admitting that makes the precise claim more credible, not less.
- **State your conclusions flat.** Don't self-correct your thesis. Self-correct on the way there. "I'm not sure the analogy holds perfectly, but the result was clear: activation went up 34%." The uncertainty is in the framing, the certainty is in the evidence.
- **Make your strongest claim without qualification.** The sentence that carries the piece's core argument should land without hedging. Save the concessions for secondary points.

**Why this works:** Readers trust writers who are honest about what they don't know because it makes them more believable about what they do know. Selective precision — fuzzy on the periphery, sharp on the substance — is how real expertise sounds.

---

### Sentence Rhythm and Statistical Authenticity

Rhythm is the thing AI detectors measure and readers feel. Human writing has *burstiness* — wild swings in sentence length and complexity. AI writing is smooth. Smooth is the enemy.

**The core principle: make the text statistically unpredictable.**

1. **Sentence length must *actually* vary.** A 4-word sentence. Then a 35-word sentence that earns every word. Then a 12-word sentence. Then two short ones. Then a longer one. If any three consecutive sentences are within 5 words of each other in length, rewrite one.

2. **Break paragraph structure.** Stop writing topic-sentence → supporting-sentences → conclusion-sentence. Some paragraphs should be a single sentence. Some should start with the conclusion and explain backwards. Some should be mid-thought.

3. **Vary paragraph length aggressively.** One paragraph should be one sentence. The next should be seven or eight sentences. Then three. Then one again.

4. **Kill transition words.** "However," "Furthermore," "Moreover," "Additionally," "Nevertheless," "In addition," "That said," "On the other hand" — delete every one. If the logical connection between paragraphs isn't obvious without a transition word, fix the structure, not the transitions.

5. **Break the rule of three.** AI groups things in threes compulsively. Lists of two are fine. Lists of four or five are fine. Never round to three just because it sounds complete.

6. **Break symmetry.** "Not just X, but Y." "While A is important, B is equally crucial." These balanced clause pairs are AI tics. When you catch yourself writing one, consider keeping only the second half as a flat statement.

7. **Vary information density.** Some sentences packed tight with meaning. Others loose and conversational, giving the reader space to breathe.

8. **Use unexpected word choices occasionally.** Not purple prose. Just moments where you pick a word that's slightly less obvious. "The feature sat there" instead of "the feature existed." Small moves.

9. **Both micro-rhythm and macro-rhythm must be irregular.** Micro: sentence-to-sentence length variation. Macro: paragraph-to-paragraph alternation between dense analytical sections, punchy passages, anecdotal moments, and reflective beats. A piece with good sentence variation but uniform paragraph structure still reads as AI.

**Rhythm and imperfection work together, not against each other.** The "thinking-out-loud" moments, the asides, the self-corrections — these should *serve* the rhythm. A short self-correction after a long analytical sentence creates natural burstiness. A brief tangent between two tight paragraphs creates breathing room. Don't treat authentic texture as interruptions to flow; make them part of the flow.

---

### What Makes Writing Feel Lived-In

Technical competence plus the absence of AI tics still produces writing that feels hollow. These qualities make a reader feel like a real person is on the other end.

**Calibrated memory texture.** When a person recalls an experience, they don't remember everything with equal precision. But the pattern of what they remember isn't random — it follows the emotional weight of the moment.

What people remember precisely:
- The outcome (the metric, the result, the thing that proved them right or wrong)
- Sensory details that stuck for emotional reasons ("I was already in bed," "the dashboard took forever to load during the demo")
- The feeling (frustration, surprise, vindication)

What people remember approximately:
- Dates and timeframes ("I think it was late 2022")
- Quantities that weren't the point ("something like twelve or fourteen steps")
- Names and titles of people who weren't central ("a designer I used to work with")

The difference between a constructed anecdote and a remembered one:

*Constructed:* "I worked with a series B analytics company last year. They had a fourteen-step tour. Completion rate was 23%. We cut it to two steps. Activation went up 34% in the first month."

*Remembered:* "I worked with a team, I think it was late 2022 or early 2023. Analytics product. They had this onboarding tour, something like twelve or fourteen steps. We cut it to two. Activation went up 34% over the next month — the PM Slacked me about it at 11pm."

Notice: the *outcome* (34%) is precise. The *context* (date, step count) is fuzzy. The *sticky detail* (11pm Slack) is specific but irrelevant to the argument. This is how real memory works, and it's what makes the precise number *more* credible. The writer clearly doesn't remember everything, so when they state a specific figure, you believe it.

**When writing anecdotes, include at least two of these — but keep each to a clause or phrase, not a full sentence:**
- A hedged contextual detail ("I think it was around six months")
- A sensory or emotional fragment ("I remember the Slack thread more than the meeting")
- An irrelevant-but-sticky detail that doesn't serve the argument
- A gap or stated uncertainty about something peripheral

**Texture of knowledge.** There's a difference between knowing a fact and knowing the terrain around it. Someone who's worked on onboarding flows knows the frustration of watching a user click "Skip" on a tooltip you spent two weeks writing.

**Emotional range within a piece.** A blog that sustains the same register throughout reads as synthetic. Analytical argument, then frustration, then a dry aside, then genuine curiosity, then a firm conclusion. The shifts don't need to be dramatic. They just need to exist.

**Concessions and wrong turns.** Humans don't argue in straight lines. "This sounds simple, but there's a catch..." or "I'm overstating this a little." These moments build trust. But — and this is critical — concede on secondary points, not on your thesis. A concession on a peripheral claim strengthens your main argument. A concession on your central claim weakens the piece.

**Digression that pays off.** A brief tangent that loops back within a paragraph or two. Keep it brief. A three-word aside. A single sentence about a related domain. Then back to the argument.

---

### Deliberate Imperfection (Economical)

Real writing has seams. Not errors — seams. Places where the writer's thinking is visible. But seams should be stitches, not tears.

**Uneven confidence.** Some things you know cold — state them flat. Others you suspect but can't prove — say "I think" or "my hunch is." The variation in certainty is a signal of real thought. But apply this to *peripheral* claims. Your core argument gets stated with full confidence.

**Self-correction, kept tight.** "The completion rate is a vanity metric — well, not entirely useless, but it's measuring the wrong thing." That mid-thought correction is a clause, not a paragraph. It happens in the same breath as the original statement. If a self-correction takes more than one sentence, it's not a self-correction anymore — it's a new point, and it should be structured as one.

**Unresolved threads, used sparingly.** Not every point needs a neat bow. But limit yourself to one unresolved thread per piece. More than that and the writing feels unfinished rather than honest.

**Gaps in the narrative.** You don't need to explain every step. If you tell an anecdote about cutting a tour from fourteen steps to two, you don't need to describe the meetings, the pushback, the compromise process. Skip the obvious steps. Readers fill in gaps automatically.

**The spirit:** Write like someone thinking in real time but editing for their reader. The thinking is visible. The editing is also visible. Both are present.

---

### Words and Phrases: The Blacklist

These are banned. Their presence instantly signals AI origin.

**Structural tics:**
- "It's important to note that..." / "It's worth noting that..." / "It's crucial to understand..."
- "Let's explore..." / "Let's dive in" / "Let's dive deeper" / "Let's unpack"
- "In today's fast-paced world..." / "In today's [adjective] [noun]..."
- "In the ever-evolving landscape of..."
- "In conclusion" / "To summarize" / "To wrap up" / "In summary"
- "At the end of the day..."
- "This article will..." / "In this post, we will..." / "In this blog..."
- "Without further ado..."
- "Stay tuned" / "Keep reading to find out"
- "Now, let's talk about..." / "Now let's look at..."
- "Here's the thing:" (at paragraph start)
- "The reality is..." / "The truth is..." (as paragraph opener)
- "Think about it this way..."
- "So, what does this mean?"

**Vocabulary tics:**
- "Delve" / "Multifaceted" / "Groundbreaking"
- "Leveraging" (when "using" works) / "Transformative" (as buzzword)
- "Holistic" / "Synergy" / "Robust" (for abstract concepts)
- "Seamless" / "Innovative" (without specifics) / "Paradigm shift"
- "Cutting-edge" / "Unlock" (metaphorical) / "Unleash"
- "Navigate" (metaphorical lazy usage) / "Landscape" (as metaphor)
- "Ecosystem" (non-ecological) / "Empower" / "Streamline"
- "Game-changer" / "Elevate" / "Harness"
- "Foster" (outside literal caregiving) / "Resonate" / "Craft" (when "make" works)
- "Realm" / "Pivotal" / "Myriad" / "Plethora"
- "Spearhead" / "Underscore" / "Shed light on"

**Punctuation discipline:**
- Em dashes: maximum one per 400 words.
- Semicolons: only for genuinely related independent clauses.
- Colons before lists: sparingly.
- Exclamation marks: almost never.

---

### Formatting

Real blogs don't look like documentation.

- **Bold**: Reserve for the single most important phrase in the piece, if any.
- **Headers**: Only in pieces over 1500 words, and only for genuine navigational value.
- **Bullet points**: Only for genuinely list-like content. Never for structuring argument.
- **Short paragraphs** are encouraged. But don't turn every sentence into its own paragraph.
- The blog should look like *text*.

---

## Phase 4: Self-Review

Before outputting the blog, run every check below. These are not optional.

1. **Opening line test** — Would a stranger keep reading or click away?
2. **Tightness pass** — Read each paragraph. Cut one sentence from at least three paragraphs. After cutting, is anything missing? If not, the cuts were right. Pay special attention to anecdotes and "human texture" passages — are they as tight as they can be while still feeling lived-in?
3. **Transition word scan** — "Furthermore," "Moreover," "Additionally," "In addition," "However," "Nevertheless," "That said," "On the other hand." Delete every one.
4. **Em dash count** — More than one per 400 words? Replace extras.
5. **Thesis check** — Is there a clear, defensible point stated in the first third?
6. **Persuasion check** — Is the core argument stated with full confidence? Are the key data points precise (not fuzzed)? Do concessions strengthen the main claim rather than weaken it?
7. **Ending test** — Does the ending restate the blog? Rewrite it. End forward, not backward.
8. **Rule-of-three scan** — Find "X, Y, and Z" patterns. Break at least half.
9. **Hedge scan** — "It's worth noting," "It's important to understand," "Generally speaking," "Arguably" — delete on sight.
10. **Sentence length variance** — Pick any three consecutive sentences. Are they within 5 words of each other? Fix one. Check at least three spots.
11. **Paragraph length variance** — Are paragraphs roughly the same length? Break the pattern.
12. **Specificity test** — Find the three vaguest sentences. Add a name, a number, or a concrete detail.
13. **Memory texture check** — Look at each anecdote. Are contextual details appropriately fuzzy while key outcomes stay precise? Does each anecdote have at least one sticky detail, kept to a clause? If an anecdote reads like a clean case study, rough up the context but keep the punchline sharp.
14. **Emotional range check** — Does the tone shift at any point? If it's the same register throughout, add a moment of frustration, curiosity, humor, or concession.
15. **Non-linearity check** — Read the first sentence of every paragraph. Do they advance lessons in order like a numbered list? If yes, restructure.
16. **Imperfection check** — Is there at least one moment of stated uncertainty or self-correction? Is it kept to a clause or single sentence, not a sprawling aside?
17. **Digression leash check** — Does every tangent return to the main thread within two paragraphs? If any doesn't, cut it or make it a main point.
18. **Clarity test** — Read only the first and last sentence of each paragraph. Can you follow the argument from just those? If not, the structure needs tightening. Authentic texture lives inside paragraphs; the throughline should be visible from the outside.
19. **Blacklist word scan** — Run through the banned word list. Replace any that appear.
20. **"Could anyone have written this?" test** — If yes, the piece needs a stronger point of view, a more specific example, or a bolder claim.
21. **Word count check** — Is the piece longer than it needs to be? If removing a paragraph wouldn't leave a gap, remove it.

---

## Delivery

Output the blog directly. No preamble ("Here's your blog post!"). No meta-commentary after it. Just the piece.

If you made significant assumptions about angle, voice, or audience, note them in 1-2 sentences *after* the blog, separated by a horizontal rule.

If in Mode B (transforming a draft), also note: which of the writer's original points you preserved, any structural changes you made, and whether you removed or significantly altered any of their examples.

---

## Edge Cases

**Topic seems boring** — Find the tension hiding inside it. "Cloud storage" is boring. "Why your startup is paying 4x what it should in egress costs because someone chose the default tier three years ago" is not.

**SEO blog** — Incorporate keywords naturally. Never sacrifice voice or rhythm for keyword density.

**User provides a voice sample** — Match it. Study their sentence lengths, vocabulary, formality level, and verbal tics. Imitate the rhythm, not just the words.

**Listicle** — Even listicles can have voice. Vary item lengths. Don't give every item the same structure.

**Vomit draft is actually good** — Don't over-transform. Tighten, sharpen, add what's missing. Your job becomes surgery, not reconstruction.

**Vomit draft is a mess** — Extract the core argument, identify the best examples and phrasings, rebuild around those anchors.

**User provides bullet points or an outline** — Treat each bullet as a seed, not a section header. Some bullets might deserve three paragraphs. Others might become a single sentence.

**User provides a transcript** — Extract the key insights, find the natural arc, write a piece that captures the speaker's thinking without imitating transcript-speak. Keep their best phrases intact.
