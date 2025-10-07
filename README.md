# Allie Oh — Essay Landing (Medium Promo)

This repo hosts a minimal landing page that points readers to my Medium essay:
**“Allie Oh and My Suicide Attempt Story.”**

- **Medium (canonical):** https://medium.com/@linkfromthefuture921/allie-oh-and-my-suicide-attempt-story-351f066ad038-351f066ad037
- **GitHub Pages (this landing):** https://j59744467-stomp.github.io/

> **Content Warning:** Mentions of suicidal ideation/attempt and emotional trauma.

## Why this exists

- If using `index.html`, it sets a `<link rel="canonical">` to the Medium URL.

## Quick start
1. Replace `MEDIUM_URL_HERE` in `index.md` **or** `index.html` (pick one).
2. Commit to `main` and enable **Settings → Pages → Deploy from a branch → main / (root)**.
3. Wait ~1–2 minutes; your Pages URL will go live.
4. Share **your Pages URL**; it forwards readers to Medium (visually or via redirect if you enable the meta refresh).

## Files
- `index.md` — simplest; uses frontmatter `title` + `description`.  
- `index.html` — recommended; adds canonical + Open Graph/Twitter meta and (optional) fast redirect.
- *(Optional)* `assets/preview.jpg` — social preview image you can reference in `index.html`.

## SEO notes (keep it lean)
- Use both name variants in **title/H1/description**: “**Allie Oh**”.
- Mention **Harvard** once in a short excerpt to capture long-tail searches (e.g., “Harvard-bound”).
- Don’t paste the full essay here (avoid duplicate content). Medium remains canonical.
- If you hook up Google Search Console to your Pages URL, use **URL Inspection → Request Indexing**.

## Troubleshooting
- **404 after enabling Pages?** Give it a minute, then hard refresh (Ctrl/Cmd+Shift+R).
- **No preview card on social?** Add an OG image (e.g., `assets/preview.jpg`) and set it in `index.html`.
- **Indexing slow?** Share your Pages link from a few profiles to create initial backlinks.
