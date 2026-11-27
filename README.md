# Jimmstar: YouTube agent skills

Twelve Claude Code skills for running a YouTube channel, installed in `.claude/skills/` from
[Jakeschincariol/youtube-agent-skill](https://github.com/Jakeschincariol/youtube-agent-skill)
(MIT, see `.claude/skills/LICENSE-youtube-agent-skill`), plus `/yt-launch` for starting a channel from zero.

| Command | What it does |
|---|---|
| `/yt-launch` | **Start here for a new channel:** name, banner, About text, the made-for-kids setting, and the first 10 videos |
| `/yt-script` | Idea → script: 5 hooks from 21 formulas, scored, with on-screen beats marked |
| `/yt-package` | Title and thumbnail written and linted together |
| `/yt-edit` | Transcript → list of cuts (dead air, filler, retakes) |
| `/yt-comment` | Sorts comments and drafts replies; says which to pin |
| `/yt-plan` | A week sized to your hours: 1 main video, 1 easy one, 3 Shorts |
| `/yt-viral` | What's working in your niche, ranked against each channel's median |
| `/yt-retention` | Reads a retention export: early drop-off, sudden drops, slow decline |
| `/yt-shorts` | Finds the Shorts inside a long video |
| `/yt-seo` | Description, tags, and the 3 searches the video should win |
| `/yt-chapters` | Chapters that pass YouTube's rules |
| `/yt-audit` | Whole-channel review ending in one fix |

## How to use it

Open a Claude Code session on this repo and ask in plain words, like "plan my first week" or
"write a Roblox story about a haunted school". The matching skill loads by itself. You can also
type the command, e.g. `/yt-launch`.

**Starting a new channel:** run `/yt-launch` first. It sets up the channel and plans the first
ten videos. Then use `/yt-script` and `/yt-package` for each video.

| Day one | After a few uploads | After ten or more uploads |
|---|---|---|
| `/yt-launch`, `/yt-script`, `/yt-package`, `/yt-seo`, `/yt-plan`, `/yt-viral` | `/yt-comment`, `/yt-edit`, `/yt-chapters`, `/yt-shorts` | `/yt-retention`, `/yt-audit` |

Every skill reads your voice profile in `channel/voice.md`. Update it whenever your style changes.
Nothing here publishes to YouTube; the skills write, you upload.
