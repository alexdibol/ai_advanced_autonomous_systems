# Advanced Autonomous Systems

## From self-improving procedures to adaptive organizations and artificial societies

**Alejandro Reynoso · September 2026**

**A research and teaching collection for AI for Financial Practitioners and Algorithmic Trading**

This repository brings together monographs and Google Colab notebooks examining how autonomy can extend beyond individual answers and actions into the organization of intelligent systems. Its central objects are configurable improvement procedures, adaptive teams, emergent collaboration networks, collectively selected institutions, and interactions across organizational boundaries.

The materials are pedagogically accessible, but the questions are demanding. They examine architectural problems associated with an advanced generation of autonomous systems: how a system can identify its own limitations, reorganize its capabilities, discover complementary agents, participate in choosing rules for collaboration, and transfer knowledge or institutional practices between otherwise separate organizations.

The monographs supply conceptual distinctions, methodological arguments, and interpretations. The notebooks make selected mechanisms inspectable through code, synthetic environments, recorded outputs, and experiments. Together, they support a progression from understanding an autonomous component to reasoning about an adaptive institution.

> **The organizing proposition:** autonomy can migrate from the choice of actions into the choice of procedures, roles, relationships, rules, and boundaries. Each migration changes both the object of study and the evidence required to evaluate it.

**Start here:** [Research agenda][m0] · [Monograph–notebook correspondence](#monographnotebook-correspondence) · [Open in Colab](#notebook-directory-and-colab-links) · [Methodological ladder](#the-methodological-ladder) · [Execution and prerequisites](#execution-and-prerequisites) · [Authorship](#authorship-and-ai-assistance) · [MIT license](#license)

## Why these systems are advanced

“Advanced” describes the level at which adaptation operates and the complexity of the resulting interactions. It does not depend on a large agent count, a particular model brand, or a claim of superior benchmark performance.

Several properties make this collection conceptually demanding:

- **Higher-order adaptation.** The system can search over the procedure used to find solutions, or over the organization responsible for producing decisions.
- **Partial endogeneity of architecture.** Some relationships and configurations arise during the experiment rather than being fully enumerated as a fixed workflow.
- **Distributed knowledge.** Relevant evidence and capabilities are spread across agents with different specialties, information sets, and resource constraints.
- **Institutional feedback.** Collaboration creates a need for rules; selected rules subsequently affect what information circulates and which relationships form.
- **Multiple levels of interaction.** Agents operate within coalitions, coalitions within organizations, and organizations within environments containing other independently governed systems.
- **Bounded authority.** Adaptability must coexist with explicit limits, inspectable decisions, provenance, and mechanisms for accepting or rejecting changes.

The difficulty is methodological as well as computational. A plausible proposal is not yet an improvement; a new network edge is not yet useful cooperation; a generated constitution is not yet an enforced institution; and an observed classroom outcome is not yet evidence of general effectiveness.

The collection studies these distinctions through deliberately bounded laboratories. Its accessibility comes from making the mechanisms visible while preserving the complexity of the questions they raise.

## The methodological ladder

The progression is organized by **what becomes a variable inside the system**. Earlier concepts remain relevant as additional decisions become adaptive. The following rows describe a conceptual ladder, not a claim that every notebook implements every preceding stage or that the files form one executable pipeline.

| Level | Object of adaptation or choice | Central methodological question | Location in this collection |
|---|---|---|---|
| 1. Models and decisions | Forecasts, scores, classifications, or proposed answers | What is the task, and how is answer quality measured? | Statistical and machine-learning forecasts in the STOP application |
| 2. Agents and constellations | Tool use and coordination among specialized roles | Which capabilities and information are available to each participant? | Foundations in the umbrella memorandum and trading examples |
| 3. Feedback | Behavior within a given organization | How do observed outcomes alter subsequent decisions? | Baselines and diagnostic loops in organizational adaptation |
| 4. Improvement of the improver | The scaffold that generates, evaluates, and selects solutions | Can a better search procedure discover better solutions under a defined budget? | STOP teaching note, trading monograph, and forecasting-policy notebook |
| 5. Organizational adaptation | Active specialists, team composition, and coordination plans | When does evidence justify changing the organization itself? | Recursive organizational adaptation and cumulative trading NB04 |
| 6. Relational endogeneity | Collaborators, contracts, and network edges | Can useful organization emerge from dispersed evidence and complementary expertise? | Swarm Discovery |
| 7. Institutional endogeneity | Candidate constitutions and a selected social compact | Which collaboration rules are chosen, and which alter behavior? | Bulletin-board essay and Constitutional Swarm |
| 8. Inter-organizational coordination | Service relationships and temporary alliances | When is obtaining an external capability preferable to acting alone? | Cumulative trading NB05 |
| 9. Boundary crossing | Cross-society information, relationships, and limited compacts | How can separately governed societies collaborate while preserving local constraints? | ESCAPES |
| 10. Institutional transfer and ecology | Imported practices and interaction among adaptive societies | Can an organization return from collaboration with a useful new method or rule? | ESCAPES and umbrella synthesis; broader ecological dynamics remain a research agenda |

Three distinctions hold this ladder together.

**Behavioral and organizational adaptation differ.** Changing a signal weight inside a fixed team changes its policy. Activating or retiring a specialist changes the organization of capabilities. The distinction is meaningful when the changed role has an operational consequence.

**Coordinated and decentralized endogeneity differ.** A supervisor can select a revised configuration from an approved registry. A swarm can develop a collaboration graph through local discoveries and responses. Both make architecture partly variable, but locate organizational choice in different mechanisms.

**Institutional adaptation remains conditional on a designed substrate.** Identities, data structures, communication surfaces, resource limits, voting procedures, and admissible actions still originate in the experimental design. “Endogenous” means that a specified decision is made within that environment; it does not mean that the system creates its entire computational world.

The ladder concerns degrees and locations of autonomy, rather than a binary distinction between fully controlled and fully autonomous systems.

## Monograph–notebook correspondence

The repository currently contains **nine PDF monograph files and seven notebooks**. Their relationship is thematic and, in several cases, directly operational. It is not a one-file-to-one-file correspondence. The table distinguishes direct companions from conceptual extensions.

The identifiers **N1–N7** are navigation labels used only in this README. They do not replace notebook titles or internal course numbering.

| Monograph | Intellectual contribution | Notebook correspondence |
|---|---|---|
| **0. [The Research Agenda: Advanced Autonomous Systems][m0]** | Umbrella framework: autonomy moves from actions toward architecture, institutions, and boundaries. | Orientation for the collection; no single exclusive companion. |
| **1. [Introduction to Self Teaching Optimizers][m1]** — internal title: *When the Improver Improves Itself* | Introduces STOP, scaffolds, utility, meta-utility, and the distinction between improving a solution and improving its search procedure. | **[N1: STOP forecasting-policy laboratory][n1]**, as a bounded financial application of the general principle. |
| **2. [Self Improving Algo Trading][m2]** — internal title: *From Forecasting Models to Self-Improving Trading Systems* | Explains the twenty-model forecasting laboratory, nested search, recorded results, and transfer evaluation. | Direct companion: **[N1][n1]**. The file named “ALGO TRADING SELF TAUGHT OPTIMIZERS” is a different team-adaptation exercise; see N3. |
| **3. [Recursive Organizational Adaptation][m3]** | Develops bounded specialist activation, sandbox comparison, constitutional constraints, and an audit ledger. | Direct companion: **[N2][n2]**. **[N3][n3]** and **[N4][n4]** extend the theme into team formation and inter-constellation interaction. |
| **4. [Swarm Discovery][m4]** | Studies local search, evidence, epistemic signals, complementary responses, simple contracts, and endogenous graphs. | Direct companion: **[N5: Swarm Discovery][n5]**. |
| **5. [Swarms: Agents with a Bulletin Board][m5]** — internal title: *The Bulletin Board: From Artificial Agents to Artificial Societies* | Explores public communication as a minimal institutional primitive and a broader vision of collaboration across unrelated tasks. | Conceptual bridge to **[N6: Constitutional Swarm][n6]** and **[N7: ESCAPES][n7]**. Its broader multi-task society is not fully implemented by a separate notebook here. |
| **6. [Constitutional Swarms][m6]** | Explains the move from endogenous coalitions to partially endogenous institutions: discovery, social awareness, proposals, voting, and governed sharing. | Direct companion: **[N6][n6]**, stored under “SWARMS WITH A BULLETIN BOARD.” |
| **7. [Autonomous Escapes][m7]** — internal title: *ESCAPES: From Artificial Societies to an Ecology of Autonomous Systems* | Develops competence frontiers, boundary crossing, institutional collision, a limited compact, and return with institutional learning. | Direct companion: **[N7: SWARM ESCAPES][n7]**. |
| **8. [A Synthesis of Our Exploration of Autonomous Systems][m8]** | Provides the umbrella perspective for reconsidering the sequence after the experiments. | Integrative reading across N1–N7. Its extracted text currently matches monograph 0: these are two entry points to the same umbrella memorandum. |

### Notebook directory and Colab links

Each notebook has a GitHub link for reading source and saved outputs, and a Colab link for opening an executable copy. A Colab link supplies access to the notebook; runtime prerequisites are documented below.

| ID | Actual subject | Exact repository filename | Open in Colab |
|---|---|---|---|
| **N1** | STOP applied to forecasting-policy and search-scaffold optimization | [SELF TAUGHT OPTIMIZERS_github.ipynb][n1] | [Open N1][c1] |
| **N2** | Recursive organizational adaptation with an approved specialist registry | [RECURSIVE_ORGANIZATIONAL_ADAPTATION_ALGO_TRADING_github.ipynb][n2] | [Open N2][c2] |
| **N3** | Cumulative trading NB04: capability discovery and team reconfiguration | [ALGO TRADING SELF TAUGHT OPTIMIZERS_github.ipynb][n3] | [Open N3][c3] |
| **N4** | Cumulative trading NB05: dynamic ecosystems and temporary alliances | [ALGO TRADING RECURSIVE ORGANIZATIONAL ADAPTATION SYSTEMS_github.ipynb][n4] | [Open N4][c4] |
| **N5** | Swarm Discovery and endogenous decentralized architecture | [SWARM_DISCOVERY_github.ipynb][n5] | [Open N5][c5] |
| **N6** | Constitutional Swarm: discovery, a bulletin board, and collective rule selection | [SWARMS WITH A BULLETIN BOARD_github.ipynb][n6] | [Open N6][c6] |
| **N7** | ESCAPES: interaction and institutional transfer between artificial societies | [SWARM ESCAPES_github.ipynb][n7] | [Open N7][c7] |

**Naming convention.** Existing filenames have been preserved. Use the actual-subject column when choosing a notebook. Internal labels such as NB04 and NB05 occur in different course sequences and are not unique repository-wide identifiers.

**GitHub editions.** The `_github` copies remove the large inserted infographic images. Code, explanatory text, generated outputs, and notebook structure were preserved. The monographs supply complementary conceptual presentation; the notebooks retain their executable teaching content.

## The main topics

### 1. STOP: improving the procedure that improves solutions

The starting distinction is between a candidate solution and the procedure that searches for candidates. A scaffold determines how proposals are generated, evaluated, retained, and revised. If that scaffold affects performance, its design can become an optimization problem.

The original STOP research studies a language-model-assisted improver that can improve programs, including its own scaffolding program, while the underlying language model remains fixed. It explicitly distinguishes this from full recursive improvement of the language model itself. See [Zelikman, Lorch, Mackey, and Kalai, COLM 2024][stop].

The [teaching note][m1] introduces that idea; [N1][n1] and its [trading monograph][m2] implement a narrower application. Twenty statistical, econometric, and machine-learning methods generate forecasts for synthetic market histories. A forecasting policy combines existing models under observable regime proxies. Predictions are prepared before the language-model search, separating expensive forecasting work from repeated policy evaluation.

The **inner loop** proposes and evaluates forecasting policies. The **outer loop** proposes changes to the inner search specification, including candidate counts, rounds, survivor counts, and search instructions. The Python control flow and language-model weights remain fixed. This is configurable scaffold optimization, not unrestricted program rewriting.

A conceptual representation is:

$$
I_{\phi}: p_0 \mapsto p^{\star}_{\phi},
\qquad
M(\phi)=U_{\mathrm{selection}}\left(p^{\star}_{\phi}\right).
$$

An improver configured by $\phi$ searches from an initial policy $p_0$, produces a selected policy $p^{\star}_{\phi}$, and receives a meta-score through that policy's evaluated quality. This notation summarizes the relationship; the notebook defines the actual aggregation across markets and the resource constraints.

The methodological lesson is especially clear in the monograph's recorded example: selection utility increases, but held-out utility deteriorates. “Self-improving” must specify **what improved, under which evaluator, and on which observations**. Those saved results do not establish improved generalization or profitable trading. A forecasting objective also differs from a complete trading objective incorporating positions, turnover, execution costs, and risk limits.

### 2. Recursive organizational adaptation: changing capabilities under governance

[N2][n2] changes the object of adaptation from a forecasting combination to a trading organization's active capabilities. Its [companion monograph][m3] explains how a system can diagnose organizational inadequacy and propose a bounded reconfiguration.

The laboratory creates six synthetic regimes: Calm, Momentum, HighVol, LiquidityStress, Reversal, and Recovery. Each lasts 180 observations. The base organization separates signal generation, risk scaling, execution, and supervision. Three pre-coded specialist capabilities address volatility, liquidity, and mean reversion.

The supervisor studies observable diagnostics and proposes additions or retirements. A deterministic sandbox compares admissible configurations on an observation window. A governance gate deploys a change only when the configured utility gain and constitutional conditions are satisfied. The constitution limits the specialist set, active specialist count, and leverage, and denies the LLM authority to execute arbitrary code or modify the constitution.

This creates a cycle: observe the current organization, diagnose a capability gap, propose alternatives, compare them, authorize a change, and record its consequences. Specialist retirement matters as much as activation: complexity must justify its continued cost.

The implementation also defines the limits of the experiment. It uses known synthetic regime blocks and a 60-observation assessment period within each block. It does not discover the timing of unknown market change points. Diagnosis and candidate comparison reuse the same observation window, while deployment occurs afterward. The exercise illustrates governed reconfiguration; it is not a fully independent evaluation protocol or a production trading system.

### 3. From adaptive teams to interacting constellations

Two cumulative trading notebooks extend the organizational perspective.

**[N3: Build Self-Adapting Agent Systems][n3]** starts from a capability requirement. An observable environment can call for resilience and low volatility, or valuation and resilience. A catalog describes specialists and resource costs. A formation mechanism searches feasible combinations; an optional LLM selects among validated candidate plans. Plans record membership, additions, removals, and dependencies. Mandatory environment, coordination, review, and execution functions remain part of the design.

The experiment distinguishes changing portfolio rankings from changing the team producing them. Its mandate is five unique stocks with 20% weight per stock at rebalance. The question is whether explicit reconfiguration adds value relative to feedback within a fixed organization.

**[N4: Build Dynamic Agentic Ecosystems][n4]** gives Growth, Recovery, and Preservation constellations separate identities, local state, service budgets, and knowledge records. A capability gap can trigger discovery of a provider, a request, an offer, a counteroffer, acceptance or rejection, delivery, and a temporary alliance. Contracts expire; provider capacity is limited; obsolete alliances dissolve.

The connected and isolated ecosystem comparison asks whether external capabilities change allocations and outcomes under a common simulation. It introduces interaction between organizations without assuming that more communication is automatically beneficial.

These notebooks are related extensions, not alternative filenames for N1 or N2. They belong to a cumulative course and require earlier datasets and results. Embedded support modules do not eliminate those dependencies.

### 4. Swarm Discovery: the problem helps shape the organization

[Swarm Discovery][m4] and [N5][n5] investigate relational endogeneity in a synthetic acquisition search. Relevant evidence includes financial characteristics, technology, intellectual property, Gulf-market compatibility, and ownership intentions. Different specialties examine different aspects of the mandate.

Private exploration produces discoveries; selected discoveries become structured signals; complementary agents respond; signal-response pairs create bilateral contracts; contracts produce graph edges and company-centered coalitions; accumulated evidence changes the ranking of hypotheses.

An **epistemic pheromone** is an informational trace that makes a finding available to other searchers. The metaphor concerns coordination through an environment. It does not imply a biological mechanism or prove that the trace is reliable. Here, signals are explicit records with provenance, confidence, novelty, and requested expertise.

The analytical object is a graph $G_t=(V,E_t)$: the population is specified, while meaningful relationships arise through implemented interaction rules. The experiment asks how the distribution of evidence produces a pattern of collaboration.

The executable discovery path uses deterministic scoring. Although an LLM helper is defined, the main search, signal, response, and contract cells do not invoke it. Contracts are generated automatically from qualifying responses; shares follow a fixed formula. This is not an implemented bargaining market.

The final comparison includes simplified solo, central, cooperative, and market-swarm benchmarks. The central benchmark uses broad access to the constructed universe. These are pedagogical counterfactuals rather than a matched-information, equal-budget tournament. They teach students to treat architecture as an experimental variable and ask what a stronger causal comparison would require.

### 5. Bulletin boards and constitutional swarms: making rules partly endogenous

The [bulletin-board essay][m5] asks how much organization can grow from a shared place to communicate. Its broader thought experiment includes unrelated agents pursuing unrelated tasks. A request becomes useful when another participant recognizes a complementary capability or relevant analogy. Communication can support relationships, coalitions, and reusable institutional practices.

The [constitutional-swarm monograph][m6] and [N6][n6] implement a narrower acquisition-search laboratory. Agents begin with private evidence and limited social awareness. Discoveries are evaluated, traces reveal other agents, a bulletin board becomes active, and candidate constitutions are proposed. Agents then choose a social compact through an inspectable voting mechanism.

The architecture is hybrid. LLM calls supply semantic assessment and candidate institutional language. Deterministic preference functions and ballots implement collective selection. Identities, search budgets, the communication primitive, and voting machinery remain designed in advance.

The key question is whether institutional choice changes behavior. In the current executable path, the adopted constitution's sharing threshold filters public signals, which support complementary relationships and coalition formation. Broader provisions concerning verification, rewards, autonomy, dissent, or merge-and-split rules appear in generated text and preference scoring; they are not all implemented as independent enforcement mechanisms.

A constitution can therefore be a proposal, a selected text, an operational parameter, or an enforceable collection of rules. These are different achievements. The notebook makes an initial causal link between constitutional selection and organization visible, while opening a research agenda for stronger rule execution and institutional evaluation.

### 6. ESCAPES: from local societies to bounded interoperability

[ESCAPES][m7] and [N7][n7] examine what happens when useful knowledge lies outside local competence. Three societies represent finance, technology and engineering, and risk/cybersecurity. They have separate agents, communication surfaces, local activity, and institutional commitments.

The worked interaction centers on finance and engineering. An attractive acquisition depends on a technical question that financial expertise cannot resolve. A finance agent gains access to a foreign public board, posts a bounded appeal, and can establish a relationship with a relevant specialist.

The materials distinguish three depths of crossing:

| Depth | What crosses the boundary? | Evidence to inspect |
|---|---|---|
| Informational | A request, claim, finding, or other informational artifact | The foreign post, disclosure scope, and event record |
| Relational | A persistent connection between participants from separate societies | The cross-society relationship and its stated purpose |
| Institutional | A method, verification practice, or rule considered for adoption at home | The transfer record, local acceptance process, and institutional change |

Collaboration reveals a tension: finance emphasizes confidentiality, while engineering requires evidence for replication and criticism. A task-specific compact can define disclosure, verification, membership, attribution, decision rights, duration, exit, provenance, and return rights. The fallback example is the **A–B Technical Diligence Bridge**. Its purpose is interoperability without replacing either society's entire constitution.

The return stage asks whether the originating society acquires more than an answer. It may consider importing independent verification as a method or institutional practice. That is organizational learning without necessarily retraining a model.

“Escape” means an organizational boundary-crossing event. Access to the foreign board is introduced by the experiment; it is not an exploit or an unauthorized escape from a security sandbox. The example also includes specified local constitutions, prepared fallbacks, a pedagogical matching safeguard, and scripted elements of the technical conclusion and transfer. It is a structured demonstration of institutional interoperability, not evidence of an independently evolved open-world society. The broader ecology is the research question that follows.

## A common method for studying the collection

### Identify the object before evaluating the outcome

For each experiment, distinguish the **environment**, **candidate object**, **proposal mechanism**, **admissible changes**, **evaluator**, **selection rule**, and **recorded evidence**. These categories connect the conceptual argument to an implemented mechanism.

| Experimental family | Candidate object | Acceptance or selection mechanism | Evidence that matters |
|---|---|---|---|
| STOP application | Forecasting policy; then improver specification | Numerical utility and candidate selection | Selection scores, held-out transfer, search history, resource use |
| Recursive adaptation | Active specialist configuration | Sandbox comparison and constitutional gate | Before/after configuration, utility gain, deployment, subsequent outcomes |
| Trading teams and ecosystems | Feasible team plan or service relationship | Capability coverage, budgets, validation, contracts | Plan changes, negotiations, deliveries, expiry, connected/isolated outcomes |
| Swarm Discovery | Signals, responses, contracts, collective hypotheses | Fixed local scoring and aggregation | Provenance, network formation, target ranking, benchmark assumptions |
| Constitutional Swarm | Candidate social compact | Deterministic preferences and collective voting | Proposals, ballots, adopted threshold, collaboration graph |
| ESCAPES | Foreign relationship, limited compact, imported practice | Matching, simplified admissibility checks, local acceptance | Crossing events, scope of exchange, compact records, transfer history |

### Separate three kinds of evidence

**Implementation evidence** establishes that a mechanism exists and changes a recorded state. **Experimental evidence** compares outcomes under a specified design. **External validity** concerns whether a result survives different environments, incentives, budgets, or deployment conditions. A notebook can succeed as a teaching instrument while leaving the latter two questions open.

Saved outputs record particular executions. They are not distributions over repeated trials, guarantees of current API behavior, or substitutes for rerunning an experiment. Likewise, an API client does not establish that an LLM contributed to a decision: inspect the actual call path and logs.

### Use the ladder as an experimental discipline

1. **State the incremental hypothesis.** Specify which new degree of freedom is introduced and why it could matter.
2. **Preserve a meaningful baseline.** Keep the task, observable information, evaluation horizon, and resource accounting comparable where the design permits.
3. **Expose the designed substrate.** Record fixed registries, scoring formulas, thresholds, scheduling assumptions, and scripted transitions.
4. **Trace the operational effect.** Connect a proposal to an accepted change and the behavior it enables.
5. **Evaluate beyond selection evidence.** Reserve independent environments or later observations; distinguish policy transfer from transfer of the procedure that found the policy.
6. **Account for complexity.** Measure communication, computation, coordination, and verification costs alongside task performance.
7. **Preserve provenance.** Retain configurations, model identifiers, prompts where applicable, seeds, inputs, responses, decision records, and repository commit.
8. **Report negative and null outcomes.** Failure to improve, a rejected proposal, or an unnecessary coalition can be informative.

Synthetic markets and acquisition universes make these distinctions teachable. Their construction also determines what an experiment can establish. Heterogeneity is often assigned; true regimes may be known to the experimenter; institutional preferences are simplified; and some transitions are deliberately staged.

## Governance and organizational observability

Governance is part of the architecture throughout the collection. The invariant question is: **what may change, who or what may propose it, what may authorize it, and where is the decision recorded?**

The arrangements differ across experiments. N2 keeps its constitution fixed while adapting specialists. N6 selects among candidate collaboration rules within a fixed voting substrate. N7 introduces limited interoperability and consideration of a foreign institutional practice. These should not be collapsed into a claim that all rules are mutable or every stated safeguard is fully enforced in code.

Organizational observability extends beyond explaining a model output. It asks which agent found evidence, why another responded, how a coalition formed, which rule shaped the relationship, what crossed a boundary, and what authority remained local. The audit object can be a search history, configuration ledger, network edge, ballot, or compact.

“Society,” “constitution,” and “institutional learning” are functional descriptions of the computational arrangements studied here. They do not imply consciousness, legal personality, or a complete theory of human institutions.

## Suggested study routes

### Conceptual route

Read the [umbrella memorandum][m0], then the [STOP introduction][m1] and [financial application][m2]. Move to [recursive organizational adaptation][m3], [Swarm Discovery][m4], the [bulletin-board essay][m5], [Constitutional Swarms][m6], and [ESCAPES][m7]. Revisit the [synthesis entry][m8] and explain how the meaning of autonomy changed at each step.

This route suits readers seeking architectural and institutional understanding before executing code.

### Computational route

Pair each monograph with the direct companion in the correspondence table. N1 develops nested optimization; N2 isolates specialist reconfiguration; N5 studies deterministic relational mechanisms; N6 introduces semantic and constitutional generation; N7 examines cross-society interaction.

Treat N3 and N4 as a separate cumulative trading branch after obtaining earlier-course inputs. They add contrasts between team formation within one organization and capability exchange between existing constellations.

For each notebook, a useful student deliverable explains what is fixed, what is adaptive, what counts as evidence, and which result would refute the proposed benefit. Readers who can answer those questions can evaluate an autonomous architecture.

## Execution and prerequisites

### General workflow

Open the notebook using its Colab link, save a working copy if editing, read its setup cells, and execute sequentially. The notebooks use Python with scientific-computing and visualization libraries; some also use scikit-learn, statsmodels, NetworkX, or provider SDKs. Follow each notebook's installation cells rather than assuming one shared environment.

The `_github` suffix concerns embedded-image size. It does not mean every notebook is independent of API access, external data, or earlier-course artifacts.

### Runtime distinctions

| Notebook | Inputs and execution considerations |
|---|---|
| **N1 — STOP** | Generates markets and forecasts internally. Proposal loops require the Colab secret `ANTHROPIC_API_KEY`. The configured API-call budget is 50. |
| **N2 — Recursive adaptation** | Generates its market internally. Includes a deterministic fallback supervisor when an Anthropic client is unavailable; supervisor LLM calls are limited to 6. |
| **N3 — Team reconfiguration** | Requires the cumulative trading dataset and prior results. Initial teaching mode is deterministic. Later demonstration cells explicitly enable LLM planning and use `OPENAI_API_KEY`. |
| **N4 — Dynamic ecosystems** | Requires the cumulative dataset and earlier strategy results for comparisons. Optional live sections use `OPENAI_API_KEY`; the core teaching policy begins in deterministic mode. |
| **N5 — Swarm Discovery** | Builds its acquisition universe internally. Its main path is deterministic. Setup nevertheless requests `ANTHROPIC_API_KEY` through Colab Secrets without a missing-secret guard; `USE_CLAUDE=False` does not itself remove that setup dependency. |
| **N6 — Constitutional Swarm** | Includes synthetic acquisition data and requires `ANTHROPIC_API_KEY` for semantic assessment and constitutional proposals. Voting is deterministic. The configured API-call budget is 28. |
| **N7 — ESCAPES** | Constructs societies internally. Includes fallback responses when no client is available or the call budget is exhausted. The configured API-call budget is 24. |

The Anthropic examples currently contain the model identifier `claude-sonnet-5`; cumulative OpenAI examples contain `gpt-5-nano`. These are configuration values in the deposited notebooks, not a certification of provider availability. Before a live run, check the identifier against models enabled for your account and record changes with your results. Live calls can incur charges and produce different outputs across runs.

### Additional inputs for the cumulative trading branch

N3 and N4 use this Colab project location:

```text
/content/drive/MyDrive/Colab Notebooks/TOPIC_767 ALGORITHMIC_TRADING_AGENTIC_SYSTEMS
```

They expect a `DATASET` directory with a manifest and market tables, and a `RESULTS` directory containing earlier outputs. The loader checks dataset hashes and reads tables such as `universe.csv`, `macro.csv`, `prices.csv`, `fundamentals.csv`, and `news.csv`. Later analyses refer to teacher regimes and earlier equity curves.

**The current repository does not include the preceding NB00–NB03 notebooks, that dataset directory, or the full set of prerequisite result files.** Obtain earlier course materials or restore their generated artifacts before running this branch end to end. Embedded Python modules still load the required data and results.

### Reproducibility status

This README is based on inspection of the deposited PDFs, notebook sources, and saved outputs. It does not certify a fresh end-to-end execution of every notebook. Seeds and deterministic mechanisms support inspection, but live model behavior, package versions, caches, execution order, and external artifacts can affect reproduction. Pin the repository commit and record the runtime when reporting a new result.

## Research directions opened by the collection

Extensions should identify which assumption is being relaxed and what additional evidence is needed.

| Direction | Next methodological step |
|---|---|
| Generalization of improvement procedures | Compare complete inner/outer pipelines over fresh environments and repeated proposal runs, under matched compute budgets. |
| Adaptation under unknown regimes | Replace instructor-known blocks with observable change-detection and decision-timing mechanisms. |
| Economic formation of coalitions | Extend automatic contracts into offers, rejection, negotiation, default, and reputation; compare gains with coordination costs. |
| Executable institutions | Translate constitutional clauses into enforceable state transitions and test violations, amendments, and competing rules. |
| Cross-domain institutional transfer | Test whether an imported practice improves subsequent decisions, beyond producing an adoption record. |
| Robust autonomous ecologies | Study repeated interaction, provenance, harmful signals, concentration of authority, resource competition, and selective interoperability. |

These are research directions, not claims that all capabilities already exist in the notebooks. Their common theme is to make organizational adaptation measurable while preserving the constraints that make it governable.

## Intellectual foundations and citation

The monographs contain their own references and further discussion. Key intellectual connections include:

- **Recursive scaffold improvement:** Zelikman, E., Lorch, E., Mackey, L., and Kalai, A. T. (2024). *Self-Taught Optimizer (STOP): Recursively Self-Improving Code Generation*. COLM 2024. [Primary paper][stop].
- **Multi-agent systems:** Wooldridge, M. (2009). *An Introduction to MultiAgent Systems*, 2nd edition. Wiley.
- **Distributed coordination:** Smith, R. G. (1980). “The Contract Net Protocol: High-Level Communication and Control in a Distributed Problem Solver.” *IEEE Transactions on Computers*, C-29(12), 1104–1113.
- **Swarm intelligence:** Bonabeau, E., Dorigo, M., and Theraulaz, G. (1999). *Swarm Intelligence: From Natural to Artificial Systems*. Oxford University Press.
- **Institutional design:** Ostrom, E. (1990). *Governing the Commons: The Evolution of Institutions for Collective Action*. Cambridge University Press.
- **Complex adaptive systems:** Holland, J. H. (1995). *Hidden Order: How Adaptation Builds Complexity*. Addison-Wesley.

These works inform the vocabulary; the notebooks are pedagogical constructions and adaptations, not reproductions of every cited theory or result. Further material is available in the [Alejandro Reynoso research archive](https://github.com/alexdibol/books).

Suggested citation:

```bibtex
@misc{reynoso2026advancedautonomoussystems,
  author = {Reynoso, Alejandro},
  title = {Advanced Autonomous Systems: Monographs and Computational Notebooks},
  year = {2026},
  howpublished = {GitHub repository},
  url = {https://github.com/alexdibol/ai_advanced_autonomous_systems},
  note = {Teaching and research collection. Cite the specific monograph or
          notebook, repository commit, and access date used.}
}
```

For a specific experiment, identify the filename and commit, and distinguish reproduced results from original saved outputs.

## Authorship and AI assistance

**Author: Alejandro Reynoso.**

Artificial intelligence assisted in the preparation and integration of the monographs and notebooks, including support for drafting, coding, explanation, and editorial organization. **The intellectual direction, conceptual design, methodological framing, and editorial responsibility belong to Alejandro Reynoso.** AI assistance does not transfer authorship or responsibility for the collection to the systems used in its preparation.

The materials are educational and exploratory. Synthetic examples and saved runs illustrate mechanisms within their stated assumptions; they do not establish deployment readiness, general empirical superiority, or investment performance.

**Copyright (c) 2026 Alejandro Reynoso.**

## License

The author's original code and associated documentation in this repository are released under the **MIT License**. The full text appears below and in the [LICENSE](LICENSE) file. Third-party software and externally referenced works retain their respective licenses and rights. The standard text is published by the [Open Source Initiative](https://opensource.org/license/mit).

```text
MIT License

Copyright (c) 2026 Alejandro Reynoso

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

[m0]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/0_The%20Research%20Agenda%20Advanced%20Autonomous%20Systems.pdf
[m1]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/1_Introduction%20to%20Self%20Teaching%20optimizers.pdf
[m2]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/2_Self%20Improving%20%20Algo%20Trading_github.pdf
[m3]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/3_Recursive%20organizational%20adaptation.pdf
[m4]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/4_Swarm%20Discovery.pdf
[m5]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/5_swarms_agents%20with%20a%20bulletin%20board.pdf
[m6]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/6_Constitutional_swarms.pdf
[m7]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/7_Autonomous%20escapes.pdf
[m8]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/monographs/8_A%20synthesis%20of%20our%20exploration%20of%20autonomous%20systems.pdf
[n1]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SELF%20TAUGHT%20OPTIMIZERS_github.ipynb
[c1]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SELF%20TAUGHT%20OPTIMIZERS_github.ipynb
[n2]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/RECURSIVE_ORGANIZATIONAL_ADAPTATION_ALGO_TRADING_github.ipynb
[c2]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/RECURSIVE_ORGANIZATIONAL_ADAPTATION_ALGO_TRADING_github.ipynb
[n3]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/ALGO%20TRADING%20SELF%20TAUGHT%20OPTIMIZERS_github.ipynb
[c3]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/ALGO%20TRADING%20SELF%20TAUGHT%20OPTIMIZERS_github.ipynb
[n4]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/ALGO%20TRADING%20RECURSIVE%20ORGANIZATIONAL%20ADAPTATION%20SYSTEMS_github.ipynb
[c4]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/ALGO%20TRADING%20RECURSIVE%20ORGANIZATIONAL%20ADAPTATION%20SYSTEMS_github.ipynb
[n5]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARM_DISCOVERY_github.ipynb
[c5]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARM_DISCOVERY_github.ipynb
[n6]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARMS%20WITH%20A%20BULLETIN%20BOARD_github.ipynb
[c6]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARMS%20WITH%20A%20BULLETIN%20BOARD_github.ipynb
[n7]: https://github.com/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARM%20ESCAPES_github.ipynb
[c7]: https://colab.research.google.com/github/alexdibol/ai_advanced_autonomous_systems/blob/main/notebooks/SWARM%20ESCAPES_github.ipynb
[stop]: https://arxiv.org/abs/2310.02304
