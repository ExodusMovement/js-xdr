- `@exodus/js-xdr@1.0.3` matches upstream [a2f09f417](https://github.com/stellar/js-xdr/commit/a2f09f41720d0344fd409679442e0a0d85882078), which is `js-xdr@1.0.3` + Buffer fix + removed `babel-runtime` dependency

We do pack only `lib/` though, unlike upstream, so we still need the fork.
