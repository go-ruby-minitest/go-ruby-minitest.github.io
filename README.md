<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-minitest/brand/main/social/go-ruby-minitest.png" alt="go-ruby-minitest" width="720"></p>

# go-ruby-minitest.github.io

The [go-ruby-minitest](https://github.com/go-ruby-minitest) organization landing
page — a single Hugo-built static page served at
[go-ruby-minitest.github.io](https://go-ruby-minitest.github.io/).

It presents the org's one-line pitch (the pure-Go, MRI-faithful core of Ruby's
Minitest), the capability phases, and links to the documentation site
([`/docs/`](https://go-ruby-minitest.github.io/docs/)) and the source repos. The
page ships a light/dark/system theme toggle (default = system).

## Build locally

```sh
hugo server
```

## Deploy

Pushing to `main` triggers `.github/workflows/deploy-pages.yml`, which builds the
site with Hugo and publishes it to GitHub Pages (Pages source = GitHub Actions).

## License

BSD-3-Clause — see [LICENSE](LICENSE). Copyright the
go-ruby-minitest/go-ruby-minitest.github.io authors.
