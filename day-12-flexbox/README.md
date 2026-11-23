# Day 12 — Flexbox

Div ko center karna ab sirf 3 lines ka kaam hai:

```css
.box {
  display: flex;          /* items ek line me */
  justify-content: center; /* left ↔ right (horizontal) */
  align-items: center;     /* upar ↕ neeche (vertical) */
  gap: 20px;               /* items ke beech doori */
}
```

| Property | Kaam |
|---|---|
| `display: flex` | Parent pe lagao — andar ke items ek line me |
| `justify-content` | Horizontal align (center, space-between...) |
| `align-items` | Vertical align |
| `gap` | Items ke beech space |

**Real example (coaching institute website):** navbar pe `display: flex` + `justify-content: space-between` → logo left, menu right. `align-items: center` se sab ek line me perfect.

**Yaad rakho:** Flexbox hamesha **parent** pe lagta hai, child pe nahi. Mobile pe items neeche-neeche chahiye? `flex-direction: column` laga do.
