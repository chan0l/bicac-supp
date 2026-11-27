# Supplementary Material — Bi-CAC

Supplementary tables for the manuscript

> **Bi-CAC: A Bi-Level Cooperative Actor-Critic Framework with Cross-Tier Attention
> for Makespan-Minimal Scheduling in Cloud-Edge Collaborative Manufacturing**

## Files

| File | Description |
|---|---|
| `Supplementary_Material.pdf` | The supplement as submitted: four US-Letter pages, single-column body, with Table S3 and Fig. S1 set full width. |
| `Supplementary_Material.docx` | Editable source of the same file. |
| `index.html` | Landing page served by GitHub Pages. |

## Contents

* **S1 — Complete notation.** Table S1 lists every symbol of the model.
* **S2 — Environment and training hyperparameters.** Table S2 gives the individual settings.
* **S3 — Per-scale statistics.** Table S3 (spans both columns) reports makespan (mean ± std over
  20 instances, best-of-four), the average gap and the seed spread for all thirteen methods at
  scales T100–T1000.
* **S3b — Paired statistics.** Table S3b gives the Holm-adjusted p-value and Cliff's δ of Bi-CAC
  against each representative baseline at every scale.
* **S4 — Reward-regularizer sensitivity.** Table S4 sweeps the congestion-penalty weight
  β ∈ {0, 0.02, 0.1}.
* **S5 — Companion gated bank.** Table S5 reports the makespan of all thirteen methods on the
  companion bank in which 30% of the orders are gated by a per-order computation, together with
  the increase relative to the main bank at T1000.
* **S6 — Feasible set.** Table S6 restates the constraints (C1)–(C7) invoked by the model.
* **S7 — Methods and rule primitives.** Table S7 defines the thirteen methods and the three axes
  crossed by rules R1–R6.
* **S8 — Ablation design.** Table S8 states what each of the six ablation variants changes and
  which component it isolates.
* **S9 — Ablation results.** Table S9 reports the relative makespan increase, the 95% confidence
  interval and the paired p-value of each variant.
* **S10 — Reward telescoping and inference cost.** The telescoping of the dense reward and the
  per-decision inference cost.
* **S11 — Architecture and training procedure.** Fig. S1 is the equation-annotated Bi-CAC
  architecture; Algorithm S1 lists the complete training procedure.

Section, equation, figure and table numbers without the `S` prefix refer to the main text.
