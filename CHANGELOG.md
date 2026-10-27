# Changelog

All notable changes to SECAV-O are documented in this file.

## [Unreleased]

### Documentation and consistency fixes

- Reconciled the repository changelog with the actual work present in the repo and the current documentation set.
- Corrected stale references to older namespace and project naming patterns that no longer match the live repository.
- Consolidated the project-level release notes around the current ontology, validation, governance, and example artifacts in this codebase.
- Added a clearer release timeline that reflects the actual repository history and publication sequence.

## [0.3.0] - 2026-10-22

### Added

- New coaching-governance extension material covering annual planning, sprint planning, retrospectives, institutional alignment, risk governance, ethics, metrics, and competency growth.
- Formal ontology extensions for learning exercises, review roles, and pessimistic defect-prevention techniques.
- SHACL validation updates for the new ontology terms and constraints.
- Worked examples and templates for design reviews, coaching sprints, risk and defect tracking, onboarding, and competency assessment.
- The first learning exercise package: `exercises/java-standard-deviation/` with its ontology instance in `examples/java-standard-deviation-exercise.ttl`.
- New governance guides for robust process criteria, internal audits, CMMI mapping, coach ethics, observation checklists, and review-quality guidance.
- High-level ontology diagrams and updated class-hierarchy documentation in the README.

### Changed

- Aligned the framework with a stable SECAV-O ontology namespace and explicit `owl:imports` declarations.
- Clarified the distinction between coaching-program risk and project risk, and between evidence/measurement and coaching intervention concepts.
- Expanded the model to include explicit participant-role traceability for review sessions.
- Updated the coaching lifecycle documentation to reflect the current operational model and artifact taxonomy.
- Clarified the repo’s public project identity and metadata for versioning and citation.

### Fixed

- Corrected stale ontology references, invalid class/property names, and documentation mismatches.
- Fixed SHACL and ontology inconsistencies for review, risk, and threat/pre-mortem artifacts.
- Corrected typos and stale references in glossary, examples, and validation metadata.
- Updated `CITATION.cff` and release metadata to match the repository versioning and public project identity.

## [0.2.0] - 2026-10-07

### Added

- Formal coaching governance extension for project planning participation, quality advocacy, dissent and escalation, annual planning, sprint planning, risk management, metrics, ethics, and alignment.
- Governance documents for coach role profile, team lifecycle, institutional alignment, and coaching cycle.
- Core extension artifacts, schemas, and templates for onboarding, sprint planning, retrospectives, and risk review.
- Supporting examples and machine-readable records for planning and risk governance.

### Changed

- Promoted a stable extension namespace and imported the core SECAV-O ontology explicitly.
- Clarified that coaching governance is an extension layer rather than a separate, standalone process model.
- Improved ontology alignment between the extension and the SECAV-O core pattern.
- Updated README and glossary content to reflect the live repository and final extension naming.

### Fixed

- Replaced provisional namespace declarations with the live repository namespace.
- Corrected core-class references and SHACL `sh:class` declarations.
- Fixed README, glossary, and citation metadata inconsistencies.

## [0.1.0] - 2026-09-01

### Added

- Initial SECAV-O repository structure and documentation set.
- Core ontology and validation artifacts for engineering activities, artifacts, competencies, evidence, and AI-assisted review concepts.
- Initial coaching governance concepts and examples establishing the initial lifecycle and artifact model.
- First governance and learning-material scaffolding for the framework.
- Initial structure for guidance, examples, and schema work supporting the conceptual model.
