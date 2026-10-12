# boeckx.com

The website of BDEV CommV: the company details, the PewPew TD page and its privacy policy
(`/pewpew-td/privacy/`, the URL given to Google Play). Plain HTML and CSS, served by GitHub Pages
from the `main` branch with the custom domain in `CNAME`.

The game's images come from the PewPew TD repo (`store/google-play/`, rendered by its
`tools/make_icons.tscn` and screenshot tour). The fonts (Chakra Petch, Barlow Semi Condensed) are
served from `assets/fonts/` under the SIL Open Font License, so the site loads nothing from other
domains.

To preview locally: `python -m http.server 8070`, then open http://localhost:8070.
