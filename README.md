# Skill-pack

A curated bundle of 32 Agent Skills for design, animation and video work.
Works in **Claude Code**, **GitHub Copilot** and other tools that read `SKILL.md`.

## Install (Claude Code, global)

```bash
git clone --depth 1 https://github.com/Temichnor/Skill-pack.git /tmp/skill-pack
mkdir -p ~/.claude/skills && cp -r /tmp/skill-pack/skills/* ~/.claude/skills/
rm -rf /tmp/skill-pack
```

For one project only, copy into `.claude/skills/` (Claude Code) or `.github/skills/` (Copilot) in that repo.

## What's inside

| Source | Skills | License |
|---|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | hyperframes, hyperframes-cli, hyperframes-registry, figma, media-use, remotion-to-hyperframes, reverse-any-video, slideshow, style-sampling | Apache-2.0 |
| [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill) | remotion-motion-graphics | MIT |
| [emilkowalski/skills](https://github.com/emilkowalski/skills) | 20 animation and UI skills (animate, choreograph, gestures, apple-design, review-animations, …) | MIT |
| [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | taste-skill | MIT |
| [pbakaus/impeccable](https://github.com/pbakaus/impeccable) | impeccable | Apache-2.0 |

All credit goes to the original authors. Each source's license is in [`licenses/`](licenses/).
This pack is a snapshot from 2026-11-19; pull from the sources for the latest versions.

## API keys

Some scripts in `media-use` read optional keys from environment variables (`GEMINI_API_KEY`, `ELEVENLABS_API_KEY`). No keys are included in this repo.
