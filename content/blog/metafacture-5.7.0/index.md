---
title: Metafacture-core release 5.7.0
date: "2023-11-24T15:35:03.2300Z"
description: "This is about changes coming with the metafacture-core release 5.7.0"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

This post describes the new developments in `metafacture-core release 5.7.0` since the [release of
 metafacture-core-5.6.0](https://blog.metafacture.org/metafacture-core-5.6.0/) in June 2023.

## Table of Contents

```toc
# this will be replaced by the toc
```

## Changes

### New Features

- Morph function: Switch from java.net.URLEncoder to guavas PercentEscaper to be conform to RFC 3986 [#490](https://github.com/metafacture/metafacture-core/issues/490)

### Bug fixes

- IO: Increment count before starting new file in ObjectFileWriter [#501](https://github.com/metafacture/metafacture-core/pull/501)

### Others

- Add description to "wait-for-inputs" [metafacture-documentation#30](https://github.com/metafacture/metafacture-documentation/issues/30)

