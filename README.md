# Homepage

This repository contains the content for the homepage of the student council congress for mechanical engineering.

It uses [Zola](https://www.getzola.org) to build the static site content into HTML.

## Development

Start a local webserver with hot-reloading.

```bash
zola serve
```

## Production

It's recommendet to check the rendered output and validate all internal and
external links. This does not perform any writings to disk.

```bash
zola check
```

Build all pages and assets into the `public` directory.

```bash
zola build
```

## Authors

- [Aiven Timptner](mailto:aiven.timptner@fatama.org)
