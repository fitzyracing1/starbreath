# starbreath

StarBreath Hand Loop. A static site for a manual emergency oxygen and rebreather bellows aimed at spacecraft cabins (Starship-class) and the Moon.

The unit circulates gas through a CO2 canister when the fan is dead, and meters oxygen from a regulator. It does not compress bottle oxygen by hand.

Concept only. Not a flight unit. Not a medical device.

## Pages

GitHub Pages, project site, from the repo root.

Expected URL: `https://fitzyracing1.github.io/starbreath/`

If the owner is different, edit the `og:*` and canonical URLs in `index.html`.

Share cards:

- `og.jpg` and `public/og.jpg` — 1200×630
- `x-banner.jpg` and `public/x-banner.jpg` — 1500×330

## Push

```bash
unzip starbreath.zip
cd starbreath
git init
git add .
git commit -m "StarBreath Hand Loop site"
git branch -M main
git remote add origin git@github.com:fitzyracing1/starbreath.git
git push -u origin main
```

Then in the repo settings, set Pages to deploy from branch `main` and folder `/` (root).

## Layout

- `index.html` — site
- `css/styles.css`
- `images/hand-loop.jpg` — product cutaway
- `images/schematic.jpg` — gas path
- `og.jpg`, `x-banner.jpg` — link previews

## Plans

This project is free, and its license stays as is. Support it through [GitHub Sponsors](https://github.com/sponsors/fitzyracing1):

- **Free**: use the code, community support.
- **Pro ($49/month)**: priority issues and support.
- **Team ($199/month)**: priority support for your team plus early access.
