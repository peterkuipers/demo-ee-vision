# OMEGA including Green and Blue

|  |  |
|---|---|
| **carrier** | `OMEGA_including_green_and_blue.pptx`, 23 slides |
| **author** | Peter Kuipers |
| **received** | 2026-09-02 |
| **setting** | a working presentation for the case *Digital Product Department (MAM)*; the speaker notes reference DGE throughout |
| **subtitle on slide 1** | *"Retrieve the ontology on narrative with AI"* |
| **carries client content** | **yes** — MAM and DGE. This is why the repository is private |

---

## What it claims, and what decides each claim

**The column that matters is the last one.** A claim with no source behind it is **vision**, and must be
treated as vision no matter how well argued it is. Checked against `demo-ee-skills:sources/` at
`9122e329`.

| # | claim | where in the deck | decided by |
|---|---|---|---|
| 1 | For each original transaction kind the **informational** layer generates a case-kind producer, a case-kind rememberer, and an existence-law calculator — one per law, *"for 1 to n"* | slides 7, 10 | **vision.** Nothing in `sources/` states this generative rule |
| 2 | For each case kind the **documental** layer generates storing, retrieving and displaying — *"however there are much more"* | slides 11, 12 | **vision.** Same |
| 3 | A **canonical roster of transactor types** per OMEGA category: Ω · 1 … 8, with role name and product kind | slides 8, 9 | **THE BOOK — corrected 2026-09-03.** This row read *"vision. The roster is not in EO2"*, and that was wrong. The roster is a TABULATION of the four reference CSDs: Fig. 10.14 (assembler / assembler / acquirer), **Fig. 10.15 (container content releaser · transporter · unloader, and container picker · mover · discharger)**, Fig. 10.16 (**ownership transfer completer**, with preparer · payer · deliverer), Fig. 10.17 (usufruct case concluder · resource seizer · resource releaser) and Fig. 10.20 (agreement starting · ending). And EO2 prints the roster's own three columns itself: **the TPT beside Fig. 10.17 is `transaction kind | product kind | executor role`**, with `TK02 resource seizing / PK02 the resource of [usufruct case] is seized / AR02 resource seizer` — the deck's row 4, verbatim. What is the deck's is the *arrangement*: one grid, all four categories, numbered Ω · 1 … 8, and the general nouns carried down from the root to the children |
| 4 | **Transporting and Storing has two levels** — content released / transported / unloaded, receptacle picked / moved / discharged | slides 2, 5, 9 | **THE BOOK — corrected 2026-09-03.** **Fig. 10.15 draws both levels**, and with these very roles: `07 container content releaser`, `08 container content transporter`, `09 container content unloader`, and beneath the transporter `21 container picker`, `22 container mover`, `23 container discharger`. §10.3.3.2 states it in prose too: *"transporting the container may be decomposed into picking the container and putting it on a truck, driving the truck to the premises of IES, and taking the container from the truck."* So this is not vision, and it does not stand against PM-21 — **PM-21's caution is what must be re-read**, since it cites the same GloLog move |
| 5 | **The payer is normally outside the focus** | slide 4, in words and in the grey box on the diagram | **THE BOOK — corrected 2026-09-03.** The extract in `sources/` does not settle it, but **the book's own figure does: Fig. 10.16 draws `03 sale payer` GREY**, and grey is DEMOSL-4.12.1's marking for an element outside the focus. §10.3.3.3 gives the reason in words: payments *"occur if the ownership transfer crosses the border of economic (or business) units. Inside such a unit, there are no payments for services"* — so the payer is a party across the boundary. The deck's grey box is the book's grey box |
| 6 | The **usufruct agreement's starting and ending belong to Obtaining Usufruct**, drawn as three roots with three CTARs, joined to the case concluder by dotted (access) lines | slides 2, 6, 9 | **the book.** EO2 §10.3.3.4 introduces them inside obtaining usufruct as *"two additional processes"*. The deck agrees with the source; it does not decide it |
| 7 | A **PSD drawing law**: compact tree of responsibility bands on the left, aligned with stretched disks on the right; the product kind sits **on** the disk, splitting the order phase from the result phase; the transaction-kind name above or below | slide 22, stated in prose | **mixed.** PM-15's responsibility areas are book-derived and `demo-render-psd` currently contradicts them outright — that part is an internal defect. The detailed layout is DEMOSL's territory and **has not been checked against DEMOSL-4** |
| 8 | The **CTP with sixteen numbered action-rule slots** `XX.1 … XX.16`, carrying all six revocations including `rvdc` and `rvrj` | slide 10, first image | **mixed.** The pattern and its six revocations are DEMOSL (and the PK line's own position, DISC-011). The **numbering** is the deck's |
| 9 | **CC intangible** is a decision or judgement — specifically *"where the executor could decide based on the existence rules, however he is forced to get approval of a higher management level"* | slide 3, speaker notes | **vision**, and a sharper discriminator than anything currently in the library |
| 10 | **ToO intangible** = owner rights, shares, bitcoin, gold. **OU intangible** = SaaS, streaming | slides 4, 6, notes | **the book, exemplified.** Table 10.2's own wording for those cells |
| 11 | **TS intangible** *"does exist, however it will be a documental transaction kind"* | slide 5, speaker notes | **vision, and it contradicts the source.** Table 10.2 marks that cell `* not applicable *`, and the deck's own table on slide 2 reproduces that marking. Applying it needs the (a)/(b)/(c) route and an explicit ground |
| 12 | The **car exchange** — Ahmed and Mohamed, each buying the other's car and paying with his own; and the variant where payment is obtaining usufruct of a pool and gym under a use agreement | slides 15–21 | **an example, not a claim.** It is a worked case and a candidate for `demo-ee-cases` |

## The open question the deck itself poses

Slide 19, speaker notes: *"The question is, ontological is TK4 sale preparing different than TK4
purchase preparing?"* Left unanswered in the carrier, and worth carrying into the case if the car
exchange becomes one.

## What has been done with it so far

A nine-point reading was produced on 2026-09-02 and published as an artifact. Four of those points
were first mislabelled as source-backed corrections when the evidence then in hand was the deck
alone; that correction is in `demo-ee-skills:docs/decision-log.md`.

**On 2026-09-03 the labelling was corrected AGAIN, the other way, and this is the more serious of
the two errors.** On the author's instruction — *"The roster is not in EO2 is not correct, they are
part of OMEGA theory, look it up in the book please"* — rows 3, 4 and 5 were checked against the
figures rather than against the `sources/` extracts, and all three turn out to be **the book**:
Fig. 10.15 draws the two-level transporting tree with its role names, Fig. 10.16 draws the payer
grey, and the TPT beside Fig. 10.17 prints the roster's own three columns.

**The lesson, written down because it caused both errors.** `sources/eo2/extracts/` holds prose
extracts; **the reference models live in the FIGURES**, and a figure cannot be grepped. Searching
the extracts and finding nothing is not evidence that the book says nothing — it is evidence that
nobody has extracted that figure yet. Any claim about a reference model must be checked against the
figure in `demo-ee-sources:Enterprise_Ontology_Edition2.pdf` before it is called vision.
