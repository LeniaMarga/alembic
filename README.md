# ⚗️ Alembic

A Design System for Open Lab research projects.

[**Go to the docs →**](https://digitalinteraction.github.io/alembic/)

## Release process

1. Run the build
2. Update API docs if needed
3. Run `npm version minor|major|patch`
4. Run `npm publish`

## Coding conventions

> TODO: find a better place for these

**css variables**

- "axioms" are single words like `--measure`
- everything else is type-prefixed like `--color-background` or `--border-thin`

**imports**

`module.js` is the main entrypoint, sub-modules are self-named files in their own folder e.g. `lib/lib.js` or `layouts/layouts.js`.

**misc**

- group source by the module, js + css alongside eachother is fine. It makes it easy to work on a module.
- avoid JavaScript's default exports
- sub-modules should explicitly export things, avoid `export * from '...'`-type code
- pure functions where possible
- exported code prefixed with `_` (an underscore) is internal, should not be used and may change between major releases

---

> This project was set up by [puggle](https://npm.im/puggle)
