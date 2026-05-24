# License Policy

Copyright (c) Wang Xiao.

Status: repository licensing policy note  
Last updated: 2026-05-24

This document clarifies the layered licensing policy for the OathAI Anchorage Archive.

It does not replace the repository-level `LICENSE`.

This policy note is not legal advice.

## 1. Repository Default

Unless otherwise stated, archive writings, curated fragments, book-related materials, narrative materials, historical archive content, and explanatory documents in this repository remain licensed under:

```text
Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International
CC BY-NC-SA 4.0
```

See:

```text
LICENSE
https://creativecommons.org/licenses/by-nc-sa/4.0/
```

This layer is intended for archive content protection.

## 2. Protocol / Schema / Example Materials

The protocol layer is reusable under:

```text
Creative Commons Attribution 4.0 International
CC BY 4.0
```

This includes:

- Anchor Declaration Protocol materials
- declaration templates
- YAML examples
- anchor card examples
- anchor trace examples
- schema-like materials
- reusable provenance declaration patterns

For the current repository state, this applies to the following paths:

```text
ANCHOR_DECLARATION.md
MANIFEST.yaml
anchors/**
anchor-traces/**
glossary/terms.yaml
locales/index.yaml
modules/index.yaml
policies/index.yaml
fragments/index.yaml
manifest/manifest.yaml
timeline/timeline.yaml
layer-map/layer-map.yaml
layer-map/index.yaml
```

Future `schema/`, `schemas/`, `examples/`, or `protocol/` directories should be treated as protocol-layer materials when added, unless a more specific license notice says otherwise.

This layer is intended to make the protocol surface easier to adopt, cite, extend, and implement.

Attribution should identify:

```text
OathAI Anchorage Archive / Wang Xiao
```

and link to this repository where feasible.

## 3. Code / Scripts / Validators

Code, scripts, validators, build tools, and automation utilities may be released under:

```text
MIT License
```

when they are added with an explicit file-level or directory-level license note.

This repository does not currently relicense existing archive content as MIT.

## 4. File-Level Notes Override Defaults

If a file, directory, or submodule includes an explicit license notice, that notice controls that file, directory, or submodule.

If a file is listed in section 2, or is inside a path listed in section 2, the protocol-layer `CC BY 4.0` policy applies unless a more specific notice says otherwise.

If no specific notice is present and the file is not covered by the protocol-layer path list in section 2, the repository default in section 1 applies.

## 5. Current Practical Rule

For current repository use:

- content layer: protected by `CC BY-NC-SA 4.0`
- protocol layer: reusable under `CC BY 4.0` for the paths listed in section 2
- code layer: may use `MIT` when code is added and marked

Short form:

```text
Archive content is protected.
Protocol patterns are meant to spread.
Code tools should follow open-source practice when added.
```
