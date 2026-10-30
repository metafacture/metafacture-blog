---
title: "Metafacture release: Core 9.0.0"
date: "2026-10-29"
description: "Changes coming with the release of metafacture-core 9.0.0"
authors: [{lastname: "Bülte",
           firstname: "Tobias"}]
---

*Preamble*

This post describes the new developments since the [release of metafacture-core 8.0.1](https://blog.metafacture.org/metafacture-releases_core-8.0.1/) in March 2026.

For release notes with downloadable CLI runner, see [GitHub release of metafacture-core-9.0.0](https://github.com/metafacture/metafacture-core/releases/tag/metafacture-core-9.0.0).

We are happy to announce the next major release of metafacture-core: 9.0.0

With the new release Metafacture moved to Java 21 which brings a couple of breaking changes.
Also the CLI handling has been improved by introducing options. The old CLI handling is still being supported, but will be deprecated in an upcoming release. For further information [see the documentation](https://metafacture.org/metafacture-documentation/docs/flux/Flux-User-Guide.html#run-a-flux-file).

## Table of Contents

```toc
# this will be replaced by the toc
```

## New Features

* **Breaking**: PICA: Add true picaxml handler, `PicaXmlHandler` now supports only [PICA XML](https://format.gbv.de/pica/xml), for  [PPXML](https://format.gbv.de/pica/ppxml) use `PpXmlHandler` [#761](https://github.com/metafacture/metafacture-core/pull/761)
* Monitoring: Add setter for log prefix in `ObjectLogger` and `StreamLogger` [#771](https://github.com/metafacture/metafacture-core/pull/771)
* Monitoring: Add setter for log level in object and stream (batch) loggers [#772](https://github.com/metafacture/metafacture-core/pull/772)
* Metafix: Optionally specify limit for number of exceptions in Metafix [#773](https://github.com/metafacture/metafacture-core/pull/773)
* Plumbing: `merge-batch-stream`: Make batchsize configurable in Flux [#784](https://github.com/metafacture/metafacture-core/pull/784)
* **Breaking**: Runner: Add Flux CLI options. `Flux.main()` now terminates the process even on success. Java applications should use the new Flux API instead (see below) [#785](https://github.com/metafacture/metafacture-core/pull/785)
* Metafix: Optionally ignore unreadable files in `FileMap` [#792](https://github.com/metafacture/metafacture-core/pull/792)
* Flux:  Provide Flux entrypoint for use as a library function [#746](https://github.com/metafacture/metafacture-core/pull/746)

## Bug Fixes

* Metafix: Skip empty strings when using `capitalize` [#757](https://github.com/metafacture/metafacture-core/pull/757)
* CSV: Decode multiline CSV [#770](https://github.com/metafacture/metafacture-core/pull/770)
* Runner: Allow whitespace in Flux runner arguments [#790](https://github.com/metafacture/metafacture-core/pull/790)

## Others

* **Breaking**:  Upgrade Log4j dependency to version 2.x [#748](https://github.com/metafacture/metafacture-core/pull/748)
* Metafix: Add best practice for maps and macros [#760](https://github.com/metafacture/metafacture-core/pull/760)
* Adjust flux example link labelling [#753](https://github.com/metafacture/metafacture-core/pull/753)
* Adjust Flux example link labelling [#753](https://github.com/metafacture/metafacture-core/pull/753)
* Provide Java 21 forward compatibility [#779](https://github.com/metafacture/metafacture-core/pull/779)
* **Breaking**:  Raise the minimum Java version to 21 [#781](https://github.com/metafacture/metafacture-core/pull/781)
* Upgrade Jena dependency to version 6.2 [#786](https://github.com/metafacture/metafacture-core/pull/786)
* Let `HelpPrinter` output options under their original setter name [#787](https://github.com/metafacture/metafacture-core/pull/787)
* Flux: Document how to open stdin [#788](https://github.com/metafacture/metafacture-core/pull/788)
* Improve documentation for `filter-strings` [#789](https://github.com/metafacture/metafacture-core/pull/789)
* Update some dependencies with current non major releases [#759](https://github.com/metafacture/metafacture-core/pull/795)
* **Breaking**: Metafix API: Deprecated Fix command enums have been removed. [c8fbd8c](https://github.com/metafacture/metafacture-core/commit/c8fbd8c)

**Full Changelog**: https://github.com/metafacture/metafacture-core/compare/metafacture-core-8.0.1...metafacture-core-9.0.0
