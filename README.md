# Helix AI Solutions — Coming Soon

A single static "coming soon" landing page for [helixaisolutions.com](https://helixaisolutions.com),
hosted on GitHub Pages.

## Structure

```
index.html                     # the page (self-contained: inline CSS, Google Fonts)
assets/
  logo-helix-inverse.png       # wordmark logo (light, for the dark page)
  helix-icon.png               # square icon mark (source for favicons)
  og-image.png                 # social-share preview image
favicon.png                    # 32×32 browser tab icon
apple-touch-icon.png           # 180×180 iOS home-screen icon
CNAME                          # custom domain for GitHub Pages
```

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deployment

Pushed to the `main` branch → served by GitHub Pages at the custom domain
`helixaisolutions.com` (DNS via GoDaddy, HTTPS via GitHub's Let's Encrypt cert).
