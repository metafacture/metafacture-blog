---
title: "Metafacture releases: Core 6.0.0, Fix 1.0.0, Playground 1.0.0"
date: "2024-03-12T17:05:03.2300Z"
description: "Changes coming with the releases of metafacture-core 6.0.0,
metafacture-fix 1.0.0 and metafacture-playground 1.0.0"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

Most remarkable is certainly the switch to `Java 11`, hence the new major
versions.

This post describes the new developments coming in:

a) [`metafacture-core release
    6.0.0`](https://central.sonatype.com/namespace/org.metafacture) since the [release of
 metafacture-core 5.7.0](https://blog.metafacture.org/metafacture-5.7.0/) in November 2023.

b) [`metafacture-fix 1.0.0`](https://github.com/metafacture/metafacture-fix/releases/tag/1.0.0).
    (metafacture-fix is ["an alternative to configuring data transformations with
    Metamorph, inspired by Catmandu Fix"](https://github.com/metafacture/metafacture-fix)).

c) `metafacture-playground 1.0.0`.
    (metafacture-playground is ["a web application to play around with Metafacture's languages Fix, Flux and Morph"](https://github.com/metafacture/metafacture-playground/)).

## Table of Contents

```toc
# this will be replaced by the toc
```

## metafacture-core

### New Features
- IO: Open gzip compressed content from HTTP [#511](https://github.com/metafacture/metafacture-core/issues/511)

### Bug fixes
- IO: Fix misconception of "Content-Encoding" [#513](https://github.com/metafacture/metafacture-core/issues/513)
- IO: Close resources [#514](https://github.com/metafacture/metafacture-core/issues/514)

### Others
- Provide examples for every flux-command [#488](https://github.com/metafacture/metafacture-core/issues/488)
- Upgrade Gradle wrapper [#520](https://github.com/metafacture/metafacture-core/issues/520)
- Switch to Java version 11 [#518](https://github.com/metafacture/metafacture-core/issues/518)

## metafacture-fix

### New Features

- Add extension snippets for all do binds [#302](https://github.com/metafacture/metafacture-fix/issues/302)
- Upgrade Gradle wrapper [#283](https://github.com/metafacture/metafacture-fix/issues/283)
- Switch to Java 11 [#343](https://github.com/metafacture/metafacture-fix/issues/343)
- Add links to playground for several Fixes [#339](https://github.com/metafacture/metafacture-fix/issues/339)

### Bug fixes

- Close resources [#340](https://github.com/metafacture/metafacture-fix/issues/340)

### Others

- Update metafacture-core dependency to its latest release (6.0.0)

## metafacture-playground

### New Features

- Clear message and result when processing [#126](https://github.com/metafacture/metafacture-playground/issues/126)

### Bug fixes

- Fix location of result in db [#131](https://github.com/metafacture/metafacture-playground/issues/131)

### Others

- Add many examples, i.a. [#152](https://github.com/metafacture/metafacture-playground/issues/152)
- Switch to Java 11 [#160](https://github.com/metafacture/metafacture-playground/issues/160)
- Process all examples as integration tests [#121](https://github.com/metafacture/metafacture-playground/issues/121)
- Add Java Security Manager
