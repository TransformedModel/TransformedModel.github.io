# Personal one-page site (Jekyll + GitHub Pages)

## Local development

```bash
bundle install
bundle exec jekyll serve --livereload
```

Then open the local URL printed by Jekyll.

## Customize
- Edit `_data/site.yml` for your name, tagline, accent color, and socials.
- Edit `_data/writing.yml` to curate Substack posts.
- Replace `assets/resume.pdf` with your real resume PDF (keep the filename).

## Deploy (GitHub Pages)
1. Push this folder to a GitHub repo.
2. In GitHub: **Settings → Pages**.
3. Choose to deploy from the `main` branch (root).

If you’re using a **project** repo (not `<username>.github.io`), set `baseurl` in `_config.yml` to `/<repo-name>` and commit.
# TransformedModel.github.io
