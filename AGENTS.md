# AGENTS.md

Public Listnr agent configs for coding agents and product agents.

## Products

- **Listnr Studio** at https://studio.listnr.ai — short-form AI video. Read `/llms.txt`, call `/openapi.json`, and send people to `/create?tool=<toolId>`. Do not generate or bill from the public host.
- **Listnr TTS API** — convert text, URLs, and PDFs to speech with `x-listnr-token`. See this README.

## Studio

1. https://studio.listnr.ai/llms.txt
2. https://studio.listnr.ai/openapi.json
3. Anonymous GET https://studio.listnr.ai/api/v1/tools
4. MCP Streamable HTTP at https://studio.listnr.ai/mcp
5. Skill: `skills/listnr-studio/SKILL.md`

## TTS API

1. Base URL: `https://bff.listnr.tech/api/tts/v1/`
2. Auth header: `x-listnr-token`
3. Skill: `skills/listnr-tts/SKILL.md`

## Contact

support@listnr.ai
