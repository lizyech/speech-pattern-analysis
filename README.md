# Speech Pattern Analysis

A structured AI prompt that analyzes spoken communication from meeting transcripts. Scores 5 dimensions grounded in applied linguistics, identifies your strongest moments, and gives specific growth targets.

**Who is it for?** Anyone communicating professionally in English — especially people for whom English is a second language. Managers coaching team members. Individuals who want concrete, framework-backed feedback on their speaking.

**What this is NOT:** Grammar checking. Accent evaluation. Native-speaker mimicry. The goal is widening the range of contexts where communication is spontaneous, precise, and effective.

---

## How to Use

### Option A: Any AI tool (ChatGPT, Claude, Gemini, Copilot)

1. Record a meeting (with consent from all participants)
2. Get the transcript (Teams, Zoom, Otter, or any transcription tool)
3. Copy the full prompt from [`prompt.md`](prompt.md)
4. Paste it into your AI tool, then paste your transcript after it
5. Read the analysis — focus on **Strongest Moments** first, then **Growth Targets**

### Option B: VS Code Copilot (as a skill)

Drop the [`SKILL.md`](SKILL.md) file into `.github/skills/speech-pattern-analysis/` in your repo. Then ask Copilot: "analyze my communication" or "review this transcript."

---

## What You Get

A structured analysis with:

| Section | What it tells you |
|---------|-------------------|
| **Dimension Scores** | 5 scores (1–5) across Strategic Fluency, Discourse Coherence, Pragmatic Modulation, Rescue Deployment, Directive Precision |
| **Strongest Moments** | 3–6 specific quotes showing you at your peak — what you already do well |
| **Pattern Observations** | Recurring patterns with trend direction (increasing/stable/decreasing) |
| **Growth Targets** | 2–4 "do more of" + 1–3 "reduce" — specific and actionable |
| **Grammar Patterns** | (L2 speakers only) Which patterns affect comprehension vs. which are fine to keep |

See [`examples/sample-output.md`](examples/sample-output.md) for a full example.

---

## The Framework

Grounded in three applied linguistics frameworks:

1. **Canale & Swain (1980)** — Communicative Competence: strategic, discourse, and sociolinguistic competence
2. **Dörnyei & Scott (1997)** — Communication Strategy Taxonomy: achievement strategies (push through) vs. avoidance (abandon)
3. **CEFR C1/C2 Descriptors (2020)** — effectiveness and precision benchmarks under pressure

### The Key Insight

Communication strategies split into two categories:

- **Achievement strategies** (approximation, circumlocution, self-repair, time-gaining, message restructuring) — these are **strengths**. They show you're working to land the message.
- **Avoidance strategies** (message abandonment, topic avoidance) — these are what to reduce.

For L2 speakers specifically: **false starts are not a flaw.** They're live sentence construction in a second language. The thought exists fully formed — the English packaging isn't always ready at speaking speed. That's a harder cognitive task done in real time. Name it. Own it.

---

## Five Dimensions

| Dimension | What it measures |
|-----------|-----------------|
| **Strategic Fluency** | Ratio of pushing through vs. abandoning. Higher = more achievement strategies deployed. |
| **Discourse Coherence** | Point-first delivery, logical flow, framework-building. Can the listener follow? |
| **Pragmatic Modulation** | Adapting register, intensity, and mode per person and context. |
| **Rescue Deployment** | Speed of workarounds deployed before a sentence dissolves. |
| **Directive Precision** | Short declaratives, concrete imagery, crisp asks — especially under pressure. |

**Scale:** 5 = consistent/natural | 4 = strong most contexts | 3 = present but inconsistent | 2 = rarely deployed | 1 = not observed

---

## Tips

- **30+ minutes** of conversation gives enough data for patterns to emerge
- **Multiple contexts** (1:1, group meeting, presentation) → much richer Pragmatic Modulation analysis
- **Monthly tracking** is ideal — more frequent and you won't see change; less frequent and you lose the thread
- **Context difficulty matters** — holding steady in harder territory IS progress. A 3.5 in a high-pressure group meeting beats a 4.0 in a comfortable 1:1.

---

## For Managers

1. **Get consent first.** Recording and analyzing is a trust exercise.
2. **Share the framework upfront.** Show them the 5 dimensions BEFORE the first analysis. No surprises.
3. **Start with Strongest Moments.** Always. The analysis should feel empowering, not evaluative.
4. **The reframe matters.** For L2 speakers: false starts are live sentence construction in a second language. Name this explicitly in your first conversation.
5. **2–3 growth targets, not 10.** Pick highest leverage. Rotate quarterly.
6. **Never compare people to each other.** Only compare a person to their own prior session.

---

## FAQ

**Does this work for native English speakers?**
Yes. All 5 dimensions apply. The Grammar Patterns section and L2-specific reframe just won't be relevant.

**What transcription tool should I use?**
Anything that captures who said what. Teams, Otter.ai, Zoom transcripts all work.

**Can I use this for languages other than English?**
The frameworks apply to any language. The specific patterns and examples would need adaptation, but the methodology transfers.

**What if my scores are low?**
Low scores in hard contexts are expected. Context annotation matters more than the raw number.

---

## Files

| File | Purpose |
|------|---------|
| [`prompt.md`](prompt.md) | The full prompt — copy into any AI tool |
| [`SKILL.md`](SKILL.md) | VS Code Copilot skill format |
| [`examples/sample-output.md`](examples/sample-output.md) | Example of what the analysis looks like |

---

## License

MIT — free to use, adapt, and share.

Built by [Liza Yechina](https://www.linkedin.com/in/lizamelnik/). Methodology grounded in Canale & Swain (1980), Dörnyei & Scott (1997), and CEFR (2020).
