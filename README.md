# LQ Tennis

## Visit Production

* https://lq.tennis

## Build and View Locally

* `jekyll serve`
* `jekyll serve --livereload`

## Hosting with GitHub Pages

* [Jekyll: GitHub Pages](https://jekyllrb.com/docs/github-pages/)
* [Setting up a GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
* [Configuring a custom domain for your GitHub Pages site](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## GitHub Actions Error

* Error Message:

```
Error: The process '/opt/hostedtoolcache/Ruby/3.1.2/x64/bin/bundle' failed with exit code 16
```

* Solution: `bundle lock --add-platform x86_64-linux`
