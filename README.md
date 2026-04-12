# shhxiao.com

Personal academic website source for [shhxiao.com](https://shhxiao.com).

## Stack

- Jekyll site with the remote theme `academicpages/academicpages.github.io`
- Global styling through `_sass/` and `assets/css/main.scss`
- Main manually maintained pages:
  - `/`
  - `/research/`
  - `/cv/`
  - `/honor/`
  - `/code/`
  - `/misc/`

## Local development

Install dependencies:

```bash
bundle install
```

Run the local development server:

```bash
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Build the site:

```bash
bundle exec jekyll build
```

## Notes

- The site depends on a remote theme, so local builds need network access when Jekyll fetches `academicpages`.
- `assets/js/main.min.js` is a committed legacy bundle. The Node-based JS build workflow in `package.json` is kept as historical context and is not part of this cleanup pass.
- Static PDFs and images linked by the site live under `files/` and `images/`.
