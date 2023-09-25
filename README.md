# Oasis API reference documentation

Branch `gh-pages` in this repository hosts the https://api.docs.oasis.io
site.

## `gh-pages` organization

- `js`: contains API reference for JavaScript and TypeScript packages named
  after the package name deployed at npmjs.org, but with stripped
  `@oasisprotocol/` prefix. For example `@oasisprotocol/client` is hosted
  inside `js/client` folder.
- `sol`: contains API reference for Solidity packages named after the package
  name deployed at npmjs.org, but with stripped `@oasisprotocol/` prefix. For
  example `@oasisprotocol/sapphire-contracts` is hosted inside
  `sol/sapphire-contracts`.
- `rust`: contains API reference for Rust packages named after the import name
  of the package e.g. `oasis_runtime_sdk`.

`gh-pages` branch is periodically updated by fetching the content of
`api-reference` branch of the `oasis-sdk`, `sapphire-paratime` and other Oasis
repositories in the future.
