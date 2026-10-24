# Independent Technical Review and Collaboration

This page identifies concrete questions where independent review can improve the research. It is an invitation to evaluate specific claims, not a claim of an existing organization, fundraise, endorsement or production deployment.

## Open engineering questions

### AXOVAR: market-data dependence and risk-policy evidence
[Adversarial source-dependency review](https://github.com/julianvanceblackwood/AXOVAR/issues/3)

The synthetic C++20 demonstration makes source eligibility and financial decision constraints inspectable. A useful review reproduces the normal/degraded scenarios, adds a synthetic upstream-dependency counterexample and reports whether the resulting simulated decision changes for defensible reasons. No real order submission or live data is involved.

### KORDAXIS: from preserved raw evidence to canonical observation
[Generation Zero engineering gate](https://github.com/julianvanceblackwood/KORDAXIS/issues/1)

The raw-evidence persistence boundary is implemented. Questions worth examining include receipt identity versus content identity, event-time versus ingestion-time semantics, preservation of parse failures and how UNKNOWN should propagate into the proposed canonical representation.

### ELENCHION: evidence-bounded claims under failing sensors
[Research Gate 0](https://github.com/julianvanceblackwood/ELENCHION/issues/10)

The project is in research validation, not a running execution-analysis service. A meaningful contribution is a falsifiable benign experiment distinguishing a missing event from evidence of absence, together with explicit sensor coverage, contradiction and provenance assumptions.

### TEICHION: verified compression and hardware record boundaries
[Generation 2 compression primitive](https://github.com/julianvanceblackwood/TEICHION/issues/8)

Review can focus on message-schedule properties, independent reference-vector checks, state-machine correctness, and what the current externally supplied tag input does and does not prove. Key protection, authenticated sealing and physical anti-tamper properties remain outside the implemented boundary.

## What to include in a technical review

- Source revision and tool versions.
- Minimal controlled input, test vector or benign fixture.
- Expected invariant and observed output.
- Reproduction instructions and any counterexample.
- Clear separation between a defect, a hypothesis and a limitation.
- Links to the relevant normative documents.

Security-sensitive discoveries belong in the relevant repository's security reporting route. Do not upload private customer data, credentials, live malware or nonpublic financial information.

## Research and partnership inquiries

Private discussion is appropriate when there is a specific technical problem, an independent verification proposal, an academic project or a bounded engineering collaboration. Please state the problem, your intended contribution and which repository boundary it relates to. Contact: [julianvanceblackwood@gmail.com](mailto:julianvanceblackwood@gmail.com).

Public code availability does not by itself grant redistribution or commercial reuse rights. Licensing and other intellectual-property matters must be clarified for each project before reuse or collaborative code acceptance.

[Research Atlas](PROJECT_ATLAS.md) · [Profile](../README.md)
