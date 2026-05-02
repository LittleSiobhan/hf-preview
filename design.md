---
name: AI文旅手绘涂鸦风
background: "#F5EFE0"
foreground: "#2A1F14"
accent: "#D4602A"
muted: "#8B7355"
surface: "#EDE4D0"
border: "#C4A97A"
highlight: "#E8A84C"
fonts:
  display: ZCOOL KuaiLe
  body: Noto Sans SC
  mono: ZCOOL QingKe HuangYou
---

# AI文旅手绘涂鸦风

## Overview

Hand-drawn notebook aesthetic — like flipping through a thoughtful travel journal with coffee stains and margin notes. Playful but substantive, warm and approachable.

## Colors

| Token | Hex | Usage |
|-------|-----|-------|
| bg | `#F5EFE0` | Aged rice paper (background) |
| fg | `#2A1F14` | Dark ink (primary text) |
| accent | `#D4602A` | Burnt sienna (highlights, step numbers) |
| muted | `#8B7355` | Faded ink (secondary text) |
| surface | `#EDE4D0` | Lighter paper (cards) |
| border | `#C4A97A` | Pencil lines (sketchy borders) |
| highlight | `#E8A84C` | Warm amber (glows, annotations) |

## Typography

- **Display:** ZCOOL KuaiLe (handwritten Chinese, playful, bold)
- **Body:** Noto Sans SC (clean, readable)
- **Mono/Annotations:** ZCOOL QingKe HuangYou

## Motion

- Entrances: `back.out(1.2)` — bouncy, hand-drawn feel
- Exits: `power2.in` — soft fade like ink lifting
- Decorative: gentle drift, subtle pulse
- Border draw-in: `stroke-dashoffset` animation

## Atmosphere

- Paper grain overlay (SVG noise, 4% opacity, fixed)
- Ghost text drift (4-8% opacity, slow)
- Sketchy/dashed borders on all containers
- Ink splatter decorations (small, bottom corners)

## Do's

- Asymmetric layouts with margin annotations
- Hand-drawn border animations
- Warm earth tones, never pure white/black
- Bouncy entrances that feel pen-drawn

## Don'ts

- Clean geometric vector illustrations
- Corporate blue or tech-purple palettes
- Centered floating layouts
- Static decorative elements