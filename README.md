This web page uses [Garth](https://github.com/daviddarnes/garth) as a Jekyll theme gem, which renders a HTML page accessible at [cbclobato.github.io](https://cbclobato.github.io).

To install Jekyll locally, follow: [https://jekyllrb.com/docs/installation/](https://jekyllrb.com/docs/installation/).

## Maintaining / Updating

All content is decoupled from the HTML/layout and should be edited in `_config.yml` and `_data/talks.yml`. Speaker photos should go in `assets/speakers/` if available.

## Previewing / Running locally

    jekyll serve --baseurl ""

Where the `--baseurl` option overwrites the GitHub-specific path, and makes the page preview available (typically) at http://127.0.0.1:4000/
