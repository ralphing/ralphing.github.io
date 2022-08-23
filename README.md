# Ralphing site

## Add an update

To add an update create a file under `posts` directory which name is:
`yyyy-mm-dd-TITLE.markdown`. Commit and push.  The site will be built and
deployed by a [github-action](https://github.com/ralphing/ralphing.github.io/actions).

## Serve the website locally

If you wish to preview changes before publishing them, you can serve the site
locally with:

```bash
cabal run site -- watch
```

The site can then be previewed in a browser at http://127.0.0.1:8000.
