# Day 14 — Responsive Design (Media Query)

Ek hi website — laptop, tablet, mobile, har screen pe perfect.

```html
<!-- HTML <head> me zaroor -->
<meta name="viewport" content="width=device-width, initial-scale=1">
```

```css
.cards { display: grid; grid-template-columns: repeat(3, 1fr); }

/* screen 768px se chhoti ho tab */
@media (max-width: 768px) {
  .cards { grid-template-columns: 1fr; }  /* cards neeche-neeche */
  h1 { font-size: 28px; }                 /* font chhota */
}
```

**Real example (gym website):** laptop pe navbar ke saare links ek line me; mobile pe media query se links chhupao aur hamburger (☰) button dikhao.

**Yaad rakho:** Mobile-first — pehle mobile ka design, phir badi screen. Check karne ke liye browser me **F12** → Device mode (Ctrl+Shift+M).
