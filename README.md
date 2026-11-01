# hourwarden.com

The sales site of HourWarden, built with [Hugo](https://gohugo.io) (no theme) and published on GitHub Pages.

    hugo server        # preview on http://localhost:1313
    hugo --minify      # build into public/

- Texts: `content/_index.md` (English) and `content/_index.nl.md` (Dutch); button labels in `i18n/`.
- Download links and the app address: `[params]` in `hugo.toml`.
- Screenshots in `static/img/` come from the demo build of the app with fictional customers
  (`cargo run -p timekeeper-core --example demo_data` in the app repository).

## Publishing

1. Push this repository to GitHub.
2. Settings → Pages → Source: **GitHub Actions**. The workflow in `.github/workflows/hugo.yml` builds and publishes every push to `main`.
3. Settings → Pages → Custom domain: `hourwarden.com` (also in `static/CNAME`), then tick **Enforce HTTPS**.
4. At your DNS provider, for `hourwarden.com`: `A` records to 185.199.108.153, 185.199.109.153, 185.199.110.153 and 185.199.111.153, and `www` as a `CNAME` to `<your-github-name>.github.io`.
   `app.hourwarden.com` stays an `A` record to the VPS.
