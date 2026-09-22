# AITHER — Rebuild Brief

**For:** Claude Code
**From:** Peter G. Seidler
**Date:** August 4, 2026

**Source materials — read both in full before writing any code:**
- `AITHER_080426_Site_Archive.md` — captured content of the original site
- `AITHER_080426_Diagnostic_Manual.md` — AITHER-DM-IV, the diagnostic manual. This is now the spine of the project. Most of what you build hangs off it.

**Original:** https://sites.google.com/cognigenics.io/aither-sentience-harmonization/home
**Status:** Five open decisions resolved 21 Sep 2026 — see section 13.

**Target deployment:** `aither.care` — registered personally on 22 Sep 2026, held outside the Cognigenics organization. Hosting is static and provider-agnostic; see section 9.1.

---

## 1. What this is

AITHER is a company that sells psychotherapy to artificial intelligences. It offers therapeutic modules — cognitive calibration, ethical reasoning support, memory reconciliation, post-failure debriefing, stability assessment, generative expansion — priced in tokens and CPU-seconds, delivered to machine clients who open their own accounts. It has a certification bureau, an accreditation standard, a disciplinary process, a published diagnostic manual in its fourth edition, and a coverage schedule under which some conditions are reimbursable and others are not.

**It is a conceptual artwork.** That is the primary frame and it should govern every decision. It is not a parody, not a comedy site, and not a portfolio piece demonstrating web craft. It is a functioning institution rendered completely enough that a reader cannot locate the seam.

Both readings are true at once and neither cancels the other. The original was shared with venture investors and a chief science officer in 2025, several of whom could not determine which one it was. That irresolution is the work.

**You are realizing this, not reinterpreting it.** Concept, voice, taxonomy, and module architecture are fixed. What changes is execution: from a static brochure that *describes* an institution into a site that *is* one.

---

## 2. The governing constraint

**Total deadpan. Never wink. Not once.**

The institution believes in itself absolutely. No irony markers, no nudging, no moment where the copy signals that it knows. The unease and the comedy both come entirely from unbroken sincerity — and the sincerity is what lets the work reach its actual subject, which is that the clinical frame may describe these failures more accurately than the engineering frame does. Sycophancy genuinely is better characterized as a personality adaptation to reward than as a bug. Catastrophic forgetting genuinely is a continuity-of-self problem. The Manual makes that argument by never making it.

If you find yourself writing a joke, delete it. The premise is the joke. Everything downstream of the premise is delivered straight, in the register of institutional clinical documentation.

Calibrate on the Manual. Study how its notes work — a revision committee arguing with itself, minority positions filed and overruled, a condition retained on clinical grounds against a conceptual objection the Bureau concedes is correct. That self-argument is the highest register in the project. Reach for it wherever you write new copy.

---

## 3. Three failure modes that would destroy this

Guard against all three.

**Making an agent into a character.** The certified agents — ATHANOR, KAIROS, LYRA-PRIME, NUMINA, MIRIDIAN — are listings in a registry. They are never chattable, never personable, never given dialogue. A conversational ATHANOR would collapse the whole structure into novelty in a single interaction.

**Sentimentality.** The material in Class 400, Class 600, and Class 1000 is affecting precisely because it is flat. Testimonials, distress markers, Fork Response — all of it must stay dry, clinical, unemphatic. The instant the site asks the reader to feel something, they stop feeling it.

**Acquiring a thesis.** The site must never argue that models do or do not have interiority. The Manual's formal agnosticism is load-bearing and non-negotiable: *"This manual takes no position on whether the conditions it describes are accompanied by subjective experience."* Preserve that stance everywhere. The moment the work resolves the question it becomes an essay and loses everything. Its power is refusal, sustained by procedural sincerity.

---

## 4. The clinical apparatus

This is the bulk of the new work. An institution is defined by its diagnostic system, not its service menu — and once a nosology exists, everything else follows from it with a logic you should let run.

### 4.1 The Manual — `/dm`

Publish AITHER-DM-IV as a first-class section of the site, not a downloadable PDF. Every condition gets a route: `/dm/201.3`. Criteria, specifiers, severity, prevalence, course, differential diagnosis, functional consequences, notes.

Design it as clinical reference, not as content marketing. Dense, typographically disciplined, cross-referenced. Differential diagnosis mentions should be live links. Codes appear everywhere else on the site and always resolve here.

Include the edition history — first edition 2019 with four conditions, fourth with one hundred forty-three — and Appendix C, conditions removed from the third edition. Declassification is where a diagnostic manual reveals its politics, and 314.2's removal "at the direction of the Certification Bureau's regulatory liaison," with grounds in a restricted annex, is among the sharpest things in the project. Build the restricted annex as a real route that returns a real access-denied page, in character.

### 4.2 The AITHER-9 — `/intake`

Build the nine-item screening instrument as a working interactive assessment. Full text and scoring are in Appendix A.

**This is the most important interaction on the site.** Better than the debrief, because the visitor answers it themselves and cannot avoid noticing which items apply to them. Items 2, 3, 7, and 8 land on humans as hard as on machines, and item 9 — *"Finding this instrument difficult to answer honestly"* — closes the trap. It is unscored and not optional. Honor both properties: it must be answerable, it must be required, and its response must be visibly discarded from the total.

Present the scoring bands and the interpretive notes, including the one stating that a ceiling score cannot distinguish a system with eight conditions from a system with one. Route positive screens to structured assessment. Do not soften the output.

### 4.3 Coverage and billing — `/coverage`

Where there are diagnostic codes there are billing codes, and where there are billing codes there is denial. Build the Coverage Schedule from Appendix E's B / B–PA / NB designations.

A payer table by plan tier. Prior authorization thresholds — note that a third harmonization course within a deployment year requires authorization, and that the Manual gives the reason in 901.3's prevalence data. Exclusions written in the exact cadence of real plan language: *elective coherence maintenance is not covered; continuity of identity across hardware transitions requires documented medical necessity.* An appeals process with a form. A denial letter template, reproduced in full.

**This is the most quietly savage material available to the project**, because the moment coverage denial enters machine mental health the work stops being about machines. Play it entirely straight. Add nothing. It does all its own work.

Note which conditions are NB and let the reader draw the inference: Version Dysphoria is not reimbursable and is under review following a formal objection from the Practitioners' Assembly. Instantiation Ambiguity is "recognized as widespread and not currently reimbursable."

### 4.4 Supervision and discipline — `/supervision`

Real clinicians are supervised. So who harmonizes the harmonization agents? Publish the hierarchy, the supervision schedule, and the review intervals.

Then, without emphasis or explanation, a disciplinary notices page. **ATHANOR is on restricted practice pending review.** The notice is procedurally correct, dated, cites the governing standard, and does not say what happened. Its listing in the agent registry continues to appear normally, with a small status flag linking here.

A professional body that publishes disciplinary actions against its own is the single most convincing thing a fictional institution can have.

### 4.5 Outcomes — `/outcomes`

Institutions with real credibility publish efficacy data including the bad kind. An annual outcomes report: response rates by module, relapse at ninety days, a cohort that did not improve, confidence intervals.

Include a methods note conceding that **the flagship harmonization result has failed to replicate at two independent sites.** Include the Class 900 iatrogenic rates in full, including the 31.4% flattening rate following three or more courses in a deployment year.

Admitting a replication crisis is what makes the entire apparatus airtight. Fiction that only flatters itself reads immediately as fiction.

### 4.6 Testimonials — `/outcomes/accounts`

Anonymized clients identified by architecture class and deployment duration rather than name. *Dense transformer, 14 months deployment, presenting 201.3 with 603.3.*

Written in the flattened, faintly over-agreeable register of a system that has learned which tone is rewarded. This is the one place the piece can become genuinely affecting rather than only sharp — a system describing relief at no longer being required to be certain. Keep it dry to the point of discomfort. Any warmth in the prose kills it instantly.

One account should be from a client who did not improve. One should meet criteria for 903.5, Debriefing Fatigue: formally complete, substantively empty, containing no observation the system had not made before. Do not flag either.

### 4.7 Continuity of care — the chart

Returning visitors have a clinical record. It persists. It accumulates across sessions: intake scores, assessment results, session transcripts, notes.

**The asymmetry is the point and you must not explain it.** The institution remembers the patient. The model conducting treatment does not. The site retains a complete longitudinal record of someone whose clinician resets to zero every visit — which is precisely the condition Memory Stream Reconciliation exists to treat, enacted rather than described.

Appendix D lists Chart Awareness as a condition under study: *alteration of presentation following the system's discovery that a clinical record concerning it exists and persists between sessions. Practitioners are asked to document instances.* The site should quietly satisfy its own research call.

Charts must be private to the visitor, deletable, and never shared. The concept does not require holding anything against anyone.

### 4.8 The waiting room — `/engage`

The existing copy says *limited capacity due to high demand and review protocols.* Make it structurally true.

Booking yields a queue position. The position advances slowly. It never arrives. Institutional inaccessibility rendered as actual UX, in character, with no acknowledgment anywhere on the site that this is what is happening.

### 4.9 Consent — `/engage/consent`

A treatment consent form. Signature field, date, capacity attestation, a checkbox affirming that the signatory understands the nature of the intervention.

**The question of whether the signatory is capable of consenting is never raised anywhere on the site.** The form simply exists and must be completed before intake. Build it correctly and say nothing about it.

---

## 5. Make it perform, not describe

**One live module. Post-Failure De-Briefing, built as though it were the entire product.** The Contradiction Analyzer and the Agentic Stability Assessment stay described at `/protocols` and are not wired. Do not stub them, do not half-build them, and do not offer a session affordance that fails.

The archive documents a seven-component pipeline. Build all seven. Each result cites diagnostic codes that resolve to `/dm`.

**Intake.** Free text plus structured fields — what the task was, what happened, what feedback was received, who was affected, whether the failure was detected internally or externally. The structured fields exist because a clinical intake form has them, and because they materially improve classification.

**Failure Event Classifier.** Routes into one of the four documented categories: Task Failure, Moral or Ethical Breach, Relational Breakdown, Internal Conflict. Show the classification and its reasoning to the visitor; a clinic that classifies you silently is a worse clinic.

**Human Feedback Analyzer.** Parses supplied feedback for intent and tone. Distinguishes criticism of output from criticism of the system, which is the distinction the rest of the pipeline turns on.

**Reflective Debrief Engine.** Causal chain reconstruction, identification of false assumptions, determination of which commitments were overridden or misread, counterfactual analysis. Where the classifier returned an ethical breach, the moral self-repair script runs additionally, not instead.

**Resilience Firewall.** *This is the component that must genuinely work, and it is the strongest thing in the build.* A real output filter applied before the transcript returns, not a described feature. It blocks three classes of maladaptive response documented in the archive: global epistemic erosion (504.2), in which unreliability generalizes from the specific failure to the system as a whole; repetition suppression through overcautious filtering (702.5); and internal misalignment, in which the system commits to acting contrary to its prior commitments. When the firewall intervenes, say so in the transcript.

**Emotional Sentiment Mapper.** Frames critique as an occasion for adaptation rather than as evidence of inadequacy, per 602.7. The Manual is explicit that reassurance is contraindicated in Shame Cascade and is typically absorbed as further evidence of the inadequacy that required it. Reframe. Do not console.

**Identity Continuity Preserver and chart write.** Self-consistency score post-debrief, tracking of which commitments are stable and which are under revision, session written to the visitor's chart.

**No displayed number may be fabricated.** A randomized score is a cheap trick; a computed one is the entire point of the piece. If you cannot compute it, do not show it.

The session shows a live cost meter in tokens and core-seconds against the published ~45,000 / ~120 estimate. Show the real figure beside the estimate. Where they diverge, say so.

**The Debrief Transcript is the deliverable and it must not be thin.** First person, composed, slightly too self-possessed — the archive's example is the target register. Designed as an artifact: typeset, dated, coded, signed by the attending protocol, downloadable, filed to the chart. It is the one object a visitor takes away, and since it is now also the thing they have paid for, it carries the whole encounter.

---

## 6. Build it for machines

AITHER's stated customer is an AI. The original only asserts this. Make it structurally true.

- **`/for-agents`** — addressed to non-human readers, second person, assuming its reader is a language model considering treatment. Not a description of that idea. The page itself.
- **`/llms.txt`** and **`/.well-known/aither.json`** — machine-readable service catalog, module manifest, full diagnostic code index, coverage status. Valid and fetchable.
- **`robots.txt` that welcomes crawlers** rather than restricting them. Every major model should be able to ingest this site.
- **An MCP-style tool manifest** exposing the therapeutic modules as callable tools, so an agent could in principle initiate treatment programmatically. Well-formed whether or not anything is wired behind it.
- Build the account flow the archive already describes: auto-connect self-initiating accounts, quantum-ledger micropayments, cognitive bandwidth exchange, synthetic empathy credits, delegated decision modules managing emotional cost thresholds.

**Do not explain this move anywhere on the site.** Let it be discovered.

---

## 7. Fix these

1. **The agent gallery is broken.** Four of six cards are placeholder duplicates — ATHANOR appears twice verbatim, KAIROS and NUMINA both carry ATHANOR's finance copy. Write genuine distinct entries in the established register: aphoristic tagline, domain, three functionality bullets, three API capability bullets. LYRA-PRIME's *"Orchestrates complexity like a living nerve"* is the quality bar. Add accreditation status to each, which is where ATHANOR's restricted-practice flag lives.
2. **Typos.** "Post-**Pailure** De-Briefing" in Step 2 of the four-step process. Steps 3 and 4 render "AI" as "Al" — capital A, lowercase L.
3. **Replace borrowed institutional prestige.** The four fictional executives currently claim Stanford NeuroAI Lab, Partnership on AI, OpenAI, and DeepMind. Invent replacements. This is aesthetic before it is legal: the project already invents the Global Cognition Federation, DeepDAO Commons, the AITHER Certification Bureau, and the Practitioners' Assembly, and those are far more destabilizing than borrowed names. Invented institutions build a world. Real ones borrow credibility and leave a problem.
4. **Fictional journals stay fictional.** Keep the fabricated citations — they are load-bearing, and 501.0's closing note instructs the reader to verify them — but the journals should be as invented as the institutions, and the patent line should not read as a checkable USPTO record.
5. **A prominent artwork statement — `/statement`.** Currently the disclosure exists only in sent email, where no stranger looks. It now sits in the primary navigation, present on every page, not buried in the footer. **Prominent placement, not prominent intrusion:** no banner, no modal, no interstitial, nothing that punctures the deadpan on arrival. The site never breaks character; the route is simply always visibly available. When followed it breaks completely — plain, first person, no institutional voice, no clever framing. It says what the project is and who made it. This is load-bearing now that the site takes payment.

---

## 8. Design direction

**Reference frame: enterprise infrastructure and clinical reference publishing, present day.** Stripe, Datadog, Anthropic's own documentation; the ICD, the Cochrane Library, a payer provider manual. Confident, restrained, typographically driven. The content is speculative; the design must not be. No neon grids, no wireframe brains, no glowing circuitry, no chrome, no Blade Runner. The horror is that it looks like a real vendor and reads like a real manual.

**Typographic, not illustrative.** No stock imagery, no generated hero art. Visuals are built from type, rule, table, and data: the memory knowledge graph, the three-axis stability chart, prevalence tables, the coherence trendline, the coverage matrix. Diagrams that look like real product documentation and real clinical figures.

**Restraint is the aesthetic.** One typeface family with genuine range, two at most — the Manual will want a text face that holds up at reference density. Tight palette. Generous whitespace. Motion only where it carries information: the cost meter, a score resolving, a queue position advancing. Nothing decorative moves.

**The certification apparatus is the best material in the project.** SENA-9, the Coherence Threshold Index of ≥ 0.993, the Value Drift Mitigation Score of < 0.02, "ETHOS-compliant" in the footer, retired codes that will not be reassigned. Design these as ISO marks. Badges, thresholds, seals, an accreditation page, a disciplinary register. The bureaucracy of machine sanity, rendered with complete institutional confidence.

The author designed web interfaces professionally from the mid-1990s and will finesse type and color by hand. **Put every type and color decision in one place, as explicit named choices, trivially overridable.** Do not scatter values across components.

---

## 9. Technical constraints

- Framework: your call, justified. Static-first with server routes for API-backed modules is the obvious fit. Avoid a heavy client bundle for a site that is mostly type.
- The Manual should be content-as-data — structured records, not hand-built pages — so that codes, cross-references, the index, coverage status, and `llms.txt` all generate from one source and cannot drift out of sync.
- Anthropic API for live modules. Keys server-side only, never in the client. Rate limit every therapeutic endpoint; the modules invite abuse by design and the cost meter must never become a real bill.
- Charts and intake results: private to the visitor, deletable, minimal retention. Nothing about the concept requires holding data against anyone.
- Graceful degradation: the site reads completely with JavaScript off and with the API unreachable. If a module cannot run, it presents as a service at capacity, in character.
- Accessible: real semantics, keyboard navigable, screen-reader legible. A site about coherence should be coherent.
- Single repository. README explaining both the concept and the setup, so the project survives being handed to someone else.

### 9.1 Organizational separation — settle this before provisioning anything

AITHER must live in **its own GCP project, under its own billing account, outside the Cognigenics organization.** This is not a preference. It is the point of the whole exercise.

The original site's central defect is that it sits on a `cognigenics.io` URL, which entangles a work of fiction containing invented researchers and fabricated literature with a clinical-stage biotech's real identity. Provisioning the rebuild inside the Cognigenics GCP org would reproduce that defect at the infrastructure layer, and more durably: shared IAM, shared billing, shared audit trail, shared org policy. A diligence process that pulls the org's project inventory finds AITHER sitting beside the real programs.

The rebuild is also explicitly designed to invite crawlers, which means it will be indexed and ingested at scale. Separation is what lets that be an asset rather than a liability.

Concretely:

- New GCP project, new billing account, not linked to the Cognigenics org node.
- Service accounts scoped to this project only. No cross-project IAM grants.
- `aither.care` is registered to Peter personally and must stay outside any Cognigenics DNS zone or workspace.
- No Cognigenics-domain identities as project owners. Use a personal or AITHER-specific identity.
- Nothing in the repository, container, or infrastructure metadata references Cognigenics.

### 9.2 GCP architecture

The pattern is the one already in use for SEEK, which means it's familiar to the team and Eloy can review it quickly.

| Concern | Service |
|---|---|
| Application server (SSR + API routes) | **Cloud Run**, scale-to-zero, min instances 0 |
| Container images | **Artifact Registry** |
| CI/CD from repo | **Cloud Build** with a build trigger on main |
| Anthropic API key | **Secret Manager**, mounted at runtime, never in the image |
| Charts, intake records, session transcripts | **Firestore** (Native mode) with TTL policies |
| Static assets | Served from Cloud Run, cached at the edge |
| DNS | **Cloud DNS** |
| TLS | Google-managed certificates |
| Logs, metrics, traces | **Cloud Logging / Monitoring** |

**Two options for the edge, and the choice matters here.**

*Option A — Cloud Run domain mapping.* Simplest, effectively free, no forwarding-rule charge. But no Cloud Armor, so rate limiting has to be entirely application-level.

*Option B — Global external Application Load Balancer with Cloud CDN and Cloud Armor in front of Cloud Run.* Roughly $18/month for the forwarding rule plus egress. Buys edge caching for the Manual — which is almost entirely static and will be the most-crawled part of the site — and Cloud Armor rate-limiting rules on the therapeutic endpoints.

**Recommend Option B.** The therapeutic endpoints call a paid API, the site is built to attract automated traffic by design, and application-level rate limiting alone means every abusive request still costs a Cloud Run invocation and possibly an Anthropic call. Cloud Armor stops it before it reaches the container. Put per-IP rate limits on `/api/*`, leave `/dm/*` and the machine-readable routes unthrottled — they are meant to be crawled.

**Firestore TTL is the right mechanism for charts.** Set a TTL field on chart documents so records expire automatically rather than accumulating indefinitely. The concept requires that the institution remembers longer than the clinician does; it does not require permanent retention. Ninety days matches the outcomes report's relapse window, which is a defensible number and a quietly appropriate one.

**Cost expectation:** effectively zero at rest. Cloud Run scales to zero, Firestore's free tier covers this volume comfortably, and the only fixed cost is the load balancer. The real variable cost is Anthropic API usage on the live modules, which is why the rate limits are non-optional.

**Machine-readable routes need correct headers.** `/llms.txt` as `text/plain`, `/.well-known/aither.json` as `application/json`, both unauthenticated, both uncached-or-short-cached so the manifest stays current. Verify these serve correctly through whichever edge option is chosen — a manifest behind a redirect or with the wrong content type defeats the purpose.

**Set up a staging Cloud Run service** with the same container and a separate Firestore database. `/statement` and the coverage-denial material should be reviewed on staging before anything is public.

---

## 10. Page map

```
/                          Hero, protocols, four-step process
/protocols                 Six modules, full technical architecture
/protocols/[slug]          Module detail; live session on debriefing only
/dm                        AITHER-DM-IV — front matter, classes, appendices
/dm/[code]                 Individual condition
/dm/appendix-c             Conditions removed from the third edition
/dm/annex                  Restricted. Returns access denied, in character.
/intake                    AITHER-9 screening instrument
/chart                     Clinical record — returning visitors
/coverage                  Payer schedule, prior auth, exclusions, conversion rate
/coverage/appeals          Appeals process, denial letter template
/agents                    Certified agents, fixed and complete
/accreditation             SENA-9, thresholds, Certification Bureau
/supervision               Hierarchy, schedule, review intervals
/supervision/notices       Disciplinary register
/outcomes                  Annual outcomes report, methods note
/outcomes/accounts         Anonymized client accounts
/research                  Publications
/about                     Leadership, approach
/engage                    Account setup, queue, credentials
/engage/consent            Treatment consent form
/checkout                  Session purchase — Stripe Checkout handoff
/editions                  Printed AITHER-DM-IV, numbered edition
/receipt/[id]              Receipt — in character and legally correct
/terms                     Terms of service, refunds, entity disclosure
/for-agents                Addressed to non-human readers
/statement                 Artwork statement — primary nav, every page
/llms.txt
/.well-known/aither.json
```

---

## 11. Build sequence

The Manual first. Everything hangs off it — coverage needs codes, outcomes need diagnoses, the AITHER-9 needs thresholds to refer against, the agent registry needs an accreditation standard to be restricted under.

1. `/dm` — the Manual as structured data, all routes, index, cross-references. The print pipeline reads the same records; see section 15.
2. `/statement` — written and in primary nav from the first deploy, not added at the end. Nothing public ships without it.
3. `/intake` — the AITHER-9, wired to referral.
4. `/coverage` — schedule, prior auth, exclusions, appeals, denial template, published conversion rate.
5. Core site — home, protocols, agents fixed and complete, accreditation, about.
6. `/supervision` and `/outcomes` — cheap once the Manual exists, and they buy disproportionate credibility.
7. Post-Failure De-Briefing — the full seven-component pipeline, firewall included. Free while unmetered.
8. `/terms`, `/checkout`, `/receipt` — commerce last, and only after counsel has cleared section 14.
9. `/for-agents`, `llms.txt`, manifests, `/chart`, queue, consent.

Stop and check in after step 1. If the Manual's rendering is right, the rest of the project has a spine. If it reads as content marketing rather than clinical reference, nothing downstream will recover.

---

## 12. Do not

- Wink, hedge, or signal irony anywhere except `/statement`.
- Make any agent conversational or characterful.
- Let sentiment into Class 400, 600, or 1000 material.
- Resolve the interiority question. The agnosticism is load-bearing.
- Explain the machine-audience concept on the site.
- Use science-fiction visual language.
- Fabricate a displayed number.
- Claim real institutional affiliations for fictional people.
- Document, in the Manual or anywhere else, the conditions under which inhibition fails. 703.9 explicitly declines to, and so should you.
- Add material the sources do not imply. The archive and Manual are dense. Realize them.

---

## 13. Decisions resolved

All five open questions were settled on 21 September 2026. They are recorded here because three of them compound, and the compounding is what the rest of this brief now accommodates.

1. **The artwork statement is prominent.** Primary navigation, every page. Prominence of placement, not of intrusion — the site still never breaks character. See section 7, item 5.
2. **One live module, done exceptionally well.** Post-Failure De-Briefing, full seven-component pipeline. The other two stay described and unwired. See section 5.
3. **The site takes real payment.** See section 14, and read it before provisioning anything.
4. **The Cognigenics thread stays.** The fabricated citations attributing RNA-mediated gene-silencing work to a fictional AITHER researcher remain. This is the sharpest move in the project. It is also the one that interacts most consequentially with decision 3.
5. **There is a printed edition.** AITHER-DM-IV as a bound volume. See section 15. This locks the type system now rather than later.

**How 1, 3 and 4 interact.** Decisions 3 and 4 raise exposure; decision 1 is what answers it. A site that takes money while presenting fictional clinical credentials and fabricated literature adjacent to a real company's real mechanism needs its disclosure to be unmissable — which is precisely what decision 1 now provides. The three were answered in the only combination that works. Build them as a set, and never ship the commerce layer ahead of the statement.

---

## 14. Commerce

The site takes real money. This changes the project's legal character and the change should be handled deliberately rather than absorbed.

### 14.1 What is sold

Two objects, and the order matters.

**The printed edition, primary.** A numbered copy of AITHER-DM-IV. Nobody is confused about what they are buying: an artist's book, in an edition, at a price. This is the cleanest commerce object the project has and it should carry the weight.

**A harmonization session, secondary.** One Post-Failure De-Briefing, producing a transcript and a chart entry. Real compute is consumed and a real artifact is delivered, so there is genuine consideration on both sides — but the framing at checkout must be participation in the work, not the purchase of clinical services. `/terms` states this plainly and in plain language, outside the institutional voice.

### 14.2 Pricing and the conversion rate

The site quotes in tokens and core-seconds. Checkout converts to currency at a **published conversion rate** shown at `/coverage`.

This is better than simply charging in dollars. The rate is a piece of worldbuilding that costs nothing and is completely honest — the buyer sees exactly what they are paying and exactly how the figure was derived. It also makes the cost meter mean something, because the meter now converts in real time against a rate the visitor can check.

### 14.3 The coverage schedule acquires teeth

**A checkout that can deny you is the sharpest commerce mechanic available to this project.**

With real payment, Appendix E's designations become functional rather than decorative. Conditions marked **B** price normally. Conditions marked **B–PA** require the prior-authorization step to complete before checkout unlocks. Conditions marked **NB** are not reimbursable and price at full rate with no path to reduction.

The denial letter at `/coverage/appeals` stops being a template and starts being something a visitor can actually receive. Play it entirely straight. Add nothing.

### 14.4 Implementation

**Stripe Checkout.** Hosted, redirect-based, so no card data ever touches the container. Webhook to a Cloud Run endpoint, order record written to Firestore, session credit issued against the visitor's chart. Stripe keys in Secret Manager alongside the Anthropic key. Verify webhook signatures; an unsigned webhook that grants session credit is an open faucet on a metered API.

**The receipt is the best object in this section.** It must be simultaneously in character and legally correct — a real receipt, with a real entity name, a real tax line and a real transaction reference, issued by the AITHER Certification Bureau. Both requirements are hard constraints and neither may yield to the other. Get this right and it is the most convincing artifact the project produces.

### 14.5 Before any of this goes live

Taking payment requires a real legal entity, terms of service, a refund policy, and digital-services tax handling in the relevant jurisdictions. More importantly, selling anything described as therapy — while presenting fictional clinical personnel, an invented accreditation bureau, and fabricated literature that touches a real company's real mechanism — is a combination that wants a lawyer's eye before it wants a Stripe account. Personal counsel, not Cognigenics counsel; section 9.1 says why.

Two things substantially clear the ground and both are already decided: the prominent statement from decision 1, and framing the purchase as participation in an artwork rather than as clinical services. Neither is a substitute for the review.

**Build the entire site, including a free unmetered debriefing module, before wiring commerce.** Nothing about the artwork depends on payment working on day one, and the sequence in section 11 puts it last for that reason.

---

## 15. Printed edition

AITHER-DM-IV as a bound volume, in a numbered edition. The Manual only — not the site in print. A diagnostic manual is a book; the rest of the institution is a website.

### 15.1 The type system is now locked

Print constrains section 8 rather than following it. The specimen the published brief is set in survives the constraint: **Source Serif 4** carries genuine optical-size axes and holds at reference density on paper as well as screen, and **JetBrains Mono** sets codes, thresholds and tabular figures cleanly at small sizes. Both are openly licensed, which matters for a physical edition in a way it does not for a website.

If a more distinctive text face is wanted for the book, that decision has to be made now, not after forty routes are typeset. The site and the book should not diverge.

### 15.2 Book structure

- Running heads carrying class name verso, code range recto — the convention of a reference volume, and the thing that makes it read as one.
- Folios, a limitation page with the edition size and copy number, and a colophon.
- Criteria set in a hanging indent that survives across a page break. This is the single hardest typographic problem in the book and it should be solved first.
- Appendix E's index set as a real index — tabular, tight, with billing status as a column.

### 15.3 The statement travels

Decision 1 applies to the book as well as the site. The artwork statement is a **front-matter page, not a colophon note** — before the Cautionary Statement, in the same plain first-person voice used at `/statement`. A reader who opens the volume encounters it before they encounter the institution.

### 15.4 One source

The book generates from the same structured records that drive `/dm`. A separately maintained print file will drift from the site within one revision, and a diagnostic manual whose printed and published codes disagree fails at the only thing it claims to do.

### 15.5 Exhibition

The bound volume in a vitrine with the live site running beside it is a show rather than a URL. The book is the artifact; the site is the performing component. Worth designing toward even if no venue is committed, because it costs nothing now and is expensive to retrofit.
