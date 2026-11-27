# Day 13 — CSS Grid

Cards ko rows + columns me saaf lagane ka sabse aasaan tareeka:

```css
.menu {
  display: grid;                          /* parent pe */
  grid-template-columns: repeat(3, 1fr);  /* 3 barabar columns */
  gap: 20px;                              /* cards ke beech doori */
}
```

| Property | Kaam |
|---|---|
| `display: grid` | Parent pe lagao |
| `grid-template-columns` | Kitne columns aur kitne bade |
| `1fr` | Bachi hui jagah ka ek hissa |
| `repeat(3, 1fr)` | `1fr 1fr 1fr` ka short form |
| `gap` | Rows/columns ke beech space |

**Real example (restaurant website):** menu ke 6 dish cards → `repeat(3, 1fr)` se 2 rows × 3 columns.

**Yaad rakho:** ek line ke items → Flexbox. Rows + columns dono → Grid. Mobile pe `grid-template-columns: 1fr;` → sab neeche-neeche.
