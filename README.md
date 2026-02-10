# Isle of Berk

A simple Viking-themed propaganda poster for the RoviSys Winter Olympics 2026. Just HTML and CSS, no frameworks or JavaScript.

The design is inspired by How to Train Your Dragon and Norse Viking aesthetics. Beards, bold colors, and propaganda poster vibes.

## Running Locally

Easiest way is to use Python's built-in HTTP server:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser. You can also just open `index.html` directly if you prefer.

## Project Structure

- `index.html` - The main page
- `styles.css` - All styles and animations
- `assets/` - Images and favicons

## Customizing Colors

All colors are set as CSS variables at the top of `styles.css`. Change them there to update the whole theme:

```css
:root {
    --color-charcoal: #2b2b2b;
    --color-deep-red: #8b1e1e;
    --color-muted-gold: #c9a227;
    --color-icy-blue: #5f9ea0;
    /* etc */
}
```

---

Made for the 2026 RoviSys Winter Olympics internal event.
