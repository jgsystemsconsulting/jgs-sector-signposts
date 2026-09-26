---
name: rail-signpost
kind: signpost
description: "Signpost (not a knowledge pack) for railway software and safety standards: CENELEC EN 50126-1 and EN 50126-2 (2017, RAMS), EN 50128 (2011+A1:2020+A2:2021, software for railway control and protection systems), EN 50129 (2018, safety related electronic systems for signalling), EN 50657 (2017+A1:2023, software on board rolling stock), and the European Union Agency for Railways TSI General Guide, CCS TSI Application Guide, and CCS TSI domain page. Contains no source content: each row carries only the designation, title, edition, owner, redistributability status, and the owner's URL. Use when you need to identify, cite, or locate a railway standard; paywalled rows point to national standards bodies, free rows point to the ERA download."
---

# Rail Software and Safety Standards: Signpost (pointers only)

**This is a signpost, not a knowledge pack.** It carries **no standards-body content**:
no reproduced clauses, no normative text, no synthesised summaries of the standards.
The CENELEC railway standards are paywalled through national standards bodies with no
redistribution grant (Excluded under this repo's `docs/SOURCE-VETTING.md`). The ERA
guides are free to download but remain (c) ERA/EU with citation-only terms, so they
cannot be repackaged either. What this skill does: tell you which document you want,
who owns it, whether a free copy exists, and where to get the authentic one.

## When to use

You are developing, assessing, or reviewing railway software or signalling systems and
need to identify or cite the governing document: which EN standard sets the RAMS
process, which covers control and protection software, which covers safety related
electronic systems for signalling, which covers software on board rolling stock, and
where the EU interoperability guidance for control command and signalling lives.

**Prerequisites:** none, plain Markdown.

## How to use

Find your document below. The **Status** column says whether it can be packaged:

- **Excluded**: paywalled, no redistribution grant; buy from a national standards body. *Cannot* be packaged here.
- **Open**: free to obtain from the owner, but copyright stays with the owner and the
  terms allow citation only, so download from the URL given.

Editions come from publisher pages or national reseller listings that name the EN
designation. The EN rows link a reseller listing as edition evidence; buy the text from
your national standards body (for example BSI, DIN, UNE, or AFNOR). Confirm the edition
your contract or safety case cites before relying on a row, and do not quote a date that
a row does not carry.

Owner URLs, including the ERA pages, appear here only because this pack is a signpost;
the repo link policy bars source-material URLs everywhere else.

## RAMS

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| EN 50126-1 | Railway applications. RAMS. Part 1: Generic RAMS process | 2017 (A1:2024 in BS-style listings; national A1:2026) | CENELEC | Excluded: paywalled; buy from a national standards body | https://www.en-standard.eu/search/?q=EN+50126 |
| EN 50126-2 | Railway applications. RAMS. Part 2: Systems approach to safety | 2017 (A1:2024 in BS-style listings; national A1:2026) | CENELEC | Excluded: paywalled; buy from a national standards body | https://www.en-standard.eu/search/?q=EN+50126-2 |

## Signalling and control software

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| EN 50128 | Railway applications. Communication, signalling and processing systems. Software for railway control and protection systems | 2011+A1:2020+A2:2021 | CENELEC | Excluded: paywalled; buy from a national standards body | https://www.en-standard.eu/une-en-50128-2012-a2-2021-railway-applications-communication-signalling-and-processing-systems-software-for-railway-control-and-protection-systems/ |
| EN 50129 | Railway applications. Communication, signalling and processing systems. Safety related electronic systems for signalling | 2018 (national adoptions 2020; a 2026 national edition is listed on reseller catalogues) | CENELEC | Excluded: paywalled; buy from a national standards body | https://www.en-standard.eu/search/?q=EN+50129 |

## Rolling stock software

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| EN 50657 | Railway applications. Rolling stock applications. Software on board rolling stock | 2017+A1:2023 | CENELEC | Excluded: paywalled; buy from a national standards body | https://www.en-standard.eu/search/?q=EN+50657 |

## EU interoperability (ERA)

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| ERA TSI General Guide | Guide for the application of the Technical Specifications for Interoperability (general) | ERA PDF, 2023-12 path | European Union Agency for Railways (ERA) | Open, free download; (c) ERA/EU; citation only, not packaged | https://www.era.europa.eu/system/files/2023-12/TSI_General_Guide.pdf |
| CCS TSI Application Guide | Guide for the application of the CCS TSI (2023) | ERA PDF, 2024-12 path | ERA | Open, free download; citation only, not packaged | https://www.era.europa.eu/sites/default/files/2024-12/ccs-tsi-2023-application-guide.pdf |
| CCS TSI (ERA domain page) | Control Command and Signalling TSI domain page, entry to the legal TSI and its guides | Live landing | ERA | Open landing; binding TSI text via EU law publications | https://www.era.europa.eu/domains/technical-specifications-interoperability/control-command-and-signalling-tsi_en |

## Free paths in this repo and fleet

- No fleet content pack covers rail. The ERA rows above are the free official path. No
  free copy of the EN texts exists; the RSSB standards catalogue covers UK rail
  standards and is not a free EN mirror.
- **pack: functional-safety-signpost** (jgs-automotive-knowledge-packs). The IEC 61508
  functional-safety lineage that EN 50126 and EN 50128 build on.
- Fleet sibling repos are named, not linked, per the fleet link policy.

---
*Signpost content © JG Systems Consulting Ltd. (MIT). Standard designations and titles
are named for reference only; "CENELEC", "European Union Agency for Railways", "ERA", and
document numbers are the property of their respective owners. Named for identification,
not endorsement.*
