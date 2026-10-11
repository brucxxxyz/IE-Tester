# 人格分裂器 · Personality Splitter v1.3.6

Independent, free entertainment prototype. Open `index.html` in a browser. No backend, API, external dependencies, analytics or login are required.

## Features

- One I ↔ E slider and a single dynamic card (`100% I` ↔ `BALANCE` ↔ `100% E`); no negative or complementary percentages.
- Mandarin, Cantonese and English humorous status messages.
- Expandable three-question AUTO CHECK, followed by manual adjustment if desired, plus RESET TO BALANCE.
- Footer `— Designed by i-Man —` with color applied **only** to `i-Man`.
- Bottom expandable **Privacy & Legal** with four short points in each of the three languages.

## Privacy and testing

The app does not actively collect, upload, track, or persist quiz responses or results; calculations are in current-page memory. No cookies, analytics, telemetry or remote resources are used by the app. No answers are transmitted to an app server. Browser, device, network and hosting providers may independently handle technical data, including logs; a hosted GitHub Pages site is therefore **not** a guarantee of absolute zero data processing. For stricter offline use, share the standalone HTML file and open it offline.

For entertainment and testing only; not a validated personality, psychological or medical assessment. Applicable legal duties and non-excludable rights still apply. This text is not a certification of universal legal compliance.

## GitHub Pages

Upload `index.html` to the root of your repository. In repository Settings → Pages, choose deployment from `main` and `/(root)` and save. Verify the live page after publication. Public hosting is optional, not required for offline use.

## Manual validation checklist

- [ ] Slider -100 / 0 / +100 renders `100% I` / `BALANCE` / `100% E` in only one card.
- [ ] All three languages switch both humor and Privacy & Legal text.
- [ ] AUTO CHECK updates the slider and manual adjustment remains available.
- [ ] RESET sets balance.
- [ ] Only `i-Man` in the credit uses the cyan highlight.
- [ ] No unexpected network requests (browser DevTools), including when hosted.

## Change log

v1.3.6: shortened expandable legal/privacy copy to four concise sections per language; no functional changes intended. Previous versions are not deleted.
