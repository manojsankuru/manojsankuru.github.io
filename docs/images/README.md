# Profile Image

Drop your profile photo here, named exactly:

    profile.jpg

Put it in `static/images/`, not `docs/images/` — `docs/` is the built site and
Hugo overwrites it. Hugo serves everything in `/static/` at the site root, so
`static/images/profile.jpg` becomes `https://yourdomain/images/profile.jpg`,
which is what `layouts/index.html` points at.

Recommended specs:
- Square crop (1:1 ratio); the hero frame crops it to 4:5, so keep the face centred
- Around 720×720 px (displays at 360 px wide, 2× for retina)
- JPEG or WebP, keep under 150 KB
