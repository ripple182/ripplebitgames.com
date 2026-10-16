# ripplebitgames.com

This is the public static site for RippleBitGames and its game Doodle Wizards.
GitHub Pages serves `docs/` at https://ripplebitgames.com. There is no build step. It is plain HTML and CSS.

## Public repo

- Everything in this repo is public, including history.
- Everything in `docs/` is on the live website.
- Only put files the website uses in `docs/`. Notes, drafts, plans and marketing docs live in the private `ripple182/SteamMarketing` repo, not here.
- Never commit secrets. No API keys, tokens, passwords, or private email addresses.
- Commit with `ripple182@users.noreply.github.com`.

## Layout

- `docs/index.html`: studio home.
- `docs/DoodleWizards/index.html`: game page.
- `docs/404.html`: lowercase redirect and not-found page.
- `docs/assets/`: `site.css` and images.
- `docs/CNAME` and `docs/.nojekyll`. Don't delete these.

## Paths

- Paths are case-sensitive. The game page is `/DoodleWizards/`. The redirect in `404.html` covers lowercase.
- Use absolute `/assets/...` paths.

## Look

- Notebook-paper background, Patrick Hand font, colors from the CSS variables in `site.css`.
- Keep it light and fast. No JS frameworks or trackers.

## Social links on the game page

TikTok @doodlewizards, YouTube @DoodleWizards, Instagram doodlewizards, X @DoodleWizards1, Bluesky doodlewizards.bsky.social, Twitch doodlewizards, r/DoodleWizards.
Discord and the Steam wishlist button get added later, when they exist.

## Before pushing

- Check the changed page at 375 px and at desktop width. Use a screenshot through a local server: `python -m http.server` from `docs/`.
- Confirm nothing in the diff is private.

## Hosting

- DNS lives in Cloudflare and must stay "DNS only" (grey cloud).
- The site's HTTPS certificate comes from GitHub, not Cloudflare.

## Rules

- Don't commit or push unless the user asks.
