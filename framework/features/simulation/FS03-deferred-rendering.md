# FS03 — Deferred rendering / observer-linked detail (simulation feature)

## Q&A

**Question:** Does the whole universe run in full detail when nobody is looking?

**Answer:** **Only if you enable FS03:** unobserved regions stay vague until a candidate observer interacts—like a game that only draws what you see.

**Status:** *Simulation feature.* Former **L04** / **U01**; builder checks absorbed from retired **R05**. See [IDS.md § ID migration](../../IDS.md#id-migration-retired-numbers).

Unobserved environment stays in superposition (many possibilities); interaction picks one outcome (Born-rule style metaphor).

**Equations:** [FORMULAS.md § FS03](../../FORMULAS.md#fs03--deferred-rendering-superposition-until-observation)

## If you enable FS03

- Detail tracks observer coupling, not global clock alone.
- `references.features.simulation` + `physics.deferred_rendering: true` + `physics.observer_entity_id`.

**Builder checks:** don’t precompute irrelevant regions at full fidelity; collapse detail on interaction.

## If you do not enable FS03

Omit from `references.features.simulation`; leave `physics.deferred_rendering` false.

## Influences

**Tags:** Wheeler · Rovelli · QBism · Zurek · digital-physics metaphor  

Prior-art map: [INFLUENCES.md § FS03](../../INFLUENCES.md#fs03--deferred-rendering--observer-collapse)
