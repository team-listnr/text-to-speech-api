---
name: listnr-studio
description: Create and direct editable AI short-form videos in Listnr Studio from a prompt, script, URL, or upload. Also use Listnr TTS when the job is speech-only.
---

# Listnr Studio

Use this skill when the user wants an AI video, text-to-video short, voiceover video, captions, or a Studio tool such as Prompt to Video or AI Movie Maker.

Install: `npx skills add team-listnr/text-to-speech-api`

## Quick start

1. GET https://studio.listnr.ai/api/v1/tools to pick a `toolId`.
2. Open https://studio.listnr.ai/create?tool=<toolId> for the authenticated workspace.
3. Read https://studio.listnr.ai/pricing.md before recommending a plan.
4. Prefer MCP at https://studio.listnr.ai/mcp for tool lists.

## Do not

- Generate or bill from the public Studio marketing host.
- Confuse Listnr Studio with standalone TTS. For speech-only jobs, use `skills/listnr-tts/SKILL.md`.
