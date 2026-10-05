<!-- tyhp-readme:start -->
# tyhpdef/bacon-bacon-qr-code

Tyhp type definitions for `bacon/bacon-qr-code` `3.1.1`.

```bash
composer require --dev tyhpdef/bacon-bacon-qr-code:3.1.1
```

This is a metapackage. Composer also installs `tyhpdef/bacon-bacon-qr-code-impl` (type files).
Require **this** name, not `tyhpdef/bacon-bacon-qr-code-impl`.

See https://tyhplang.com.

## Maintain `bacon/bacon-qr-code`? Ship the types yourself

If you are a Packagist maintainer of `bacon/bacon-qr-code`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/bacon-bacon-qr-code-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `bacon/bacon-qr-code` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/bacon-bacon-qr-code": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `bacon/bacon-qr-code` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `bacon/bacon-qr-code` with a real constraint,
   `"replace": { "tyhpdef/bacon-bacon-qr-code": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `bacon/bacon-qr-code` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/bacon-bacon-qr-code` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
