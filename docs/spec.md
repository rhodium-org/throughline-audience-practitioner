# Audience — Practitioner reader — throughline source

This document is **generated from the graph** by `tl docs`; `tl docs --check` gates
it in CI. The prose headings are hand-owned — everything between `tl:*` markers is
injected from the YAML items, so the published spec can never drift from the graph.

This source is the **audience axis** for one level: a **practitioner** (working,
applied) reader with working familiarity but not deep specialist expertise. It governs
how the writing is *calibrated* to the reader's expertise — assumed knowledge,
terminology, depth, orientation and examples — not universal readability, spelling,
punctuation, register, purpose, medium or brand voice, each of which is its own
throughline source. Audience levels are mutually exclusive: **expert**,
**practitioner** and **general** are sibling sources and a consumer composes exactly
one under the `audience` namespace. Every principle is a `user_requirement`; every rule
is a `system_requirement` that `implements` its principle. The throughline UIDs are
this source's own and immutable — a consumer cites a rule as `audience:SR-0001`.

It carries
<!-- tl:count type == 'user_requirement' -->
5
<!-- tl:end --> principles and
<!-- tl:count type == 'system_requirement' -->
10
<!-- tl:end --> rules.

## Purpose

<!-- tl:item INT-0001 -->
**INT-0001 — Text is pitched for a practitioner reader** — `intent`, status `proposed`

> A practitioner has working familiarity with the field but not deep specialist expertise. They know the everyday basics and common vocabulary, so the writing can build on those, but it should explain the deeper theory, give the practical depth needed to apply the subject, and orient to the task rather than the fundamentals. This axis governs how the writing is calibrated to the reader's expertise — assumed knowledge, terminology, depth and orientation — not universal readability, spelling, register or purpose, each of which is a separate source. Audience levels are mutually exclusive: a consumer composes exactly one of the expert, practitioner or general sibling sources.

**source_ref**: TBS Audience — Practitioner reader
<!-- tl:end -->

## 1. Assume working familiarity, not deep expertise

<!-- tl:item UR-0001 -->
**UR-0001 — Assume working familiarity, not deep expertise** — `user_requirement`, status `proposed`

> Build on the everyday basics the reader already works with, but do not assume specialist theory.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Practitioner reader — Assumed prior knowledge
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0001' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0001 | system_requirement | proposed | Assume the everyday basics and common workflow, but not the underlying theory |
| SR-0002 | system_requirement | proposed | Use common acronyms, processes and roles freely; introduce specialist ones |
<!-- tl:end -->

## 2. Use common terms of the trade; explain the specialist ones

<!-- tl:item UR-0002 -->
**UR-0002 — Use common terms of the trade; explain the specialist ones** — `user_requirement`, status `proposed`

> Use the field's everyday working vocabulary freely, but explain deeper specialist or theoretical terms.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Practitioner reader — Terminology and jargon
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0002' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0003 | system_requirement | proposed | Use the field's common working vocabulary without defining it |
| SR-0004 | system_requirement | proposed | Explain deeper specialist or theoretical terms in plainer working language |
<!-- tl:end -->

## 3. Give practical depth — enough to apply, not the full theory

<!-- tl:item UR-0003 -->
**UR-0003 — Give practical depth — enough to apply, not the full theory** — `user_requirement`, status `proposed`

> Give the depth needed to apply the subject correctly, and leave the deeper theory out.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Practitioner reader — Depth and detail
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0003' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0005 | system_requirement | proposed | Include the detail needed to apply the subject correctly in practice |
| SR-0006 | system_requirement | proposed | Leave out theoretical depth that does not change what the reader does |
<!-- tl:end -->

## 4. Orient to the task, not the fundamentals

<!-- tl:item UR-0004 -->
**UR-0004 — Orient to the task, not the fundamentals** — `user_requirement`, status `proposed`

> Open on the practical task and treat the routine context as known.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Practitioner reader — Context and orientation
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0004' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0007 | system_requirement | proposed | Open with the practical situation or task, not first-principles background |
| SR-0008 | system_requirement | proposed | Assume the routine context is known, but state anything task-specific |
<!-- tl:end -->

## 5. Use realistic worked examples from practice

<!-- tl:item UR-0005 -->
**UR-0005 — Use realistic worked examples from practice** — `user_requirement`, status `proposed`

> Anchor points in realistic scenarios and the tools and procedures the reader uses day to day.

*Derives from:* INT-0001

**source_ref**: TBS Audience — Practitioner reader — Examples and reference points
<!-- tl:end -->

<!-- tl:table attrs.get('principle') == 'UR-0005' -->
| UID | Type | Status | Title |
|---|---|---|---|
| SR-0009 | system_requirement | proposed | Illustrate with realistic scenarios from day-to-day practice |
| SR-0010 | system_requirement | proposed | Relate to the common tools, procedures and cases the reader works with |
<!-- tl:end -->
