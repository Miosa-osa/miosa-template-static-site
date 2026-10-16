# static-site

A plain HTML and CSS site. Railpack detects the `index.html` at the root and serves it with a static file server; there is no build step and no configuration.
It is a starting point for MIOSA Services.

## Endpoints

- `GET /` returns 200 with `index.html`.

## Variables

None. The server listens on `$PORT`, which the platform sets.

## License

MIT
