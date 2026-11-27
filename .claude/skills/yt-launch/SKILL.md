---
name: yt-launch
description: >-
  Start a brand-new YouTube channel from zero: the name and handle, the
  profile picture, banner and About text, the audience (made for kids)
  setting, and the first ten videos as a launch plan. Use for "new channel",
  "start a channel", "I'm launching", "day one", "set up my channel", "my
  first videos", or whenever the channel has no uploads yet.
---

# yt-launch

A new channel has no data, so nothing here guesses at numbers. Day one is about three things: a
channel a stranger understands in two seconds, ten videos planned before the first goes up, and a
habit of measuring from upload one.

## Before you write

1. Read `channel/voice.md` (at the repo root). If it's missing or still the blank template, build
   it first with the user. Ask what they'll make, who narrates (their voice, text only, or AI/TTS),
   the tone, and who the viewer is. Then write the file. Don't wait for videos that don't exist yet.
2. Never invent a number, a result or a source. A new channel has no stats, so say so instead of
   estimating.

## Step 1: the identity

- **Name:** give five options that say what the channel is or have a sound that sticks. Check each
  one: is it easy to spell after hearing it once, and could it still fit if the content changes
  slightly? Remind the user to check the **@handle** is free in YouTube Studio. You can't check that
  from here.
- **Profile picture:** one subject, readable as a 40px circle, consistent with the thumbnail style.
- **Banner:** what the channel is, plus when uploads come ("New Roblox stories every Tue / Fri").
  Keep the text in the centre safe area, because the edges get cropped on phones.
- **About section:** two sentences. What a viewer gets, and how often. The first line is the one
  that shows.
- **Channel keywords:** five to eight words describing what you actually make.

## Step 2: the settings people forget

Hand these back as a checklist the user ticks off in YouTube Studio:

- [ ] **Audience: made for kids or not.** This is a legal setting (COPPA), not a style choice. If
      the content is aimed at children, it must be marked made for kids. That turns off comments,
      end screens and some other features. Explain the trade-off and let the user decide. Never
      tell them to mark kid-directed content as "not made for kids" to keep comments.
- [ ] Upload defaults: the hashtags, description footer and category used every time.
- [ ] Verify the account with a phone number, which unlocks custom thumbnails on long-form videos.
- [ ] Add the channel trailer or featured video once the first video exists.

## Step 3: the first ten videos

Plan **ten** before posting **one**. A new channel is judged by its first few uploads, and having
the list removes the "what do I post today" stall that kills most channels in week three.

- Make 3–4 variations of the core format, not ten different ideas. The early job is finding which
  version works.
- For each one: a working title, the hook line (run it through `../yt-script/hookscore.py`), and
  a one-sentence summary.
- Pick a **cadence the user can keep for eight weeks** (ask how many hours a week they have). Two
  a week that never misses is better than daily for ten days.
- Use `/yt-script` to write the first three in full and `/yt-package` for their titles.

## Step 4: what to measure from day one

Nothing to analyse yet, so set up the habit instead:

- After each upload's first 48 hours, note **views, average % viewed, and swipe-away / CTR** in
  `channel/log.md`. Create it if it doesn't exist.
- After ten uploads, the other skills have data to work with: `/yt-retention` on the best and
  worst, `/yt-audit` on the whole channel, and `/yt-viral` on the niche.

## Which skills work on day one

| Day one | After a few uploads | After ten or more uploads |
|---|---|---|
| `/yt-launch`, `/yt-script`, `/yt-package`, `/yt-seo`, `/yt-plan`, `/yt-viral` (niche research only) | `/yt-comment`, `/yt-edit`, `/yt-chapters`, `/yt-shorts` | `/yt-retention`, `/yt-audit` |

## What to hand back

1. The five names with a recommendation.
2. Profile picture, banner and About text, ready to copy.
3. The settings checklist.
4. The ten-video table: number, working title, hook, hook score, and the format variation.
5. The cadence, and the date the first video should go up.

## The gate

Nothing here publishes. This skill writes and you publish. Every output ends in a block the user
copies, and the last line of every run is the question: **ship it, or change it?**
