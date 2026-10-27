# SECAV-O

Software Engineering Coaching and AI Validation Ontology / Coaching Lifecycle, Planning, Risk, Alignment and Ethics Artifacts

> Current version: v0.3.0
>
> SECAV-O is an ontology-supported framework for software-engineering coaching, observable evidence, AI-assisted validation, human review, competency development, and governance.

This repository extends the core SECAV-O ontology with a coaching governance layer covering:

- team coaching from inception through launch and onboarding
- annual and sprint planning
- risk management with preventive and corrective actions
- institutional alignment and project planning participation
- ethics and coach accountability
- quality advocacy, dissent, and escalation

## Table of contents

- [Overview](#overview)
- [Repository structure](#repository-structure)
- [Core ontology and validation](#core-ontology-and-validation)
- [Governance and operating model](#governance-and-operating-model)
- [Templates and examples](#templates-and-examples)
- [Learning exercises](#learning-exercises)
- [Citing the project](#citing-the-project)
- [License](#license)

## Overview

SECAV-O connects software-engineering activities, artifacts, competencies, evidence, AI assistance, human validation, and coaching interventions in a single conceptual model. The framework is designed to make coaching practices traceable to observable evidence and to support explicit review, planning, governance, and quality decisions.

The repository includes:

- the core ontology and SHACL validation rules
- governance guides for coaching operations and quality assurance
- templates for planning, risk management, and assessment
- worked examples and machine-readable schemas
- learning exercises and example records

## Repository structure

```text
SECAV-O/
├── CHANGELOG.md
├── CITATION.cff
├── LICENSE
├── readme.md
├── coaching-governance/
│   ├── docs/
│   ├── glossary/
│   └── guides/
├── examples/
├── exercises/
├── ontology/
├── pilot/
├── schemas/
├── templates/
├── validation/
└── .github/
```

## Core ontology and validation

The ontology layer is the backbone of the framework.

- [`ontology/secav-o.ttl`](ontology/secav-o.ttl) — core SECAV-O ontology
- [`ontology/secav-o-coaching-governance-extension.ttl`](ontology/secav-o-coaching-governance-extension.ttl) — coaching-governance extension
- [`validation/secav-o.shacl.ttl`](validation/secav-o.shacl.ttl) — SHACL validation for the core ontology
- [`validation/secav-o-coaching-governance.shacl.ttl`](validation/secav-o-coaching-governance.shacl.ttl) — validation for the governance extension

These files model engineering activities, artifacts, competencies, evidence, measurement, coaching interventions, review outcomes, AI assistance, and human validation.

## Governance and operating model

The governance material defines how coaching works in practice across teams, plans, risks, ethics, and quality decisions.

### Operating model documents

- [`coaching-governance/docs/coaching-cycle.md`](coaching-governance/docs/coaching-cycle.md)
- [`coaching-governance/docs/team-coaching-lifecycle.md`](coaching-governance/docs/team-coaching-lifecycle.md)
- [`coaching-governance/docs/project-planning-participation.md`](coaching-governance/docs/project-planning-participation.md)
- [`coaching-governance/docs/institutional-alignment.md`](coaching-governance/docs/institutional-alignment.md)
- [`coaching-governance/docs/metrics-model.md`](coaching-governance/docs/metrics-model.md)
- [`coaching-governance/docs/competency-growth-scale.md`](coaching-governance/docs/competency-growth-scale.md)
- [`coaching-governance/docs/ontology-alignment.md`](coaching-governance/docs/ontology-alignment.md)

### Governance guides

- [`coaching-governance/guides/minimum-quality-criteria.md`](coaching-governance/guides/minimum-quality-criteria.md)
- [`coaching-governance/guides/robust-process-criteria.md`](coaching-governance/guides/robust-process-criteria.md)
- [`coaching-governance/guides/requirements-inspection.md`](coaching-governance/guides/requirements-inspection.md)
- [`coaching-governance/guides/peer-review-sessions.md`](coaching-governance/guides/peer-review-sessions.md)
- [`coaching-governance/guides/formal-inspections.md`](coaching-governance/guides/formal-inspections.md)
- [`coaching-governance/guides/risk-management.md`](coaching-governance/guides/risk-management.md)
- [`coaching-governance/guides/defect-tracking.md`](coaching-governance/guides/defect-tracking.md)
- [`coaching-governance/guides/code-review-best-practices.md`](coaching-governance/guides/code-review-best-practices.md)
- [`coaching-governance/guides/ai-assisted-code-review.md`](coaching-governance/guides/ai-assisted-code-review.md)

### Glossary

- [`coaching-governance/glossary/glossary.md`](coaching-governance/glossary/glossary.md)

## Templates and examples

### Templates

The repository includes reusable planning, assessment, and governance templates:

- [`templates/annual-coaching-plan.md`](templates/annual-coaching-plan.md)
- [`templates/coaching-sprint-plan.md`](templates/coaching-sprint-plan.md)
- [`templates/sprint-retrospective.md`](templates/sprint-retrospective.md)
- [`templates/team-launch-coaching-plan.md`](templates/team-launch-coaching-plan.md)
- [`templates/member-preparation-checklist.md`](templates/member-preparation-checklist.md)
- [`templates/new-member-onboarding.md`](templates/new-member-onboarding.md)
- [`templates/risk-register.csv`](templates/risk-register.csv)
- [`templates/defect-log.csv`](templates/defect-log.csv)
- [`templates/competency-trend.csv`](templates/competency-trend.csv)
- [`templates/coach-committee-charter.md`](templates/coach-committee-charter.md)
- [`templates/coach-ethics-acknowledgement.md`](templates/coach-ethics-acknowledgement.md)
- [`templates/engineer-development-record.md`](templates/engineer-development-record.md)

### Worked examples

- [`examples/design-review.ttl`](examples/design-review.ttl)
- [`examples/java-standard-deviation-exercise.ttl`](examples/java-standard-deviation-exercise.ttl)
- [`examples/example-coaching-sprint.yaml`](examples/example-coaching-sprint.yaml)
- [`examples/example-team-launch-and-onboarding.yaml`](examples/example-team-launch-and-onboarding.yaml)
- [`examples/example-quality-planning-escalation.yaml`](examples/example-quality-planning-escalation.yaml)
- [`examples/example-engineer-development-record.md`](examples/example-engineer-development-record.md)

### Schemas

- [`schemas/project-planning-governance.schema.json`](schemas/project-planning-governance.schema.json)
- [`schemas/team-coaching-lifecycle.schema.json`](schemas/team-coaching-lifecycle.schema.json)
- [`schemas/coaching-sprint.schema.json`](schemas/coaching-sprint.schema.json)

## Learning exercises

The repository includes structured learning exercises to practice engineering and review skills with explicit competency targets and deliverables.

- [`exercises/java-standard-deviation/`](exercises/java-standard-deviation/)
- [`exercises/java-standard-deviation/README.md`](exercises/java-standard-deviation/README.md)

## Changelog

See [`CHANGELOG.md`](CHANGELOG.md) for the release history and notable changes.

## Citing the project

This project is cited via [`CITATION.cff`](CITATION.cff).

## License

This project is licensed under the MIT License. See [`LICENSE`](LICENSE).

## Status

This repository represents an experimental but structured ontology-supported framework for engineering coaching, AI-assisted validation, and governance. It is intended as a practical model and reference set rather than as a claimed universal standard or third-party certification.

---

For a detailed conceptual overview, review the ontology and governance documents in this repository, starting with:

- [`ontology/secav-o.ttl`](ontology/secav-o.ttl)
- [`coaching-governance/docs/coaching-cycle.md`](coaching-governance/docs/coaching-cycle.md)
- [`coaching-governance/glossary/glossary.md`](coaching-governance/glossary/glossary.md)
