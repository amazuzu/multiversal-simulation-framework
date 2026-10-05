# Influences and prior ideas

This document maps **themes** in this framework to thinkers and works that discuss **similar ideas**.

**What this is:** a pointer—“if you want nearby ideas, read these people.” **What it is not:** proof that they said this, page-perfect quotes, or formal academic citations.

- No line numbers or page references are required for that purpose.
- Listed authors **do not** endorse this axiom set unless a source explicitly says so.
- Overlap in theme ≠ copying their text or your framework being “their theory.”

**Provenance of this repository**

- Core formalization in `framework/` under the editorship of **Taras Biletskyi**.
- Wording and structure were produced with **generative AI assistance**; the published compilation, license, and curation are the author’s responsibility.

**How to read tags**

| Tag | Meaning |
|-----|---------|
| **theme** | Idea rhymes with a classic position or debate |
| **formal** | Mathematical or logical tool used in the notation |
| **parallel** | Analogous setup in ethics, myth, or fiction—not a scientific claim |

---

## Part I — Axioms

### A01 — Non-contradiction / plenitude

| Name | Relevance |
|------|-----------|
| **Aristotle** | Law of non-contradiction as a foundation of logic. |
| **Leibniz** | *Principle of plenitude* — God actualizes all worthy possibilities (historical “possible ⇒ actual” rhetoric). |
| **David Lewis** | *Modal realism* — possible worlds as concrete existents (different mechanism than consistency⇔exists, but same family of “many structures exist”). |
| **Kurt Gödel** | Consistency, incompleteness, and limits of proof inside a formal system (related to $\text{Consistent}(S) \iff S \nvdash \bot$). |
| **Max Tegmark** | Level IV multiverse — all mathematical structures exist (close thematic neighbor to plenitude over structures). |

**See also:** [axioms/A01-non-contradiction.md](axioms/A01-non-contradiction.md)

---

### A02 — Mathematical monism

| Name | Relevance |
|------|-----------|
| **Max Tegmark** | *Mathematical Universe Hypothesis* — reality is a mathematical structure. |
| **John Archibald Wheeler** | “It from bit” — physical law from information-theoretic primitives. |
| **Edward Fredkin** | Digital physics — universe as computation over discrete states. |
| **Konrad Zuse** | *Rechnender Raum* (Calculating Space) — universe as cellular computation. |
| **Claude Shannon** | Information as a rigorous quantity (language for $\text{Information}(\mathcal{M})$). |
| **Rolf Landauer** | Information has physical cost — bridges information and thermodynamics. |
| **Baruch Spinoza** | Monism — one substance (historical parallel to rejecting matter/spirit dualism). |

**See also:** [axioms/A02-mathematical-monism.md](axioms/A02-mathematical-monism.md)

---

### A03 — Self-reference / consciousness

| Name | Relevance |
|------|-----------|
| **René Descartes** | *Cogito* — irreducible first-person awareness as starting point. |
| **Douglas Hofstadter** | Strange loops — self-reference giving rise to “I”. |
| **Giulio Tononi** (with **Christof Koch** and others) | *Integrated Information Theory* — $\Phi$ as consciousness-related measure. |
| **Robert Rosen** | Anticipatory systems — models that model themselves. |
| **Humberto Maturana & Francisco Varela** | Autopoiesis — self-maintaining organizational closure (weaker but related loop motif). |

**See also:** [axioms/A03-self-reference-consciousness.md](axioms/A03-self-reference-consciousness.md)

---

### A04 — Inherent local reality

| Name | Relevance |
|------|-----------|
| **David Chalmers** | Virtual worlds can be **genuinely experiential** (“Matrix” metaphysics). |
| **Nick Bostrom** | Simulation argument — simulated minds are still minds with moral weight. |
| **Robert Nozick** | Experience machine thought experiment — experience counts even when “external” status is odd. |
| **Hilary Putnam** | Internal realism — truth relative to conceptual scheme (distant cousin to local physics fixing experience). |

**See also:** [axioms/A04-inherent-reality.md](axioms/A04-inherent-reality.md)

---

## Simulation features

### FS01 — Session entanglement / quantum projection

| Name | Relevance |
|------|-----------|
| **Einstein, Podolsky & Rosen (1935)** | EPR — nonlocal correlations in quantum theory ($E_{PR}$ in the feature text). |
| **John Stewart Bell** | Bell’s theorem — constraints on local hidden variables. |
| **Standard QM** | Entangled states e.g. $\vert\Psi\rangle = \frac{1}{\sqrt{2}}(\vert A\rangle \otimes \vert B\rangle)$ (formal **theme**). |

*Speculative narrative device* (base entity ⊗ avatar), not an established physics protocol. Former **L01** — same concept.

**See also:** [features/simulation/FS01-session-entanglement.md](features/simulation/FS01-session-entanglement.md)

---

### FS03 — Deferred rendering / observer collapse

| Name | Relevance |
|------|-----------|
| **John Archibald Wheeler** | Participatory universe — observation linked to actuality. |
| **Carlo Rovelli** | Relational quantum mechanics — facts relative to systems. |
| **QBism** (Fuchs, Mermin, Schack) | Quantum states as agent beliefs — observer-centric formalism. |
| **Wojciech Zurek** | Decoherence — emergence of classical outcomes from entanglement with environment. |
| **Eugene Wigner** | Early “consciousness causes collapse” (historical **theme**; not endorsed here as physics). |

*“Deferred rendering” also rhymes with **simulation / game-engine** metaphors in digital physics (Fredkin, Zuse) and popular science writing.*

Former **L04** / **U01** — same concept.

**See also:** [features/simulation/FS03-deferred-rendering.md](features/simulation/FS03-deferred-rendering.md)

---

## Assumptions

### AS01 — Session amnesia / unbiased testing

| Name | Relevance |
|------|-----------|
| **John Rawls** | *Veil of ignorance* — unbiased moral assessment (ethical **parallel** to suppressed $\mathcal{M}_{Primary}$). |
| **Nick Bostrom** | Discussion of nested simulations and what subjects know about “base” reality. |
| **Greek myth (Lethe)** | River of forgetfulness — cultural **parallel** to session amnesia. |
| **Rebirth traditions** (e.g. Hindu/Buddhist *samsara*) | Doctrines of rebirth with **no ordinary recall** of past lives — phenomenological **parallel** to $\mathcal{M}_{\text{prior-lives}} \subset \mathcal{M}_{Primary}$. |

Former **L02** — same concept.

**See also:** [assumptions/AS01-session-amnesia.md](assumptions/AS01-session-amnesia.md)

---

### AS02 — Artificial scarcity / meaning through constraint

| Name | Relevance |
|------|-----------|
| **Ludwig Boltzmann / Rudolf Clausius** | Entropy and the second law ($\frac{dS}{dt} > 0$ motif). |
| **Ernest Becker** | *The Denial of Death* — mortality and meaning. |
| **Epicurus / Stoic tradition** | Finite life as frame for value (*memento mori*). |
| **Lionel Robbins** | Economics of scarcity — choice under constraint. |

Former **L03** — same concept.

**See also:** [assumptions/AS02-artificial-scarcity.md](assumptions/AS02-artificial-scarcity.md)

---

## Rules

### R06 — Multiversal intersection

| Name | Relevance |
|------|-----------|
| **Hugh Everett III** | Many-worlds — branching structure space. |
| **Max Tegmark** | Multiverse hierarchy — coexistence of structure types. |
| **Lisa Randall & Raman Sundrum** | Brane-world scenarios — overlapping domains with mixed effective laws (loose **parallel**). |
| **David Lewis** | Plurality of worlds (strict Lewis worlds are not intersecting—contrast note). |

Former **L08**. **See also:** [rules/R06-overlap-blending.md](rules/R06-overlap-blending.md)

---

### Q01 — Existential purpose / evaluation (open question)

| Name | Relevance |
|------|-----------|
| **Aristotle** | Virtue as stable character revealed through action over a life. |
| **Immanuel Kant** | Moral worth of choices under duty (not identical to scoring integral, but same moral-assessment **theme**). |
| **Lawrence Kohlberg** | Stages of moral reasoning — developmental testing motif. |
| **Abrahamic & other traditions** | Judgment / trial narratives after life (cultural **parallel** to $\text{Evaluate}(Entity)$). |

**See also:** [questions/Q01-existential-purpose.md](questions/Q01-existential-purpose.md)

---

### R09 — Soul resuscitation / cognitive entropy

| Name | Relevance |
|------|-----------|
| **Boltzmann / Shannon** | Entropy formalisms — metaphorical source for $H_{cognitive}$. |
| **Ernest Becker** | Mortality awareness and renewal of meaning. |
| **Joseph Campbell** | Death–rebirth cycle in myth (symbolic **parallel** to rejuvenation via finite life). |

Former **L06**. **See also:** [rules/R09-soul-resuscitation.md](rules/R09-soul-resuscitation.md)

---

### Q02 — Free choice and unpredictability

| Name | Relevance |
|------|-----------|
| **Stephen Wolfram** | Algorithmic irreducibility — computation that cannot be shortcut. |
| **Daniel Dennett / compatibilists** | Choice as real at the level of agents even if physics is deterministic (debate). |
| **Everett / branching QM** | Many branches as formal backdrop for “decision manifolds.” |

**See also:** [questions/Q02-free-choice.md](questions/Q02-free-choice.md)

---

### R10 — Block time and experienced time

| Name | Relevance |
|------|-----------|
| **Eternalism** | Past and future equally real in a 4D block. |
| **Carlo Rovelli** | Relational / perspective-dependent time (distant **theme**). |
| **McTaggart** | A-series (experienced flow) vs B-series (ordered dates). |

**See also:** [rules/R10-dual-time.md](rules/R10-dual-time.md)

---

### R12 — Gödel encoding and universe prime

| Name | Relevance |
|------|-----------|
| **Kurt Gödel** | Arithmetization of syntax; encoding of formal systems as numbers. |
| **Leopold Dirichlet** | Primes in arithmetic progressions (cited in synthesis notes—**theme only**, not a claim about physics). |
| **Max Tegmark** | Mathematical structure as reality (neighbor to static $P$ metaphor). |

**See also:** [rules/R12-universe-prime.md](rules/R12-universe-prime.md)

---

### R13 — Cosmological boundaries

| Name | Relevance |
|------|-----------|
| **Roger Penrose** | Conformal infinity $\mathscr{I}^+$, boundary geometry. |
| **Bekenstein / 't Hooft / Susskind** | Holographic bounds on information in a region. |
| **Cosmology textbooks** | Big Bang as initial boundary condition (model-dependent). |

**See also:** [rules/R13-cosmological-boundaries.md](rules/R13-cosmological-boundaries.md)

---

### R11 — Constrained infinity

| Name | Relevance |
|------|-----------|
| **Max Tegmark** | Level IV multiverse vs internal structure of a single $S_i$. |
| **Set theory / number theory** | Infinite sets with sparse subsets (prime analogy). |

**See also:** [rules/R11-constrained-infinity.md](rules/R11-constrained-infinity.md)

---

### R08 — Equivalence of realities

| Name | Relevance |
|------|-----------|
| **Nick Bostrom** | Simulation hypothesis — base vs nested implementation. |
| **David Chalmers** | Ontological seriousness of simulated experience. |
| **David Deutsch** | Multiverse realism and physical explanation (structural **theme**). |

Former **L07**. **See also:** [rules/R08-equivalence-of-realities.md](rules/R08-equivalence-of-realities.md)

---

## Where to read similar ideas (starting points)

Informal reading list—not a bibliography for footnotes. Use it to explore **related** work, not to cite exact passages.

- Tegmark, M. — *Our Mathematical Universe* (2014)  
- Wheeler, J. A. — “Information, Physics, Quantum: The Search for Links” (1990)  
- Bostrom, N. — “Are You Living in a Computer Simulation?” (2003)  
- Chalmers, D. — “The Matrix as Metaphysics” (2003)  
- Hofstadter, D. — *I Am a Strange Loop* (2007)  
- Wolfram, S. — *A New Kind of Science* (2002) — irreducibility (theme for Q02)  
- Tononi, G. et al. — Integrated Information Theory (2004–; see review literature)  
- Lewis, D. — *On the Plurality of Worlds* (1986)  
- Rawls, J. — *A Theory of Justice* (1971) — veil of ignorance  
- Everett, H. — “Relative State” formulation of QM (1957)  
- Rovelli, C. — relational QM popular and technical expositions  

---

## What this framework does *not* claim

- Novel invention of the **mathematical universe**, **simulation hypothesis**, **IIT**, or **many-worlds** ideas.  
- Empirical validation of quantum avatar entanglement, session amnesia, or eschatological scoring.  
- Endorsement by any person listed above.

For licensing and attribution of **this text**, see the repository [LICENSE](../LICENSE) and [README](../README.md).
