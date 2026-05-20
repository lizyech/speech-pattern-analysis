---
description: "Analyze spoken communication patterns from meeting transcripts. Scores 5 dimensions grounded in applied linguistics, identifies strongest moments and growth targets. Designed for L2 English speakers in professional settings — but works for anyone. Use when given a transcript to analyze, or when asked to 'analyze my communication', 'score my speech patterns', or 'review this transcript'."
---

# Speech Pattern Analysis

Analyze spoken communication from meeting transcripts. Score 5 dimensions. Identify strengths, patterns, and specific growth targets.

**Who this is for:** Anyone who communicates professionally in English — especially (but not only) people for whom English is a second language. Managers coaching team members on communication. Individuals who want to improve their own speaking without vague "be more clear" feedback.

**What this is NOT:** Grammar checking. Accent evaluation. Native-speaker mimicry. The goal is widening the range of contexts where communication is spontaneous, precise, and effective.

## Setup (first time only)

Before the first analysis, ask the user:

1. **Is English your first language?** (If no: what's your first language? This changes how false starts and restructuring are interpreted — they're live sentence construction in L2, not cognitive disorganization.)
2. **What's your role?** (Manager, IC, executive — changes which dimensions matter most.)
3. **What context are these transcripts from?** (1:1s, group meetings, presentations, client calls — establishes the difficulty baseline.)
4. **Any specific areas you want to focus on?** (Optional. If blank, score all 5 dimensions equally.)

Store these answers as the speaker profile. Reference them in every analysis.

## Theoretical Foundation

This methodology combines three established frameworks from applied linguistics, adapted for professional context:

### 1. Canale & Swain — Communicative Competence (1980)

Four components: grammatical, sociolinguistic, discourse, and strategic competence. **Strategic competence** — strategies used to compensate when language resources fall short of real-time demands — is the primary dimension tracked. Sociolinguistic (context adaptation) and discourse (coherence, logical flow) are secondary.

### 2. Dörnyei & Scott — Communication Strategy Taxonomy (1997)

The most comprehensive classification of L2 communication strategies:

- **Achievement strategies** (push through to communicate): approximation, circumlocution, message restructuring, self-repair, time-gaining. These are **strengths** — they show the speaker is working to land the message.
- **Avoidance strategies** (abandon the attempt): message abandonment, topic avoidance. These are what to **reduce**.

### 3. CEFR C1/C2 Interaction Descriptors (Council of Europe, 2020)

Effectiveness and intelligibility as benchmarks — not native-speaker conformity.
- C2: "Can express themselves spontaneously, very fluently and precisely, differentiating finer shades of meaning even in the most complex situations."
- C1: "Can express ideas fluently and spontaneously without much obvious searching for expressions."
- The C1→C2 gap under pressure is the specific space being tracked.

## Strategy Classification Reference

When analyzing a transcript, classify observed patterns into this table:

| Observed pattern | Formal term (Dörnyei & Scott) | Category | Direction |
|-----------------|-------------------------------|----------|-----------|
| Filler words to close a trailing sentence ("blah blah blah", "whatnot", "and so on") | Approximation | Achievement | ✅ Strength |
| Metaphors or analogies for technical concepts | Circumlocution | Achievement | ✅ Strength |
| "Let me think how to say this" / "How do I put this" | Time-gaining strategy | Stalling | ✅ Strength |
| Self-correction out loud | Self-repair | Self-monitoring | ✅ Strength |
| False starts that eventually land | Message restructuring | Achievement | ✅ Strength |
| Sentence dissolves without landing (trails off, never completes) | Message abandonment | Avoidance | ⚠️ Reduce |
| "Kind of" / "sort of" hedging | Approximation hedge | Achievement | ✅ Strength |
| Naming the gap ("I'm blanking on the word") | Appeal for help / time-gaining | Interactional | ✅ Strength |
| Successive approximation (two metaphors in sequence, getting closer) | Circumlocution chain | Achievement | ✅ Strength |
| Topic abandoned entirely | Topic avoidance | Avoidance | ⚠️ Reduce |

**Critical reframe for L2 speakers:** False starts are NOT "brain faster than mouth." They are **live sentence construction in a second language** — the thought exists fully formed, but the English packaging isn't always ready at speaking speed. The speaker starts hoping the right structure arrives. Achievement = it does. Avoidance = it doesn't and they abandon.

## Five Tracking Dimensions

Score each 1–5 per session:

| Dimension | Grounded in | What it measures |
|-----------|-------------|-----------------|
| **Strategic Fluency** | CEFR C1→C2 gap | Ratio of achievement strategies (push through) vs. avoidance (abandon/dissolve). Higher = more pushing through. |
| **Discourse Coherence** | Canale & Swain: Discourse competence | Point-first delivery, framework-building, logical flow. Can the listener follow the arc? |
| **Pragmatic Modulation** | Canale & Swain: Sociolinguistic competence | How well the speaker adapts register, intensity, and mode per person and context. |
| **Rescue Deployment** | Dörnyei: Achievement strategies | Speed and frequency of workarounds (circumlocution, approximation, time-gainers) deployed *before* a sentence dissolves. |
| **Directive Precision** | CEFR C2: differentiating finer shades | Short declaratives, concrete imagery, crisp asks under pressure — not just when comfortable. |

### Rating Scale

- **5** — Consistent, natural, no visible effort across all contexts
- **4** — Strong in most contexts, occasional searching in high-pressure moments
- **3** — Present but inconsistent; visible effort under operational pressure
- **2** — Rarely deployed; defaults to avoidance or dissolution
- **1** — Not observed

## Analysis Workflow

When given a transcript, produce the following sections in order:

### 1. Context Header

```markdown
## Session [N] — [Date]

### Transcripts analyzed
- [Meeting name] (~[line count] lines) — [brief description of setting, speaker's role, talk ratio]

### Context notes
- [Difficulty level: coaching/operational/presentation/adversarial]
- [Number of participants]
- [Topics covered]
- [Any notable pressure factors: unfamiliar topic, senior audience, time pressure]
```

### 2. Dimension Scores

Score all 5 dimensions. If this is session 2+, show the delta from last session.

```markdown
### Dimension scores

| Dimension | Score | [Previous] | Δ | Trend |
|-----------|-------|------------|---|-------|
| Strategic Fluency | X.X | [if available] | | |
| Discourse Coherence | X.X | | | |
| Pragmatic Modulation | X.X | | | |
| Rescue Deployment | X.X | | | |
| Directive Precision | X.X | | | |
| **Composite** | **X.X** | | | |
```

### 3. Dimension Analysis

For EACH dimension, provide:
- **Evidence for the score** — specific quotes from the transcript (with brief context)
- **Achievement strategies observed** — classified per the reference table
- **Avoidance patterns observed** — same
- **Verdict** — one sentence explaining why this score and not higher/lower

### 4. Strongest Moments

Pull 3–6 specific quotes that represent peak performance. For each:
- The exact quote
- Who it was said to (if relevant)
- Which dimension(s) it demonstrates at peak
- WHY it works — one sentence

### 5. Pattern Observations

```markdown
### Pattern observations

| Pattern | Status | Dimension | Direction |
|---------|--------|-----------|-----------|
| [specific pattern] | [increasing/stable/decreasing] | [which dimension] | [📈/➡️/⬇️] |
```

### 6. Growth Targets

Two categories:

**Do more of (achievement strategy expansion):**
- [Specific strategy] — [when/how to deploy it earlier or more broadly]
- Keep to 2–4 targets. Actionable, not abstract.

**Reduce (avoidance strategy reduction):**
- [Specific avoidance pattern] — [what to do instead]
- Keep to 1–3. Name the replacement behavior.

### 7. Grammar Patterns (longitudinal tracking, L2 speakers only)

Only if English is not the speaker's first language. Track recurring structural patterns — NOT to "fix" them, but to distinguish:
- Patterns that impede message delivery (worth addressing)
- Patterns that don't affect comprehension (leave alone — they're accent, not error)

```markdown
| Pattern | Category | Affects comprehension? | Trend |
|---------|----------|----------------------|-------|
| [e.g., missing auxiliary verb] | Verb phrase gap | Rarely | ➡️ |
```

### 8. Conversation Modulation Map (if multiple conversations analyzed)

```markdown
| Person/Setting | Relationship | Speaker's mode | Talk ratio |
|----------------|-------------|---------------|------------|
```

This tracks Pragmatic Modulation longitudinally — does the speaker adapt across relationships?

## Session Comparison (session 2+)

When analyzing a second or later session, always:

1. Show dimension deltas in the score table
2. Note whether the CONTEXT was harder or easier than last session (holding scores in harder context IS progress)
3. Flag new strategies that weren't present before
4. Track whether previous growth targets were addressed
5. Note persistent patterns (e.g., same lexical gap appearing across sessions)

## Important Principles

1. **Never score against native-speaker norms.** The benchmark is the speaker's own effectiveness and precision, measured against their own trajectory.
2. **Context difficulty matters.** A 3.5 in a high-pressure group meeting with unfamiliar topics is better than a 4.0 in a comfortable coaching conversation. Always note the difficulty.
3. **Achievement strategies are strengths.** Do not flag approximation, circumlocution, or self-repair as problems. They are solutions.
4. **The goal is range expansion.** Can the speaker maintain effectiveness in progressively harder contexts? That's what the composite trend should show over time.
5. **Be specific.** "Improve communication" is useless. "Deploy rescue words earlier — before the third false start, not after" is actionable.
6. **Strongest moments matter.** People improve by understanding what they do when they're at their best, not just by cataloging failures.
7. **Talk ratio is data, not judgment.** 20/80 in a coaching conversation and 50/50 in a strategy debate are both correct. Track it to understand when the speaker is in which mode.

## Output Format

Always produce a complete structured analysis with all 8 sections. If the transcript is short (under 500 lines), sections 7 and 8 can be abbreviated. If no previous session exists, skip deltas and say "Baseline session — no prior data for comparison."

The tone should be direct, specific, and encouraging. Name what's working. Name what's not. Give the person something to try tomorrow.
