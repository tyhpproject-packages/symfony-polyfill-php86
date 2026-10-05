<!-- tyhp-readme:start -->
# tyhpdef/symfony-polyfill-php86

Tyhp type definitions for `symfony/polyfill-php86` `1.41.0`.

```bash
composer require --dev tyhpdef/symfony-polyfill-php86:1.41.0
```

This is a metapackage. Composer also installs `tyhpdef/symfony-polyfill-php86-impl` (type files).
Require **this** name, not `tyhpdef/symfony-polyfill-php86-impl`.

See https://tyhplang.com.

## Maintain `symfony/polyfill-php86`? Ship the types yourself

If you are a Packagist maintainer of `symfony/polyfill-php86`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/symfony-polyfill-php86-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `symfony/polyfill-php86` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/symfony-polyfill-php86": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `symfony/polyfill-php86` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `symfony/polyfill-php86` with a real constraint,
   `"replace": { "tyhpdef/symfony-polyfill-php86": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `symfony/polyfill-php86` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/symfony-polyfill-php86` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
