# Math and TCS research

Formal / published research artifacts tied to Astra — not GUI demos.

## Ten Lean-certified advances

<a href="https://openai.com/index/ten-advances-in-mathematics/"><img src="../media/openai-ten-math.jpg" alt="Ten advances in mathematics" width="100%"></a>

- **Author:** OpenAI · announced with [Sébastien Bubeck](https://x.com/SebastienBubeck/status/2083456300692979886)
- **Original:** https://openai.com/index/ten-advances-in-mathematics/ · proofs https://github.com/openai/ten-proofs
- **Date:** 2026-08-01 (Bubeck post) / ongoing publication
- **What it is:** Ten long-open results (non-sofic groups, Connes rigidity, sphere packing, CVP hardness, …) with Lean 4 certificates.
- **Why here:** Strongest public “Astra did research” package — machine-checkable math/TCS, not a vibe demo.
- **Evidence boundary:** Company-reported discovery + Lean certificates; specialist debate on significance continues.

## FrontierMath Erdős (Bloom 68)

<a href="https://epoch.ai/latest/announcing-frontiermath-erdos"><img src="../media/frontiermath-erdos.jpg" alt="FrontierMath Erdős" width="100%"></a>

- **Author:** Epoch AI (Tom Adamczewski, Greg Burnham) + Thomas F. Bloom (U. Manchester); model = pre-release GPT-6 Astra
- **Original:** https://epoch.ai/latest/announcing-frontiermath-erdos · PDF https://epoch.ai/files/frontiermath-erdos.pdf · bench https://epoch.ai/benchmarks/frontiermath-erdos
- **Date:** eval ~2026-08 / announced with Astra era
- **What it is:** 68 Bloom-curated open Erdős conjectures, Lean-checked. Default protocol ($300 / 72h): Astra **2/68 (3%)**, other models 0%. Extra non-protocol attempts: five solutions (#1, #74, #126, #548, #571).
- **Why here:** Formal open-problem research math with machine verification — beyond ten-proofs package and PrimeGaps186.
- **Evidence boundary:** Pre-release Astra; score vs extra attempts carefully separated in the paper; formalization burden + contamination caveats apply.

## Short prime gaps ≤ 186 (Lean + certificate)

- **Author:** GPT-6 Astra / OpenAI · public witness Weijie Su
- **Original:** https://cdn.openai.com/pdf/51126fac-1b68-4128-9666-c908bcc16033/short_gaps.pdf · https://github.com/openai/PrimeGaps186
- **Date:** paper 2026-08-30 · public ~2026-09-03
- **What it is:** $\liminf (p_{n+1}-p_n)\le 186$ with conditional Lean formalization + Python-FLINT numerical certificate (distinct from the ten-proofs package).
- **Why here:** Decade-scale gap-bound progress with machine-checkable scaffolding.
- **Evidence boundary:** **Conditional** on three explicit input axioms (Kloosterman/Deligne-style + numerical caps). Not twin primes.

## Large prime-gap Rankin-term improvement

- **Author:** OpenAI / GPT-6 Astra
- **Original:** https://cdn.openai.com/pdf/51126fac-1b68-4128-9666-c908bcc16033/long_gaps.pdf
- **Date:** ~2026-09-03
- **What it is:** Improves a term in large-gap bounds OpenAI says sat ~unchanged for >80 years.
- **Evidence boundary:** OpenAI-attributed preprint + Lean claim; peer-review status unclear at catalog time.

## Short / large prime-gap improvements (launch science) — index


- **Author:** OpenAI
- **Original:** https://openai.com/index/gpt-6-astra/ · e.g. https://cdn.openai.com/pdf/51126fac-1b68-4128-9666-c908bcc16033/short_gaps.pdf
- **Date:** 2026-09-03
- **What it is:** Launch science add-on: short-gap bound tightened (reported to 186 vs prior 240) and a large-gap improvement, with PDFs.
- **Why here:** Concrete number-theory claim attached to the public model.
- **Evidence boundary:** OpenAI-published proofs; treat as official research claim, not community repro.
