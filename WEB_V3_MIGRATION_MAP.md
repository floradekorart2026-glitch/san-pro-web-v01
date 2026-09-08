# SAN PRO WEB V3 — CONTROLLED MIGRATION MAP

Статус: WORKING / SAFE BRANCH / NOT MERGED / NOT PUBLISHED

## 1. Rollback baseline

- Repository: `floradekorart2026-glitch/san-pro-web-v01`
- Production/default branch: `main`
- Frozen V0.1 HEAD: `54845170163ccdbdee5bf2249ec9d319f09664c6`
- Frozen tree: `9352233f7e8e18807468af8a5b2785e127ff7915`
- Safe migration branch: `web-v3-migration`
- Rule: `main` remains untouched until explicit Owner approval.

## 2. Authoritative working sources

WEB V3 is assembled from the M08 working migration layer:
- WEB-P01 HOME
- WEB-P02 WHO WE ARE
- WEB-P03 SAN PRO SYSTEM
- WEB-P04 PRODUCTS
- WEB-P05 QUALITY
- WEB-P06 INVESTORS
- WEB-P07 KNOWLEDGE & TECHNOLOGY
- WEB-P08 FUTURE & COMMUNITY
- WEB-P09 CONTACT ROUTING
- M08-WEB-V3 FULL CONTENT MIGRATION & GAP CLOSURE MAP

Governance: latest Owner Decision overrides older conflicting working text. Public copy must not expose Restricted Core or convert assumptions, roadmap items, candidate relationships, future options, certifications, technical performance or investment expectations into facts.

## 3. V0.1 → V3 page map

| V0.1 route | V3 page | Action |
|---|---|---|
| `/` | P01 HOME | REWRITE |
| `/slavonija/` | legacy origin route | REPLACE WITH POINTER to P02; keep historical route compatibility |
| `/san-pro/` | P03 SAN PRO SYSTEM | REWRITE |
| `/programi/` | legacy programmes route | REPLACE WITH POINTER to P04; keep historical route compatibility |
| `/kvaliteta/` | P05 QUALITY | REWRITE |
| `/partnerstva/` | legacy partnership route | REPLACE WITH POINTER to P06/P09 |
| `/inovacije/` | P07 KNOWLEDGE & TECHNOLOGY | REWRITE |
| `/buducnost/` | P08 FUTURE & COMMUNITY | REWRITE |
| `/kontakt/` | P09 CONTACT | REWRITE; no invented contact identifiers |
| `/pravne-informacije/` | legal info | KEEP pending legal validation |
| `/privatnost/` | privacy | KEEP pending legal validation |
| new `/o-nama/` | P02 WHO WE ARE | CREATE |
| new `/proizvodi/` | P04 PRODUCTS | CREATE |
| new `/ulaganja/` | P06 INVESTORS | CREATE |

## 4. Navigation target

`Početna / O nama / SAN PRO sustav / Proizvodi / Kvaliteta / Ulaganja / Inovacije / Budućnost / Kontakt`

The current Slavonia-first hierarchy is superseded in V3 navigation. Slavonia remains an origin/identity layer, not the sole public thesis.

## 5. Content guardrails

- M1 starts from qualified defatted sunflower meal.
- M0–M4 are separate investment/project economics; no group consolidation claim.
- M2 excludes white bread.
- M3 and M4 are development platforms; no final hero SKU claim where not validated.
- Future modules/feedstocks/replication/licensing/JV remain FUTURE OPTION ONLY until a later Owner gate.
- Quality page communicates design intent, controls and roadmap; roadmap ≠ certification.
- No public CAPEX/OPEX/ROI/IRR/payback promises in V3.
- Contact identifiers remain OPEN until supplied/verified.
- Human+AI: AI accelerates research/structuring; final responsibility remains human.

## 6. Visual reuse

Existing V0.1 visual assets are reused where they support V3 without creating a false factual impression. Concept images remain explicitly conceptual/development visuals. No new visual claim is treated as proof.

## 7. Technical migration approach

- Reuse existing static HTML/CSS/JS architecture where stable.
- Introduce V3-specific shared classes in `assets/css/styles.css` rather than rebuild the stack.
- Preserve mobile navigation and accessibility basics.
- Keep `_headers`, `robots.txt` and existing noindex/pre-publication posture unchanged until publication gate.
- No DNS, custom-domain or Cloudflare production change in this phase.

## 8. Hard stops

1. No write to `main` before explicit Owner approval.
2. No production deployment/publication before explicit Owner approval.
3. No ACTIVE/PUBLISHED/LIVE V3 claim without provider proof and read-back.
4. If `main` diverges from frozen baseline during migration, stop and re-baseline before any merge proposal.

Execution state at creation: PHYSICALLY WRITTEN TO SAFE BRANCH / READ-BACK PENDING.
