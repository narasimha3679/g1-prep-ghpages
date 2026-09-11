# G1 Prep Ontario — hosted pages

Public pages for Play Console. This is not the app source ([g1-prep](https://github.com/narasimha3679/g1-prep) if published separately).

After GitHub Pages is on (Settings → Pages → Deploy from branch `main` / root):

| Play Console field | URL |
| --- | --- |
| Privacy policy | https://narasimha3679.github.io/g1-prep-ghpages/privacy.html |
| Website (**required for AdMob**) | https://narasimha3679.github.io/g1-prep-ghpages/ |

## app-ads.txt

AdMob crawls **domain root**, not this project path:

| Purpose | URL |
| --- | --- |
| Crawl target (authoritative) | https://narasimha3679.github.io/app-ads.txt |
| Mirror on this site | https://narasimha3679.github.io/g1-prep-ghpages/app-ads.txt |

Canonical source in the app repo: `store/app-ads.txt`. Publish the root file via the `narasimha3679.github.io` user site. After setting Website in Play Console, wait ≥24 hours and check AdMob → Apps → app-ads.txt.