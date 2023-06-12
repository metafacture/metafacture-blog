---
title: Metafacture-core release 5.6.0
date: "2023-06-06T12:36:03.2300Z"
description: "This is about changes coming with the metafacture-core release 5.6.0"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

This post describes the new developments in `metafacture-core release 5.6.0` since the [release of
 metafacture-core-5.5.0](https://blog.metafacture.org/metafacture-core-5.5.0/) in March 2023.

## Table of Contents

```toc
# this will be replaced by the toc
```

## Changes

### New Features

- CSV: Add CsvEncoder [#483](https://github.com/metafacture/metafacture-core/issues/483)
- HTTP: Emit combined text for mixed content in HtmlDecoder [#477](https://github.com/metafacture/metafacture-core/pull/477)

Have a look at the [flux-commands](https://github.com/metafacture/metafacture-documentation/blob/master/flux-commands.md) how to use these features: [encode-csv](https://github.com/metafacture/metafacture-documentation/blob/master/flux-commands.md#encode-csv) and [decode-html](https://github.com/metafacture/metafacture-documentation/blob/master/flux-commands.md#decode-html).

### Bug fixes

- HTTP: Reset inputUsed after processing to fix reusing opener [#480](https://github.com/metafacture/metafacture-core/pull/480)

### Others

- Update dependencies [#489](https://github.com/metafacture/metafacture-core/pull/489)

