> Note from the editor:
> 
> The creation of project was assisted by Claude Opus 4.5 (and some Sonnet 4.5) with GitHub Copilot in VS Code.

# Isle of Berk

An interactive Viking/How To Train Your Dragon themed propaganda poster for the RoviSys Winter Olympics 2026. Just plain HTML and CSS!

<b> Beards, strength, speed, dragons . . . </b>

[Check it out!](https://www.isleofberk.org)
> If that link breaks because I forget to renew the domain, try [this one](https://isleofberk.pages.dev)
## Running Locally

Clone the repo and open `index.html` in your browser. No weird deprecated dependency installs here.

## Project Structure

- `index.html` - The main page
- `styles.css` - All styles and animations
- `assets/` - Images, gifs, favicons

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
