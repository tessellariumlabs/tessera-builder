# Codex Kickoff — tessera-builder

tessera-builder is the backroom builder lane for Tessera-targeted candidates.

## Task

Create a synthetic build-candidate packet set.

Expected files:

```text
examples/build_candidate_packet.md
sample_outputs/reviews/build_candidate_review.json
sample_outputs/reports/build_candidate_report.md
```

## Boundary

Keep all examples synthetic and noncanonical.

Do not include private implementation, private component protocols, real receipts, real manifests, or automatic movement into Tessera.

## Required Gate

```text
proof_packet: present
disclosure_critic: present
protected_terms_review: present
target_repository: tessera
human_review: required
final_gate: hold / review / deny
```

## Default Outcome

```text
decision: hold_for_review
authority_ceiling: candidate_only
hardware_authority: not_granted
actuator_authority: not_granted
```
