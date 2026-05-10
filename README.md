# DIKWP SemanticJustice OS

**DIKWP SemanticJustice OS** is an open-source, offline-first semantic-space justice scaffold. It transforms legal norms, facts, evidence, and stakeholder narratives into DIKWP semantic ledgers, then produces a non-adjudicative explanation report for human legal review.

It is designed for legal aid intake, administrative dispute preparation, public-interest clinics, compliance teams, court technology research, and explainable AI & law education.

## Core idea

Traditional legal AI often stays in a conceptual or symbolic layer: rules, elements, citations, and predicted outcomes. DIKWP semantic-space justice adds a structured semantic layer:

- **D / Data**: raw facts, sources, claims, actors, timelines.
- **I / Information**: differences, relations, contested points, procedural gaps.
- **K / Knowledge**: legal elements, norms, precedents, duties, burden of proof.
- **W / Wisdom**: fairness, due process, proportionality, equity, dignity, human impact.
- **P / Purpose**: the intended legal transformation from input state to target state.
- **R / Reliability**: source custody, support scope, uncertainty, kill conditions.

## What it does

- Builds a **DIKWP normative content graph** from laws, rules, policies, and legal elements.
- Builds a **DIKWP stakeholder cognition graph** from party narratives, goals, fears, constraints, and perceived injustice.
- Compares the two through a **DIKWP×DIKWP semantic alignment matrix**.
- Flags cognitive gaps, evidence gaps, due process issues, proportionality concerns, and purpose misalignment.
- Produces a human-readable **semantic justice report**, issue list, legal review checklist, and explanation pack.

## What it does not do

This project does **not** provide legal advice, legal representation, outcome prediction, verdict generation, sentencing, automated adjudication, or any substitute for qualified legal professionals. It is a semantic preparation and audit scaffold.

## Quickstart

```bash
pip install -e .
semanticjustice analyze examples/sample_admin_case.json --out outputs/demo
semanticjustice static-audit src --out outputs/demo/static_boundary_audit_report.json
```

Optional local UI:

```bash
pip install -e .[app]
streamlit run src/dikwp_semanticjustice/app.py
```

## Demo outputs

- `semantic_justice_report.json`
- `dikwp_normative_graph.json`
- `dikwp_stakeholder_graph.json`
- `semantic_alignment_matrix.csv`
- `justice_issue_queue.csv`
- `legal_review_checklist.md`
- `party_explanation_pack.md`
- `static_boundary_audit_report.json`

## Governance boundary

Use this system only for intake, education, legal aid preparation, human legal review support, evidence organization, and explainability research. Do not use it for automated legal decisions, enforcement, sentencing, deportation, denial of benefits, criminal risk scoring, surveillance, or legal determinations without human professionals and jurisdiction-specific validation.
