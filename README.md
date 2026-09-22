# AITHER — complete handoff

Conceptual artwork by Peter G. Seidler. A company that sells psychotherapy to artificial
intelligences: diagnostics, therapeutic protocols, a certification bureau, and a diagnostic
manual in its fourth edition.

**Domain:** `aither.care` — registered personally, 22 Sep 2026.
Held outside the Cognigenics organization. That separation is deliberate and load-bearing.

---

## Files

| File | What it is |
|---|---|
| `index.html` | **The website.** One self-contained file, 68 routes, fonts embedded. No build step, no backend, no dependencies. Open it directly, or drop it on any static host as `index.html`. |
| `robots.txt` | Permissive. The site is designed to be crawled and ingested. |
| `docs/AITHER_080426_Rebuild_Brief.md` | Build brief. Concept, constraints, design direction, page map, build sequence, commerce, printed edition. Fifteen sections. |
| `docs/AITHER_080426_Diagnostic_Manual.md` | AITHER-DM-IV source text. Ten classes, 143 conditions, appendices A–F. |
| `docs/AITHER_080426_Site_Archive.md` | Faithful capture of the original 2025 Google Site. Kept unedited as a record. |
| `comps/comp-heading-faces.html` | Type comparison. Switcher across seven heading faces, live. |
| `comps/comp-inter-tight.html` | Whole site set in Inter Tight. |
| `comps/comp-google-sans.html` | Whole site set in Google Sans Flex. |

The three comps are for decision-making, not for publishing. They load fonts over the network.

---

## The site

**Institutional routes** — home, protocols, agents, accreditation, about, statement, checkout,
supervision, disciplinary register, outcomes, client accounts, publications, coverage, appeals,
treatment consent, AITHER-9 screening.

**Manual routes** — 42 conditions across ten classes, front matter, appendices A–F, index,
restricted annex. One shell; the classification sidebar appears on Manual routes.

**Working:** hash routing, AITHER-9 live scoring, nine machine-facing session switches driving
a live cost model, digital readouts, three QR codes generated from current switch state,
per-protocol QR codes, scrolling session trace, queue countdown, footer mark tooltips, Figure 1.

**Not wired:** payment. The button hands off to an in-character notice and charges nothing.

---

## Type

- Text — IBM Plex Serif (embedded, subsetted)
- Mono — JetBrains Mono (embedded, subsetted)
- Headings — currently the text face at bold. See the comps for alternatives.

Source Serif 4 was the original intent and was unavailable at build time. Supplying the font
files would allow a swap; the stacks are aliased as `'AITHER Serif'` and `'AITHER Mono'` so
only the `@font-face` block changes.

---

## Decisions settled 21 Sep 2026

1. Artwork statement is **prominent** — primary navigation, every page.
2. **One** live therapeutic module: Post-Failure De-Briefing, built deeply.
3. The site **takes real payment** — not yet implemented; counsel first.
4. The **Cognigenics thread stays** — fabricated citations referring to RNA interference.
5. There is a **printed edition** of the Manual. This locks the type system.

---

## Open, in priority order

1. ~~Verify the Stanford Encyclopedia links in Appendix F.~~ **Done, 22 Sep 2026.** Of the
   twenty-two citations written from memory, two slugs were dead (`entries/functions/`,
   `entries/moral-status-full/`) and three had inaccurate titles (`health-disease`,
   `mental-disorder`, `social-construction-naturalistic`). `entries/functions/` was swapped for
   the real entry on the same topic, `entries/teleology-biology/` (Teleological Notions in
   Biology); `entries/moral-status-full/` was dropped as a dead duplicate of
   `entries/grounds-moral-status/`, already cited two lines above it. The three mistitled
   citations were corrected to the SEP entries' actual titles. Twenty-one links now resolve to
   the entries they claim to be.
2. **Delete or unpublish the original Google Site** at `sites.google.com/cognigenics.io/…`
   It is public, has no artwork statement, and is the last thing tying AITHER to the company.
   Its full text is preserved in the archive file; nothing is lost.
3. **Counsel before the payment layer goes live.** Personal counsel, not company counsel.
   See brief section 14.5.
4. **Host it.** Static file, any provider. Cloudflare Pages or Firebase is ten minutes.
   Use a standalone project outside the Cognigenics org — brief section 9.1.
5. Decide the heading face from the comps, and whether the Manual wants a printed edition
   built from the same structured records.

---

## Starting a fresh conversation

Paste this README into the first message. It carries the state — concept, decisions, constraints,
what is built and what is not. The brief carries the rest.
