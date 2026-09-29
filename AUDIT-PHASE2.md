# Phase 2 Internal Audit Report — data.xuanbaoenvironment.com

Date: 2026-09-29. Scope: full repository audit before Phase 2 (Knowledge Graph + Data Evidence + Engineering SEO).

## 1. Inventory & structure

- 89 markdown pages under docs/, 10 sections (activated-carbon 15, molecular-sieves 9, scr-denox 15, co-oxidation 9, voc-catalysts 10, voc-engineering 13, water-purification 2, testing 5, compliance 5, methodology 4)
- All 89 pages present in mkdocs.yml nav → **0 orphan pages**
- Nav has no entries pointing to missing files
- 0 broken internal links (scripted check across all pages)

## 2. SEO basics — PASS

- title + description frontmatter on all 89 pages ✓
- Exactly 1 H1 per page ✓
- 0 duplicate titles ✓
- 0 pages.dev references (docs + overrides) ✓
- 199 internal links to main site https://xuanbaoenvironment.com/ ✓
- robots.txt present: AI crawlers (GPTBot, ClaudeBot, PerplexityBot etc.) allowed + Sitemap directive ✓
- llms.txt present (124 lines) — needs refresh after Phase 2 adds pages
- Canonical/schema domains all use https://data.xuanbaoenvironment.com/ ✓

## 3. Schema — GOOD, small upgrade needed

overrides/main.html has 4 JSON-LD blocks: Organization (@id main site), WebSite, page-level TechArticle/CollectionPage/WebPage, BreadcrumbList. All use correct domains.
Gap: no DefinedTerm/DefinedTermSet (fits the technical-terms glossary page).

## 4. Data evidence system — EXISTS but underused

- methodology/data-classification.md defines the 7 data types ✓ (matches prompt requirement)
- methodology/sources.md defines evidence levels A–E ✓
- Field-test evidence handled correctly (CO sintering 1,499→18 ppm marked Field Test Result + completeness caveat) ✓
- **Gap: only 4 files actually use data-type labels.** Key parameter tables (GHSV, temperature, BET, iodine, pressure drop, etc.) mostly lack "Data type" annotations.

## 5. Entity coverage — key gaps

- Material hubs exist for all 5 core groups (index pages) but lack explicit entity blocks: Material Class/Composition, Target Pollutants, Limitations, Safety notes, Evidence.
- **Pollutant entity pages: MISSING entirely** (NOx, CO, VOC, benzene/toluene/xylene, formaldehyde — 12 files mention BTEX but no entity pages).
- Technology entities: index pages serve as technology guides, but **none has a "When it should NOT be selected" or "How performance is tested" block** (0 pages match).
- Engineering decision pages exist: AC selection, VOC catalyst selection, AC vs Zeolite, Pt vs Pt-Pd, Plate vs Honeycomb SCR, RCO vs RTO, Adsorption vs Catalytic Oxidation. **Gap: no dedicated "How to Select an SCR Catalyst" page** (only volume calculation + plate-vs-honeycomb).

## 6. Content boundary — PASS

0 references to BBQ/hookah/shisha/camping charcoal. Site stays on industrial emission control.

## 7. FAQ blocks

5 pages have FAQ sections — all with genuine engineering value (e.g. YC-XB-C on toluene streams), not generic filler. Keep.

## 8. Conclusion

Foundation is strong. Phase 2 = fill entity gaps (pollutants section, SCR selection page), strengthen material/technology entity blocks, sweep data-type labels onto key tables, add DefinedTermSet, refresh llms.txt + home navigation. No mass article production.
