# stoiss.dk

Static portfolio for Stoiss Media / Morten Wiberg. Hosted on GitHub Pages.

## Deploy
Replace the repo contents with these files and push. `CNAME` keeps the custom domain (stoiss.dk);
`.nojekyll` makes Pages serve files as-is.

## Before going live
1. **Prices & turnaround:** in `index.html`, search for `XX` (Rates section) and fill in real numbers.
2. **Form:** create a free form at https://formspree.io, copy its ID, and replace `YOUR_FORM_ID`.
   Until then, the form opens the visitor's email app with everything pre-filled, so it works either way.
3. **Check the claims:** "reply within a day", "one round of revisions", "invoiced in EUR or DKK", free-test sizes.

## Common edits
- **Add a video:** copy a `<li class="card">` block, change `data-id` and the two `i.ytimg.com/vi/<ID>/`
  image URLs, then update channel and title.
- **Voice demos:** put MP3s in `assets/audio/` and uncomment the `VOICE DEMOS` block.
- **Experience numbers:** the `<!-- EXPERIENCE -->` section.
- **Accent colour:** `--accent` in `styles.css`.
