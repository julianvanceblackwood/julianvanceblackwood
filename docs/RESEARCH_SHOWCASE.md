# Research Showcase — Independent Systems Engineering

**Public research portfolio | Finance, cyber evidence and hardware assurance**

This page is a concise external introduction to four independent engineering and research projects. It is written for engineers who want to evaluate a specific idea, reproduce a test or examine a research assumption. Each repository is the authoritative source for implementation status and limitations.

## AXOVAR — Evidence-constrained financial decision research

[Repository](https://github.com/julianvanceblackwood/AXOVAR) · [Recorded synthetic dashboard replay](https://github.com/julianvanceblackwood/AXOVAR#recorded-demonstration) · [External evaluation](https://github.com/julianvanceblackwood/AXOVAR/blob/main/docs/EXTERNAL_EVALUATION.md)

**Question:** What should a financial research system conclude when reported market prices disagree, arrive late or appear independent but share an upstream source?

**Available today:** A C++20 synthetic-event research engine, explicit eligibility and risk-policy checks, normal/degraded fixtures, a local loopback dashboard, recorded replay and automated verification.

**Review sought:** Independent reproduction, numeric-assurance critique, source-dependency counterexamples and tests for incorrect promotion of evidence into confidence.

**Limits:** No authenticated real-time feeds, exchange connectivity, live trading or production risk approval.

## KORDAXIS — Evidence-native defensive cyber reasoning

[Repository](https://github.com/julianvanceblackwood/KORDAXIS) · [Implemented scope](https://github.com/julianvanceblackwood/KORDAXIS#what-exists-today) · [External evaluation](https://github.com/julianvanceblackwood/KORDAXIS/blob/main/docs/EXTERNAL_EVALUATION.md)

**Question:** How can a defender preserve the basis for a conclusion when logs are incomplete, conflicting or received out of order?

**Available today:** Preserved raw evidence, distinct collection receipts, SHA-256 content identity, PostgreSQL persistence and integrity checks with unit and integration-test coverage.

**Review sought:** Model counterexamples around receipt identity, canonical-observation semantics, source provenance, replay and uncertainty.

**Limits:** Normalization and later mission-level reasoning remain development gates, not an implemented end-to-end product.

## ELENCHION — Evidence-bounded execution intelligence

[Repository](https://github.com/julianvanceblackwood/ELENCHION) · [Current research state](https://github.com/julianvanceblackwood/ELENCHION#current-project-state) · [External evaluation](https://github.com/julianvanceblackwood/ELENCHION/blob/main/docs/EXTERNAL_EVALUATION.md)

**Question:** What is actually justified about a program execution when sensors have blind spots or contradict one another?

**Available today:** Phase Zero research thesis, evidence-bounded claim model and falsification agenda.

**Review sought:** Benign controlled experiments, explicit sensor coverage models, contrary hypotheses and tests that can reveal false certainty.

**Limits:** Not a deployed execution engine, production sandbox or malware-response platform.

## TEICHION — Hardware-owned sequence and record research

[Repository](https://github.com/julianvanceblackwood/TEICHION) · [Current implementation](https://github.com/julianvanceblackwood/TEICHION#current-state) · [Verification instructions](https://github.com/julianvanceblackwood/TEICHION#verification)

**Question:** What record-ordering properties can be checked at a hardware acceptance boundary if the host later becomes untrusted?

**Available today:** SystemVerilog chain-state controller, canonical accepted-record representation, reference vectors and RTL/reference tests.

**Review sought:** Counterexamples around reset, ordering, rejected input, backpressure, canonical bytes and independent reference validation.

**Limits:** No implemented RTL HMAC sealing, protected device key, persistent anti-rollback or physical FPGA security guarantee.

---

## How to engage

A useful technical response includes the project name, commit SHA, operating environment, minimal fixture or test vector, expected result and observed result. Report security-sensitive material using the corresponding repository's private disclosure instructions, not a public issue.

Research collaboration is welcome where a concrete test, specification question or reproducible engineering task exists. For public technical feedback, use the relevant project's issue tracker. For private discussions, use the [profile contact link](https://github.com/julianvanceblackwood).

**Licensing and attribution:** These repositories are public research code, but the reviewed GitHub metadata did not identify an open-source license for the four projects. They should be described as **public/source-available research**, not as licensed open-source packages, until licensing is explicitly decided. Public visibility does not grant redistribution, modification or commercial reuse permission.

No customers, investors, institutional relationships, production deployments, performance returns or external endorsements are claimed.

[Main profile](../README.md) · [Research Atlas](PROJECT_ATLAS.md) · [Collaboration questions](EXTERNAL_COLLABORATION.md)
