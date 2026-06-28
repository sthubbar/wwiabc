# wwiabc.org

Source for "Who's Who in abc Conjecture Research" at https://wwiabc.org.
Sister site to wwigr.org. Same three-source pipeline (arXiv + OpenAlex + zbMATH),
retargeted to the abc conjecture.

`_site/` is the deployable static site; Cloudflare serves it as static assets
(see `wrangler.toml`). Every push to `main` auto-deploys.
