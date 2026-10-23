# Grace Ng — Portfolio (Version 1)
Static site: HTML, CSS, vanilla JS. No build step, no dependencies.

## Files
index.html, style.css, script.js, projects/ (6 case studies), images/, README.md

## Adding images
Drop files into `images/` using the exact filenames below. Until a file exists, a graphite placeholder showing the expected filename appears. Once uploaded it replaces the placeholder automatically. Use JPG/WebP, around 1600px wide for landscape; 1080x1920 for the 9:16 stills.

- images/grace-portrait.jpg
- images/cube-thumb-crop.jpg (cropped extract of one Star article)
- images/longform-actors-journey.jpg
- images/longform-ipoh-by-train.jpg
- images/short-malaysian-cultural-comedy.jpg
- images/short-client-behaviours.jpg
- images/short-singapore.jpg
- images/urban-decay-no-tell-motel.jpg
- images/urban-decay-invitation.jpg
- images/urban-decay-graffiti.jpg
- images/urban-decay-performers.jpg
- images/urbanscapes-overpass-performance.jpg
- images/urbanscapes-dancers-frames.jpg
- images/urbanscapes-audience-rain.jpg
- images/urbanscapes-stamping.jpg
- images/urbanscapes-installation.jpg
- images/urbanscapes-programme.jpg
- images/annihilation-mocap-forest.jpg
- images/otherworld-promo.jpg
- images/voice-guild-storyboard.jpg
- images/voice-guild-animation-still.jpg
- images/weekend-artist-waves-poster.jpg
- images/weekend-artist-rooftop.jpg
- images/weekend-artist-drawing.jpg
- images/weekend-artist-circle.jpg
- images/weekend-artist-goddesses-poster.jpg
- images/cube-the-star-cube-on-the-tube-2010-10-03.jpg
- images/cube-the-star-grace-ng-2010-10-21.jpg

## Updating content
- Project text: edit the matching file in `projects/`. Look for `[PLACEHOLDER: ...]` and replace.
- Homepage cards: edit the `.card` blocks in `index.html` (`#work`).
- Colours/fonts: CSS variables at the top of `style.css`.
- Contact: replace placeholder spans in `#contact` with `<a href="...">` links. Enable the two future-website rows the same way (remove the `disabled` class).
- Short-form stats come from archived screenshots, not live data.

## Deploy (GitHub + Cloudflare Pages)
1. Create a GitHub repository and upload all files, keeping the folder structure.
2. Cloudflare dashboard > Workers & Pages > Create > Pages > Connect to Git; choose the repo.
3. Framework preset: None. Build command: leave empty. Build output directory: `/`.
4. Save and Deploy. Every later commit redeploys automatically.
