---
title: "Metafacture release: Core 8.0.0"
date: "2025-02-27T13:15:03.2300Z"
description: "Changes coming with the release of metafacture-core 8.0.0"
authors: [{lastname: "Bülte",
           firstname: "Tobias"}]
---

*Preamble*

This post describes the new developments since the [release of metafacture-core 7.0.0](https://blog.metafacture.org/metafacture-releases_core-7.0.0/) in June 2025.

For release notes with downloadable CLI runner, see [GitHub release of metafacture-core-8.0.0](https://github.com/metafacture/metafacture-core/releases/tag/metafacture-core-8.0.0).

## Table of Contents

```toc
# this will be replaced by the toc
```

New Features

* MARC: Optionally escape Unicode in MarcXmlEncoder. [#710](https://github.com/metafacture/metafacture-core/issues/710)
* SRU: New SRU opener [#682](https://github.com/metafacture/metafacture-core/issues/682)
* Metafix: Add function utf8_normalizer [#741](https://github.com/metafacture/metafacture-core/issues/741)
* Metafix: Add function html_to_text [#740](https://github.com/metafacture/metafacture-core/issues/740)

Bug fixes

* Metafix: Enforce unique result in  list-fix-paths [#687](https://github.com/metafacture/metafacture-core/issues/687)
* IO: Fix `RecordReader` to reset buffer on exception. [#717](https://github.com/metafacture/metafacture-core/issues/717)
* Runner: Fix logging [#733](https://github.com/metafacture/metafacture-core/issues/733)
* Runner: Fix broken runner examples [#742](https://github.com/metafacture/metafacture-core/issues/742)

Others

* **Breaking**: Metafix: Change `set_*` functions to not create intermediate structures [#704](https://github.com/metafacture/metafacture-core/issues/704) (Replace with `add_*` versions to repair!)
* Simplify Gradle build logic for making releases. [#687](https://github.com/metafacture/metafacture-core/issues/687)
* IO: Fix wrong description for `StdInOpener`. [#679](https://github.com/metafacture/metafacture-core/issues/679)
* Metafix: Add integration test for [#711](https://github.com/metafacture/metafacture-core/issues/711). [#712](https://github.com/metafacture/metafacture-core/issues/712)
* Metafix: Move Fix command enums to individual classes. [#706](https://github.com/metafacture/metafacture-core/issues/706)
* Runner: Delete heapspace limitiation [#718](https://github.com/metafacture/metafacture-core/issues/718)
* Metafix/Runner: Add missing examples [#640](https://github.com/metafacture/metafacture-core/issues/640)
* Add how to maintain using Maven Central. [#727](https://github.com/metafacture/metafacture-core/issues/727)
* Metafix/JSON: Provide Jackson 2.16/2.17 forward compatibility [#738](https://github.com/metafacture/metafacture-core/issues/738)
* **Breaking**: Separate internal and external loggers [#737](https://github.com/metafacture/metafacture-core/issues/737)


[Full change log](https://github.com/metafacture/metafacture-core/compare/metafacture-core-7.0.0...metafacture-core-8.0.0)
