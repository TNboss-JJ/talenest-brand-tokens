# TaleNest Brand Tokens

Design tokens (colors, characters, typography, motion) of [TaleNest](https://talenest.org) — a behavioral observation SaaS for children's emotional learning.

Released under **Apache 2.0** for educators, designers, researchers, and the open-source community to reference, study, or integrate into compatible tools.

> **Trademark note**: This license grants you rights to the design tokens (color values, naming conventions, structure). It does **not** grant you rights to the TaleNest® name, logo, or character artwork. See [TRADEMARK.md](./TRADEMARK.md).

---

## What's in here

```
brand-tokens/
├── colors/
│   ├── characters.json      # 8 character signature colors
│   ├── emotion-families.json # 7 emotion-family color palette
│   └── brand.json           # primary brand palette (slate / cream / coral)
├── typography/
│   └── stack.json           # font fallback stack
└── motion/
    └── timing.json          # animation easings & durations
```

---

## 8 Character Colors

| ID | Korean | Animal | Hex | Preview |
|---|---|---|---|---|
| `nesto` | 네스토 | 🐰 Rabbit | `#A8D8EA` | ![](https://img.shields.io/badge/-A8D8EA-A8D8EA?style=flat-square) |
| `ollie` | 올리 | 🐢 Turtle | `#7EC8B8` | ![](https://img.shields.io/badge/-7EC8B8-7EC8B8?style=flat-square) |
| `meela` | 밀라 | 🐱 Cat | `#C5A3D9` | ![](https://img.shields.io/badge/-C5A3D9-C5A3D9?style=flat-square) |
| `chippy` | 치피 | 🐿️ Squirrel | `#E6CCAE` | ![](https://img.shields.io/badge/-E6CCAE-E6CCAE?style=flat-square) |
| `pipi` | 피피 | 🐥 Chick | `#FFE066` | ![](https://img.shields.io/badge/-FFE066-FFE066?style=flat-square) |
| `rusty` | 러스티 | 🦊 Fox | `#FFB347` | ![](https://img.shields.io/badge/-FFB347-FFB347?style=flat-square) |
| `lumo` | 루모 | 🐶 Dog | `#9BB8D3` | ![](https://img.shields.io/badge/-9BB8D3-9BB8D3?style=flat-square) |
| `bamboo` | 밤부 | 🐼 Panda | `#2D2D2D` | ![](https://img.shields.io/badge/-2D2D2D-2D2D2D?style=flat-square) |

---

## 7 Emotion Family Colors

| Family | Korean | Hex | Emotion Count |
|---|---|---|---|
| `joy_energy` | 기쁨과 활력 | `#FFE066` | 7 |
| `pride_confidence` | 자부심과 자신감 | `#FFA94D` | 8 |
| `love_connection` | 사랑과 연결 | `#FF69B4` | 6 |
| `sadness_loss` | 슬픔과 상실 | `#5C7CFA` | 7 |
| `anger_conflict` | 분노와 갈등 | `#FF6B6B` | 7 |
| `fear_anxiety` | 두려움과 불안 | `#9775FA` | 7 |
| `complex_emotions` | 복합 감정 | `#868E96` | 7 |

Total: **49 emotions** mapped across 7 families × 8 characters.

---

## Primary Brand Palette

| Token | Hex | Usage |
|---|---|---|
| `brand-dark` | `#4E6F79` | Primary text, navigation, anchor |
| `brand-cream` | `#EDE5D0` | Active states, soft highlights |
| `brand-coral` | `#D08B74` | Accent, CTAs, important actions |
| `brand-soft` | `#FCF3DC` | Background washes, hero sections |

---

## Quick install

```bash
npm install talenest-brand-tokens
# or copy the JSON files directly
```

```typescript
import characters from "talenest-brand-tokens/colors/characters.json"

console.log(characters.ollie.hex) // "#7EC8B8"
```

---

## Philosophy

TaleNest's color system follows three principles:

1. **Soft, child-friendly hues** — pastel base, never saturated alarm colors
2. **Animal-character anchoring** — every color belongs to a story-world character (not abstract)
3. **Emotion-family clustering** — 7 emotion families × consistent hue logic (joy=yellow, sadness=blue, etc.)

This makes the system **memorable for children** (color → character → story) and **maintainable for developers** (semantic naming, not arbitrary hex).

---

## License

[Apache License 2.0](./LICENSE) — code and tokens are free to use, modify, distribute. See [TRADEMARK.md](./TRADEMARK.md) for name/logo limitations.

---

## Related

- [TaleNest](https://talenest.org) — the SaaS this brand belongs to
- [Positioning Guard](https://github.com/TNboss-JJ/TNboss-JJ) — language rules (observation, not diagnosis)

---

© 2026 TaleNest / Jung Dajeong. Some rights reserved (Apache 2.0).
