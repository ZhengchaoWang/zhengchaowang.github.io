# Zhengchao Wang academic website

This site is set up for GitHub Pages with Jekyll. It does not require RStudio.

## Common updates

- Personal information: edit `_data/profile.yml`
- Publications and working papers: edit `_data/publications.yml`
- News items: edit `_data/news.yml`
- Appearance: edit `assets/css/style.css`
- CV: replace `CV_WZC.pdf`
- Photo: replace `zhengchaowang.jpg`

For example, to show a temporary announcement, edit `_data/profile.yml`:

```yaml
notice: I am on the 2026-2027 academic job market.
```

To add a news item, edit `_data/news.yml`:

```yaml
- date: 2026-05-28
  text: I updated my website.
```

## Publish changes

```bash
git status
git add .
git commit -m "Update website"
git push
```

GitHub Pages will build the site after you push.

## Local preview

This computer does not currently have Jekyll installed. If Jekyll is installed later, preview with:

```bash
bundle install
bundle exec jekyll serve
```

Without Jekyll, push to GitHub and use the GitHub Pages build preview.
