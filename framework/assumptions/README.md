# Assumptions (optional)

**Assumptions** are mechanisms that *may* hold in a given universe. They are **not** treated as established fact—only as **toggleable models** you can adopt when building a scenario.

**Nested-simulation coupling** (entanglement) is a **feature**, not an assumption: [features/simulation/FS01](../features/simulation/FS01-session-entanglement.md).

| ID | File | Related law | Status |
|----|------|-------------|--------|
| AS02 | [AS02-session-amnesia.md](AS02-session-amnesia.md) | Q01 | Memory partition + optional blind vetting narrative (former **L02**) |
| AS03 | [AS03-artificial-scarcity.md](AS03-artificial-scarcity.md) | Q01, R09 | Scarcity + meaning-through-constraint (former **L03**) |

## How to use

- In [universe.schema.yaml](../universe.schema.yaml), list under `references.assumptions`.
- For **FS01**, use `references.features.simulation` instead.
- **Rules** (R01–R04, R06–R07) apply when you adopt the operational story; they do not assert that assumptions are true. Deferred rendering uses **FS03** (**R05**, **U01** retired).
- If **AS02** is off, do not require primary-memory suppression. If **AS03** is off, do not treat hardship as intentional meaning-engineering—even in a sim.

## Naming

**AS** = assumption (distinct from **A**, **L**, **FS**, **R**). Files use **AS02**, **AS03**, …

**Retired:** `AS01` (session entanglement) → [FS01](../features/simulation/FS01-session-entanglement.md). See [IDS.md § ID migration](../IDS.md#id-migration-retired-numbers).
