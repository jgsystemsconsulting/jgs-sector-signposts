<!--
Copyright (c) 2026 JG Systems Consulting Ltd. - MIT License (see LICENSE).
SPDX-License-Identifier: MIT
-->

<h1 align="center">jgs-sector-signposts</h1>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT%20(tooling)-blue" alt="License: MIT (tooling)">
  <img src="https://img.shields.io/badge/version-0.1.0-green" alt="Version 0.1.0">
</p>

<p align="center">
  <strong>Standards signposts (pointers only) for rail, space, and maritime
  software and safety work, installable as Agent Skills for coding agents.</strong>
</p>

**Copyright (c) 2026 JG Systems Consulting Ltd. - MIT License (tooling and signposts); citation-only signpost pointers, no third-party content ships (see [NOTICE](NOTICE)).**

---

## What it is

This repo is the rail, space, and maritime member of the industry knowledge-pack
fleet. It ships three signposts and no content pack: the governing standards are
paywalled (CENELEC EN 5012x, IMO instruments) or copyright-restricted (ECSS), and
the free US space path already lives in jgs-se-knowledge-packs.

- **`rail-signpost`**: CENELEC RAMS, signalling, and rolling-stock software
  standards plus ERA interoperability guides.
- **`space-signpost`**: ECSS software engineering and product assurance plus NASA
  software assurance and engineering.
- **`maritime-signpost`**: IMO instruments plus DNV, ABS, and Lloyd's Register
  class rules.

Each signpost row gives the designation, title, edition, owner, status, and the
owner's URL; no standard text is reproduced. This is engineering signposting,
not legal or compliance advice.

## Install

```bash
python install.py --dry-run   # preview
python install.py             # install the packs as agent skills
```

Shell equivalents: `install.sh` (bash) and `install.ps1` (PowerShell). After
install, each pack is invocable as an Agent Skill.

## Use

- **`/signposts <question>`**: the orchestrator. Type a free-text rail, space, or
  maritime standards question and it routes to the right signpost and answers with
  designation, edition, owner, status, and URL.
- Each signpost is also invocable directly as **`/rail-signpost`**,
  **`/space-signpost`**, or **`/maritime-signpost`**.

## Gates

Run all three from the repo root:

```bash
python tooling/validate_pack.py --all   # every pack matches docs/PACK-SPEC.md
python tooling/check_release.py         # release readiness: files, versions, leaks, links, index, headers
python tooling/test_ci_gate.py          # proves CI (.github/workflows/validate.yml) checks the same things
```

CI green is not release-ready: `check_release.py` is the pre-tag gate. Run it
before tagging and confirm the sha on its `RELEASE CHECK: PASS` receipt matches
the commit you tag.

## Licence

Tooling and signpost content are [MIT](LICENSE) (JG Systems Consulting Ltd.). No
pack carries third-party content. Standards are named for identification only and
remain the property of their owners. The model is set out in
[docs/LICENSING.md](docs/LICENSING.md).
