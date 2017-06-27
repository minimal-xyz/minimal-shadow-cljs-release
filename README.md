
Release build example for [shadow-cljs](https://github.com/thheller/shadow-cljs)
----

> build ClojureScript projects into modules with hashes in files.

### Usage

To compile to `dist/`:

```bash
yarn
yarn compile # shadow-cljs compile app
```

To build to `dist/`:

```bash
yarn build # shadow-cljs release app
```

Informations about files are saved in `dist/manifest.json`, which can be used to generate HTML.

Note: configs in `:release` will overwrite `:app` config, which is used in `:comiple`.

Docs related:

* [:module-hash-names](https://github.com/thheller/shadow-cljs/wiki/ClojureScript-for-the-browser#module-hash-names)
* [Release-only Configuration](https://github.com/thheller/shadow-cljs/wiki/Production-Builds)

### License

MIT
