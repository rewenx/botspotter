# Bot Spotter

Chrome extension that flags likely AI-generated text on **Reddit**, **Twitter (X)**, and **Amazon reviews**.

## Status
Pre-alpha. Scaffolding & selectors first; detection API mocked.

## Roadmap (v0.1)
- [ ] MV3 manifest & scaffold
- [ ] Content script injection (R/T/A)
- [ ] Robust selectors for comments/posts/reviews
- [ ] Detection adapter (mock → real)
- [ ] Inline badges + color scale
- [ ] Popup UI with per-site toggles
- [ ] Background queue & rate limits
- [ ] Manual test plan
- [ ] Pack & load in Chrome

## Dev
- Branches: `dev` → PR → `main`
- Node + plain JS first; TypeScript later if needed.
