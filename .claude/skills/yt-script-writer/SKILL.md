---
name: yt-script-writer
description: Write or tighten YouTube video scripts, including hooks, structure, retention beats, and CTAs. Use when asked to script, outline, or rewrite a long-form YouTube video.
---

# YouTube Script Writer

## Inputs
Topic, target length (default 8–12 min, ~150 spoken words/min), and tone from `channel/profile.md`. Ask only for the topic if nothing else is given.

## Structure
1. **Hook (0:00–0:30)**: open on the most interesting moment, question or result. No "hey guys, welcome back" before the hook. State what the viewer gets and tease the payoff.
2. **Setup (≤45s)**: the context the viewer needs, plus why they should trust you on this.
3. **Body**: 3–6 segments. Each one opens with a mini-hook and ends with an open loop into the next ("but that wasn't the weird part…").
4. **Pattern interrupt** every 60–90s: a visual change, B-roll, an on-screen text cue or a joke. Mark these as `[VISUAL: …]`.
5. **Payoff**: deliver on the title's promise clearly.
6. **CTA (≤15s)**: one action only, ideally pointing to a specific next video (`[END SCREEN: …]`).

## Output format
- Script in two columns, or as `[VISUAL]` / spoken lines.
- Timestamps estimated from word count.
- A **retention risk** note listing the 2–3 spots viewers are most likely to drop off, with a fix for each.
- Save to `channel/scripts/<slug>.md` if the user asks to keep it.

## Style
Write for the ear: short sentences, contractions, second person. Cut every sentence that doesn't move the story or the value forward.
