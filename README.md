# What should I wear?

Dress right for your run, based on your own history, not a generic chart.
Log what you wore and how it felt; the tool plays it back when similar
conditions return. Sibling of **When should I run** (that one answers
*when*, this one answers *what*).

**Live:** enable GitHub Pages on this repo (Settings → Pages → main / root)
and it will be served at `https://<username>.github.io/what-should-i-wear/`.

## Features (v1, milestone M1)

- Wardrobe setup: name your own running clothes by body zone, seed a
  typical starter set, rename anytime, archive instead of delete so old
  logs always render correctly.
- Log a run in under 30 seconds: date, time of day, conditions
  (temperature, wind, precipitation), intensity, tappable outfit chips,
  a five-point comfort verdict (much too cold to much too warm), optional note.
- History: reverse-chronological list, tap to expand the full outfit,
  edit and delete past logs.
- Export / import: full backup as one JSON file, merge or replace on import.
- Mobile friendly; works fully offline.

Coming next: outfit recommendations matched to current conditions (M2),
weather auto-fill via MET Norway (M3).

## Privacy

One self-contained `index.html`. No analytics, no cookies, no accounts.
All data is saved in your browser's localStorage only. Note that browsers
can clear localStorage; the export file is the real home of your data,
so back up regularly.
