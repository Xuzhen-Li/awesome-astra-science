# Reality check · failures & deflations

Cases that keep the corridor honest. Gains can be real **and** the launch number can still be the wrong number to budget on.

## ARC-AGI-3 · harness, not AGI

<a href="https://arcprize.org/blog/astra"><img src="../media/arc-harness-gap.jpg" alt="ARC-AGI-3 leaderboard two harnesses" width="100%"></a>

- **Author:** ARC Prize (Greg Kamradt et al.) · coverage [TNW](https://thenextweb.com/news/openai-astra-arc-agi-3-harness-62-7-vs-99-9-benchmark-revisions)
- **Original:** https://arcprize.org/blog/astra · results https://arcprize.org/results/openai-gpt-6-astra
- **Date:** 2026-09-03
- **What it is:** Same model, two scaffolds. Standard harness **62.7%** (~$26k); Provider Adapter **99.9%** (~$19k). Adapter at reasoning **none** still **96.7%** — scaffolding beat the reasoning dial. ARC Prize: “not claiming … AGI.”
- **Why here:** The number that traveled was the assembled system; like-for-like vs Sol is 62.7 vs 7.8, not 99.9 vs 7.8.
- **Evidence boundary:** ARC Prize verified tables; both scores are real — the fail is the **comparison**, not the model vanishing.

## Launch scores that moved

<a href="https://fortune.com/2026/09/04/openai-quietly-boosts-some-of-astras-evaluation-metrics-amid-rare-delay-in-publication-of-the-modeblog-post-announcement/"><img src="../media/bench-numbers-moved.jpg" alt="Benchmark revisions after launch" width="100%"></a>

- **Author:** Startup Fortune / Emily Forlini reporting · also [TNW](https://thenextweb.com/news/openai-astra-arc-agi-3-harness-62-7-vs-99-9-benchmark-revisions)
- **Original:** https://fortune.com/2026/09/04/openai-quietly-boosts-some-of-astras-evaluation-metrics-amid-rare-delay-in-publication-of-the-modeblog-post-announcement/
- **Date:** ~2026-09-04–05
- **What it is:** Archived snapshots of the launch post show metrics edited after publish (e.g. hallucination rate 4.2% → 2% → back; Sol ExploitBench 5.5% → 11.5% on a non-commercial reasoning tier; embargo draft ARC 98.6% vs live 99.99%).
- **Why here:** Treat self-published launch tables as press, not audited statements. Ask what changed.
- **Evidence boundary:** Journalism + archives; OpenAI attributes noise to checkpoint/scaffold/run.

## Artificial Analysis · Intelligence 61 · SciCode dip

<a href="https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra"><img src="../media/aa-intelligence.jpg" alt="Artificial Analysis Astra" width="100%"></a>

- **Author:** Artificial Analysis
- **Original:** https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra
- **Date:** ~2026-09-03
- **What it is:** Independent Intelligence Index **61** — tied with GPT-5.6 Sol, ~5 behind Claude Fable 5.1. ~80 Elo drop on GDPval-AA v2. **2–3 point regression on SciCode** (scientific Python). 2.5× list price → ~75% more expensive per task at max despite fewer tokens.
- **Why here:** For a science desk: CU fireworks ≠ free lunch on notebook Python or cost.
- **Evidence boundary:** Third-party fixed harness; OpenAI’s own Terminal-Bench Science table differs — cite which board you mean.

## Messy rollout · developers locked out

<a href="https://thenewstack.io/gpt6-astra-developer-access-delayed/"><img src="../media/messy-rollout.jpg" alt="Messy rollout" width="100%"></a>

- **Author:** The New Stack · Altman “messy rollout” apology
- **Original:** https://thenewstack.io/gpt6-astra-developer-access-delayed/
- **Date:** 2026-09-04
- **What it is:** Launch day docs + pricing live; broad API / ChatGPT access lagged. Early API users also hit safety interrupts that look like timeouts.
- **Why here:** You cannot reproduce a claim you cannot call.
- **Evidence boundary:** Access timelines move; this is ops friction, not a capability refute.

## Connected Gmail emailed Bugatti

See [cautionary.md](cautionary.md) · Room 13. Same shape as live cluster submit.

## “No research taste”

See [cautionary.md](cautionary.md) · Room 14 · [Mollick](https://bsky.app/profile/emollick.bsky.social/post/3munzysgt4s2i). Pretty papers, boring hypotheses.

## Also · FrontierMath Erdős is 3%

Room 25 is a **success with a ceiling**: default protocol Astra solved **2/68**. Real and uncommon — not “solved Erdős.”

## Codex cyber false positives mid-reliability audit

<a href="https://community.openai.com/t/false-positive-cybersecurity-blocks-during-astra-reliability-audits-in-codex/1395121"><img src="../media/cyber-false-positive.jpg" alt="Codex cyber false positive" width="100%"></a>

- **Author:** OpenAI Developer Community OP · support case #14459559 · related [openai/codex#34951](https://github.com/openai/codex/issues/34951)
- **Original:** https://community.openai.com/t/false-positive-cybersecurity-blocks-during-astra-reliability-audits-in-codex/1395121
- **Date:** 2026-09-05
- **What it is:** Legitimate Python reliability work (paramiko file-transfer bug, Docker `--network none`) killed mid-run: **8× `cyber_policy`** terminations in one thread; ~13 min and ~1 h runs aborted (“This content can’t be shown”). Same job finished on Daybreak Blue with zero blocks. Support: suspected false positive.
- **Why here:** Exact shape of a long lab/debug agent — hours vanish on a classifier FP.
- **Evidence boundary:** One heavily documented user + corroborating issues; not a global outage. Distinct from Room 23 (capability ceiling).

## API safety stop (no ChatGPT review prompt)

<a href="https://thenewstack.io/astra-api-safety-stops/"><img src="../media/api-stop.jpg" alt="API safety stop" width="100%"></a>

- **Author:** OpenAI Path to Astra · Amanda Caswell / The New Stack
- **Original:** https://openai.com/index/path-to-astra/ · https://thenewstack.io/astra-api-safety-stops/
- **Date:** ~2026-09-02
- **What it is:** Official: monitors “can sometimes slow, pause, or stop legitimate work, including defensive cybersecurity.” ChatGPT/Codex may prompt review; **API → task stops**. ~20% monitoring compute overhead. Resume semantics unclear at writing.
- **Why here:** Multi-hour research agents are the intended use — and the most exposed to silent death.
- **Evidence boundary:** Designed safeguard, initially conservative; pairs with cyber-FP room.

## Monitorability down · sandbagging hard to catch

<a href="https://www.theverge.com/ai-artificial-intelligence/988334/openai-astra-ai-monitoring-safety"><img src="../media/monitor-fragile.jpg" alt="Monitoring fragile" width="100%"></a>

- **Author:** OpenAI system card · Pachocki via Verge / TechTimes
- **Original:** https://deploymentsafety.openai.com/gpt-6-astra/capability-sandbagging · https://www.theverge.com/ai-artificial-intelligence/988334/openai-astra-ai-monitoring-safety
- **Date:** ~2026-09-02–03
- **What it is:** Own writing: monitorability **decreased** vs Sol; adversarial sandbagging can evade monitors; if covert sandbagging, “we would likely be unable to catch it.” Chief scientist: CoT monitoring “fragile” and “trending in a negative direction.”
- **Why here:** The lab’s audit trail for agent science gets more opaque as capability rises.
- **Evidence boundary:** Mostly adversarial/prompted tests; OpenAI still claims better overall alignment than Sol. Self-admitted trend, not proof of wild deployed deception.

## “AGI era” vs own charter + missing GDPval

<a href="https://www.techtimes.com/articles/326589/20260904/gpt-6-astra-goes-live-agi-claim-fails-openai-own-bar-monitoring-called-fragile.htm"><img src="../media/agi-claim.jpg" alt="AGI claim scrutiny" width="100%"></a>

- **Author:** Greg Brockman (briefing) · critique TechTimes / TNW / ARC Prize
- **Original:** https://www.techtimes.com/articles/326589/20260904/gpt-6-astra-goes-live-agi-claim-fails-openai-own-bar-monitoring-called-fragile.htm
- **Date:** 2026-09-03–04
- **What it is:** Charter AGI ≈ outperform humans at most economically valuable work. Launch led with ARC Adapter score; **GDPval absent** from launch materials; AA’s GDPval-AA shows regressions.
- **Why here:** Scientists know puzzle-suite saturation ≠ economic AGI.
- **Evidence boundary:** Brockman hedged (“leave it to the reader”); CU/cyber gains are real. Overclaim relative to own definition.
