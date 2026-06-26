# Ontologica Lease

tessera-builder leases Ontologica OS as its intake proofing lane for physical tabletop OS builder candidates.

## Lease Role

```text
Ontologica OS
  proofing lane
  protected-term review
  disclosure critic
  governed packet generator

tessera-builder
  backroom builder lane
  component preparation
  embodiment-kernel staging
  Tessera-targeted review packets
```

## Intake Rule

Material entering tessera-builder from private work, campaign tooling, or forge-facing surfaces should arrive with a governed review packet when it may later move toward Tessera.

Required packet fields:

```text
proof_packet: present
disclosure_critic: present
protected_terms_review: present
source_repository: declared
target_repository: tessera
human_review: required
final_gate: hold / review / deny
```

## Default Authority

```text
authority_ceiling: candidate_only
production_authority: none
hardware_authority: none
actuator_authority: none
merge_authority: none
human_review: required
```

## Lease Receipt

```text
lease_from: Ontologica OS
lease_to: tessera-builder
lease_status: active_scaffold
release_gate: human_review_required
```
