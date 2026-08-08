# The Mobile Bunker — Website

**Live site:** https://hazmattic33.github.io/mobile-bunker/

Mobile golf simulator and event entertainment serving New Hampshire and Vermont.

## How this site is built

The whole site is one self-contained file, `index.html`. No build step, no framework,
no server. Images are embedded directly in the file, so you can double-click it on any
computer and it works offline.

Routing is hash based (`#/pricing`, `#/gallery`, `#/contact` and so on). That is what lets
a static host like GitHub Pages serve every page out of a single file.

## Editing content

Visit `#/admin` on the site and enter the passphrase to reach the content editor.

> **Important:** the admin area saves to your own browser storage only. Edits show up on
> the computer you made them on and nowhere else. To change the live site for everyone,
> edit `index.html` in this repo and commit.

## Before this is really launched

- [ ] **Contact form has no backend.** Submissions are saved in the visitor’s own browser
      and are NOT delivered to you. Connect it to a form service (Formspree, Netlify Forms,
      Basin) before promoting the site anywhere.
- [ ] Phone number, email address and social links are still placeholders.
- [ ] Service radius has not been defined.
- [ ] The "fully insured" line stays hidden until coverage is actually in place.
- [ ] Google Analytics and Facebook Pixel are commented-out placeholders.
- [ ] No custom domain connected yet.

## Deploying

GitHub Pages is enabled on the `main` branch, root folder. Every commit to `main`
redeploys automatically, usually within a minute.
# mobile-bunker
Website for The Mobile Bunker - mobile golf simulator rentals in NH and VT
