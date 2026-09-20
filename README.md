# matrogers.github.io

Personal homepage and resume for Mathew Rogers, served by GitHub Pages at
[matrogers.github.io](https://matrogers.github.io/).

Built with Jekyll on the [Resume theme](https://github.com/jglovier/resume-template).
Content lives in `_config.yml` (name, title, intro, social links, which
sections are shown) and in `_data/*.yml` (one file per resume section).

## Local preview

```
docker build -t matrogers-site .
docker run --rm -p 4000:4000 -v "$PWD":/home/app matrogers-site \
  bundle exec jekyll serve --host 0.0.0.0 --port 4000
```
