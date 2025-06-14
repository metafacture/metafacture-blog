---
title: "Metafacture releases: Core 7.0.0"
date: "2025-06-10T16:15:03.2300Z"
description: "Changes coming with the releases of metafacture-core 7.0.0"
authors: [{lastname: "Bülte",
           firstname: "Tobias"}]
---

*Preamble*

Wit this release `metafacture-fix` is [incorporated into `metafacture-core`](https://github.com/metafacture/metafacture-core/issues/577). `metafacture-fix` as a standalone repository is now archived.

This post describes the new developments since the [release of metafacture-core 6.2.0](https://blog.metafacture.org/metafacture-releases_core-6.2.0_fix-1.2.0/) in July 2024, including new developments in metafacture-fix.

For release notes with downloadable CLI runner, see [Github release of metafacture-core-7.0.0](https://github.com/metafacture/metafacture-core/releases/tag/metafacture-core-7.0.0).

## Table of Contents

```toc
# this will be replaced by the toc
```

## New Features
- Metafix: Make metafacture-fix part of metafacture-core [#577](https://github.com/metafacture/metafacture-core/issues/577)
- Metafix: Add less_than()/greater_than() Fix functions [#650](https://github.com/metafacture/metafacture-core/issues/650)
- Linkeddata: Make markers in rdf-macro configurable [#657](https://github.com/metafacture/metafacture-core/issues/657)

## Bug fixes
- Metafix and Morph Filemap: Fix memory leak due to missing Closeable [#666](https://github.com/metafacture/metafacture-core/issues/666) (see also the [blog post](https://blog.metafacture.org/2025-03-10-fixing-memory-leak/))

## Others
- Runner: Update examples by adding metafacture-fix versions of existing examples [#589](https://github.com/metafacture/metafacture-core/issues/589)
- Runner: Prevent multiple SLF4J bindings warning [#649](https://github.com/metafacture/metafacture-core/issues/649)
- IO, JSON and Metafix: Consolidate dependency versions [#670](https://github.com/metafacture/metafacture-core/pull/670)

[Full change log](https://github.com/metafacture/metafacture-core/compare/metafacture-core-6.2.0...metafacture-core-7.0.0)(note that due to the merge of `metafix` into `metafacture-core` there are more than 1k commits)
