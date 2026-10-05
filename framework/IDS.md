# Canonical element IDs

All cross-references use **zero-padded** IDs (`A01`, `R07`, `FS03`, …).

| Kind | Pattern | Count |
|------|---------|-------|
| Axiom | `A01` … `A04` | 4 |
| Question | `Q01` … `Q02` | 2 |
| Feature (simulation) | `FS01` … `FS03` | 3 |
| Assumption | `AS01` … `AS02` | 2 |
| Measure | `M01` … | 1 |
| Rule | `R01` … `R13` (`R05` retired) | 12 |

**Laws merged into rules** — do not use `L**` IDs.

## Files

| Prefix | Location |
|--------|----------|
| `FS**` | `features/simulation/` |
| `AS**` | `assumptions/` |
| `R**` | `rules/` |

## Adopting elements

When you describe a universe, cite only the IDs your story **uses** (minimal overlap—don’t list optional pieces you are not modeling).

**Typical bundles:**

- **Foundation:** axioms **A01–A04**; rules **R01–R04** for almost any spec.
- **Nested sim:** **FS01** (entanglement), **FS03** (deferred detail), optionally **FS02** (host narrative).
- **Session test fiction:** **Q01**; optionally **AS01**, **AS02**, **R07**.
- **Parity:** **R08**, often **M01** when comparing base vs sim in lore.
- **Extras:** **R06** (overlaps), **R09** (rejuvenation), **R10** (block + lived time), **R11** (tier), **R12** (Gödel / universe prime), **R13** (cosmic boundaries), **Q02** (free choice).

## ID migration (retired numbers)

| Old | Current | Notes |
|-----|---------|--------|
| **L01** | **FS01** | Entanglement feature |
| **L02** | **AS01** | Session amnesia assumption |
| **L03** | **AS02** | Scarcity assumption |
| **L04** / **U01** | **FS03** | Deferred rendering |
| **L05** | **Q01** | Existential purpose question |
| **L06** | **R09** | Soul resuscitation (optional rule) |
| **L07** | **R08** | Equivalence of realities |
| **L08** | **R06** | Merged into overlap blending (deduplicated) |
| **L** (all) | **R** | Laws folder removed—use rules only |
| **AS01** (entanglement, obsolete) | **FS01** | Entanglement is a feature, not an assumption |
| **AS02** (old amnesia id) | **AS01** | Assumption IDs aligned from 1 |
| **AS03** (old scarcity id) | **AS02** | |
| **R05** | **FS03** | Do not use R05 |
| **R08** (old rejuvenation checks) | **R09** | Was duplicate of L06 narrative |
| **R09** (old ontological parity rule) | **M01** + **R08** | |

## When to include an ID

| ID | Include when… |
|----|----------------|
| **FS01** | Base entity and sim avatar stay entanglement-coupled |
| **FS02** | You tell a parent-layer quantum-host story |
| **FS03** | Unobserved regions stay vague until observation |
| **AS01** | Blind-session / withheld primary memory |
| **AS02** | Scarcity and lifespan caps are intentional for stakes |
| **R06** | Two structures overlap in one place |
| **R07** | You define a lifetime scoring protocol (with **Q01**) |
| **R08** | Sim vs base ontological equality matters |
| **R09** | Optional rejuvenation-after-sim story |
| **R10** | Both block-time and experienced finite time appear in the spec |
| **R11** | You document multiverse tier (bounded / constrained infinite / plenitude) |
| **Q02** | You explore free choice vs determinism (open) |
| **R12** | You use Gödel-style encoding or “universe prime” metaphor |
| **R13** | You document $t=0$, far-future horizon, or $I_{\max}$ caps |

Baseline for most specs: **R01–R04** from axioms.

## Validation checklist

- [x] No **L** IDs in new docs
- [x] **L08** content only in **R06** (not duplicated)
- [x] **L07** → **R08**; **L06** → **R09**
- [x] Deferred rendering → **FS03** only (**R05** retired)
