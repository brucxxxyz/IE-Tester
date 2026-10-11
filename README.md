# 人格分裂器 · Personality Splitter v1.4

Independent, free, offline-capable entertainment-only social-energy app.

## First-use flow

1. Opening the page shows **no personality result or percentage** and AUTO CHECK is expanded.
2. Complete all three questions, then press **GENERATE MY STATE**.
3. The result card and manual I ↔ E slider unlock. Only one value is shown: up to 100% I on the left, BALANCE in the middle, or up to 100% E on the right. No negatives or complementary scores.
4. Open AUTO CHECK again to retest, or manually adjust the slider. RESET TO BALANCE sets the position to zero without locking the controls.
5. Reloading the webpage clears the result, responses and unlocked state. There is no user-data persistence.

## Deployment

Upload `index.html` to the root of your GitHub repository and enable **Settings → Pages → Deploy from a branch → main / (root)**. Public hosting may independently process access information, including logs. For offline use, open the HTML file locally in a browser.

## Data & status

No external JavaScript, database, analytics, cookies, localStorage or application network requests. The three-question calculation happens in page memory only. The app does not actively collect results. The browser, operating system, or hosting provider may have their own data processing. This is an entertainment prototype, not a psychological or clinical measurement.

## Credits

— Designed by i-Man — (only `i-Man` accented).

## Testing checklist

- [ ] Initial load: no result / no percent / quiz expanded
- [ ] Slider hidden before answering
- [ ] Quiz submission unlocks slider and one result card
- [ ] Slider left/centre/right correctly shows 100% I / BALANCE / 100% E
- [ ] Mandarin/Cantonese/English change texts
- [ ] Retest replaces the displayed result
- [ ] Manual slider edits result
- [ ] Reset returns BALANCE without locking
- [ ] Refresh clears session
- [ ] Privacy & Legal disclosure opens correctly

Implementation is designed to fulfill these checks; actual browser/device testing should be performed before publishing.
