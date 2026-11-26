# Summit Siege — Web Demo

Official public browser demo of **Summit Siege** (tactical 3D elevation-driven tower defense & siege game built with React 19 + PixiJS 8).

## Play Online Now

- **Main (`v0.3.0`):** https://gcerkez.github.io/summit-siege-web/
- **`dev/0.3.1` Preview (`v0.3.1-dev.1`):** https://gcerkez.github.io/summit-siege-web/branches/dev-0-3-1/

## Build Versions & Switcher

The root page serves the latest `main` production build, tracked in `versions.json`.
Additional branch previews live under `branches/<slug>/`, share `/assets/` with root, and can be switched anytime using the draggable right-edge tab (`version-switcher.js`).

To deploy or update the current branch preview from the game repo:

```bash
npm run deploy:demo
```

## Native Releases

- Android APK / AAB & iOS IPA builds live in the private source repo releases (`gcerkez/SummitSeige`).
