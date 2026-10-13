# Iron & Grace

A Scripture-centered weekly men's Bible study hub with daily ESV readings, reflection prompts, brotherhood check-ins, and meeting planning.

## Live site

The app deploys from `main` to GitHub Pages at:

https://awemissions.github.io/Iron-and-grace/

GitHub Actions workflow: `.github/workflows/deploy-pages.yml`. Each push to `main` publishes the static site in `dist/`.

## Current features

- Week 1: Strength Under Christ, with daily ESV reading references.
- A 12-week topic outline and one-hour weekly meeting guide.
- Local daily-reading progress and device-local check-ins.
- Shareable group-chat prompts, availability sharing, and a Google Calendar event link.
- ESV passages link to ESV.org; the ESV text is not bundled.

Check-ins and reading progress are stored in the visitor's browser. Live shared chat, server-saved member profiles, and automatically tallied availability are not connected yet.

## Site files

- Static entry point: `dist/index.html`
- Former ChatGPT Sites project ID: `appgprj_6acd9611759c819182f8cb2092f0f8ce`
