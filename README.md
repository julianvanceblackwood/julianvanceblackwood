<div align="center">

# JULIAN VANCE BLACKWOOD

### QUANTITATIVE FINANCE · CRYPTO · BLOCKCHAIN · FPGA · CYBERSECURITY · INTELLIGENCE

**SYSTEMS ENGINEERING AND INDEPENDENT RESEARCH**

Financial infrastructure, digital assets, secure computation and intelligence systems.

I study and build systems where correctness depends on timing, trust, execution, hardware behavior and the quality of the underlying evidence.

[Contact](mailto:julianvanceblackwood@gmail.com) · [GitHub](https://github.com/julianvanceblackwood)

</div>

---

## Focus

My primary interests are quantitative finance and crypto infrastructure. Blockchain protocols, FPGA engineering, cybersecurity and intelligence systems extend that work into settlement, hardware, adversarial environments and decisions made under uncertainty.

These are connected problems.

A trading strategy depends on its data and execution path. A digital asset system depends on custody, authorization and settlement semantics. A security finding depends on what was actually observed. An intelligence assessment depends on the reliability of its sources.

The common engineering task is to identify the guarantees a system needs, locate where those guarantees can fail and make the result independently verifiable.

## 01  Finance and Quantitative Systems

The financial stack is more than a model. It includes data acquisition, time alignment, research methodology, market structure, execution, position keeping, risk controls and recovery.

I am particularly interested in the parts of this stack where apparently small implementation details change financial outcomes.

**Research and market structure**

- Market microstructure, order books, liquidity, transaction costs and execution quality
- Statistical research, numerical methods, time-series analysis and robust backtesting
- Temporal validity, point-in-time data, survivorship bias and look-ahead bias
- Portfolio construction, exposure measurement, scenario analysis and risk limits
- Market data provenance, normalization, sequencing and reconciliation

**Trading and financial infrastructure**

- Deterministic event processing and reproducible simulation
- Low-latency C++ systems, concurrency, memory layout and profiling
- Order lifecycle modeling, idempotency, acknowledgments, fills and cancellations
- Accounting invariants, cash and position reconciliation, settlement and audit trails
- Failure handling when market data is late, duplicated, missing or inconsistent

The research result is not separate from its implementation. A backtest that violates event ordering is unreliable. An execution engine that loses track of an acknowledgment is unsafe. A risk limit that cannot be enforced during degraded operation is not a sufficient control.

My standard is to connect the hypothesis, the data, the execution assumptions and the measured outcome. Performance numbers must include the workload and measurement method. Research claims must survive chronological validation and realistic costs.

## 02  Crypto and Digital Asset Infrastructure

Crypto spans financial infrastructure and applied cryptography. Both matter.

Digital asset systems combine markets, custody, transaction construction, signing, identity, network behavior and settlement. Failures can cross those boundaries quickly, especially when a service treats a valid message as evidence of a valid business action.

**Digital asset engineering**

- Exchange infrastructure, market connectivity, pricing and liquidity
- Wallet architecture, key custody, signing policies and transaction authorization
- Transaction lifecycle analysis, confirmation assumptions and reconciliation
- Asset accounting, transfer limits, exposure controls and operational recovery
- On-chain and off-chain state consistency

**Cryptographic foundations**

- Hash functions, message authentication, signatures and authenticated data
- Key lifecycle, entropy assumptions, domain separation and replay resistance
- Canonical encoding, serialization, transcript integrity and protocol composition
- Trust boundaries between host software, secure elements and hardware logic
- Verification against published specifications, reference vectors and independent implementations

A cryptographic primitive can be mathematically sound while the surrounding system remains vulnerable. Key ownership, transaction intent, message context and recovery procedures are part of the security model.

I am interested in implementing and understanding the underlying mechanisms, not merely calling an API and assuming that the resulting system is secure. Experimental cryptographic code must remain separate from production use until it has received the necessary validation and expert review.

## 03  Blockchain and Protocol Systems

A blockchain is a replicated state machine operating under explicit assumptions about consensus, network behavior and adversarial participants.

Its important properties are expressed through rules rather than branding.

- Consensus, finality, forks, reorganization and validator assumptions
- State transitions, transaction ordering, fees and resource accounting
- Mempools, propagation, peer behavior and network-level failure
- Smart contract execution, permissions, upgrade paths and invariant testing
- Bridges, oracles, cross-domain messages and the limits of inherited trust
- Settlement guarantees, replay protection, auditability and recovery

A successful transaction submission is not final settlement. A compatible interface does not imply compatible semantics. A valid signature does not establish that every surrounding authorization condition was satisfied.

I approach protocols through their state machines, byte formats, invariants and failure behavior. The objective is to determine precisely what each participant can know and what each transition guarantees.

## 04  FPGA and Hardware Systems

Hardware matters when software abstractions are no longer sufficient to explain timing, trust or physical behavior.

My work and research interests include digital design, electronics, embedded computing and hardware-software boundaries, with particular attention to security and deterministic processing.

- RTL design with explicit state transitions and interface contracts
- FPGA-oriented datapaths, pipelines, registers and finite-state machines
- Clock domains, reset behavior, latency budgets and timing closure
- Bit-level arithmetic, fixed-width representations, overflow and endianness
- Hardware-rooted evidence, integrity chains and protected state
- Testbenches, simulation, assertions, trace analysis and reproducible verification
- Hardware-software co-design for financial, cryptographic and security workloads

A simulation pass is not timing closure. A correct software reference is not proof of equivalent RTL behavior. A hardware security boundary is meaningful only when its assumptions, interfaces and failure modes are specified.

I prefer small, inspectable units with precise contracts. Verification starts with the representation of state and the conditions under which that state may change.

## 05  Cybersecurity and Secure Systems

My security focus is defensive research and the engineering of systems that remain understandable under adversarial conditions.

I study how trust is established, how authority is delegated, how execution changes state and how evidence can be distorted or lost.

- Operating systems, Linux internals, networking and systems programming
- Threat modeling, attack-surface analysis and authorization boundaries
- Reverse engineering, program analysis and malware analysis in controlled environments
- Vulnerability research and protocol security in authorized scope
- Secure software architecture, isolation, memory safety and defensive design
- Incident reconstruction, digital forensics, telemetry integrity and response engineering
- Supply-chain risk, dependency review and reproducible builds

Tools provide observations. They do not replace a model of the system.

A detection must account for sensor coverage. An authorization check must be evaluated along the full path to the protected action. A defensive decision must consider false positives, containment effects and the possibility of incomplete evidence.

Security is a property of the operating system, application, protocol, hardware and human process together.

## 06  Intelligence and Decision Systems

Intelligence engineering begins with a distinction between observation and conclusion.

A record may be authentic without being accurate. An event may be absent from telemetry without being absent from reality. Two sources may agree because they share the same underlying error.

I am interested in systems that preserve those distinctions while supporting useful decisions.

- Intelligence data engineering, collection boundaries and source provenance
- Entity resolution, relationship analysis and temporal reconstruction
- Evidence fusion, competing hypotheses and contradiction handling
- Uncertainty representation, confidence calibration and analytical traceability
- Cyber threat intelligence, operational context and mission consequence
- Human-machine decision support with explicit authority and review boundaries
- Defensive and defense-oriented systems operating with limited or contested information

The analyst should be able to trace a conclusion to its inputs, assumptions and transformations. Where the evidence is insufficient, the system should say so.

Automation can organize information and test hypotheses. It should not silently convert an inference into an established fact.

## Supporting Engineering Disciplines

| Discipline | Areas of study and engineering |
| :--- | :--- |
| Systems programming | C, C++, Python, Linux, memory management, concurrency, operating systems |
| Performance engineering | Profiling, cache behavior, latency distributions, benchmarking, deterministic execution |
| Distributed systems | Replication, consistency, messaging, ordering, failure detection, recovery |
| Protocol engineering | Binary formats, parsers, state machines, compatibility, identity, authentication |
| Mathematics and statistics | Probability, inference, optimization, numerical stability, stochastic modeling |
| AI and machine learning | Data quality, model evaluation, uncertainty, decision support, safe integration |
| Electronics and embedded systems | Digital logic, interfaces, FPGA, firmware, hardware-software integration |
| Behavioral and strategic analysis | Incentives, adversarial reasoning, human factors, decision-making under uncertainty |

These disciplines are supporting foundations, not claims of equal depth or mastery in every area.

## Engineering From First Principles

I favor direct ownership of critical system behavior.

That means understanding the representation, memory model, state transitions, algorithms and failure conditions beneath an interface. When a core dependency is central to the problem, I prefer to build a focused implementation that can be read, tested, measured and maintained.

This applies to libraries as much as to applications.

**Library engineering is part of the work.**

- Define the public contract before implementing the internals
- Keep interfaces narrow and separate mechanisms from policy
- Make ownership, lifetimes, error states and invariants explicit
- Test edge cases, malformed inputs, boundary conditions and recovery paths
- Use reference vectors, property tests, fuzzing and differential testing where appropriate
- Benchmark representative workloads and document measurement conditions
- Maintain build reproducibility, portability and an understandable versioning policy

A custom implementation is justified by control, auditability, research value or measured constraints. It is not justified by the desire to avoid dependencies at any cost.

External components require the same scrutiny as internal code: provenance, license, maintenance, attack surface and operational risk. Established, security-critical implementations should not be replaced in production by unreviewed experimental cryptography.

The goal is engineering independence. It comes from understanding the system well enough to make and defend the implementation choice.

## How I Work

    DEFINE THE PROBLEM
           |
    IDENTIFY INVARIANTS
           |
    MODEL STATE, TIME AND TRUST
           |
    BUILD A MINIMAL REFERENCE
           |
    TEST FAILURE AND ADVERSARIAL CASES
           |
    MEASURE REAL CONSTRAINTS
           |
    REFINE THE IMPLEMENTATION
           |
    VERIFY AND DOCUMENT THE RESULT

I work from a testable claim toward an implementation, not from a preferred technology toward a justification.

A design begins with what must remain true. A prototype establishes whether the idea can work. Verification determines whether the behavior matches the contract. Measurement determines whether further specialization is necessary.

Every meaningful optimization has to preserve correctness.

### Review standard

| Concern | Question |
| :--- | :--- |
| Correctness | Which invariants are guaranteed and how are they tested? |
| Time | Can ordering, freshness or clock assumptions invalidate the result? |
| Trust | Which inputs and actors can change protected state? |
| Failure | What remains correct during partial failure or recovery? |
| Performance | What was measured, under which workload and on which hardware? |
| Evidence | Can another engineer reproduce the claim? |
| Maintainability | Can the design be understood without relying on its original author? |

## Research Discipline

I distinguish a hypothesis from a result and a result from an operational guarantee.

A prototype is not a deployed platform. A simulation is not a field measurement. A passing test suite does not establish the absence of defects. A benchmark is not meaningful without context. Security claims require a defined threat model.

Research notes, specifications, test vectors, experiments, failure cases and limitations are part of the engineering artifact. Documentation should explain why a system takes its shape, not merely how to run it.

I value small, consequential changes over activity for its own sake. A commit should improve the system, its verification or the ability of another engineer to understand it.

## Long-Term Direction

My objective is to develop independent technical depth across financial computation, crypto infrastructure, protocol systems, hardware security and intelligence engineering.

These fields meet at the boundaries that matter most: money moving through networks, instructions changing protected state, hardware enforcing trust, evidence informing decisions and systems recovering when assumptions fail.

I want to understand those boundaries from the mathematical model to the machine-level implementation, and to build the components needed when existing abstractions are inadequate.

<div align="center">

---

**CORRECTNESS BEFORE SPEED**

**EVIDENCE BEFORE CONCLUSIONS**

**CONTROL THROUGH UNDERSTANDING**

[Private contact](mailto:julianvanceblackwood@gmail.com)

<sub>JULIAN VANCE BLACKWOOD · ENGINEERING · RESEARCH</sub>

</div>
