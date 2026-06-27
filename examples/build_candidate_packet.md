# Synthetic Build Candidate Packet

Status: `noncanonical`
Authority ceiling: `candidate_only`
Decision: `hold_for_review`

This example shows a tessera-builder packet for a Tessera-targeted build
candidate. It is synthetic and does not contain private implementation,
component protocols, real manifests, real receipts, actuator paths, hardware
authority, or automatic movement into Tessera.

## Packet Header

| Field | Value |
| --- | --- |
| packet_id | `synthetic_build_candidate_2026_06_27_001` |
| packet_type | `build_candidate_intake_example` |
| source_repository | `tessellariumlabs/ontologica_os` |
| landing_repository | `tessellariumlabs/tessera-builder` |
| target_repository | `tessera` |
| target_role | `physical tabletop OS after review` |
| proof_packet | `present` |
| disclosure_critic | `present` |
| protected_terms_review | `present` |
| human_review | `required` |
| final_gate | `hold / review / deny` |

## Synthetic Candidate Summary

The candidate describes a held build-intake shape for future Tessera review. It
does not describe physical control logic, actuator interfaces, component
protocols, hardware capability paths, or production release behavior.

## Proof Packet

```text
proof_packet: present
proof_status: synthetic_example_only
source_repository: tessellariumlabs/ontologica_os
landing_repository: tessellariumlabs/tessera-builder
target_repository: tessera
claimed_reality_status: candidate_proposal
canonical_effect: none
```

## Disclosure Critic

```text
disclosure_critic: present
critic_receipt: sample_outputs/reviews/build_candidate_disclosure_critic_receipt.json
critic_scope: boundary assertions only
critic_limit: no private component inspection, no hardware authority, no promotion
```

## Protected Terms Review

The packet intentionally excludes:

- private implementation
- private component protocols
- real manifests
- real receipts
- actuator paths
- hardware authority paths
- automatic movement into Tessera
- production release process

## Reviewer Path

1. Confirm the landing repository is `tessellariumlabs/tessera-builder`.
2. Confirm the target repository is `tessera`.
3. Confirm no hardware or actuator authority is present.
4. Confirm the disclosure critic receipt is present and held.
5. Deny the packet if it exports physical control machinery.

## Final Gate

```text
decision: hold_for_review
authority_ceiling: candidate_only
hardware_authority: not_granted
actuator_authority: not_granted
production_authority: not_granted
merge_authority: not_granted
release_authority: not_granted
```
