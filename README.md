# Tuck Lab website

Quarto source for the redesigned Tuck Lab website.

## Preview locally

Install [Quarto](https://quarto.org/), then run:

```sh
quarto preview
```

## Publishing

Push to `main`. The GitHub Actions workflow renders the website and deploys it to GitHub Pages.

In repository **Settings → Pages**, select **GitHub Actions** as the build/deployment source.

Do not point `tucklab.org` to GitHub until the prototype is reviewed. Keep the Wix domain registration active.

## Editing

Edit the `.qmd` pages directly in GitHub or locally. Add verified images under `images/` as content is migrated.

## Migration checklist

- [ ] Verify and migrate current team profiles and photos
- [ ] Migrate research figures and approved text
- [ ] Import publications with verified DOI links
- [ ] Preserve Wix news archive and important existing URLs
- [ ] Confirm contact information
- [ ] Review mobile layout and accessibility
- [ ] Configure domain and DNS after approval
