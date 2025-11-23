# Kalinoff website

Static one-pager for Valentin Kalinov built with Jekyll (for easy GitHub Pages hosting) and Tailwind CDN.

## Local setup

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` to preview.

## Customization
- Replace `assets/images/profile.svg` with your photo (use the same filename to keep markup intact).
- Update links in `index.html` for any new destinations.
- Set `url` (and `baseurl` if needed) in `_config.yml` before deploying.
