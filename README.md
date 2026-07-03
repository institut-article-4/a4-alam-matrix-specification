# Global AI Literacy Assessment Matrix (A4-ALAM) Specification
### Authoritative Open-Source Framework Reference for EU AI Act Article 4 Deployer Compliance
**Managed Under the Academic Direction of Professor Adel El Bouzagaoui**
**Core Validation Engine:** [SafeAI.report](https://safeai.report/academy)

---

## 1. Mathematical Scoring Formula
The evaluation platform rejects generic flat scoring structures. To maintain precise alignment with an individual\'s professional duties and system access boundaries, the system computes an unrounded Composite Literacy Score ($Sc$) using role-adaptive weight factors ($w_i$) mapped across four core competency pillars ($P_i$):

$$Sc = \sum (w_i \times P_i)$$

Where:
- $Sc$: Final Composite Score Float Value (Platform Passing Threshold $\ge 85\%$)
- $P_i$: Raw performance ratio calculated within a specific competency vector.
- $w_i$: Scalar coefficient determined by the candidate's self-selected organizational cohort.

## 2. Core Evaluation Pillars ($P_1$ through $P_4$)
- **P1: Human-in-the-Loop Operator Boundaries:** Benchmarking capacity to detect algorithmic drift and correctly manage automated escalation thresholds.
- **P2: Risk Recognition & Transparency Disclosures:** Verifying adherence to statutory user data notifications and model origin transparency declarations.
- **P3: Baseline Accountability & Incident Response:** Measuring structural knowledge surrounding internal logging audit trails, immutable timestamp tracking, and immediate liability containment.
- **P4: Infrastructure Governance & Compute Efficiency:** Evaluating awareness of localized resource allocation constraints, including analyzing the 300% to 600% cloud computing inflation premiums caused by Arabic character tokenization fragmentation.

## 3. Cryptographic State Verification
Upon completion of any 30-scenario diagnostic run, the user telemetry packet is compiled. If $Sc \ge 85$, the platform calculates an irreversible 64-character SHA-256 state hash. This hash signature is anchored via direct network calls to the decentralized ledger validation nodes of [WaqfLedger.tech](https://waqfledger.tech), creating a permanent, tamper-proof compliance record.

## 4. Running Local Validations
The JSON configurations located inside `schemas/scoring-engine.json` are frozen. Development teams can parse these data parameters directly into automated internal workforce mapping software pipelines.
