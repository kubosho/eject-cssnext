# eject-cssnext

Removing [postcss-cssnext](https://github.com/MoOx/postcss-cssnext) dependencies and install only used each plugins contained in postcss-cssnext.

## Motivation

I think postcss-cssnext is **DON'T USE**.

It has some reasons:

- cssnext contains many PostCSS plugins
  - Don't know affected range when updated cssnext
  - `node_modules` bloated
  - Contains plugin hardly used
- I think not applicable to `Do one thing, and do it well` in [PostCSS Plugin Guidelines](https://github.com/postcss/postcss/blob/master/docs/guidelines/plugin.md)
- Some PostCSS plugin behaves differently specs
