# MedSynIQ Lite

**Free medical intelligence for AI assistants.**

5 specialist agents · 20 clinical skills · MIT-0 license · ClawHub compatible

> **DISCLAIMER:** All output is AI-generated educational content. It does not constitute medical advice, diagnosis, or treatment. Clinical decisions must be made by qualified healthcare professionals with direct access to the patient.

---

## What's included

| Agent | Domain | Skills |
|-------|--------|--------|
| `clinical-reasoner` | Differential diagnosis, Bayesian reasoning, decision rules | 4 |
| `pharmacologist` | Drug interactions, dosing, pharmacokinetics | 4 |
| `evidence-appraiser` | Critical appraisal, GRADE, evidence synthesis | 4 |
| `biostatistician` | Sample size, hypothesis testing, survival analysis | 4 |
| `medical-educator` | Teaching cases, learning objectives, curriculum design | 4 |

## Install

### Claude Code / ClawHub
```bash
/install-skill ProFlow-Labs-Ai/medsyniq-lite-clawhub
```

Or add to your `CLAUDE.md`:
```
Use skills from: ProFlow-Labs-Ai/medsyniq-lite-clawhub
```

## Usage examples

```
/differential 65yo male, acute chest pain, diaphoresis, DM, smoker
/drug-check warfarin + amiodarone
/evidence-search SGLT2 inhibitors in heart failure
/sample-size RCT, binary outcome, 80% power, alpha 0.05
/teaching-case 28yo female, fever, rash, joint pain
```

## File structure

```
medsyniq-lite-clawhub/
  SKILL.md                    — Skill definition (ClawHub entry point)
  LICENSE                     — MIT-0
  references/
    clinical-reasoner.md      — DDx frameworks, illness scripts, Bayesian analysis
    pharmacologist.md         — CYP450 tables, TDM targets, interaction examples
    evidence-appraiser.md     — CASP checklists, GRADE methodology
    biostatistician.md        — Test selection, formulas, SAP structure
    medical-educator.md       — Case design, Bloom's taxonomy, curriculum mapping
  scripts/
    disclaimer-check.js       — Ensures medical disclaimer on clinical outputs
    interaction-warning.js    — Flags dangerous drug combinations
```

## Lite vs Pro

MedSynIQ Lite covers 5 of 27 agents and 20 of 142 skills in MedSynIQ Pro.

| Feature | Lite | Pro |
|---------|------|-----|
| Agents | 5 | 27 |
| Skills | 20 | 142 |
| Drug interaction database | — | 160K+ pairs |
| Clinical score calculator | — | 27 scores |
| Evidence search (PubMed proxy) | — | ✓ |
| Guidelines RAG | — | ✓ |
| Multi-harness (Codex, Gemini, Cursor) | — | ✓ |
| License | MIT-0 (free) | Commercial |

**Full version:** [medsyniq.com](https://medsyniq.com)

## License

MIT-0 — use freely, no attribution required. See [LICENSE](LICENSE).

---

*MedSynIQ Lite by [ProFlow Labs AI](https://medsyniq.com)*
