# BBKB Community

A website documenting the growing variety of pocket-sized keyboards and computers built using leftover inventory of BB keyboards.

Built using [Material for MkDocs](https://github.com/squidfunk/mkdocs-material).

## Development

Make sure you have [`uv`](https://docs.astral.sh/uv/) installed locally.

To serve the site on a local webserver:

```
uv run mkdocs serve
```

## Deployment

To deploy the site to [bbkb-community.github.io](https://bbkb-community.github.io/), simply commit to the **main** branch. The site will be automatically updated by the [deploy.yml](.github/workflows/deploy.yaml) GitHub Action.
