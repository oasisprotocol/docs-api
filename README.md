# Oasis API reference documentation

Branch `gh-pages` in this repository hosts the https://api.docs.oasis.io
site.

## `gh-pages` organization

- `js`: holds JavaScript and TypeScript packages named after the package name
  deployed at npmjs.org, but with stripped `@oasisprotocol/` prefix. For example
  `@oasisprotocol/client` is hosted inside `js/client` path.
- `rust`: holds Rust packages named after the import name of the package e.g.
  `oasis_runtime_sdk`.

The branch is periodically updated by fetching the content of `api-reference`
branch of the `oasis-sdk`, `sapphire-paratime` and other relevant Oasis
repositories.
