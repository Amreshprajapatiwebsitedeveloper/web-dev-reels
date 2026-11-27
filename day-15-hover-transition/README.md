# Day 15 — Hover Effects & Transition

Button / card ko "zinda" banao — mouse aate hi smooth animation.

```css
.btn {
  background: #ff3d7f;
  transition: all 0.3s;        /* NORMAL state pe lagao */
}
.btn:hover {                   /* jab mouse upar aaye */
  background: #8b5cf6;
  transform: scale(1.1);       /* thoda bada */
}
```

| Cheez | Kaam |
|---|---|
| `:hover` | Mouse upar aaye tab ye CSS |
| `transition: all 0.3s` | Badlaav 0.3 second me smooth |
| `transform: scale(1.1)` | 10% bada |
| `transform: translateY(-10px)` | 10px upar uthao |
| `box-shadow` | Shadow / glow |

**Real example (salon website):** services cards hover pe upar uthte hain + shadow aata hai → premium feel.

**Yaad rakho:** transition hamesha normal state pe (hover pe nahi) — tabhi aana aur jaana dono smooth. Mobile pe hover nahi hota — zaroori cheez sirf hover pe mat chhupao.
