# Profile Image

Drop your profile photo here, named exactly:

    headshot.jpg

Put it in `static/images/`, not `docs/images/` — `docs/` is the built site and
Hugo overwrites it. Hugo serves everything in `/static/` at the site root, so
`static/images/headshot.jpg` becomes `https://yourdomain/images/headshot.jpg`,
which is what `layouts/index.html` points at.

Recommended specs:
- Square crop (1:1); the hero renders it as a circle, so leave a little space
  above the hair or the mask will clip it
- Head should fill roughly 55-60% of the height, face centred horizontally
- Around 1040×1040 px (displays at 360 px wide, so ~2.9× for retina)
- JPEG or WebP, keep under 200 KB

Changing the filename is a free cache-bust — browsers and the GitHub Pages
edge both cache `/images/*` aggressively, so a new name is more reliable than
replacing bytes at the same URL.
