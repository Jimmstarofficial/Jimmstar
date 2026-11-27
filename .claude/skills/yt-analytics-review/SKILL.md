---
name: yt-analytics-review
description: Analyze YouTube Studio analytics exports or pasted metrics (CTR, AVD, retention, impressions, subs) and recommend concrete next actions. Use when the user shares channel or video stats or asks why a video under/over-performed.
---

# Analytics Review

## Inputs
A CSV export from YouTube Studio (Advanced mode → Export) or pasted numbers. Read the files the user names; don't guess at missing data. Ask for it instead.

## Diagnose with this order
1. **Impressions low?** It's a topic or reach problem: discovery, search demand, browse fit.
2. **CTR low (under ~4% for browse traffic, depending on the niche)?** It's a packaging problem. Hand off to `yt-title-thumbnail`.
3. **Avg view duration or % viewed low?** It's a content problem. Check the retention graph: a drop in the first 30s means the hook broke its promise, and a steady slide means pacing. Hand off to `yt-script-writer`.
4. **Good retention but few subs or returning viewers?** It's a CTA or series problem.

Always compare against the **channel's own median** of recent uploads, not against generic benchmarks.

## Output
- A 3-line summary of what happened and why.
- A table of the key metrics against the channel median.
- **3 prioritised actions**, each specific and testable ("Re-test the thumbnail with a face close-up and no text").
- Use a short Python/pandas script for CSVs when the data is large, and show the numbers you computed.

## Logging
If the user agrees, append the insight to `channel/learnings.md` so later sessions build on it.
