# Day 11 — Box Model

CSS me **har element ek box** hai — andar se bahar:

| Layer | Matlab |
|---|---|
| `content` | Text ya image |
| `padding` | Andar ki jagah |
| `border` | Box ki line |
| `margin` | Doosre box se doori |

**Real example (real estate website):** property cards chipke hue bure lagte hain → har card ko `padding` do (photo + price andar aaram se) aur `margin` do (cards ke beech gap) → page ekdum clean.

**Yaad rakho:** `width` dene par padding + border bahar jud jaate hain aur box bada ho jata hai. Isliye hamesha `* { box-sizing: border-box; }` lagao — box utna hi rahega jitna tumne bola.
