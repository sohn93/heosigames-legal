# heosigames-legal

Legal pages for HeosiGames apps (privacy policy and terms).

## app-ads.txt

This repository now includes [`app-ads.txt`](./app-ads.txt) for AdMob verification:

```text
google.com, pub-4045275485305988, DIRECT, f08c47fec0942fa0
```

Important: AdMob checks `https://<hostname>/app-ads.txt` using the hostname from the
developer website in the app store listing. If you use a GitHub Pages project URL such
as `https://sohn93.github.io/heosigames-legal/`, the crawler checks
`https://sohn93.github.io/app-ads.txt`, not `/heosigames-legal/app-ads.txt`.

To complete verification:

1. Add the developer website URL to the Google Play store listing.
2. Host this repository at a root hostname that can serve `/app-ads.txt`, or move the
   file to the root GitHub Pages site/custom domain.
