---
name: maritime-signpost
kind: signpost
description: "Signpost (not a knowledge pack) for maritime safety instruments and ship classification rules: SOLAS 1974 as amended and the International Safety Management (ISM) Code from IMO, the IMO ISM introduction page, Circulars browser, and Publications hub, and the current DNV, ABS, and Lloyd's Register class rule portals. Contains no source content: each row carries only the designation, title, edition, owner, redistributability status, and the owner's URL. Use when you need to identify, cite, or locate a maritime convention, code, or class rule set; paywalled IMO instruments point to IMO Publishing, free rows point to the owner's page or portal."
---

# Maritime Software and Safety Standards: Signpost (pointers only)

**This is a signpost, not a knowledge pack.** It carries **no standards-body content**:
no reproduced clauses, no normative text, no synthesised summaries of the instruments or
rules. IMO sells the SOLAS and ISM Code texts with no redistribution grant (Excluded
under this repo's `docs/SOURCE-VETTING.md`). The class society portals are free to read
under each society's terms but cannot be repackaged. What this skill does: tell you
which document you want, who owns it, whether a free copy exists, and where to get the
authentic one.

## When to use

You are developing or reviewing shipboard software, a safety management system, or a
class submission and need to identify or cite the governing document: which IMO
convention sets ship safety requirements, which IMO code sets safety management, where
IMO publishes circulars, and where each major classification society publishes its
current rules.

**Prerequisites:** none, plain Markdown.

## How to use

Find your document below. The **Status** column says whether it can be packaged:

- **Excluded**: paywalled, no redistribution grant; buy from the owner. *Cannot* be packaged here.
- **Open**: free to obtain or read from the owner, but copyright stays with the owner
  and the terms allow citation only, so read or download from the URL given.

Class rule sets change by edition; read the edition tag on the portal before citing a
rule. The DNV landing often shows a bot challenge to scripted clients; open it in a
browser. The ISM Code row and the ISM orientation row share one URL on purpose: IMO
sells the Code, and that page is IMO's own entry point for it. Do not quote a date that
a row does not carry.

Owner URLs appear here only because this pack is a signpost; the repo link policy bars
source-material URLs everywhere else.

## IMO instruments

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| SOLAS 1974 | International Convention for the Safety of Life at Sea (SOLAS), 1974 | 1974 as amended; consolidated editions via IMO Publishing | IMO | Excluded: convention publication paywalled; buy from IMO Publishing | https://www.imo.org/en/About/Conventions/Pages/International-Convention-for-the-Safety-of-Life-at-Sea-(SOLAS),-1974.aspx |
| ISM Code | International Safety Management (ISM) Code | Current IMO published edition (confirm on IMO Publishing at freeze) | IMO | Excluded: code publication paywalled; buy from IMO Publishing | https://www.imo.org/en/OurWork/HumanElement/Pages/ISMCode.aspx |

## IMO free orientation

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| IMO ISM page (orientation) | IMO Human Element ISM Code introduction page | Live | IMO | Open HTML introduction; not the Code text | https://www.imo.org/en/OurWork/HumanElement/Pages/ISMCode.aspx |
| IMO Circulars | IMO Circulars (public browser) | Live | IMO | Open index; document-level access varies | https://www.imo.org/en/OurWork/Circulars/Pages/Default.aspx |
| IMO Publications | IMO Publications and ePublications hub | Live | IMO | Open hub; shop for paid instruments | https://www.imo.org/en/publications/Pages/Home.aspx |

## Classification society rules

| Designation | Title | Edition | Owner | Status | URL |
|---|---|---|---|---|---|
| DNV Rules and Standards | DNV Rules and Standards (Rules and Standards Explorer) | Current portal set (re-read January edition tags at freeze) | DNV | Open portal, free read under DNV terms; not packaged | https://www.dnv.com/rules-standards/ |
| ABS Rules | ABS Rules and Guides (Rule Manager) | Current Rule Manager set | ABS | Open portal; citation only | https://ww2.eagle.org/en/rules-and-resources/rules-and-guides-v2.html |
| LR Rules | Lloyd's Register rules, regulations and standards for ships | Current LR rules set | Lloyd's Register | Open portal; citation only | https://www.lr.org/en/knowledge/lloyds-register-rules/ |

## Free paths in this repo and fleet

- No fleet content pack covers maritime. The class society portals above (DNV, ABS,
  Lloyd's Register) are the free read path, under each society's terms.
- The IMO orientation rows are the free entry points for the paywalled instruments.
- Fleet sibling repos are named, not linked, per the fleet link policy.

---
*Signpost content © JG Systems Consulting Ltd. (MIT). Instrument designations and titles
are named for reference only; "IMO", "SOLAS", "DNV", "ABS", "Lloyd's Register", and
document numbers are the property of their respective owners. Named for identification,
not endorsement.*
