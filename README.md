# stoiss.dk

Static portfolio for Stoiss Media / Morten Wiberg. Hosted on GitHub Pages.

## Deploy
Replace the repo contents with these files and push. `CNAME` keeps the custom domain (stoiss.dk);
`.nojekyll` makes Pages serve files as-is.

## Common edits
- **Add a video:** copy a `<li class="card">` block in `index.html`, change the `data-id` and the two
  `i.ytimg.com/vi/<ID>/` image URLs to the new YouTube ID, and update the channel and title.
- **Add voice demos:** put MP3s in `assets/audio/` and uncomment the `VOICE DEMOS` block in the Voice section.
- **Accent colour:** `--accent` in `styles.css` (the only colour on the page).
