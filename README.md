# Cross-Lingual Medical NER (Arabic ↔ English)

Fine-tuning XLM-RoBERTa on English biomedical NER (BC5CDR) and
evaluating zero-shot transfer to Arabic medical text.

**Status:** in progress — Phase 2 of 6.

## Scope
Entity types: Disease and Chemical, following BC5CDR.
Symptom mentions are out of scope.

## Hypothesis
Chemical entities should transfer better than Disease entities,
because Arabic drug names are largely transliterated from English
while disease names are typically native Arabic terms.

## Results
_Pending._

## Repo
- `notebooks/` — run in numbered order
- `data/` — Arabic evaluation set and annotation guide
- `results/` — evaluation output
