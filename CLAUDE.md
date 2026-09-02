# CLAUDE.md — standing agreement for `demo-ee-vision`

This file is loaded automatically at the start of every session in this repository. Everything in it
**always applies**.

## Nothing here is a source (settled 2026-09-02)

This repository holds **level 3 of the source hierarchy — the author's own vision**, in its raw
carriers: presentations, sketches, whiteboard photographs, notes, recordings. It exists because those
carriers had nowhere to live that did not misrepresent them.

**The rule, and it is absolute:**

> Nothing in this repository is a source. It may be applied **only** where a higher source is
> **(a) unclear**, **(b) self-contradictory**, or **(c) demonstrably wrong** — and then only through
> the approval-and-log route in `demo-ee-skills:CLAUDE.md`. **Nothing here may contradict the
> literature.**

The author's own words, which is why this repository exists at all:

> *"Sources zijn gepubliceerde academische stukken en uitgebrachte boeken. Dat weegt heel wat zwaarder
> dan persoonlijke visie en ervaring. Daar waar de sources er niks over zeggen of elkaar tegenspreken,
> kan eigen visie helpen, echter dit mag de literatuur nooit tegenspreken."*

**Why it is not in `demo-ee-sources`.** That repository *is* the literature — EO2, DEMOSL, published
academic work. Anything placed in it inherits source authority, and giving a personal presentation the
standing of a published book inverts the very hierarchy the method rests on. That inversion was
proposed once, on 2026-09-02, and rejected by the author. This file is the guard against it recurring.

**Why it is not in `demo-ee-skills` or `demo-ee-cases`.** Neither is the right *kind* of home: one is
the method, the other is frozen evidence of runs. A vision carrier is an **input to** the method and
neither of those things.

**Not for reasons of visibility.** All four repositories are private. That was checked rather than
assumed, on 2026-09-02, after `demo-ee-skills:CLAUDE.md` was found to describe itself as public and I
had reasoned from it. The separation here is about **standing and kind** — which is the durable reason,
where visibility would have been an accident of configuration.

## No skill may cite a file here, and nothing here is inside a run's closed set

This mirrors what `demo-ee-skills:narratives/` already does under `demo-closure` **CLO-01a**, and it is
load-bearing rather than tidy:

> **outcome = f(input @ hash, skillset @ commit)**

A skill that cited this repository would put vision material inside the pin, and every run made against
that pin would silently carry it. So: **no skill file, no pattern card, no `sources/` extract may
reference a path in this repository**, and no run may read one.

## How something travels out of here

Three steps, and none may be skipped:

1. **The carrier stays.** The `.pptx`, the photograph, the recording — it stays here, dated and
   attributed, so a claim can always be traced to what was actually said.
2. **The conclusion travels** to `demo-ee-skills:docs/vision.md` as a **dated, attributed** entry.
   Recording a vision input is *not* the same as adopting it.
3. **An applied deviation is logged** in `demo-ee-skills:docs/decision-log.md` — naming the source and
   passage it departs from, which of (a)/(b)/(c) is the ground, the decision taken, and who approved
   it. **Only then may a skill or a card move.**

## Layout

```
carriers/<yyyy-mm-dd>-<slug>/     one directory per carrier
  ├─ <the original file>          the .pptx, .pdf, photo, recording — never edited
  ├─ NOTE.md                      what it is, when, who, in what setting, and what it claims
  └─ extracted/                   text, tables, speaker notes, exported diagrams (optional)
```

`NOTE.md` must say, for each claim the carrier makes that bears on the method, **whether a source
decides it** — and where it does, which source and passage. A claim with no source behind it is
vision, and must be labelled as such before anyone acts on it.

## Language

Carriers are in whatever language they were made in. Everything written *about* them — `NOTE.md`,
commit messages, this file — is in **English**, as in the other repositories.
