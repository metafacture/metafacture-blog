---
title: "Metafacture releases: Core 6.2.0, Fix 1.2.0"
date: "2025-01-24T16:15:03.2300Z"
description: "Changes coming with the releases of metafacture-core 6.2.0 and
metafacture-fix 1.2.0"
authors: [{lastname: "Christoph",
           firstname: "Pascal"}]
---

*Preamble*

This will be the last time `metafacture-fix` will be released on its own as it will be [incorporated into `metafacture-core`](https://github.com/metafacture/metafacture-core/issues/577).

This post describes the new developments coming with:

a) [`metafacture-core release 6.2.0`](https://central.sonatype.com/namespace/org.metafacture) since the [release of metafacture-core 6.1.2](https://blog.metafacture.org/metafacture-releases_core-6.1.2_fix-1.1.2_playground-1.1.2/#metafacture-core) in July 2024.

b) [`metafacture-fix 1.2.0`](https://github.com/metafacture/metafacture-fix/releases/tag/1.2.0).
    (metafacture-fix is ["an alternative to configuring data transformations with
    Metamorph, inspired by Catmandu Fix"](https://github.com/metafacture/metafacture-fix)).

## Table of Contents

```toc
# this will be replaced by the toc
```

## metafacture-core

### New Features
- Biblio: Make encode-marc21 validation optional [#567](https://github.com/metafacture/metafacture-core/issues/567)
- Flowcontrol: New flux command "sleep" [#495](https://github.com/metafacture/metafacture-core/issues/495)
- XML/biblio: Ignore namespace in MARC XML Handler[#552](https://github.com/metafacture/metafacture-core/issues/552), [#569](https://github.com/metafacture/metafacture-core/issues/569)
- XML: Parameter to set max entities [#554](https://github.com/metafacture/metafacture-core/issues/554)

### Bug fixes
- CSV: Fix escaping by using RFC compliant parser [496](https://github.com/metafacture/metafacture-core/issues/496)
- IO and XML/biblio: Fix "batch-reset creates empty records" [#543](https://github.com/metafacture/metafacture-core/issues/543)
- XML/biblio: Pretty indentation of marc:leader [#550](https://github.com/metafacture/metafacture-core/issues/550) and [#548](https://github.com/metafacture/metafacture-core/issues/548)

### Others
- Upgrade Gradle wrapper to version 8.11.1
- XML/biblio: Improve XML documentation [#497](https://github.com/metafacture/metafacture-core/issues/497)
- Documentation: add @in in ObjectToLiteral [#561](https://github.com/metafacture/metafacture-core/pull/561)
- Update opencsv dependency to version 5.9

## metafacture-fix

### New Features

- Implicit array creation with $append, general $prepend support [#368](https://github.com/metafacture/metafacture-fix/issues/368)
- Add log function [#319](https://github.com/metafacture/metafacture-fix/issues/319)
- Set variable with element value [#282](https://github.com/metafacture/metafacture-fix/issues/282)
- Use the default option in lookups as in catmandu [#333](https://github.com/metafacture/metafacture-fix/issues/333)
- Add new functions add_array and add_hash [#374](https://github.com/metafacture/metafacture-fix/issues/374)
- Add option "url_safe" to "to_base64" function [#386](https://github.com/metafacture/metafacture-fix/issues/386)
- Optionally specify limit for number of entities in a record [#373](https://github.com/metafacture/metafacture-fix/issues/373)

### Bug fixes

- Delete escape signs in default template for find-fix-paths [#347](https://github.com/metafacture/metafacture-fix/issues/347)
- Ignore old value's path in copy_field Fix function [#380](https://github.com/metafacture/metafacture-fix/issues/380)
- Set wildcard classpath for Windows' start batch [#382](https://github.com/metafacture/metafacture-fix/issues/382)

### Others

- Add multiple missing playground examples for fix functions [#363](https://github.com/metafacture/metafacture-fix/issues/363)
 - Update description of Metafix [#370]((https://github.com/metafacture/metafacture-fix/pull/370))
- Add log4j logging [#388](https://github.com/metafacture/metafacture-fix/issues/388)
- Update Gradle wrapper to version 8.11.1

