# What should I wear?

Dress right for your run, based on your own history, not a generic chart.
Log what you wore and how it felt; the tool plays it back when similar
conditions return. Sibling of **When should I run** (that one answers
*when*, this one answers *what*).

**Live:** enable GitHub Pages on this repo (Settings → Pages → main / root)
and it will be served at `https://<username>.github.io/what-should-i-wear/`.

## Features

- **Now:** current conditions (fetched automatically from MET Norway if you
  set a home location, always editable) matched against every logged run.
  Your three closest past runs appear with what you wore, how it felt, and
  a similarity label; a one-line hint suggests warmer or lighter when the
  closest match was off. With no close match, a generic dress-by-temperature
  chart steps in until your own data takes over.
- **Log a run** in under 30 seconds: conditions and outfit are prefilled
  from the weather fetch and your closest match; adjust with taps, give a
  five-point comfort verdict (much too cold to much too warm), done.
- **Wardrobe:** your own running clothes by body zone, seedable starter
  set, rename anytime, archive instead of delete so old logs always render.
- **History:** reverse-chronological, tap to expand, edit and delete.
- **Export / import:** full backup as one JSON file, merge or replace.
- Transparent matching: plain arithmetic, documented in Settings, no AI.
- Mobile friendly; fully usable offline with manual condition entry.

## Privacy

One self-contained `index.html`. No analytics, no cookies, no accounts.
All data is saved in your browser's localStorage only. The only network
request is the forecast fetch to [MET Norway](https://api.met.no/), and
only if you set a home location; leave it unset and nothing is fetched at
all. Location permission is requested only if you tap "Use device
location", never on load. Browsers can clear localStorage; the export file
is the real home of your data, so back up regularly.

Weather data by MET Norway (NLOD / CC BY 4.0).
