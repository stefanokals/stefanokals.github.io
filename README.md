# stefanokals.github.io

# Branches

Either choose between **static-site** or **travel-blog** branch and set it as default to use for github pages.

# Development

```bash
docker-compose up -d
docker-compose run jekyll /bin/bash
```

You can keep it runing and work on the local files because everything refreshes, except for _config.yml changes.

## Build _site files for production

```bash
jekyll build
```

# TODO

* fix or finish 404 page
* add another teaser.png
* add another me.jpg