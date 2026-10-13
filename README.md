# Iron & Grace

A Scripture-centered weekly men's Bible study hub with daily ESV readings, reflection prompts, brotherhood check-ins, and meeting planning.

## Deployment status

The GitHub Pages workflow is configured in `.github/workflows/deploy-pages.yml`. GitHub Pages must first be enabled for this repository with the source set to **GitHub Actions**. Then rerun the workflow from the Actions tab. Until that succeeds, the site is not live.

Intended URL: https://awemissions.github.io/Iron-and-grace/

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
