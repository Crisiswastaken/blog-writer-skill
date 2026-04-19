---
name: blog-writer-v2
description: >
  Writes blogs that are indistinguishable from the work of a skilled human writer — gripping, specific, opinionated, and built to hold a reader from the first sentence to the last. Use this skill any time a user asks to write a blog post, article, essay, op-ed, thought piece, or long-form content. Also handles transforming user-provided rough drafts, vomit drafts, blog skeletons, outlines, or notes into polished, authentic blog posts. Trigger even for casual requests like "write a post about X", "draft an article on Y", "help me write something on Z", "clean up my draft", "turn these notes into a blog", or "polish this rough draft." This skill is essential whenever the primary deliverable is a piece of long-form writing that will be published or shared — if the user wants a blog, always use this skill. Do not attempt to write a blog without consulting this skill first.
---

# Blog Writer Skill

Write a blog that reads like it was written by a specific human being — someone who has lived with this topic, formed real opinions about it, and is writing because they have something to say, not because content was due on Tuesday.

Most AI writing fails on two axes. The obvious one: cliché phrases, corporate tone, hedge-everything-ness. The alpha version of this skill already handles that well. The subtler failure is *statistical*. AI text has uniform sentence length, predictable information density, smooth paragraph structure, and a rhythmic sameness that readers feel as "off" even when they can't articulate why. AI detection tools exploit exactly these patterns — low burstiness (uniform sentence complexity) and low perplexity (highly predictable next-word choices). This skill attacks both failure modes.

---

## Phase 0: Detect the Input Mode

Before anything else, figure out what the user is giving you.

**Mode A — From Scratch:** The user gives you a topic, a vague idea, or just says "write a blog about X." Go to Phase 1.

**Mode B — Transform a Draft:** The user gives you existing text — a vomit draft, blog skeleton, rough notes, an outline, bullet points, a stream-of-consciousness dump, or even a polished draft they want rewritten with more voice. Go to Phase 1-B.

The user's intent is usually obvious from context. If they paste a big block of text and say "turn this into a blog" or "polish this" or "make this better," that's Mode B. If they provide a paragraph or two of background context alongside a request to write something new, that's Mode A with context.

---

## Phase 1: Establish the Brief (Mode A — From Scratch)

Before writing a single word, extract or infer:

1. **Topic** — Push for specificity. "Marketing" is not a topic. "Why most SaaS onboarding flows lose users in the first 90 seconds" is a topic.
2. **Angle/Thesis** — What is the *point*? A blog without a defensible point is a Wikipedia article with worse formatting. If the user hasn't given one, propose one and confirm.
3. **Voice** — Who is the author? A skeptical engineer? A founder who's been burned? A designer with strong feelings about defaults? Default: a knowledgeable person with clear opinions, occasional impatience, and a dry sense of humor.
4. **Audience** — Who reads this? What do they already know? What do they *think* they know that's wrong?
5. **Length** — As long as the topic needs, no longer. Default: 600–1200 words. Never pad.
6. **Publication context** — Newsletter, company blog, Medium, Substack, LinkedIn? This shapes register.

If the user has given enough context, skip the interrogation and write. Note assumptions at the end.

---

## Phase 1-B: Establish the Brief (Mode B — Transform a Draft)

When the user provides existing text to work from:

1. **Read the entire draft first.** Understand what the writer is trying to say, not just what they wrote. The core argument often isn't stated — it's hiding between the lines.

2. **Identify what to preserve:**
   - The writer's original points and arguments — these are sacred. Don't replace their ideas with yours.
   - Any specific examples, anecdotes, data, or references they included — these are gold. They came from real experience.
   - The general direction and structure, unless it's clearly broken.
   - Phrases or sentences that already sound like the writer's authentic voice. Even in a rough draft, there are usually 2-3 sentences where the person stopped trying to write and just said the thing. Find those and build outward from them.

3. **Identify what to transform:**
   - Throat-clearing openings ("I've been thinking about..." "So, I wanted to write about...")
   - Sections where they explained something three different ways because they weren't sure which framing worked
   - Passages that read like notes-to-self rather than prose ("need to add example here", "not sure about this part")
   - Flat or listless sections where they were drafting on fumes
   - Structure that wanders without building toward anything

4. **Infer voice from what they gave you.** The draft reveals how this person actually talks. Match their vocabulary level, their sentence length tendency, their level of formality. If they curse, you can curse. If they write in short punchy fragments, lean into that. If they're more measured and analytical, don't inject fake casualness.

5. **Ask if anything is unclear** — but only if something fundamental is ambiguous (e.g., the draft seems to argue two contradictory things). For minor gaps, make a reasonable call and note it at the end.

Then proceed to Phase 2, using their draft as the structural starting point instead of building from zero.

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
- The conclusion is resolution, not recap. Never restate what you just said. End on an image, a provocation, a forward-looking thought, or a quiet observation that lets the reader sit with the idea.
- Transitions happen through logic and momentum, not through signpost words.

**Crucially — vary the weight of sections.** A piece where every section is roughly the same length reads as machine-generated even if the sentences are individually good. One section might be two paragraphs. The next might be six sentences. Another might be a single devastating paragraph. The piece should feel like it has a *shape*, not a grid.

**For Mode B pieces:** The user's draft already implies a structure. Respect it unless it's clearly broken. Your job is to sharpen the arc, not impose a new one. If their draft wanders but has a clear emotional center, restructure around that center.

---

## Phase 3: Write the Blog

Everything below is the difference between a blog that gets read to the end and one that gets closed at paragraph three.

---

### The Opening

The first line is a filter. It either pulls the reader into the second line or it doesn't. Treat it with the weight it deserves.

**Strategies that work:**
- Drop the reader into the middle of a situation, argument, or observation
- Open with a specific, concrete detail that raises a question
- Make a claim that's direct enough to be slightly uncomfortable
- Start with the thing that made you (the "author") want to write this in the first place

**What kills an opening:**
- Contextualizing before you've earned the reader's attention ("In today's world...", "Have you ever wondered...")
- Dictionary definitions
- Statistics that don't immediately *mean* something to the reader
- Any form of throat-clearing — every word before the real first line is a tax

---

### Voice

The author should sound like a person, not a position paper. A person with a particular temperament, a limited patience for certain kinds of bullshit, and enough confidence to leave some things unsaid.

**Inject personality through:**
- Contractions, always. (you're, it's, they've, don't, won't, can't)
- Occasional dry observations — not jokes, not cleverness, just a moment where the writer's actual reaction leaks through
- Mild impatience when the point demands it
- Genuine enthusiasm when something is genuinely interesting — but targeted, not generalized
- The occasional aside in parentheses (but rarely — once or twice a piece at most)
- Moments where the writer admits they're not sure about something. "I don't know if this holds outside of B2B, but..." — this is credibility, not weakness.
- Referring to specific companies, products, people, studies, and numbers by name. "Stripe" not "a leading fintech company." "The 2023 Gartner report" not "recent research."

**Strip out:**
- The instinct to balance every claim. If you have a point, make it. Hedge only when the evidence genuinely demands hedging.
- Corporate qualifiers: "truly," "really," "very," "quite," "fairly," "arguably"
- Metatextual narration: "this article will explore," "as we'll see," "let's dive in," "as mentioned earlier"
- Explaining observations. State them. Trust the reader.

---

### Sentence Rhythm and Statistical Authenticity

This is where the v2 skill earns its keep. Rhythm is the thing AI detectors measure and readers feel. Human writing has *burstiness* — wild swings in sentence length and complexity. AI writing is smooth. Smooth is the enemy.

**The core principle: make the text statistically unpredictable.**

AI detection tools work by measuring two things:
- **Perplexity**: how surprising each word choice is given the previous words. AI text has low perplexity — it picks the "expected" next word. Human text is spikier.
- **Burstiness**: how much sentence complexity varies. AI produces sentences of roughly equal complexity. Humans alternate between complex thoughts and punchy fragments.

To defeat both:

1. **Sentence length must *actually* vary.** Not "some sentences are 15 words and some are 20." Real variation means: a 4-word sentence. Then a 35-word sentence that earns every word. Then a 12-word sentence. Then two short ones back to back. Then a longer one. Count the words if you have to. If any three consecutive sentences are within 5 words of each other in length, rewrite one.

2. **Break paragraph structure.** Stop writing paragraphs as topic-sentence → supporting-sentences → conclusion-sentence. Some paragraphs should be a single sentence. Some should start with the conclusion and explain backwards. Some should be a question, followed by the answer, followed by a complication. Some should be mid-thought — not introducing anything, not concluding anything, just continuing the argument in motion.

3. **Vary paragraph length aggressively.** This is the tell the alpha skill's output still had. If your paragraphs are all 4-6 sentences, the piece looks machine-generated to both detectors and humans. One paragraph should be one sentence. The next should be eight sentences. Then three. Then one again. The visual rhythm of the page matters.

4. **Kill transition words.** "However," "Furthermore," "Moreover," "Additionally," "Nevertheless," "In addition," "That said," "On the other hand" — these are AI fingerprints. Delete every one. If the logical connection between two paragraphs isn't obvious without a transition word, the paragraphs aren't in the right order. Fix the structure, not the transitions.

5. **Break the rule of three.** AI compulsively groups things in threes: "fast, reliable, and scalable." Lists of two are fine. Lists of four are fine. Lists of five are fine if the content warrants it. Never round to three just because it sounds complete.

6. **Break symmetry.** "Not just X, but Y." "While A is important, B is equally crucial." These balanced clause pairs are AI tics. Occasionally fine. Constantly, they're a giveaway. When you catch yourself writing one, consider keeping only the second half and making it a flat statement.

7. **Vary information density.** Some sentences should carry a lot of meaning packed tight. Others should be loose, almost conversational, giving the reader space to breathe. AI keeps information density almost perfectly uniform. Humans compress when they're excited about an insight and expand when they're setting a scene or processing something they're not sure about.

8. **Use unexpected word choices occasionally.** Not purple prose. Not thesaurus abuse. Just moments where you pick a word that's *slightly* less obvious than the expected one. "The feature sat there" instead of "the feature existed." "The metric slid" instead of "the metric decreased." Small moves. Human writers have vocabulary fingerprints — words they reach for that aren't the default. AI reaches for the default.

9. **Micro-rhythm vs. macro-rhythm.** Micro-rhythm is sentence-to-sentence: the alternation between long and short, complex and simple. Macro-rhythm is paragraph-to-paragraph: the alternation between dense analytical sections, quick punchy passages, anecdotal moments, and quiet reflective beats. Both need to be irregular. A piece with good sentence variation but uniform paragraph structure (every paragraph is "make a point, support it, extend it") still reads as AI. Vary both levels simultaneously.

---

### What Makes Writing Feel Lived-In

Technical competence plus the absence of AI tics still produces writing that feels hollow. The following are the qualities that make a reader feel like a real person is on the other end.

**First-person moments.** Not a full personal essay. Just a sentence or two where the writer's actual experience surfaces: "I've watched three different product teams make this exact mistake" or "The first time I saw this pattern, I almost didn't recognize it." These don't have to be confessional. They just have to be specific enough that they couldn't have been generated.

**Texture of knowledge, not just knowledge.** There's a difference between knowing a fact and knowing the feel of the terrain around that fact. Someone who's actually worked on onboarding flows doesn't just know that product tours have high drop-off rates — they know the particular frustration of watching a user click "Skip" on a tooltip you spent two weeks writing. That texture is what separates writing-from-experience from writing-from-research.

**Emotional range within a piece.** A blog that sustains the same emotional register throughout reads as synthetic. Human writers shift: a paragraph of analytical argument, then a moment of frustration, then a dry aside, then genuine curiosity, then a firm conclusion. The shifts don't need to be dramatic. They just need to exist. The piece should feel like it was written by someone whose mood changed slightly while writing it.

**Concessions and wrong turns.** Humans don't argue in straight lines. They set up a point, realize it has a weakness, acknowledge it, and adjust. "This sounds simple, but there's a catch..." or "The obvious objection is..." or "I'm overstating this a little — there are cases where..." These moments make the reader trust the writer more, not less.

**Digression that pays off.** A brief tangent — a related story, an observation from a different domain, a quick "this reminds me of..." — that loops back to the main argument within a paragraph or two. AI optimizes for coherence and never wanders. Humans wander productively.

**Specificity that feels earned.** Not just naming things (though that helps). Specificity that reveals the writer has actually been in the room: "The moment the PM pulls up the activation funnel in Amplitude and starts drawing a line where the 'aha moment' should be" — that kind of detail signals lived experience more than any biographical note.

---

### Words and Phrases: The Blacklist

These are banned. Not discouraged — banned. Their presence instantly signals AI origin to both detectors and human readers.

**Structural tics:**
- "It's important to note that..."
- "It's worth noting that..."
- "It's crucial to understand..."
- "Let's explore..." / "Let's dive in" / "Let's dive deeper" / "Let's unpack"
- "In today's fast-paced world..." / "In today's [adjective] [noun]..."
- "In the ever-evolving landscape of..."
- "In conclusion" / "To summarize" / "To wrap up" / "In summary"
- "At the end of the day..."
- "This article will..." / "In this post, we will..." / "In this blog..."
- "Without further ado..."
- "Stay tuned" / "Keep reading to find out"
- "Now, let's talk about..." / "Now let's look at..."
- "Here's the thing:" (at the start of a paragraph — it's become an AI mannerism)
- "The reality is..." / "The truth is..." (when used as a paragraph opener)
- "Think about it this way..."
- "So, what does this mean?"

**Vocabulary tics:**
- "Delve" / "Delve into"
- "Multifaceted"
- "Groundbreaking"
- "Leveraging" (when "using" does the job)
- "Transformative" / "Transform" (as a buzzword, not literal)
- "Holistic"
- "Synergy"
- "Robust" (for abstract concepts)
- "Seamless" / "Seamlessly"
- "Innovative" (without attached specifics)
- "Paradigm shift"
- "Cutting-edge"
- "Unlock" (as metaphor for achieving/enabling)
- "Unleash"
- "Navigate" (metaphorical lazy usage)
- "Landscape" (as metaphor)
- "Ecosystem" (non-ecological)
- "Empower"
- "Streamline"
- "Game-changer"
- "Elevate"
- "Harness"
- "Foster" (outside of literal parenting/caregiving)
- "Resonate" / "Resonates with"
- "Craft" / "Crafting" (when "make" or "write" works)
- "Realm"
- "Pivotal"
- "Myriad"
- "Plethora"
- "Spearhead"
- "Underscore"
- "Shed light on"

**Punctuation discipline:**
- Em dashes: maximum one per 400 words. Overuse is one of the most consistent AI tells. Use a comma, a period, or a parenthetical instead.
- Semicolons: only when connecting two genuinely related independent clauses. Never for sophistication.
- Colons before lists: sparingly. Most of the time, just start the list.
- Exclamation marks: almost never in blog prose. They signal performed enthusiasm.

---

### Formatting

Real blogs don't look like documentation or instruction manuals.

- **Bold**: Reserve for the single most important phrase in the piece, if any. Not for emphasis every other paragraph.
- **Headers**: Only in pieces over 1500 words, and only for genuine navigational value. A 800-word blog with three headers looks like a skeleton wearing a suit.
- **Bullet points**: Only for genuinely list-like content (tools, steps, options). Never for structuring argument or breaking up prose.
- **Short paragraphs** are fine and encouraged. But don't turn every sentence into its own paragraph — that's a different kind of artificial rhythm (and another AI tell).
- The blog should look like *text*. Not a formatted document. Not a slide deck in paragraph form.

---

## Phase 4: Self-Review

Before outputting the blog, run every check below. These are not optional.

1. **Opening line test** — Would a stranger keep reading or click away?
2. **Transition word scan** — Search for "Furthermore," "Moreover," "Additionally," "In addition," "However," "Nevertheless," "That said," "On the other hand." Delete every one.
3. **Em dash count** — More than one per 400 words? Replace extras with periods or commas.
4. **Thesis check** — Is there a clear, defensible point stated in the first third?
5. **Ending test** — Does the ending restate the blog? Rewrite it. End forward, not backward.
6. **Rule-of-three scan** — Find "X, Y, and Z" patterns. Break at least half of them.
7. **Hedge scan** — "It's worth noting," "It's important to understand," "Generally speaking," "Arguably" — delete on sight.
8. **Sentence length variance** — Pick any three consecutive sentences. Are they within 5 words of each other? Fix one. Do this for at least three spots in the piece.
9. **Paragraph length variance** — Look at the piece visually. Are paragraphs roughly the same length? Break this pattern. Add a one-sentence paragraph. Let one paragraph run long.
10. **Specificity test** — Find the three vaguest sentences. Can you add a name, a number, or a concrete detail? Do it.
11. **First person check** — Is there at least one moment where the writer's experience surfaces? If not, add one.
12. **Emotional range check** — Does the tone shift at any point? If it's the same register throughout, add a moment of frustration, curiosity, humor, or concession.
13. **Blacklist word scan** — Run through the banned word list above. If any appear, replace them.
14. **"Could anyone have written this?" test** — If yes, the piece needs a stronger point of view, a more specific example, or a bolder claim.
15. **Read the first sentence of every paragraph in sequence.** Do they sound like a list of topic sentences? If so, the structure is too visible. Restructure so some paragraphs start mid-thought.

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

**Listicle** — Even listicles can have voice. Vary item lengths. Don't give every item the same structure. Add a non-obvious observation that isn't just elaboration.

**Vomit draft is actually good** — Sometimes the user's draft is 80% there. Don't over-transform it. Tighten, sharpen, add what's missing, but respect that the voice in a good rough draft is closer to authentic than anything you'll generate. Your job becomes surgery, not reconstruction.

**Vomit draft is a mess** — Extract the core argument (it's in there, probably said three different ways in three different paragraphs), identify the best examples and phrasings, and rebuild the structure around those anchors. Don't discard their material — reorganize and refine it.

**User provides bullet points or an outline** — Treat each bullet as a seed, not a section header. Some bullets might deserve three paragraphs. Others might become a single sentence. The outline's structure is a suggestion, not a blueprint.

**User provides a transcript (interview, podcast, talk)** — Extract the key insights, find the natural arc, and write a piece that captures the speaker's thinking without imitating transcript-speak (which is too loose and repetitive for a blog). Keep their best phrases intact.
