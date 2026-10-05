# 01 — Voiceover for free instead of $22 a month

**Read it as a page:** https://alexander-domanov.github.io/channel-pages/v/01-local-voice/

Two open models, Apache 2.0, running on a MacBook with an M2 chip and 8 GB of memory. Nothing to
subscribe to.

## The numbers

| Model | Audio produced | Time it took |
|---|---|---|
| OmniVoice | 22 s | 26 s |
| Qwen3-TTS | 23 s | 73 s |

Twenty minutes of narration: about 23 minutes of waiting on OmniVoice, about an hour on Qwen3-TTS.
Peak memory 1.76 GB out of 8. Cost: zero.

## What's in this folder

- `index.html` — the page itself, the one the link opens.
- `files/measurements.html` — the table above, plus the quality-setting test.
- `files/setup.html` — the two-environment rule and the license check.
- `files/voice-clone.html` — how to record a sample the model won't butcher.

## The two things worth remembering

1. The two models can't share an environment. One wants library 5.3+, the other is pinned to 4.57.
2. The accent comes from the sample, not from the language you're generating.
