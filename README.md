# Paw Park Pulse Support Website

This is the support documentation for Paw Park Pulse, hosted on GitHub Pages.

## Files

- **index.md** – Main support page (FAQ & troubleshooting)
- **privacy.md** – Privacy Policy
- **_config.yml** – Jekyll configuration
- **CNAME** – Custom domain configuration

## Local Testing

To test locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`

## Deployment

Push to your GitHub repository. GitHub Pages will automatically build and deploy.

## Custom Domain

1. Update the `CNAME` file with your domain (e.g., `support.pawparkpulse.com`)
2. In your domain registrar, add a CNAME record pointing to `yourusername.github.io`
3. Enable custom domain in GitHub repo Settings > Pages

## Customization

- Change the theme in `_config.yml` (jekyll-theme-slate, jekyll-theme-minimal, etc.)
- Add a logo by updating `_config.yml` with a logo path
- Edit markdown files to update content

## Updates

When you push changes to this repository, GitHub Pages will automatically rebuild the site.
