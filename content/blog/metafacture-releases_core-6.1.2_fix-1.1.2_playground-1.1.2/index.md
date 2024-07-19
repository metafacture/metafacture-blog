---
title: "Metafacture releases: Core 6.1.2, Fix 1.1.2, Playground 1.1.2"
date: "2024-07-19T15:05:03.2300Z"
description: "Changes coming with the releases of metafacture-core 6.1.2,
metafacture-fix 1.1.2 and metafacture-playground 1.1.2"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

As the [release of metafacture-core 6.1.0 introduces a bug](https://github.com/metafacture/metafacture-core/issues/540) and as the consecutive [release of [metafacture-core 6.1.1](https://github.com/metafacture/metafacture-core/issues/546) also had a bug posts about these releases are ommitted.

This post describes the new developments coming in:

a) [`metafacture-core release
    6.1.2`](https://central.sonatype.com/namespace/org.metafacture) since the [release of metafacture-core 6.0.0](https://blog.metafacture.org/metafacture-releases_core-6.0.0_fix-1.0.0_playground-1.0.0/#metafacture-core) in March 2024.

b) [`metafacture-fix 1.1.2`](https://github.com/metafacture/metafacture-fix/releases/tag/1.1.2).
    (metafacture-fix is ["an alternative to configuring data transformations with
    Metamorph, inspired by Catmandu Fix"](https://github.com/metafacture/metafacture-fix)).

c) `metafacture-playground 1.1.2`.
    (metafacture-playground is ["a web application to play around with Metafacture's languages Fix, Flux and Morph"](https://github.com/metafacture/metafacture-playground/)).

## Table of Contents

```toc
# this will be replaced by the toc
```

## metafacture-core

### New Features
- XML: Provide namespace for XML file in flux [#505](https://github.com/metafacture/metafacture-core/issues/505)

### Bug fixes
- XML/biblio: Fix creation of MARC XML leader [#454](https://github.com/metafacture/metafacture-core/issues/454),[#524](https://github.com/metafacture/metafacture-core/issues/524),[#527](https://github.com/metafacture/metafacture-core/issues/527),[#528](https://github.com/metafacture/metafacture-core/issues/538),[#548](https://github.com/metafacture/metafacture-core/issues/548)
- XML/biblio: Reset indentation variable when stream is resetted [#525](https://github.com/metafacture/metafacture-core/issues/525)

### Others
- Upgrade Gradle wrapper to version 8.8
- Update guava and opencsv dependencies [#540](https://github.com/metafacture/metafacture-core/issues/540)

## metafacture-fix

### New Features

- Add flux-command for easily finding path for certain value [#347](https://github.com/metafacture/metafacture-fix/issues/347)
- Add to_base64 function [#354](https://github.com/metafacture/metafacture-fix/issues/354)
- Add links to playground for several Fixes [#339](https://github.com/metafacture/metafacture-fix/issues/339)

### Others

- Update Gradle wrapper to version 8.8

## metafacture-playground

### Others

- Update metafacture dependencies [#179](https://github.com/metafacture/metafacture-playground/issues//179)

