# Canonical element IDs

All cross-references and YAML `references.*` use **zero-padded** IDs.

| Kind | Pattern | Count |
|------|---------|-------|
| Axiom | `A01` … `A04` | 4 |
| Rule | `R01` … `R09` (`R05` retired) | 8 |
| Question | `Q01` … | 1 |
| Feature (simulation) | `FS01` … `FS03` | 3 |
| Assumption | `AS02` … `AS03` | 2 |
| Measure | `M01` … | 1 |

**Laws merged into rules** — do not use `L**` or `references.laws`.

## Files

| Prefix | Location |
|--------|----------|
| `FS**` | `features/simulation/` |
| `AS**` | `assumptions/` |
| `R**` | `rules/` |

## YAML

**Minimal overlap** — see [universe.schema.yaml](universe.schema.yaml), [examples/earth-session.yaml](examples/earth-session.yaml).

```yaml
references:
  axioms: [A01, A02, A03, A04]
  questions: [Q01]                 # if evaluation / life-as-test
  features:
    simulation: [FS01, FS03]       # match session/physics flags
  assumptions: [AS02, AS03]
  rules: [R01, R02, R03, R04, R08, R07]  # + R06 if overlaps; + R09 if rejuvenation story
  measures: [M01]                    # if base vs sim parity matters
```

## ID migration (retired numbers)

| Old | Current | Notes |
|-----|---------|--------|
| **L01** | **FS01** | Entanglement feature |
| **L02** | **AS02** | Session amnesia assumption |
| **L03** | **AS03** | Scarcity assumption |
| **L04** / **U01** | **FS03** | Deferred rendering |
| **L05** | **Q01** | Existential purpose question |
| **L06** | **R09** | Soul resuscitation (optional rule) |
| **L07** | **R08** | Equivalence of realities |
| **L08** | **R06** | Merged into overlap blending (deduplicated) |
| **L** (all) | **R** | Laws folder removed—use `references.rules` only |
| **AS01** | **FS01** | |
| **R05** | **FS03** | Do not use R05 |
| **R08** (old rejuvenation checks) | **R09** | Was duplicate of L06 narrative |
| **R09** (old ontological parity rule) | **M01** + **R08** | |

## Conditional gates

| ID | When to list |
|----|----------------|
| **FS01** | `session.entanglement.enabled` |
| **FS02** | Optional host narrative only |
| **FS03** | `physics.deferred_rendering` |
| **AS02** | Memory / blind-session protocol |
| **AS03** | `physics.scarcity.enabled` |
| **R06** | `multiverse.overlaps` non-empty |
| **R07** | Evaluation / Q01 protocol |
| **R08** | Sim vs base parity in story (often with **M01**) |
| **R09** | Optional rejuvenation teleology |

Baseline for most instances: **R01–R04** from axioms.

## Validation checklist

- [x] No `references.laws` or **L** IDs in new docs
- [x] **L08** content only in **R06** (not duplicated)
- [x] **L07** → **R08**; **L06** → **R09**
- [x] Deferred rendering → **FS03** only (**R05** retired)
