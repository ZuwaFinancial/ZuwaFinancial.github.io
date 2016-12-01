# Zuwa Financial

This is the source code for ZuwaFinancial.com.

## Code

This is a Jekyll app.  Jekyll is a static site generator.  For more info, head here: https://jekyllrb.com/.

The app contains a "contact us" form that is powered by [formspree](https://formspree.io/).

## Hosting

Hosting for this site is done through Github, which allows free hosting for jekyll-based sites.

## Deployment

Push to the master branch of the Github repo to deploy.

You'll also need to clear the cache in the CDN.  This app uses [Cloudflare](https://www.cloudflare.com/)
to the maximize performance.

Log into Cloudflare, navigate to the the caching page and purge the cache.
