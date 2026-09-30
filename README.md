# sultonmusic.github.io

Root of the `sultonmusic.github.io` domain. The music station itself lives in
[sultonmusic/Spotify](https://github.com/sultonmusic/Spotify) and is served at `/Spotify/`.

- `.well-known/assetlinks.json` tells Android that the Cavi Music app (`io.github.sultonmusic.cavi`) belongs to
  this domain, so it opens full screen without the browser's address bar. The fingerprint is the signing
  certificate of the APK published at
  [releases/android](https://github.com/sultonmusic/Spotify/releases/tag/android); when that APK is rebuilt with a
  new key, add the new fingerprint from the release's `assetlinks.json` to the list here.
- `.nojekyll` keeps GitHub Pages from hiding the `.well-known` folder.
