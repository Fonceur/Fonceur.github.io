# Fonceur.github.io

GitHub Pages user site for the Romi and Tromi apps, served at https://fonceur.github.io/.

- `index.html` / `index-fr.html` — landing page linked from the Google Play and Amazon Appstore listings (store links, rules in 18 languages). English by default; a French browser is redirected to the French page unless a toggle choice is stored in `localStorage`.
- `images/` — launcher icon and a downscaled board screenshot (`docs/images/anglais/Screenshot_20251227_210141.png` in the Romi repo).
- `app-ads.txt` — authorized sellers for AdMob and Amazon Publisher Services; both crawlers fetch it at the domain root.
- `romi-privacy.html` / `romi-privacy-fr.html` — the Romi privacy policy (all editions, one document), linked from every store listing.
- `doc/` — the in-app rules documentation, a verbatim copy of `romi/src/main/assets/doc*.html` and its images from the Romi repo. Refreshed by `tools/publier-site.sh` in the Romi repo (run by its `ship` skill); do not edit here.

- `tromi/index.html` / `tromi/index-fr.html` — the Tromi landing page, served at https://fonceur.github.io/tromi/ (store link, features, data sources). Same language redirect as the Romi page; both read the same `localStorage` key, so a toggle choice on one carries over to the other.
- `tromi/images/` — the launcher icon (`docs/images/tromi_icon_512.png` in the Tromi repo, downscaled to 192 px) and three phone screenshots per language (`docs/images/phone/{en,fr}/01_map.png`, `02_station_detail.png`, `05_trip_map.png`, downscaled to 480 px wide JPEG).

The Tromi privacy policy lives in the separate [tromi-legal](https://github.com/Fonceur/tromi-legal) project site; the Tromi landing page links to it.
