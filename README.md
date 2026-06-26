# tessera-builder

tessera-builder is the backroom builder lane for preparing Tessera physical tabletop OS work before it moves into the controlled Tessera repository.

It is not the public worldbuilder frontdoor and not the hardware authority layer. It exists to stage, describe, packetize, and review builder-side work under human control.

## Role

```text
tessera-builder
  backroom builder lane
  physical tabletop OS preparation
  embodiment-kernel staging
  component build planning
  review-packet generation
  human-controlled intake toward Tessera
```

## What Belongs Here

tessera-builder may contain:

- builder-side planning notes
- component preparation packets
- noncanonical build sketches
- review manifests for Tessera-targeted work
- protected-term reports
- implementation candidates pending review
- human-controlled intake reports
- scaffolding for future Tessera movement

## What Does Not Belong Here Without Review

Do not land:

- public-facing claims without Ontologica review
- actuator or hardware authority paths
- executable physical control logic
- private component protocols
- production release authority
- unreviewed private source history
- real private manifests or receipts
- automatic movement into Tessera

## Relationship To The Ecosystem

```text
Ontologica OS
  decides what can be safely said or moved

Ontologica Forge
  public worldbuilder and git campaign frontdoor

tessera-builder
  private/backroom builder lane for Tessera-targeted candidates

Tessera
  physical tabletop OS and embodied-kernel target
```

## Intake Gate

Material moving from tessera-builder toward Tessera requires:

```text
proof_packet: present
disclosure_critic: present
protected_terms_review: present
target_repository: tessera
human_review: required
final_gate: hold / review / deny
```

## Current Status

```text
status: scaffolded_backroom_builder_lane
authority_ceiling: candidate_only
hardware_authority: none
production_claim: none
```
