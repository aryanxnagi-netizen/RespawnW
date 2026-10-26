# RESPAWN Official Website

Fresh, standalone static multi-page website. It does not modify or depend on the RESPAWN app repository.

## Pages
- `index.html` — cinematic story-led homepage
- `features.html` — planned product pillars
- `fragz.html` — gaming clips concept
- `squad.html` — Squad Finder concept
- `tournaments.html` — ARENA/community tournament concept
- `games.html` — intended game-community focus

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.

## Publish on GitHub Pages
1. Create a **new repository** for the official website.
2. Upload the contents of this folder to the repository root (keep `index.html` at the root).
3. In Settings → Pages, select the branch and `/ (root)`.
4. Save and wait for GitHub Pages to publish.

## External waitlist
The website does not pretend to collect signups. In `assets/js/main.js`, set `const WAITLIST_URL = "";` to your real external waitlist form URL when available. Until then, buttons show an honest coming-soon message.

## Download claim
No Play Store listing or installable release was provided, so this website does not claim the app is downloadable. Update the CTA to a verified listing only when a real public release exists.

## Truthfulness
Features are described as planned/in development. Game names describe intended focus only; no partnerships, live tournaments, player counts, testimonials, social links, or contact details are fabricated.

## Customization
- `assets/css/styles.css` — visual system and responsive styles
- `assets/js/main.js` — page content, navigation, animations, waitlist URL
