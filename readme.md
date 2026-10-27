# SECAV-O Coaching Lifecycle, Planning, Risk, Alignment and Ethics Artifacts

> Current version: v0.3.0 — See [CHANGELOG.md](CHANGELOG.md) for the detailed release history.

This package extends the SECAV-O coaching operating model with six connected governance dimensions:

1. team coaching from team inception, planning, and launch, including member preparation and onboarding;
2. annual coaching planning executed through Coaching Sprints;
3. risk management with preventive and corrective actions;
4. explicit alignment between coaching objectives and institutional objectives;
5. a Code of Ethics for coaches; and
6. formal coach participation in project planning, quality advocacy, documented dissent, and proportional escalation when material quality activities are omitted or weakened.

## Included artifacts

### Glossary
- [coaching-governance/glossary/glossary.md](coaching-governance/glossary/glossary.md) — authoritative definitions for the framework terms and quality concepts.

### Operating model
- [coaching-governance/docs/coach-role-profile.md](coaching-governance/docs/coach-role-profile.md) — authoritative role profile for the SECAV-O coach.
- [coaching-governance/docs/project-planning-participation.md](coaching-governance/docs/project-planning-participation.md) — coach participation in project planning and quality-gate advocacy.
- [coaching-governance/docs/team-coaching-lifecycle.md](coaching-governance/docs/team-coaching-lifecycle.md) — coaching from team inception through onboarding and baseline establishment.
- [coaching-governance/docs/coaching-cycle.md](coaching-governance/docs/coaching-cycle.md) — annual planning, sprint execution, retrospectives, and replanning.
- [coaching-governance/guides/requirements-inspection.md](coaching-governance/guides/requirements-inspection.md) — formal inspection of requirements documents.
- [coaching-governance/guides/retrospective-participation.md](coaching-governance/guides/retrospective-participation.md) — coach role in sprint retrospectives.
- [coaching-governance/guides/defect-tracking.md](coaching-governance/guides/defect-tracking.md) — coach defect tracking and metrics collection.
- [coaching-governance/guides/risk-management.md](coaching-governance/guides/risk-management.md) — coaching risk-management model.
- [coaching-governance/guides/incremental-adoption.md](coaching-governance/guides/incremental-adoption.md) — strategic guide for incremental framework adoption.
- [coaching-governance/docs/institutional-alignment.md](coaching-governance/docs/institutional-alignment.md) — method for connecting individual and institutional objectives.
- [coaching-governance/docs/coach-code-of-ethics.md](coaching-governance/docs/coach-code-of-ethics.md) — SECAV-O Code of Ethics for coaches.
- [coaching-governance/docs/coach-committee.md](coaching-governance/docs/coach-committee.md) — governance model for multi-coach organizations.
- [coaching-governance/docs/metrics-model.md](coaching-governance/docs/metrics-model.md) — defects, reviews, inspections, unit tests, and competency-growth metrics.
- [coaching-governance/docs/competency-growth-scale.md](coaching-governance/docs/competency-growth-scale.md) — longitudinal competency maturity scale.
- [coaching-governance/guides/peer-review-sessions.md](coaching-governance/guides/peer-review-sessions.md) — coach observation protocol during peer reviews.
- [coaching-governance/guides/formal-inspections.md](coaching-governance/guides/formal-inspections.md) — structured formal inspections of critical system modules.
- [coaching-governance/guides/project-kickoff-alignment.md](coaching-governance/guides/project-kickoff-alignment.md) — pre-project alignment session for the technical leader, coach, and management.
- [coaching-governance/guides/coach-team-behaviors.md](coaching-governance/guides/coach-team-behaviors.md) — team leader behaviors the coach observes.
- [coaching-governance/guides/design-documentation-standards.md](coaching-governance/guides/design-documentation-standards.md) — design artifacts required by system characteristics.
- [coaching-governance/guides/minimum-quality-criteria.md](coaching-governance/guides/minimum-quality-criteria.md) — minimum quality bar for reasonable software quality.
- [coaching-governance/guides/unit-test-review.md](coaching-governance/guides/unit-test-review.md) — checklist and guide for unit-test design review.
- [coaching-governance/guides/code-review-best-practices.md](coaching-governance/guides/code-review-best-practices.md) — evidence-based practices for code review.
- [coaching-governance/guides/ai-assisted-code-review.md](coaching-governance/guides/ai-assisted-code-review.md) — guidance for reviewing AI-assisted code.

### Templates
- [templates/project-planning-quality-gate-review.md](templates/project-planning-quality-gate-review.md)
- [templates/quality-planning-dissent-and-escalation.md](templates/quality-planning-dissent-and-escalation.md)
- [templates/team-launch-coaching-plan.md](templates/team-launch-coaching-plan.md)
- [templates/member-preparation-checklist.md](templates/member-preparation-checklist.md)
- [templates/new-member-onboarding.md](templates/new-member-onboarding.md)
- [templates/annual-coaching-plan.md](templates/annual-coaching-plan.md)
- [templates/coaching-sprint-plan.md](templates/coaching-sprint-plan.md)
- [templates/sprint-retrospective.md](templates/sprint-retrospective.md)
- [templates/risk-register.csv](templates/risk-register.csv)
- [templates/institutional-alignment-matrix.csv](templates/institutional-alignment-matrix.csv)
- [templates/coach-ethics-acknowledgement.md](templates/coach-ethics-acknowledgement.md)
- [templates/coach-committee-charter.md](templates/coach-committee-charter.md)
- [templates/engineer-coaching-assessment.md](templates/engineer-coaching-assessment.md)
- [templates/engineer-development-record.md](templates/engineer-development-record.md)
- [templates/organizational-competency-view.csv](templates/organizational-competency-view.csv)
- [examples/example-engineer-development-record.md](examples/example-engineer-development-record.md)
- [templates/metrics-register.csv](templates/metrics-register.csv)
- [templates/defect-log.csv](templates/defect-log.csv)
- [templates/rca-defect-analysis.md](templates/rca-defect-analysis.md)
- [templates/competency-trend.csv](templates/competency-trend.csv)
- [templates/coaching-backlog.csv](templates/coaching-backlog.csv)

### Machine-readable artifacts
- [schemas/project-planning-governance.schema.json](schemas/project-planning-governance.schema.json)
- [examples/example-quality-planning-escalation.yaml](examples/example-quality-planning-escalation.yaml)
- [schemas/team-coaching-lifecycle.schema.json](schemas/team-coaching-lifecycle.schema.json)
- [examples/example-team-launch-and-onboarding.yaml](examples/example-team-launch-and-onboarding.yaml)
- [ontology/secav-o-coaching-governance-extension.ttl](ontology/secav-o-coaching-governance-extension.ttl)
- [ontology/alignment-matrix.csv](ontology/alignment-matrix.csv)
- [validation/secav-o-coaching-governance.shacl.ttl](validation/secav-o-coaching-governance.shacl.ttl)
- [schemas/coaching-sprint.schema.json](schemas/coaching-sprint.schema.json)
- [examples/example-coaching-sprint.yaml](examples/example-coaching-sprint.yaml)

## Governance principles

- Coaching objectives should be traceable to an institutional, team, quality, engineering, security, workforce, or learning objective where appropriate.
- Risk management is part of the annual plan and is reviewed during every sprint retrospective.
- Each risk records probability, impact, preventive actions, corrective/contingency actions, owner, status, and review history.
- Coaching metrics are evidence for improvement, not instruments for punishment or isolated performance ranking.
- Coaches must protect confidentiality, avoid conflicts of interest, distinguish evidence from opinion, and preserve engineer dignity and professional autonomy.

## Core artifacts

The SECAV-O core ontology files that this extension builds on:

- [ontology/secav-o.ttl](ontology/secav-o.ttl) — core ontology: engineering activities, artifacts, competencies, evidence, measurement, AI assistance, human validation, assessment, and coaching concepts.
- [validation/secav-o.shacl.ttl](validation/secav-o.shacl.ttl) — SHACL constraints for the core ontology.
- [examples/design-review.ttl](examples/design-review.ttl) — worked example: AI-assisted design review instance.
- [examples/java-standard-deviation-exercise.ttl](examples/java-standard-deviation-exercise.ttl) — worked example: secav:LearningExercise instance for the Java standard deviation exercise.
- [exercises/java-standard-deviation/README.md](exercises/java-standard-deviation/README.md) — learning exercise statement handed to the engineer.

## Claim boundary

These artifacts define an operating and governance model. They do not claim that the metrics are validated predictors of engineer performance, that any numeric target is universally appropriate, or that SECAV-O has been independently validated, standardized, or adopted by third parties.

The engineer development record example (Valeria Montes) is entirely fictional and serves only as a template illustration. Templates and example files are not evidence of adoption or measured outcomes. The pilot protocol ([pilot/pilot-protocol.md](pilot/pilot-protocol.md)) describes a planned future validation activity, not a completed one.

## Ontology alignment note

Version 0.3.0 explicitly aligns coaching governance with the SECAV-O core pattern: Engineering Activity → Artifact → Competency → Acceptance Criterion → Evidence/Measurement → Coaching Intervention.

The extension uses the stable namespace `https://github.com/vlorenzana/software-engineering-coaching-framework/ontology/secav-o-coaching-governance#` and formally imports the core ontology via `owl:imports`.

## Planning participation and quality advocacy

Version 0.2.0 introduced a formal governance role for the coach in project planning. The recommended model gives the coach an explicit voice in planning and, when granted by the adopting organization, a vote on decisions that materially affect quality, competency development, and human validation.

The coach can raise a documented quality-planning concern when reviews, peer reviews, inspections, unit-test activities, or other material quality controls are omitted or weakened. If the residual risk remains material, the coach can record formal dissent and escalate through the defined management chain.
