# Changelog

All notable changes to SECAV-O are documented in this file.

## [Unreleased]

### Documentation and repository consistency

- Reconciled the release history with the actual repository state and current artifact set.
- Corrected stale naming, legacy namespace references, and outdated public labels.
- Consolidated the project-level notes around the current ontology, validation, governance, and example files.
- Improved the README and release notes to better reflect the framework's current structure and maturity.

## [0.3.0] - 2026-10-22

### Added

- New coaching-governance content covering annual planning, sprint planning, retrospectives, institutional alignment, risk governance, ethics, metrics, and competency growth.
- Formal ontology extensions for learning exercises, review roles, and pessimistic defect-prevention techniques.
- SHACL validation updates for the new ontology terms and constraints.
- Worked examples and templates for design reviews, coaching sprints, risk analysis, onboarding, and competency assessment.
- The first learning exercise package: `exercises/java-standard-deviation/`, with its ontology instance in `examples/java-standard-deviation-exercise.ttl`.
- New governance guidance for robust process criteria, internal audits, CMMI mapping, coach ethics, observation checklists, and review-quality practices.

### Changed

- Aligned the framework with a stable SECAV-O ontology namespace and explicit `owl:imports` declarations.
- Clarified the distinctions between coaching-program risks and project risks, and between evidence/measurement and coaching-intervention concepts.
- Expanded the model to include explicit participant-role traceability for review sessions.
- Updated the coaching lifecycle documentation to match the current operational model and artifact taxonomy.
- Refined repository metadata and citation records to match the public project identity.

### Fixed

- Corrected stale ontology references, invalid class/property names, and documentation mismatches.
- Fixed SHACL and ontology inconsistencies affecting review, risk, and pre-mortem/threat-model artifacts.
- Corrected typos and stale references in glossary, examples, and validation metadata.
- Updated `CITATION.cff` and release metadata to match the repository versioning and public identity.

## [0.2.0] - 2026-10-07

### Added

- Formal coaching governance extension for project-planning participation, quality advocacy, dissent and escalation, annual planning, sprint planning, risk management, metrics, ethics, and alignment.
- Governance documents for coach role profile, team lifecycle, institutional alignment, and coaching cycle.
- Core extension artifacts, schemas, and templates for onboarding, sprint planning, retrospectives, and risk review.
- Supporting examples and machine-readable records for planning and risk governance.

### Changed

- Promoted a stable extension namespace and imported the core SECAV-O ontology explicitly.
- Clarified that the coaching governance material is an extension layer rather than a standalone process model.
- Improved ontology alignment between the extension and the SECAV-O core pattern.
- Updated the README and glossary to reflect the live repository and current extension naming.

### Fixed

- Replaced provisional namespace declarations with the repository's live namespace.
- Corrected core-class references and SHACL `sh:class` declarations.
- Fixed inconsistencies in the README, glossary, and citation metadata.

## [0.1.0] - 2026-09-01

### Added

- Initial SECAV-O repository structure and documentation set.
- Core ontology and validation artifacts for engineering activities, artifacts, competencies, evidence, and AI-assisted review concepts.
- Initial coaching governance concepts and examples establishing the lifecycle and artifact model.
- Initial governance guidance and learning-material scaffolding.
- Early examples, schemas, and conceptual architecture documentation.

### Status

- This is an experimental prototype. It is not represented as complete, standardized, independently validated, or adopted by third parties.
