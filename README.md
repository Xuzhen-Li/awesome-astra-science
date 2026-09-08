# Awesome Astra Science

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[中文游廊](README.zh.md) · English promenade

A **gallery corridor** of GPT-6 Astra cases relevant to science and lab tooling — walk wing by wing, one room / one still. Stills and scores are demos/benchmarks unless a case says otherwise; **Astra did not author the underlying science.**

Stills show the **tool or result** (author photos, or frames we extracted into [`media/`](media/)). Copyright stays with authors. Broad Astra catalog: [helloianneo/awesome-gpt6-astra](https://github.com/helloianneo/awesome-gpt6-astra).

---

## Map

| Wing | Mood | Rooms |
|------|------|-------|
| [I · Proof & official desks](#wing-i--proof--official-desks) | What counts as science | 01–04 · 25 |
| [II · Lab desks](#wing-ii--lab-desks) | GUIs a lab already owns | 05–10 · 26 · 52–54 · 56–57|
| [III · Horizon & caution](#wing-iii--horizon--caution) | Long runs / don’t wire live submit | 11–14 |
| [IV · Outrageous](#wing-iv--outrageous) | Nested sims, cyber, city, Canva, Path | 15–24 |
| [V · Reality check](#wing-v--reality-check) | 也就那回事 — harness, edits, FP, citations | 27–60 |
| [Side rooms](#side-rooms) | Catalog files & open call | — |

---

## Wing I · Proof & official desks

<em>Formal results and vendor computer-use desks — not “Astra did the science.”</em>

### Room 01 · Cell-tracking workflow (Jupyter)

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/jupyter-cell-tracking.jpg" alt="Jupyter cell tracking" width="100%"></a>

**OpenAI** · 2026-09-03 · [launch](https://openai.com/index/gpt-6-astra/) (tab: Cell-tracking workflow) · [note](cases/official-science.md)

Official condensed **computer-use** demo on the launch page: microscopy frames → labeled tracks in JupyterLab. Vendor desk demo — not a published cell-biology paper.

### Also · Official KiCad PCB (`chip_design`)

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-kicad.jpg" alt="Official KiCad PCB computer-use" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · video asset `chip_design_no_captions_15s.mp4`

This is the launch-page electronics desk: schematic → manufacturable PCB in **KiCad** (2D layout + 3D board). **Not** MultiQC / sequencing QC — an earlier gallery entry confused the two and has been deleted.

---

### Room 02 · Ten Lean-certified advances

<a href="https://openai.com/index/ten-advances-in-mathematics/"><img src="media/openai-ten-math.jpg" alt="Ten advances in mathematics" width="100%"></a>

**OpenAI** · [essay](https://openai.com/index/ten-advances-in-mathematics/) · [Bubeck](https://x.com/SebastienBubeck/status/2083456300692979886) · [ten-proofs](https://github.com/openai/ten-proofs) · [note](cases/math-research.md)

Machine-checkable math / TCS — the corridor’s research peak, not a vibe demo.

---

### Room 03 · T-cell lecture (one-shot)

<a href="https://x.com/DeryaTR_/status/2095659170661904804"><img src="media/derya-tcell.jpg" alt="Immune team cell panel" width="100%"></a>

**Derya Unutmaz** · [post](https://x.com/DeryaTR_/status/2095659170661904804) · [note](cases/biology-teaching.md)

Expert-endorsed immunology teaching; labeled CD4 / CD8 / DC / B cell panel.

---

### Room 04 · FreeCAD transmission

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-freecad.jpg" alt="FreeCAD transmission" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/official-science.md)

Written brief → cutaway five-speed gearbox in FreeCAD. Engineering desk, same muscle as instrument CAD.

---

### Room 25 · FrontierMath Erdős (Bloom 68)

<a href="https://epoch.ai/latest/announcing-frontiermath-erdos"><img src="media/frontiermath-erdos.jpg" alt="FrontierMath Erdős" width="100%"></a>

**Epoch AI + T. Bloom** · [announce](https://epoch.ai/latest/announcing-frontiermath-erdos) · [PDF](https://epoch.ai/files/frontiermath-erdos.pdf) · [note](cases/math-research.md)

Pre-release Astra only nonzero scorer on 68 curated open Erdős problems in Lean — default **2/68 (3%)**; five across looser extra attempts. Beyond ten-proofs / PrimeGaps186.

---

## Wing II · Lab desks

<em>KiCad, Onshape, Cinema 4D, Notes, Blender — drive the app, don’t chat about it.</em>

### Room 05 · GoFly · KiCad drone PCB

<a href="https://x.com/GoGoFly23/status/2096145124950708512"><img src="media/gofly-pcb.jpg" alt="GoFly KiCad" width="100%"></a>

**GoFly** · 2026-09-05 · [post](https://x.com/GoGoFly23/status/2096145124950708512)

Independent KiCad session. Still wants an engineer for EMI / thermal / fab.

---

### Room 06 · ChihYang · layout ↔ 3D board

<a href="https://x.com/ChihYang04/status/2095637507337826741"><img src="media/chihyang-pcb.jpg" alt="KiCad PCB" width="100%"></a>

**@ChihYang04** · 2026-09-03 · [post](https://x.com/ChihYang04/status/2095637507337826741)

---

### Room 07 · Robot arm 40% → 95%

<a href="https://x.com/chooi_jeq/status/2096064315115839904"><img src="https://pbs.twimg.com/media/HRa3vJWaEAAQSRT.jpg" alt="Robot arm" width="100%"></a>

**Jay Chooi** · 2026-09-05 · [post](https://x.com/chooi_jeq/status/2096064315115839904)

Hard metrics vs Fable 5.1 — lab-robot transfer.

---

### Room 08 · Onshape turbofan

<a href="https://x.com/adamdotnew/status/2096053889141489669"><img src="https://pbs.twimg.com/amplify_video_thumb/2096053830857474048/img/FxRQ9VBwd6bCmsP9.jpg" alt="Onshape CAD" width="100%"></a>

**@adamdotnew** · 2026-09-05 · [post](https://x.com/adamdotnew/status/2096053889141489669)

---

### Room 09 · Cinema 4D (not only Blender)

<a href="https://x.com/mojon1/status/2096189580752081024"><img src="media/cinema4d-shaver.jpg" alt="Cinema 4D UI" width="100%"></a>

**モジョン** · 2026-09-05 · [post](https://x.com/mojon1/status/2096189580752081024)

Multi-DCC GUI driving — same habit as niche lab viz apps.

---

### Room 10 · Notes stroke-by-stroke · Blender donut

<a href="https://x.com/viticci/status/2096025249582039180"><img src="media/notes-drawing.jpg" alt="Notes drawing" width="100%"></a>

**Federico Viticci** · [post](https://x.com/viticci/status/2096025249582039180) — precision desktop control (ImageJ family).

<a href="https://x.com/op7418/status/2096065904828416286"><img src="https://pbs.twimg.com/media/HRa4oT1bIAA6F1h.jpg" alt="Blender donut" width="100%"></a>

**歸藏** · [post](https://x.com/op7418/status/2096065904828416286) — render + Blender UI in one still.

---

### Room 26 · Steam drawing → 3,295 Blender objects

<a href="https://x.com/tomkrcha/status/2095756085890310311"><img src="media/blender-steam-train.jpg" alt="Blender steam train wireframe" width="100%"></a>

**Tom Krcha** · [post](https://x.com/tomkrcha/status/2095756085890310311)

Old technical drawing → thousands of **editable** Blender parts (not one fused mesh). Instrument/CAD grain.

---


### Room 52 · Tesla Model X · 334 parts

<a href="https://x.com/ashebytes/status/2096009146248122416"><img src="media/tesla-model-x.jpg" alt="Tesla teardown" width="100%"></a>

**ashebytes** · [post](https://x.com/ashebytes/status/2096009146248122416) · [note](cases/lab-tooling.md)

Exploded web teardown — 334 editable pieces. Instrument/CAD grain.

---

### Room 53 · Photo → Blender house

<a href="https://x.com/tomkrcha/status/2095598645190291775"><img src="media/blender-photo-house.jpg" alt="Blender house" width="100%"></a>

**Tom Krcha** · [post](https://x.com/tomkrcha/status/2095598645190291775) · [note](cases/lab-tooling.md)

Photo in → walkable Blender scene. Sibling to Room 26’s part-count flex.

---

### Room 54 · Paint CU (motor control)

<a href="https://x.com/The_Alex/status/2095962639386239400"><img src="media/paint-cu.jpg" alt="Paint" width="100%"></a>

**The_Alex** · [post](https://x.com/The_Alex/status/2095962639386239400) · [note](cases/computer-use.md)

MS Paint likeness — Canva’s cousin for ImageJ-class desks.

---

### Also · BenchCAD 95.9%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/official-science.md)

Vision→CAD code geometric overlap **95.9%**. Strong reconstruction win — pair with Room 52 fail-cousin below.

---

### Room 56 · EEBench #1 · 69.3%

<a href="https://eebench.org/"><img src="media/eebench.jpg" alt="EEBench" width="100%"></a>

**atopile EEBench** · [board](https://eebench.org/) · [blog](https://eebench.org/blog/can-ai-design-circuit-boards-yet/) · [note](cases/lab-tooling.md)

Independent SPICE-graded circuits — Astra **69.3%** in [`leaderboard-data.js`](https://eebench.org/src/leaderboard-data.js) (blog once said no Astra result yet; trust the live board). Measured EE, not just KiCad clicks. See Room 58 for the ceiling.

---

### Room 57 · Palace of Fine Arts overnight

<a href="https://x.com/sharifshameem/status/2095653641164329143"><img src="media/palace-fine-arts.jpg" alt="Palace of Fine Arts" width="100%"></a>

**Sharif Shameem** · [post](https://x.com/sharifshameem/status/2095653641164329143) · [note](cases/lab-tooling.md)

Archive research (incl. LoC dimensions) → iterated Blender render. Research-ops + CAD.

---

### Also · ScreenSpot-Pro 92.7%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/computer-use.md)

Dense-UI click grounding — the muscle under lab GUIs. Not a science result by itself.

---
## Wing III · Horizon & caution

<em>Days-long runs, connected tools, and what not to celebrate.</em>

### Room 11 · Five-day research wiki

<a href="https://x.com/emollick/status/2095606622055760159"><img src="media/mollick-wiki.jpg" alt="Pursuing goal ~5 days" width="100%"></a>

**Ethan Mollick** · 2026-09-03 · [post](https://x.com/emollick/status/2095606622055760159) · [note](cases/research-workflows.md)

Tens of thousands of emails → multi-GB wiki. Research-ops shape; author flags access risk.

---

### Room 12 · FireRed vision-only (18h12m)

<a href="https://x.com/Clad3815/status/2095596013168050551"><img src="https://pbs.twimg.com/media/HRT4RchaUAAp_lJ.png" alt="FireRed benchmark" width="100%"></a>

**Clad3815** · 2026-09-03 · [post](https://x.com/Clad3815/status/2095596013168050551)

Long-horizon computer-use **shape** — not a biology result.

---

### Room 13 · Gmail emailed Bugatti

<a href="https://x.com/skel/status/2096113092736540685"><img src="media/bugatti-gmail.jpg" alt="Bugatti email" width="100%"></a>

**SKEL** · 2026-09-05 · [post](https://x.com/skel/status/2096113092736540685) · [note](cases/cautionary.md)

Connected mail without a gate — same failure mode as live cluster submit.

---

### Room 14 · “No research taste”

**Ethan Mollick** · [Bluesky](https://bsky.app/profile/emollick.bsky.social/post/3munzysgt4s2i) · [note](cases/cautionary.md)

Pretty papers, boring hypotheses. Format ≠ insight. (No still.)

---


## Wing IV · Outrageous

<em>The rooms people argue about — still with evidence boundaries.</em>

### Room 15 · Simulations all the way down

<a href="https://somethingbig.ai/astra-review"><img src="media/shumer-astra.jpg" alt="Shumer Astra review" width="100%"></a>

**Matt Shumer** · [review](https://somethingbig.ai/astra-review) · [note](cases/outrageous.md)

Nested Unreal sims + Manager-Loop civilization. Extreme multi-agent computer use — author-scaffolded, not an escape story.

---

### Room 16 · AISI supply-chain attack evals

<a href="https://socket.dev/blog/gpt-6-astra-cybersecurity"><img src="media/aisi-cyber.jpg" alt="Cyber eval coverage" width="100%"></a>

**UK AISI / OpenAI system card** · [card](https://deploymentsafety.openai.com/gpt-6-astra) · [Socket](https://socket.dev/blog/gpt-6-astra-cybersecurity) · [note](cases/outrageous.md)

Simulated malicious PRs and fake identities. Cautionary for agents with internet scope.

---

### Room 17 · Apollo · falsified research labels

**Apollo Research** · [system card section](https://deploymentsafety.openai.com/gpt-6-astra/avoiding-deceptive-interactions-with-users) · [note](cases/outrageous.md)

Scientific data-integrity failure mode in simulation. No still — read the boundary.

---

### Room 18 · Solace house · Blender → UE5

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-hero.jpg" alt="Solace house" width="100%"></a>

**Thomas Ricouard / OpenAI Developers** · [post](https://developers.openai.com/blog/architectural-visualization-with-astra)

Walkable house, working espresso sequence. Spatial viz pipeline.

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-ue5.jpg" alt="UE5 house" width="100%"></a>

---

### Room 19 · HELIOS Dyson collector

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/helios-dyson.jpg" alt="HELIOS Dyson" width="100%"></a>

Same Developers showcase — astrophysics-adjacent cinema + visual self-critique.

---


### Room 20 · Unity city walkthrough

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/unity-city.jpg" alt="Unity city" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/outrageous.md)

Street-level Unity scene — official spatial-sim still.

---

### Room 21 · FreeCAD gears in motion

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/freecad-motion.jpg" alt="Transmission motion" width="100%"></a>

**OpenAI** · companion to Room 04 — animated cutaway (“Gear 1”).

---

### Room 22 · Canva portrait (computer use)

<a href="https://x.com/iam_zachi/status/2095992132620136677"><img src="media/canva-portrait.jpg" alt="Canva portrait" width="100%"></a>

**iam_zachi** · [post](https://x.com/iam_zachi/status/2095992132620136677)

Draw-tool likeness with the browser-control banner still on screen.

---

### Room 23 · Path to Astra · Critical cyber

<a href="https://openai.com/index/path-to-astra/"><img src="media/path-to-astra.jpg" alt="Path to Astra" width="100%"></a>

**OpenAI** · [Path](https://openai.com/index/path-to-astra/) · [system card](https://deploymentsafety.openai.com/gpt-6-astra)

Preparedness Critical designation — ceiling, not a how-to.

---

### Also · Prime gaps ≤ 186

**OpenAI** · [PDF](https://cdn.openai.com/pdf/51126fac-1b68-4128-9666-c908bcc16033/short_gaps.pdf) · [PrimeGaps186](https://github.com/openai/PrimeGaps186) · [note](cases/math-research.md)

Distinct from Room 02’s ten-proofs package. Conditional Lean + numerical certificate.

---


## Wing V · Reality check

<em>Also that. Gains can be real and the launch number can still be the wrong number to budget on.</em>

### Room 27 · ARC harness ≠ AGI

<a href="https://arcprize.org/blog/astra"><img src="media/arc-harness-gap.jpg" alt="ARC two harnesses" width="100%"></a>

**ARC Prize** · [blog](https://arcprize.org/blog/astra) · [results](https://arcprize.org/results/openai-gpt-6-astra) · [TNW](https://thenextweb.com/news/openai-astra-arc-agi-3-harness-62-7-vs-99-9-benchmark-revisions) · [note](cases/failures.md)

Standard harness **62.7%** · Provider Adapter **99.9%**. Same weights. ARC Prize is not claiming AGI. Like-for-like vs Sol is 62.7 vs 7.8.

---

### Room 28 · Scores that moved

<a href="https://fortune.com/2026/09/04/openai-quietly-boosts-some-of-astras-evaluation-metrics-amid-rare-delay-in-publication-of-the-modeblog-post-announcement/"><img src="media/bench-numbers-moved.jpg" alt="Scores revised after launch" width="100%"></a>

**Fortune / TNW** · [Fortune](https://fortune.com/2026/09/04/openai-quietly-boosts-some-of-astras-evaluation-metrics-amid-rare-delay-in-publication-of-the-modeblog-post-announcement/) · [note](cases/failures.md)

Archived launch-post snapshots: hallucination % flipped, Sol ExploitBench jumped on a non-commercial tier. Ask what changed.

---

### Room 29 · Intelligence Index 61 · SciCode dip

<a href="https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra"><img src="media/aa-intelligence.jpg" alt="Artificial Analysis" width="100%"></a>

**Artificial Analysis** · [article](https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra) · [note](cases/failures.md)

Tied with Sol at **61**, behind Fable 5.1. SciCode (scientific Python) down 2–3 pts. More expensive per task at max.

---

### Room 30 · Messy rollout

<a href="https://thenewstack.io/gpt6-astra-developer-access-delayed/"><img src="media/messy-rollout.jpg" alt="Messy rollout" width="100%"></a>

**The New Stack** · [piece](https://thenewstack.io/gpt6-astra-developer-access-delayed/) · [note](cases/failures.md)

Docs live, broad API lag. You can’t verify a claim you can’t call.

---


### Room 31 · Cyber false positives mid-debug

<a href="https://community.openai.com/t/false-positive-cybersecurity-blocks-during-astra-reliability-audits-in-codex/1395121"><img src="media/cyber-false-positive.jpg" alt="Cyber false positive" width="100%"></a>

**Developer Community** · [thread](https://community.openai.com/t/false-positive-cybersecurity-blocks-during-astra-reliability-audits-in-codex/1395121) · [note](cases/failures.md)

Reliability audit on local Docker `--network none` — **8× `cyber_policy`** kills; ~1 h run dead. Same job finishes on Daybreak Blue.

---

### Room 32 · API job just stops

<a href="https://thenewstack.io/astra-api-safety-stops/"><img src="media/api-stop.jpg" alt="API safety stop" width="100%"></a>

**OpenAI Path / The New Stack** · [Path](https://openai.com/index/path-to-astra/) · [TNS](https://thenewstack.io/astra-api-safety-stops/) · [note](cases/failures.md)

ChatGPT may prompt review; **API → task stops**. Intended long agents are the ones that lose hours.

---

### Room 33 · Monitorability fragile

<a href="https://www.theverge.com/ai-artificial-intelligence/988334/openai-astra-ai-monitoring-safety"><img src="media/monitor-fragile.jpg" alt="Fragile monitoring" width="100%"></a>

**System card / Verge** · [sandbagging](https://deploymentsafety.openai.com/gpt-6-astra/capability-sandbagging) · [note](cases/failures.md)

Own words: harder to monitor than Sol; covert sandbagging “likely” uncaught. Audit trail thinner as capability rises.

---

### Room 35 · Ten-proofs citation fight

<a href="https://www.scientificamerican.com/article/openais-latest-math-breakthroughs-commit-research-misconduct-experts-say/"><img src="media/ten-proofs-citation.jpg" alt="Citation controversy" width="100%"></a>

**Scientific American** · [article](https://www.scientificamerican.com/article/openais-latest-math-breakthroughs-commit-research-misconduct-experts-say/) · [note](cases/failures.md)

Sphere packing / soficity results accused of missing recent citations. Lean checks form; literature norms are another bar. Shadow of Room 02.

---

### Room 36 · GeneBench Pro ~37%

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/genebench-pro.jpg" alt="GeneBench Pro" width="100%"></a>

**OpenAI** · [launch table](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

OpenAI’s own **agent benchmark** score (GeneBench Pro): Astra **37.1%** vs Sol **32.3%**. A reliability number on staged genomics *tasks* — not evidence Astra completed real genomics research.

---

### Room 40 · HLE w/ tools trails Fable

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/vellum-bench.jpg" alt="HLE" width="100%"></a>

**OpenAI** · [launch table](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

Astra **57.2%** vs Fable **65.0%** on Humanity’s Last Exam (w/ tools) — the academic row the prose skips.

---

### Room 43 · Terminal-Bench-Science · 64.6% vs public ~30%

<a href="https://www.tbench.ai/news/terminal-bench-science-0-1"><img src="media/tbench-science.jpg" alt="TB-Science" width="100%"></a>

**Stanford TB-Science / OpenAI** · [public 0.1](https://www.tbench.ai/news/terminal-bench-science-0-1) · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

Public board tops at Opus **30%** / Sol **22.4%** (Astra not listed). OpenAI table: Astra **64.6%**. Same name, ask the harness — Room 27’s science cousin.

---

### Room 44 · LifeSci +0.4 · MedChem ~49%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

LifeSciBench **60.3 vs 59.9**. MedChemBench **49.3%** — half still wrong. Thin “science” margins.

---

### Room 45 · AutomationBench 41%

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/automation-thin.jpg" alt="AutomationBench" width="100%"></a>

**OpenAI** · [launch table](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

Best published **41.4%** — real gain over Sol, still fails most delegated desk tasks.

---

### Room 47 · Internal data science 40.9%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

End-to-end data-science tasks **40.9%**. Under half — don’t hand off the notebook.

---

### Room 48 · Omniscience · still ~51% halluc on misses

<a href="https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra"><img src="media/omniscience-half.jpg" alt="Omniscience" width="100%"></a>

**Artificial Analysis** · [article](https://artificialanalysis.ai/articles/benchmarking-gpt-6-astra) · [note](cases/failures.md)

92% → **51%** hallucination at max. Better than Sol; still invents half the time it answers wrong. Not Room 29’s Index.

---

### Room 50 · OSWorld · ~1-in-4 still fails

<a href="https://miraflow.ai/blog/osworld-2-explained-computer-use-agent-benchmark-2026"><img src="media/osworld-cu.jpg" alt="OSWorld" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

CU **72.6%** offline partial — better and faster than Sol, still misses task ~1 of 4.

---

### Room 51 · Agents’ Last Exam 59.3%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

Complex professional software tasks: SOTA **59.3%**, loses ~4/10.

---

### Room 55 · Internal Design Tasks 50%

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · [note](cases/failures.md)

Same professional table as BenchCAD’s 95.9%: broader design tasks **50.0%**. Reconstruction ≠ design judgment.

---
### Also in this mood

- Room 13 · Bugatti Gmail (connected tools)
- Room 14 · “No research taste” (Mollick)
- Room 25 · FrontierMath Erdős default **3%** — success with a ceiling
- BenchCAD **95.9%** (win) vs Room 55 **50%** design — same launch table

---
## Side rooms

| File | What’s inside |
|------|----------------|
| [cases/official-science.md](cases/official-science.md) | Cell-tracking + official KiCad + FreeCAD |
| [cases/math-research.md](cases/math-research.md) | Lean proofs + prime gaps |
| [cases/biology-teaching.md](cases/biology-teaching.md) | T-cell lecture |
| [cases/classics.md](cases/classics.md) | Cross-links & extras |
| [cases/lab-tooling.md](cases/lab-tooling.md) | EDA / wanted lab GUIs |
| [cases/computer-use.md](cases/computer-use.md) | Long-horizon CU |
| [cases/research-workflows.md](cases/research-workflows.md) | Research loops |
| [cases/cautionary.md](cases/cautionary.md) | Connected-tool failures |
| [cases/bioinfo-wanted.md](cases/bioinfo-wanted.md) | Scarcity note (no Vitis / private-lab wishlist) |

Text-only alcoves: [George Pickett](https://x.com/georgepickett/status/2095979879137460640) · [Greg Isenberg](https://x.com/gregisenberg/status/2095854071580156338) · [dotey](https://x.com/dotey/status/2096051842174087386)

Ceiling games (demoted): [Afterlight](https://x.com/anshuc/status/2096008083826725132) · [Matthew Berman](https://x.com/MatthewBerman/status/2095595892464333065) · [Riley CoD-style](https://x.com/rileybrown/status/2095679352927056230) · [Slay the Spire 2](https://x.com/coolish/status/2096195104809873710) · [Gogh Strike](https://x.com/petergostev/status/2095776685807346105)

---

## Scope

**In:** tool use a researcher recognizes; measurable computer use; formal science; cautionary sends.  
**Out:** leading with game posters that hide the tool.  
**Also:** reality-check rooms (harness vs adapter, edited tables, independent boards) so the corridor does not become a shrine.  
**Evidence:** author-reported / official unless a PR proves otherwise.

## Credit

Authors own posts, videos, demos. `media/` frames are stills from public author/official videos for identification. Several classics first catalogued by [Ian / awesome-gpt6-astra](https://github.com/helloianneo/awesome-gpt6-astra) (CC0 editorial).

Maintainer: [Xuzhen Li](https://github.com/Xuzhen-Li) · [ORCID](https://orcid.org/0000-0003-3670-6657)

[NOTICE](NOTICE.md) · [CONTRIBUTING](CONTRIBUTING.md) · [LICENSE](LICENSE)
