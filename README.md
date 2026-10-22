# asctane-dashboard docs

The documentation for asctane-dashboard v3, built with [Mintlify](https://mintlify.com).
The code lives in [Discord-Dashboard/Core](https://github.com/Discord-Dashboard/Core).

## Preview locally

```bash
npx mint dev
```

Then open http://localhost:3000. Before opening a pull request, run:

```bash
npx mint validate
npx mint broken-links
```

## Layout

- `docs.json`: the site config and navigation.
- `introduction.mdx`, `quickstart.mdx`, `how-it-works.mdx`: getting started.
- `guides/`: settings, lite mode, remote bots, the web app, modules, the page
  builder and production.
- `reference/`: fields, configuration, the HTTP API, the protocol and packages.
- `migration/`: moving from v2.

When a pull request in Core changes behavior, update the page that describes it.
