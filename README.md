# SFX Factory

Theo & Joah's sound board — a single static page (`index.html`) plus the sounds in `sfx/` and `sfx-cool/`. Also here: the Fart Factory (`fart-factory/`) and the cash register game (`cash-register-game.html`).

Live at **https://sfx-factory.pages.dev** (Cloudflare Pages, deployed on every push to `main`).

Run locally:

```sh
python3 serve.py   # http://localhost:3001
```

The page's “Download” button builds a zip by fetching `index.html` and `wrangler.toml` from this public repo, so keep it public.
