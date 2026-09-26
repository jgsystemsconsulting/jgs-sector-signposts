---
name: space-signpost
kind: signpost
description: "Signpost (not a knowledge pack) for space software engineering and assurance standards: ECSS-E-ST-40C Rev.1 (30 April 2025) and issue C (6 March 2009) space software engineering, ECSS-Q-ST-80C Rev.2 (30 April 2025) software product assurance, NASA-STD-8739.8B (Rev B, 2022-09-08) software assurance and software safety, NPR 7150.2D (effective 2022-03-08, expires 2027-03-08) NASA software engineering requirements, the NASA Software Engineering and Assurance Handbook (NASA-HDBK-2203, SWEHB Ver D), and the ECSS Active Standards list and training material. Contains no source content: each row carries only the designation, title, edition, owner, redistributability status, and the owner's URL. Use when you need to identify, cite, or locate a space software standard; ECSS rows point to the owner's standard page, NASA rows point to the free NASA catalogue, NODIS, or wiki."
---

# Space Software and Safety Standards: Signpost (pointers only)

**This is a signpost, not a knowledge pack.** It carries **no standards-body content**:
no reproduced clauses, no normative text, no synthesised summaries of the standards.
ECSS standards are free to download from the owner but remain (c) ECSS with no consent
to reproduce, so this repo cites them and never packages them. The NASA documents are
free US government works; their reconstructed notes live in a fleet sibling repo. What
this skill does: tell you which document you want, who owns it, whether a free copy
exists, and where to get the authentic one.

## When to use

You are developing, assuring, or reviewing flight or ground software for a space
programme and need to identify or cite the governing document: which ECSS standard sets
space software engineering, which sets software product assurance, which NASA standard
covers software assurance and software safety, and which NASA directive sets software
engineering requirements.

**Prerequisites:** none, plain Markdown.

## How to use

Find your document below. The **Status** column says whether it can be packaged:

- **Excluded**: paywalled, no redistribution grant; buy from the owner. *Cannot* be packaged here.
- **Open**: free to obtain from the owner, but copyright stays with the owner or the
  terms allow citation only, so download from the URL given.

Every row here is Open. The ECSS rows are owner downloads: free to read from the ECSS
site, with redistribution still barred. The fleet's se-standards-signpost marks ECSS
rows Excluded; both packs agree that no ECSS text can be packaged. Editions come from
the ECSS Active Standards list and the NASA technical standards catalogue. Confirm the
edition your contract cites before relying on a row, and do not quote a date that a row
does not carry.

Owner URLs, including the NASA pages, appear here only because this pack is a signpost;
the repo link policy bars source-material URLs everywhere else.

## ECSS software engineering and product assurance

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| ECSS-E-ST-40C Rev.1 | Space engineering. Software | 30 April 2025 (Active Standards list) | ECSS | Open owner download; (c) ECSS; citation only, not packaged | https://ecss.nl/standard/ecss-e-st-40c-rev-1-software-30-april-2025/ |
| ECSS-E-ST-40C | Space engineering. Software (issue C, cited by legacy programmes) | 6 March 2009 | ECSS | Open owner download; citation only, not packaged | https://ecss.nl/standard/ecss-e-st-40c-software-general-requirements/ |
| ECSS-Q-ST-80C Rev.2 | Space product assurance. Software product assurance | 30 April 2025 | ECSS | Open owner download; citation only, not packaged | https://ecss.nl/standard/ecss-q-st-80c-rev-2-software-product-assurance-30-april-2025/ |

Note: the owner's page for ECSS-E-ST-40C Rev.1 reports that work on that revision is
paused until the ECSS NextGen effort picks it up again. Check the Active Standards list
row below before citing Rev.1, and keep the 2009 issue C row for contracts that still
name it.

## NASA software assurance and engineering

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| NASA-STD-8739.8B | Software Assurance and Software Safety Standard | Rev B, 2022-09-08, ACTIVE | NASA OSMA | Open, free; US government work; citation path only | https://standards.nasa.gov/standard/NASA/NASA-STD-87398 |
| NPR 7150.2D | NASA Software Engineering Requirements | 7150.2D, effective 2022-03-08 (expires 2027-03-08) | NASA OCE | Open, free (NODIS) | https://nodis3.gsfc.nasa.gov/displayDir.cfm?t=NPR&c=7150&s=2 |
| NASA-HDBK-2203 (SWEHB Ver D) | NASA Software Engineering and Assurance Handbook | Ver D (NTSS metadata 2020-04-20; live wiki) | NASA OCE | Open wiki | https://swehb.nasa.gov/ |

## Indexes and training

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| ECSS Active Standards list | ECSS Active Standards (index) | Live list | ECSS | Open HTML index | https://ecss.nl/standards/active-standards/ |
| ECSS training material downloads | ECSS training material downloads | Live | ECSS/ESA | Open landing; training packs, not the normative ST text | https://ecss.nl/ecss-training/ecss-training-material-downloads/ |

## Free paths in this repo and fleet

- **pack: nasa-npr-7150** (jgs-se-knowledge-packs). NPR 7150.2D as reconstructed
  reference notes.
- **pack: nasa-system-safety** (jgs-se-knowledge-packs). NASA system safety guidance
  as reconstructed reference notes.
- **pack: se-standards-signpost** (jgs-se-knowledge-packs). ECSS systems engineering
  rows alongside the other SE standards.
- Fleet sibling repos are named, not linked, per the fleet link policy.

---
*Signpost content © JG Systems Consulting Ltd. (MIT). Standard designations and titles
are named for reference only; "ECSS", "ESA", "NASA", and document numbers are the
property of their respective owners. Named for identification, not endorsement.*
