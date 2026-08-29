# Cardell Exhibit Service — public site

Static HTML for [cardellexhibits.com](https://cardellexhibits.com/). No build step, no framework, no package manager.

## Copy

All public copy lives in `index.html`. Keep it a small year-1 page: contact, services, and a portfolio only when there is a paid job Nick has approved to show.

Contact email: `nick@cardellexhibits.com`. Do not add a phone number until one is provided for the business line.

## Deploy (GitHub Pages)

This is a user site: repo `cardellexhibits/cardellexhibits.github.io`, branch `main`, folder `/` (root).

1. Edit `index.html` (and `favicon.svg` if needed).
2. Commit to `main`.
3. Pages builds from `main` and publishes to the custom domain.

`CNAME` must contain exactly `cardellexhibits.com`. Apex DNS at GoDaddy is four A records to GitHub Pages (`185.199.108.153` `185.199.109.153` `185.199.110.153` `185.199.111.153`). `www` is a CNAME to `cardellexhibits.github.io`. Do not change MX, TXT, DKIM, or autodiscover (Microsoft 365 mail).

HTTPS is issued by GitHub Pages after DNS is correct. Do not buy hosting, themes, or registrar add-ons.

## Local preview

Open `index.html` in a browser, or from this directory:

    python3 -m http.server 8080

Then visit http://127.0.0.1:8080/
