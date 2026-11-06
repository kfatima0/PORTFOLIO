# PORTFOLIO

One-page portfolio built with [Astro](https://astro.build) (no other frameworks).

## Files you will edit

| File | What it contains |
| --- | --- |
| `src/pages/index.astro` | The whole page. **All text, links and image paths are at the top**, between the `---` lines. The HTML below just displays them. |
| `src/styles/global.css` | All the styling. Colours are at the top (`--accent` is the deep blue). |
| `public/` | Files copied as they are: put your images in `public/images/`. |

## Run it on your computer

```bash
npm install      # once
npm run dev      # open http://localhost:4321 — updates as you save
npm run build    # creates the final site in the "dist" folder
```

## Publish

**Netlify:** connect the GitHub repo on netlify.com. `netlify.toml` already tells Netlify what to do.

**GitHub Pages:**
1. In `astro.config.mjs`, uncomment `site` and `base` (use your username and repo name).
2. On GitHub: Settings → Pages → Source: **GitHub Actions**.
3. Push to `main`. The workflow in `.github/workflows/deploy.yml` builds and publishes the site.
