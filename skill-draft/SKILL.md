---
name: agent-lottie-asset-generation
description: Draft workflow for turning product moments into agent-generated Lottie assets.
---

# Agent Lottie Asset Generation

## Steps
1. Pick one product moment and emotional intent.
2. Specify duration, loop behavior, size, transparency, and brand constraints.
3. Ask the coding agent to generate `public/lottie.json` in a hot-reload harness.
4. Review on desktop and mobile sizes.
5. Record file size, visual defects, and handoff notes.

## Pitfalls
- Avoid open-ended “make it pretty” prompts.
- Do not accept raster-heavy JSON without size checks.
- Keep generated claims as draft until a real asset ships.
