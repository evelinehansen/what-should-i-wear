# What should I wear?

Dress right for your run, based on your own history, not a generic chart.
Log what you wore and how it felt; the tool plays it back when similar
conditions return. Sibling of **When should I run** (that one answers
*when*, this one answers *what*).


## Features

- **Now:** current conditions (fetched automatically from Open-Meteo,
  defaulting to Oslo; pick any city or use device location in Settings,
  and everything stays editable by hand)
  matched against every logged run. Your three closest past runs appear
  with what you wore, how it felt, and a similarity label; a one-line hint
  suggests warmer or lighter when the closest match was off. With no close
  match, a generic dress-by-temperature chart steps in until your own data
  takes over.
- **Log a run** in under 30 seconds: conditions and outfit are prefilled
  from the weather fetch and your closest match; adjust with taps, give a
  five-point comfort verdict (much too cold to much too warm), done.
- **Wardrobe:** your own running clothes by body zone, seedable starter
  set, rename anytime, archive instead of delete so old logs always render.
- **History:** reverse-chronological, tap to expand, edit and delete.
- **Export / import:** full backup as one JSON file, merge or replace.
- Transparent matching: plain arithmetic, documented in Settings, no AI.
- Mobile friendly, installable to the home screen; fully usable offline
  with manual condition entry.

## Privacy

One self-contained `index.html`. No analytics, no cookies, no accounts.
All data is saved in your browser's localStorage only. The only network
requests go to [Open-Meteo](https://open-meteo.com/) for the weather fetch
and the Settings city search; the coordinates they carry are the home
location and your search text, nothing else. Location permission is requested only if you tap "Use device
location", never on load. Browsers can clear localStorage; the export file
is the real home of your data, so back up regularly.

Weather data by Open-Meteo (CC BY 4.0), based on national weather services
such as MET Norway.
