# Agent instructions — Cardell Exhibit Service site

This file is for coding agents working in this repo. It is not site copy.

## What this is

Public website for Cardell Exhibit Service, a Washington shop that is successor of record for orphaned 2010s learning-center interactives: break/fix, conversions, and care of exhibits already on the floor.

Live: https://cardellexhibits.com/
Repo: https://github.com/cardellexhibits/cardellexhibits.github.io
Clone: https://github.com/cardellexhibits/cardellexhibits.github.io.git

## How to change the live site

Static files only. Push or merge to `main` and GitHub Pages deploys. There is no CI beyond the default Pages workflow. Do not add a bundler, SSG, npm, or a theme.

Public copy is `index.html`. Do not put product copy in this file.

## Locks (do not violate)

- Keep the site small: contact, services, portfolio as it grows. No marketing landing page, no blog, no shop.
- Never mention AI, models, Qwen, Grok, Codex, or similar in public-facing copy (including index.html, titles, meta, alt text, and visible comments).
- No prices.
- Do not offer gallery remodels, new fabrication, or display sales. TVs and projectors: refer to Desco AV in Olympia (https://www.descoav.com/).
- Do not put LOTT, Brightwater, Cedar River, Seitel, or any other client name on the portfolio unless Nick has said that job may be shown. The LOTT microscope work is real but Seitel-era; it stays off the site until Nick or Manager say otherwise.
- No phone number until a live Quo (OpenPhone) 360 or 253 is provided. Email only: nick@cardellexhibits.com.
- Do not email clients from this work. Do not charge cards or buy GitHub, GoDaddy, or hosting add-ons. If a change would cost money, stop.
- Do not add analytics, chat widgets, forms that need a paid backend, or third-party fonts/CDNs unless asked.

## Files

- index.html — the public page
- favicon.svg — tab icon
- CNAME — custom domain cardellexhibits.com (do not delete)
- README.md — how it builds and deploys
- AGENTS.md — this file

## PRs

Prefer a branch and pull request against `main`. Keep diffs small. Do not rewrite the page for style. Do not add a portfolio section with placeholders.
