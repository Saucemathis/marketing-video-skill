# marketing-video

A [Claude Code](https://claude.com/claude-code) skill that makes a finished marketing video for any brand: one morphing UI shape, a real cursor, springs, a camera that zooms, a soundtrack cut on the beat, rendered to MP4 from code.

It starts by asking for your context: what the video is about, screenshots of your product, your design system, and an inspiration video. It reads the inspiration, proposes a beat-by-beat plan for you to approve, then builds, checks and renders the video in 1:1 and 9:16.

## Install

```bash
git clone https://github.com/Saucemathis/marketing-video-skill ~/.claude/skills/marketing-video
```

Or download the ZIP (Code, then Download ZIP), unzip it, and rename the folder to `marketing-video` inside `~/.claude/skills/`. The path must end in `skills/marketing-video/SKILL.md`.

Then ask Claude Code for a marketing video, or type `/marketing-video`.

## Requirements

node, ffmpeg, and python3 with numpy. The skill installs the rest (Playwright's Chromium) in each video project.

## License

[MIT](LICENSE)
