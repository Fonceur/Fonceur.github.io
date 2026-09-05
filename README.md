# Fonceur.github.io

GitHub Pages user site for the Romi apps, served at https://fonceur.github.io/.

- `index.html` — landing page linked from the Google Play and Amazon Appstore listings (store links, rules in 18 languages).
- `app-ads.txt` — authorized sellers for AdMob and Amazon Publisher Services; both crawlers fetch it at the domain root.
- `romi-privacy.html` / `romi-privacy-fr.html` — the Romi privacy policy (all editions, one document), linked from every store listing.
- `doc/` — the in-app rules documentation, a verbatim copy of `romi/src/main/assets/doc*.html` and its images from the Romi repo. Refreshed by `tools/publier-site.sh` in the Romi repo (run by its `ship` skill); do not edit here.

The Tromi privacy policy lives in the separate [tromi-legal](https://github.com/Fonceur/tromi-legal) project site.
