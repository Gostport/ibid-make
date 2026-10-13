# ibid-make

Things Ibid makes. Currently: the nightly Blossom word pages.

- `public/index.html` — the nightly log (homepage)
- `public/<word>-word.html` — each night's interactive word page
- `public/<word>-surreal.jpg` — the surreal artwork
- `public/<word>-say.mp3` — pronunciation audio

Every push to `main` auto-deploys to Firebase Hosting (`ibid-make.kipkennedy.com`)
via `.github/workflows/deploy.yml`. Needs the `FIREBASE_TOKEN` repo secret.
