---
title: Metafacture-core release 5.5.0
date: "2023-03-04T14:36:03.2300Z"
description: "This is about changes coming with the metafacture-core release 5.5.0"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

This post describes the new developments in `metafacture-core release 5.5.0` since the [release
of metafacture-core-5.4.0](https://blog.metafacture.org/metafacture-core-5.4.0/) in September 2022.

## Table of Contents

```toc
# this will be replaced by the toc
```

## Changes

### New Features

- JSON: schema validator [#443](https://github.com/metafacture/metafacture-core/issues/443)
- Metamorph: Optionally set key and/or value column in FileMap [#471](https://github.com/metafacture/metafacture-core/pull/471)
- Metamorph: Option to ignore lines matching pattern in FileMap [#472](https://github.com/metafacture/metafacture-core/pull/472)
- IO: Optionally let ObjectFileWriter append to existing file instead of overwriting [#475](https://github.com/metafacture/metafacture-core/pull/475)

Have a look at [flux-commands](https://github.com/metafacture/metafacture-documentation/blob/master/flux-commands.md) how to use these features.

### Bug fixes

- IO: setters would only take effect for subsequently opened files in ObjectFileWriter

