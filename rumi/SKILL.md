---
name: rumi
description: Display a random Rumi poem in a beautiful ASCII frame. Use when the user types "rumi" or asks for a Rumi poem, quote, or moment of zen/inspiration.
---

# Rumi

A moment of peace for engineers. Do NOT read any files or run any commands.

## Instructions

Output a Rumi poem in this ASCII frame. The first line must be the centered `·` decoration:

```
                    ·
  +--------------------------------------+
  |                                      |
  |              R U M I                 |
  |             · · ✦ · ·                |
  |                                      |
  |      What you seek is seeking you.   |
  |                                      |
  +--------------------------------------+
                    ·
```

Rules:
- First line: spaces + centered `·` (aligned with frame center)
- Last line: same `·` for symmetry
- Use `+` corners, `-` horizontal, `|` vertical
- Center everything
- Adjust width to fit poem with ~4 char padding per side
- Pick a different well-known Rumi poem/quote each time
- Output ONLY the framed poem, nothing else
