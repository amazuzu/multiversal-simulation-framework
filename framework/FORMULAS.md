# Formula guide

**All display math lives here.** Element pages (`axioms/`, `rules/`, `features/`, `assumptions/`, `questions/`) are prose + checks only.

Symbols: [notation.md](notation.md). Constants: [universe.schema.yaml](universe.schema.yaml).

**Convention:** Mix of rigorous logic/QM notation and metaphor (cognitive entropy, ethical score).

---

## Part I — Axioms

### A01 — Existence iff consistency

**Formula**

$$\forall S, \quad \text{Exists}(S) \iff \text{Consistent}(S), \quad \text{Consistent}(S) \iff (S \nvdash \bot)$$

| Piece | Role |
|--------|------|
| $\forall S$ | “For every candidate structure $S$ …” (any formal universe-spec you can write down). |
| $S$ | A **universe-candidate**: axioms + rules + state space (its physics, formalized). |
| $\text{Exists}(S)$ | Predicate: this structure is **actually realized** in the multiverse $\mathcal{M}$. |
| $\iff$ | **If and only if** — the two sides always agree. |
| $\text{Consistent}(S)$ | $S$ never proves a contradiction. |
| $S \nvdash \bot$ | In the proof system of $S$, **⊥** (absurdity / false) is **not derivable**. |
| $\nvdash$ | “Does not prove.” |

**In words:** A universe **exists** exactly when its laws are **logically possible as a whole**—“physics works” means no contradictory theorems inside $S$. There is no extra gate (“hardware,” “energy”) beyond consistency.

**Not claiming:** That every existing universe matches human science, or that consistency is experimentally testable in one line—it is the **ontological rule** of this framework.

---

### A02 — Reality as the set of consistent structures

**Formula 1**

$$\mathcal{R}_{total} \equiv \mathcal{M} = \{ S_i \mid \text{Consistent}(S_i) \}$$

| Piece | Role |
|--------|------|
| $\mathcal{R}_{total}$ | “All of reality.” |
| $\equiv$ | **Defined to be the same as** the right-hand side. |
| $\mathcal{M}$ | The **multiverse**: collection of all structures. |
| $\{ S_i \mid \ldots \}$ | Set of all $S_i$ such that … |
| $S_i$ | One consistent structure (universe index $i$). |

**In words:** Reality **is** the set of every logically consistent mathematical structure. Nothing outside that set is “real” in this framework.

**Formula 2**

$$\text{Matter} \cup \text{Spirit} \subseteq \text{Information}(\mathcal{M})$$

| Piece | Role |
|--------|------|
| $\text{Matter} \cup \text{Spirit}$ | Everything usually called physical **or** mental. |
| $\subseteq$ | Is included in (may be strictly smaller than the full information content). |
| $\text{Information}(\mathcal{M})$ | Information-theoretic description of structures in $\mathcal{M}$ (bits, states, relations—not a single number unless you define a measure). |

**In words:** “Stuff” and “mind” are **modes of information** inside $\mathcal{M}$, not a second kind of substance.

---

### A03 — Consciousness as self-modeling loop

**Formula 1 (feedback loop)**

$$\mathcal{C}(S) > 0 \iff \exists f \subset S \quad \text{such that} \quad f(t+1) = g\big(f(t), \mathbf{M}(f(t))\big)$$

| Piece | Role |
|--------|------|
| $\mathcal{C}(S)$ | Consciousness level of structure $S$ (scalar summary). |
| $> 0$ | “Has consciousness” (non-zero). |
| $\exists f \subset S$ | Some sub-part $f$ of the structure (e.g. a subsystem / agent). |
| $f(t)$ | State of that subsystem at discrete time $t$. |
| $\mathbf{M}(f(t))$ | **Self-model**: internal representation of $f$’s own state. |
| $g(\cdot,\cdot)$ | Update rule: next state depends on current state **and** the model of that state. |
| $f(t+1) = g(f(t), \mathbf{M}(f(t)))$ | **Closed loop**: the system evolves using its self-description. |

**In words:** Consciousness here means **self-referential dynamics**, not merely complexity.

**Formula 2 (integrated information)**

$$\Phi(S) = \mathbf{I}\big(S ; \mathbf{M}(S)\big) > \Phi_{critical}$$

| Piece | Role |
|--------|------|
| $\Phi(S)$ | Integrated information (IIT-inspired): how much $S$ and its self-model **mutually constrain** each other. |
| $\mathbf{I}(S ; \mathbf{M}(S))$ | **Mutual information** between whole structure and self-model (depends on chosen probability measure). |
| $\Phi_{critical}$ | **Constant (you choose):** minimum $\Phi$ to count as a moral/experiential subject in a given implementation. |

**In words:** The loop must be **informationally tight** enough—not a trivial mirror. Implementations must define how $\mathbf{I}$ is computed.

---

### A04 — Local reality normalized to unity

**Formula**

$$\forall n \in S_i, \quad \text{Reality}_{local}(n) = 1, \quad \text{Reality}_{local}(n) = \frac{\text{PerceivedExperience}(n)}{\text{LocalPhysics}(S_i)}$$

| Piece | Role |
|--------|------|
| $n$ | A **node**: an experiencing agent inside universe $S_i$. |
| $S_i$ | One structure (e.g. a simulation instance). |
| $\text{Reality}_{local}(n)$ | **Ontological weight of experience from the inside** (not “is it a sim?” from outside). |
| $= 1$ | **Normalization axiom:** for any valid conscious node, local reality is **full**—never 0.5 because “only a sim.” |
| $\text{PerceivedExperience}(n)$ | Qualia / phenomenology as defined by local physics (symbolic placeholder). |
| $\text{LocalPhysics}(S_i)$ | The rule set and dynamics **inside** $S_i$ that govern what $n$ can experience. |

**In words:** The fraction is a **conceptual ratio**: experience is measured **in the units of the world where it occurs**. The axiom fixes that ratio to 1 for every subject—**simulation labels do not dilute lived reality**.

**Not claiming:** A measurable division in SI units; it is a **normative statement** about perspective.

**Vs M01 / R08:** A04 = per-node phenomenology; R08 = equal structure value; M01 = audit when comparing worlds. See [A04](axioms/A04-inherent-reality.md) and [M01](measures/M01-ontological-parity.md).

---

## Simulation features (formulas)

### FS01 — Entangled base and avatar

**Scope:** Only when [FS01](features/simulation/FS01-session-entanglement.md) is enabled (nested simulation with entanglement coupling). Former law **L01** retired—same content.

**Formula 1 (pure state)**

$$\vert{}\Psi_{Total}\rangle = \frac{1}{\sqrt{2}} \left( \vert{}\text{Entity}_{Base}\rangle \otimes \vert{}\text{Avatar}_{Sim}\rangle \right)$$

| Piece | Role |
|--------|------|
| $\vert{}\Psi_{Total}\rangle$ | Combined quantum state of **base entity + sim avatar** (Hilbert space state vector). |
| $\vert{}\text{Entity}_{Base}\rangle$ | State of the entity in the “outer” / primary layer. |
| $\vert{}\text{Avatar}_{Sim}\rangle$ | State of the embodied instance in the simulation. |
| $\otimes$ | **Tensor product** — joint system with degrees of freedom in both parts. |
| $1/\sqrt{2}$ | Coefficient for a **maximally entangled** two-qubit-style normalization (example, not unique). |

**In words:** One joint system—not a classical copy-paste of memory into a clone.

**Formula 2 (correlation sketch)**

$$\frac{\partial}{\partial t} \rho_{Sim} \longrightarrow \delta \rho_{Base} \quad (E_{PR})$$

| Piece | Role |
|--------|------|
| $\rho_{Sim}$ | **Density matrix** of the simulation subsystem (mixed state in QM). |
| $\frac{\partial}{\partial t}$ | Time evolution (informal: “as sim state changes …”). |
| $\longrightarrow$ | “Implies / correlates with” (not a rigorous theorem here). |
| $\delta \rho_{Base}$ | Small change in base density matrix. |
| $E_{PR}$ | **EPR**-type non-local correlations (Einstein–Podolsky–Rosen). |

**In words:** Updates on the sim side stay **linked** to the base side. **Speculative** narrative device, not a lab protocol.

---

### FS03 — Deferred rendering (superposition until observation)

**Scope:** Only when [FS03](features/simulation/FS03-deferred-rendering.md) is enabled. Former **L04** / **U01** retired—same content.

**Formula 1 (no observer)**

$$\vert{}\psi_{env}\rangle = \sum_{k} c_k \vert{}x_k\rangle \quad \text{for } \hat{O}_{observer} = \emptyset$$

| Piece | Role |
|--------|------|
| $\vert{}\psi_{env}\rangle$ | State of **environment** (not yet fixed detail). |
| $\sum_k c_k \vert{}x_k\rangle$ | **Superposition** of configurations $x_k$ with amplitudes $c_k$. |
| $\hat{O}_{observer}$ | **Observer operator** — interaction channel from candidate to env. |
| $= \emptyset$ | No qualifying observation yet (“null operator” / no coupling). |

**Formula 2 (collapse on observation)**

$$\vert{}\psi_{env}\rangle \xrightarrow{\hat{O}_{observer} \neq \emptyset} \vert{}x_k\rangle \quad P = \vert{}c_k\vert{}^2$$

| Piece | Role |
|--------|------|
| $\xrightarrow{\ldots}$ | Transition when observation turns on. |
| $\vert{}x_k\rangle$ | One definite outcome. |
| $\vert{}c_k\vert{}^2$ | Born-rule **probability** for branch $k$. |

**In words:** **Lazy evaluation** of world detail—QM notation as metaphor for computational / epistemic efficiency.

---

### FS02 — Quantum host (optional sketch)

$$\dim(\mathcal{H}_{\text{host}}) = 2^N \quad \text{(ideal } N \text{ qubits)}$$

Guest update is some map on a subspace of the host Hilbert space (unitary or noisy channel—you specify). See [FS02](features/simulation/FS02-quantum-computer-host.md).

---

## Assumptions (formulas)

### AS02 — Active memory without primary knowledge

**Scope:** Only when [AS02](assumptions/AS02-session-amnesia.md) is enabled. Former law **L02** retired—same content. **Not** a universal claim about Earth or every universe.

**Phenomenology AS02 can explain (when on):** people **do not remember previous lives** because $\mathcal{M}_{\text{prior-lives}} \subset \mathcal{M}_{Primary}$ is excluded from $\mathcal{M}_{Active}$ for each session $[t_{birth}, t_{death}]$.

**Primary partition (conceptual)**

$$\mathcal{M}_{Primary} \supseteq \mathcal{M}_{\text{origin}} \cup \mathcal{M}_{\text{prior-lives}} \cup \mathcal{M}_{\text{meta}}$$

| Subset | Role |
|--------|------|
| $\mathcal{M}_{\text{origin}}$ | Base identity, pre-embodiment, “true” home layer |
| $\mathcal{M}_{\text{prior-lives}}$ | **Past sessions / past lives** — names, deaths, accumulated episodic memory |
| $\mathcal{M}_{\text{meta}}$ | Test/sim status, immortality, judged outcomes, role briefings |

**Formula 1**

$$\mathcal{M}_{Active}(t) = \mathcal{M}_{Total} \setminus \mathcal{M}_{Primary}, \quad t \in [t_{birth}, t_{death}]$$

| Piece | Role |
|--------|------|
| $\mathcal{M}_{Total}$ | All memories the entity **could** access in principle (including prior lives). |
| $\mathcal{M}_{Primary}$ | **Withheld** partition; includes prior-life recall when reincarnation applies. |
| $\setminus$ | Set **difference** — remove primary memories from what is active. |
| $\mathcal{M}_{Active}(t)$ | What actually influences cognition at time $t$ **this life**. |
| $t_{birth}, t_{death}$ | One embodied session (one life). |

**In words:** This life runs on **edited memory**; past lives are not in the edit buffer.

**Formula 2**

$$\mathbb{P}(\text{Action} \mid \mathcal{M}_{Active}) \perp \mathcal{M}_{Primary}$$

| Piece | Role |
|--------|------|
| $\mathbb{P}(\text{Action} \mid \mathcal{M}_{Active})$ | Probability of actions given only active memory. |
| $\perp$ | **Statistical independence** — primary memory does not shift those probabilities. |
| $\mathcal{M}_{Primary}$ | Suppressed set (still exists but not conditioning behavior this life). |

**In words:** Choices this life must be **unbiased** by origin, meta-knowledge, and **memory of prior lives**.

---

### AS03 — Scarcity and choice value

**Scope:** Only when [AS03](assumptions/AS03-artificial-scarcity.md) is enabled. Former law **L03** retired—same content. Otherwise the formulas may still **describe** finite life or entropy without teleology.

**Formula 1**

$$\frac{d S_{entropy}}{d t} > 0, \quad \Delta t_{lifespan} \le T_{max}$$

| Piece | Role |
|--------|------|
| $S_{entropy}$ | Entropy of the environment / body / society (thermodynamic or metaphorical). |
| $\frac{d}{dt} > 0$ | Entropy **increases over time** (second-law flavor). |
| $\Delta t_{lifespan}$ | Length of life in the session. |
| $T_{max}$ | **Constant:** hard cap on lifespan (e.g. ~80 years in [earth-session.yaml](examples/earth-session.yaml)). |

**Formula 2**

$$\text{Value}(\text{Choice}) \propto \frac{1}{\text{ResourceAvailability} \times \text{RemainingTime}}$$

| Piece | Role |
|--------|------|
| $\propto$ | **Proportional to** (up to an unspecified positive factor). |
| ResourceAvailability | How scarce goods, health, safety are (higher ⇒ less scarcity). |
| RemainingTime | Time left until $t_{death}$. |

**In words:** Scarcer resources and less time ⇒ **stakes per choice** rise.

---

## Rules (formulas)

### R06 — Overlapping universes

**Formula 1**

$$S_A \cap S_B = \Omega_{overlap} \neq \emptyset, \quad x \in \Omega_{overlap} \Rightarrow x \models \text{Rules}(S_A) \land x \models \text{Rules}(S_B)$$

| Piece | Role |
|--------|------|
| $S_A, S_B$ | Two universe structures. |
| $\cap$ | **Intersection** — shared domain points. |
| $\Omega_{overlap}$ | Overlap region (non-empty). |
| $x$ | A point / history / state in the joint domain. |
| $x \models \text{Rules}(S_A)$ | $x$ **satisfies** (is a model of) $A$’s rules (logical **⊨**). |

**Formula 2 (law blend)**

$$L_{local}(x) = \alpha L_A(x) + (1 - \alpha) L_B(x), \quad \alpha \in [0, 1]$$

| Piece | Role |
|--------|------|
| $L_A(x), L_B(x)$ | How each universe maps state $x$ to dynamics / constraints (functionals). |
| $L_{local}(x)$ | Effective law in the overlap. |
| $\alpha$ | **Blend constant** — 1 = pure $A$, 0 = pure $B$, between = mixed physics. |

**In words:** Border zones can have **interpolated** laws if both rule sets agree on $x$.

---

### R09 — Cognitive entropy and empathy

**Formula 1**

$$H_{cognitive}(Entity_{Base}) \xrightarrow{\text{Experience}(Sim)} H_{cognitive} - \Delta H_{rejuvenation}$$

| Piece | Role |
|--------|------|
| $H_{cognitive}$ | **Metaphorical entropy** — staleness / habituation of an long-lived mind. |
| $\xrightarrow{\text{Experience}(Sim)}$ | After undergoing the simulation session. |
| $\Delta H_{rejuvenation}$ | Positive drop in entropy (rejuvenation amount). |

**Formula 2**

$$\Delta \text{Empathy} \propto \int_0^T \text{Vulnerability}(t) \, dt$$

| Piece | Role |
|--------|------|
| $T$ | Session duration. |
| $\text{Vulnerability}(t)$ | Exposure to loss, risk, finitude (protocol-measurable proxy). |

---

### R08 — Ontological parity

**Formula 1**

$$\text{OntologicalValue}(S_{Base}) \equiv \text{OntologicalValue}(S_{Sim})$$

**In words:** No ranking of “realness” between base and sim **structures** in $\mathcal{M}$.

**Formula 2**

$$\text{SubjectiveTruth}(n \in S_i) = \text{Invariant}(\mathcal{C}_n)$$

| Piece | Role |
|--------|------|
| $\mathcal{C}_n$ | Conscious structure of node $n$ (A03). |
| $\text{Invariant}(\mathcal{C}_n)$ | What is true **for** $n$ depends only on its conscious structure, not on whether $S_i$ is labeled base or sim. |

---

## Questions (open)

### Q01 — Ethical integral and threshold

*Not a law—see [questions/Q01-existential-purpose.md](questions/Q01-existential-purpose.md).*

**Formula 1**

$$\text{Evaluate}(Entity) = \int_{t_{birth}}^{t_{death}} \mathbf{EthicalChoice}(t) \cdot w(t) \, dt$$

| Piece | Role |
|--------|------|
| $\mathbf{EthicalChoice}(t)$ | Vector or scalar score of morally relevant choices at $t$ (protocol-defined). |
| $w(t)$ | **Weight** — importance of time $t$ (crises vs routine). |
| $\int \ldots dt$ | **Accumulated** moral performance over life *if* post-life review is part of your model. |

**Formula 2**

$$\text{Outcome} = \begin{cases} \text{Passed}, & \text{Evaluate} \ge \Theta_{threshold} \\ \text{Recalibrated}, & \text{otherwise} \end{cases}$$

| Piece | Role |
|--------|------|
| $\Theta_{threshold}$ | **Constant:** passing grade (you define per protocol). |

---

## Constants checklist (per universe)

| Constant | Used in | Typical role |
|----------|---------|----------------|
| $\Phi_{critical}$ | A03 | Minimum integrated information for “subject” |
| $T_{max}$ | AS03 | Lifespan cap |
| $\Theta_{threshold}$ | Q01 | Pass/fail on evaluation (if modeled) |
| $\alpha$ | R06 | Overlap law mix (can vary with $x,t$) |
| $t_{birth}, t_{death}$ | AS02, Q01 | Session window |
| $w(t)$ | Q01 | Ethical weighting function |

Set these in YAML: [universe.schema.yaml](universe.schema.yaml).
