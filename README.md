# stoiss.dk

Static portfolio for Stoiss Media / Morten Wiberg. Hosted on GitHub Pages.

## Deploy
Replace the repo contents with these files and push. `CNAME` keeps the custom domain (stoiss.dk);
`.nojekyll` makes Pages serve files as-is.

## Before going live
1. **Prices:** final editing rates are in the Rates section of `index.html` (USD).
2. **Form:** opens the visitor's email app (mailto) with their details pre-filled. No third-party service.
3. **Check the claims:** "reply within a day", free-test sizes.
4. `pricing-mockup.html` is a private draft (it has your hourly notes). It is NOT in the upload zip; don't push it.

## Pages (v26)
- `index.html`: home (hero, services, proof, rates teaser, about, FAQ, contact)
- `video-editing.html`: full editing rates and scope rules
- `voiceover.html`: voice page (rates placeholder: "quoted per project")
- `localization.html`: localization & LQA (rates placeholder: "quoted per project")
- Shared styles in `styles.css`. Header, footer and contact form are repeated on every page; edit all four if you change them.

## Still to fill in
- Voiceover and localization rates (currently "quoted per project").
- Game logos: save as `assets/logos/<name>.png` (names in each `data-logo` attribute) and swap the text placeholder for an `<img>`.
- Voice demos: MP3s in `assets/audio/` (intro-en, intro-da). Replace a file with the same name to update it.

## Common edits
- **Add a video:** copy a `<li class="card">` block, change `data-id` and the two `i.ytimg.com/vi/<ID>/`
  image URLs, then update channel and title.
- **Voice demos:** put MP3s in `assets/audio/` and uncomment the `VOICE DEMOS` block.
- **Experience numbers:** the `<!-- EXPERIENCE -->` section.
- **Accent colour:** `--accent` in `styles.css`.
