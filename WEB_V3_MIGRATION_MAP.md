# SAN PRO WEB V3 — CONTROLLED MIGRATION MAP

Статус: WORKING / SAFE BRANCH / NOT MERGED / NOT PRODUCTION-PUBLISHED

## 1. Rollback baseline

- Repository: `floradekorart2026-glitch/san-pro-web-v01`
- Production/default branch: `main`
- Frozen V0.1 HEAD: `54845170163ccdbdee5bf2249ec9d319f09664c6`
- Frozen tree: `9352233f7e8e18807468af8a5b2785e127ff7915`
- Safe migration branch: `web-v3-migration`
- Rule: `main` remains untouched until explicit Owner approval.

## 2. Current V3 content authority and routing

Current M08 V3 content input is the MASTER-routing pointer:

- `WEB-V3-EN-MASTER-001`
- Document: `M08-WEB-V3 — ENGLISH MASTER CONTENT BASE — 7×7×7 — V0.1 — WORKING`
- Document ID: `162AL4XM30YCbN91ARnq9JX59XD12hDkWGAZZc7fDFBc`
- Status: WORKING / M08 / NOT MASTER FACT / NOT PUBLISHED
- Content mode: ENGLISH MASTER PUBLIC BASE
- Design status: FROZEN / OUT OF SCOPE
- Disclosure: N0/N1 PUBLIC ONLY / RESTRICTED CORE EXCLUDED

P01–P09 draw from the same controlled public-content graph. English is the master public-content language in this phase; Croatian is a later controlled localization, not a parallel source of truth.

The English Master declares the M08-WEB-01:09 source chain. Where the current working English Master document does not yet contain a complete later-pillar node set, the already controlled M08 P06–P09 routing/migration packages from that declared source chain may be used as bridge sources. Missing content must not be invented.

Governance: latest explicit Owner Decision and current ACTIVE project source override older conflicting working text. Public copy must not expose Restricted Core or convert assumptions, roadmap items, candidate relationships, future options, certifications, technical performance or investment expectations into facts.

## 3. V0.1 → V3 page map

| V0.1 route | V3 page | Action |
|---|---|---|
| `/` | P01 HOME | REWRITE FROM CURRENT ENGLISH MASTER |
| `/slavonija/` | legacy origin route | KEEP COMPATIBILITY POINTER; Slavonia remains origin layer |
| `/san-pro/` | P03 SAN PRO SYSTEM | REWRITE FROM CURRENT ENGLISH MASTER |
| `/programi/` | legacy programmes route | KEEP COMPATIBILITY POINTER to P04 |
| `/kvaliteta/` | P05 QUALITY | REWRITE FROM CURRENT ENGLISH MASTER |
| `/partnerstva/` | legacy partnership route | KEEP COMPATIBILITY POINTER to P06/P09 |
| `/inovacije/` | P07 KNOWLEDGE & TECHNOLOGY | REWRITE from controlled M08 source chain |
| `/buducnost/` | P08 FUTURE & COMMUNITY | REWRITE from controlled M08 source chain |
| `/kontakt/` | P09 CONTACT | REWRITE; no invented contact identifiers |
| `/pravne-informacije/` | legal info | KEEP pending legal validation |
| `/privatnost/` | privacy | KEEP pending legal validation |
| new `/o-nama/` | P02 WHO WE ARE | CREATE / CURRENT ENGLISH MASTER |
| new `/proizvodi/` | P04 PRODUCTS | CREATE / CURRENT ENGLISH MASTER |
| new `/ulaganja/` | P06 INVESTORS | CREATE from controlled M08 source chain |

## 4. Navigation target

`Home / Who we are / SAN PRO system / Products / Quality / Investment / Innovation / Future / Contact`

The former Slavonia-first hierarchy is superseded in V3 navigation. Slavonia remains a root and responsibility layer, not the sole public thesis.

## 5. Content guardrails

- M1 starts from qualified defatted sunflower meal.
- Current M1 project modelling basis, when context-relevant: one working shift and 45 t qualified defatted sunflower meal per working day; this is not a claim of current production.
- No 90 t/day, second-shift or shift-multiplier base case without a later explicit Owner Decision.
- M0–M4 are separate project/investment economics; no hidden group-consolidation claim.
- M2 excludes white bread.
- M3 and M4 are development platforms; no final hero-SKU claim where not validated.
- Future modules/feedstocks/replication/licensing/JV remain FUTURE OPTION ONLY until a later Owner gate.
- Quality page communicates design intent, controls and roadmap; roadmap ≠ certification.
- No public unsupported CAPEX/OPEX/ROI/IRR/payback promises in V3.
- Contact identifiers remain OPEN until supplied/verified.
- Human + AI: AI accelerates research, comparison and structuring; final responsibility remains human.

## 6. Visual reuse

Existing V0.1 visual assets and the existing V3 visual system are reused. Design is frozen for this content-regeneration task. Concept images remain explicitly conceptual/development visuals. No visual is treated as proof of a factual facility, line or product state.

## 7. Technical migration and preview approach

- Reuse existing static HTML/CSS/JS architecture.
- Preserve existing shared styling and V3 additions in `assets/css/v3.css`.
- Preserve mobile navigation and accessibility basics.
- Keep `robots.txt`, `<meta name="robots">` and pre-publication noindex posture unchanged until publication gate.
- Cloudflare Worker target name: `san-pro-web-v02`.
- Workers Static Assets configuration: `wrangler.jsonc` with root static-assets directory.
- Asset packaging exclusions: `.assetsignore`.
- Git-connected non-production branch builds create the controlled V3 preview.
- No write to `main`, DNS, custom-domain or Cloudflare production traffic in this phase.

## 8. Hard stops

1. No write to `main` before explicit Owner approval.
2. No production deployment/publication before explicit Owner approval.
3. A successful branch preview is not a production-publication claim.
4. No ACTIVE/PUBLISHED production V3 claim without provider proof and production read-back.
5. If `main` diverges from frozen baseline during migration, stop and re-baseline before any merge proposal.
6. Missing M08 content is preserved as a gap; it is not filled by invention.

## 9. Current controlled execution state — 09.09.2026

- MASTER routing pointer `WEB-V3-EN-MASTER-001`: PHYSICALLY WRITTEN / READ-BACK VERIFIED.
- English V3 P01–P09 safe-branch regeneration: PHYSICALLY WRITTEN / READ-BACK VERIFIED.
- Workers Static Assets configuration: PHYSICALLY WRITTEN / READ-BACK VERIFIED.
- Cloudflare branch preview pipeline: PROVIDER-NATIVE SUCCESS on the regenerated branch before this provenance-map synchronization; current branch check must remain green after this map-only commit.
- `main`: FROZEN / UNCHANGED.
- PR #1: DRAFT / NOT MERGED.
- Production V3: NOT PUBLISHED / OWNER GATE REMAINS ACTIVE.
