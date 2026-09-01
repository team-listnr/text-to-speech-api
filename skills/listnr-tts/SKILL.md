---
name: listnr-tts
description: Convert text, article URLs, and PDFs to speech with the Listnr TTS API.
---

# Listnr TTS API

Use this skill when the user wants text-to-speech, cloned voices, or word timestamps — not a video.

## Auth

Header `x-listnr-token` from https://voices.listnr.ai/api

## Endpoints

- Base: `https://bff.listnr.tech/api/tts/v1/`
- `POST /convert-text` with `voice` and `ssml`
- `GET /available-voices`
- Ultra/cloned stream: `https://cloning.listnr.tech/api/v2/stream-voice`

See the repository README for request bodies.
