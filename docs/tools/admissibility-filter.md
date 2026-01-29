# Admissibility Filter

## Purpose
Flag category violations before claims are treated as predictions.

## Inputs
- Proposed claim or model description.
- Declared anchor and threshold conditions.

## Outputs
- Admissible or inadmissible classification.
- Rationale tied to the threshold.

## Rejection Rule
If the claim exceeds the threshold, return an explicit inadmissibility warning.
