# stefanokals.github.io

## Branches
Either choose between **static-site** or **travel-blog** branch and set it as default to use for github pages.

## Development
```bash
docker-compose up --build -d
docker-compose logs -f
docker-compose run jekyll /bin/bash
```

We can keep it runing and work on the local files because everything refreshes, except for _config.yml changes.

### Build _site files for production
```bash
jekyll build
```

## Workaround

To work local on docker and upload to gh-pages so that it works for both I made the following adjustments to the Gemfile:

```Gemfile
source "https://rubygems.org"

gem 'jekyll'
gem 'jekyll-feed'
gem 'jekyll-sitemap'
gem 'jekyll-seo-tag'
gem 'jemoji'
gem 'jekyll-readme-index'
gem 'jekyll-paginate'
gem 'jekyll-gist'
gem 'jekyll-include-cache'
```

Thanks to https://github.com/chibicode/duo/issues/1

## Images

Convert images the easy way with imagemagick: `magick convert input.jpg -resize 50% -quality 75 output.jpg`

To find out the width and height: `magick identify -format "%wx%h" test.jpg`