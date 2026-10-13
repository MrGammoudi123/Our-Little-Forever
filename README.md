# Our Little Forever ❤️

A mobile-first romantic surprise website, written primarily in Tunisian Arabic (RTL).

## Website

Once GitHub Pages is enabled, visit:

**https://mrgammoudi123.github.io/Our-Little-Forever/**

## Enable GitHub Pages (one-time)

1. Open [Repository Settings → Pages](https://github.com/MrGammoudi123/Our-Little-Forever/settings/pages).
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Set **Branch: `main`**, **Folder: `/ (root)`**, and press **Save**.
4. GitHub will publish the website, typically within a few minutes. Later updates to `main` are deployed automatically.

## Editing the gift

The full, standalone site lives in **`index.html`**, with no required npm setup.

Find `window.loveConfig = {` in `index.html` to customize:
- `girlfriendName`, `myName`
- `relationshipStartDate: "2026-06-01"` (calendar counter uses `Africa/Tunis`)
- romantic welcome and secret letters
- `monthlyMemories` (unlocked stars)
- `galleryPhotos` (replace six photo placeholders)
- `loveReasons`
- `futureLetter`, `unlockDate: "2027-06-01"`
- `backgroundMusic` (leave empty to hide music button)

For photos or music, add files to this repository using folders such as `photos/` and `music/`, then update their relative paths in the config (e.g. `photos/our-photo.jpg`).

## Features

- Animated secret envelope and welcome
- Accurate completed calendar months + remaining days together
- Interactive monthly galaxy, gallery lightbox, and swipe-friendly cards
- Tap-to-reveal love reasons and secret letter
- Time capsule locked until June 1, 2027, in the Tunisia timezone
- Optional user-activated background music
- Romantic finale; responsive styling; reduced-motion support

No user accounts, server, or tracking scripts.

> **Privacy:** This repository is public. The website and any uploaded personal photos or romantic messages are publicly accessible. Only publish content that you want to share.
