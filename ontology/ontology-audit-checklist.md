# SECAV-O Ontology Audit Checklist

Use this checklist before a release or when reconciling documentation to the ontology.

## 1) Namespace integrity

- [ ] All ontology documents use the canonical prefixes:
  - `secav:` -> `https://github.com/vlorenzana/software-engineering-coaching-framework/ontology/secav-o#`
  - `secavo:` -> `https://github.com/vlorenzana/software-engineering-coaching-framework/ontology/secav-o-coaching-governance#`
- [ ] No lingering references to `https://example.org/secav-o#` remain in TTL, SHACL, docs, or schemas.
- [ ] Documentation notes reflect the canonical namespace mapping instead of historical placeholders.

## 2) Class declarations

- [ ] Every class used in SHACL or documentation is declared in the appropriate ontology file.
- [ ] No class names are referenced without declaration or import.
- [ ] Core and extension classes are not accidentally duplicated across namespaces.

Priority classes to verify:
- [ ] `secav:Artifact`
- [ ] `secav:Evidence`
- [ ] `secav:Measurement`
- [ ] `secav:Competency`
- [ ] `secav:EngineeringActivity`
- [ ] `secav:CoachingIntervention`
- [ ] `secav:AcceptanceCriterion`
- [ ] `secav:PreventiveAction`
- [ ] `secavo:Risk`
- [ ] `secavo:CoachingObjective`
- [ ] `secavo:AnnualCoachingPlan`
- [ ] `secavo:CoachingSprint`
- [ ] `secavo:CorrectiveAction`

## 3) Property declarations and semantics

- [ ] Each property has a correct `rdfs:domain` and `rdfs:range`.
- [ ] No property is declared with a stale or placeholder namespace.
- [ ] Property names follow the naming style used in the ontology (for example, lowerCamelCase for object and datatype properties).
- [ ] Risk properties are not confused with core properties or with project-level risk terms.

Properties to verify:
- [ ] `secavo:hasRisk`
- [ ] `secavo:sprintHasRisk`
- [ ] `secavo:hasPreventiveAction`
- [ ] `secavo:hasCorrectiveAction`
- [ ] `secavo:riskProbability`
- [ ] `secavo:riskImpact`
- [ ] `secavo:riskStatus`
- [ ] `secavo:riskOwner`
- [ ] `secav:respondsToExercise`
- [ ] `secav:exerciseTargetsCompetency`
- [ ] `secav:requiresDeliverable`
- [ ] `secav:hasEvaluationCriterion`

## 4) SHACL validation consistency

- [ ] Every `sh:targetClass` corresponds to an actual OWL class.
- [ ] Every `sh:class` predicate references a declared ontology class.
- [ ] `minCount`, `maxCount`, and datatype constraints match the intended semantics.
- [ ] SHACL constraints do not contradict the textual documentation.
- [ ] Constraints for learning exercises, review roles, and risks are aligned with the ontology they validate.

## 5) Documentation-to-model alignment

- [ ] README, changelog, and guide docs describe the current version and namespace correctly.
- [ ] Risk and governance guides reflect the stable URL namespace, not historical placeholders.
- [ ] Ontology alignment docs describe the same model as the TTL/SHACL, not an earlier prototype.
- [ ] Example artifacts and schemas align with current classes and properties.

## 6) Example and schema correctness

- [ ] Example RDF files use the canonical namespace prefixes.
- [ ] JSON schemas use real repository URIs, not placeholder domains.
- [ ] Example data instantiates only declared classes and properties.
- [ ] The examples remain valid under the current SHACL rules.

## 7) Release-readiness gate

- [ ] No placeholder domains remain.
- [ ] No stale doc note remains in risk, ontology, or governance guides.
- [ ] Ontology and SHACL are consistent with one another.
- [ ] Docs and examples match the release version declared in the repo.
- [ ] The repo is ready for a clean release tag or publication.

## 8) Recommended next validation step

Run a validation session that compares:
- ontology declarations -> SHACL targets
- SHACL class constraints -> declared classes
- docs and examples -> canonical namespaces
- changelog claims -> actual repo state

If all checks are green, the repository is in a credible release state.

