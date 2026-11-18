# Licensing at Vibe Craft Studios

This page is the licensing policy for **all repositories** of
[Vibe Craft Studios](https://github.com/vibec-studios). A repository follows it unless it is listed under
[Exceptions](#exceptions).

## The default

| What | Terms |
|---|---|
| **Source code** (incl. build scripts, configs, docs) | [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0): fork, change and share it, also commercially |
| **Names and logos** ("Vibe", "Vibey", "Vibe Craft Studios", "H&H Armors", the seal …) | not licensed, see [TRADEMARKS.md](TRADEMARKS.md): forks need their own name and look |
| **Artwork and models** (textures, models, animations, sounds, cosmetics, icons, screenshots, branding) | all rights reserved, see [ASSETS-POLICY.md](ASSETS-POLICY.md) |
| **Online services** (vibe.henny.dev, the Vibey relay, …) | official builds only, see [SERVICES.md](SERVICES.md) |

In short: **you may fork our code, but not publish it under our names, with our art, or connected to our servers.**

Each repository carries:

- `LICENSE`: the Apache License 2.0 text (GitHub needs it per repository),
- `NOTICE`: copyright line, a pointer to this page and the repository-specific asset paths
  (template below),
- a short "License" section in the README.

## Exceptions

| Repository | Terms | Why |
|---|---|---|
| `vibe-backend` | proprietary, all rights reserved | closed source service |
| `vibe-backend`: `packages/sdk`, `packages/shared` | MIT | public client SDK, also vendored into the open source launcher |
| `hha-arius`, `HHA_void` | MIT (as published) | co-authored with Crix05z; changes only with their agreement |
| `hha-blood` | no license yet (all rights reserved by its authors) | made by Crix05z; their call |
| `vibey-client`, `vibey-multiplayer`, `vibey-lyrics`, `HHA` | Apache-2.0 from 2026-11-18 | releases published before that date stay under MIT |

A new exception is added to this table in the same change that introduces it.

## Contributions

Contributions to a repository are made under that repository's license (Apache-2.0 by default). By contributing
artwork or models you confirm that you made them yourself (or may share them) and agree that Vibe Craft Studios may
use and distribute them as part of its projects under [ASSETS-POLICY.md](ASSETS-POLICY.md). See
[CONTRIBUTING.md](CONTRIBUTING.md).

## NOTICE template

```text
<Project name>
Copyright 2026 Vibe Craft Studios

The source code is licensed under the Apache License, Version 2.0 (see LICENSE).

Not covered by that license – see https://github.com/vibec-studios/.github/blob/main/LICENSING.md :
  - our names and logos (TRADEMARKS.md),
  - artwork, models, textures, animations and sounds (ASSETS-POLICY.md), in this repository in particular:
      <paths>
  - access to the Vibe online services (SERVICES.md).
```

*This policy is written in good faith and is not legal advice.*
