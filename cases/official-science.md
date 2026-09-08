# Official science demos (OpenAI)

Company demonstrations from the [GPT-6 Astra launch post](https://openai.com/index/gpt-6-astra/). Demonstration environment — not an independent user reproduction log.

## Sequencing quality → MultiQC / variant stats

<a href="https://openai.com/index/gpt-6-astra/"><img src="../media/openai-multiqc.jpg" alt="MultiQC report driven by Astra" width="100%"></a>

- **Author:** OpenAI
- **Original:** https://openai.com/index/gpt-6-astra/ (tab: Sequencing quality) · Vimeo embed `1223245025`
- **Date:** 2026-09-03
- **Still:** Frame from the official demo video (hosted in `media/`), showing a local MultiQC v1.18 report with Samtools / FastQC / Bcftools sections and substitution chart.
- **What it is:** Astra navigates scientific software to inspect sequencing QC and genetic-variation summaries.
- **Why here:** Clearest public **lab-GUI computer-use** still tied to Astra. MultiQC is everyday tooling; the demo is navigation, not a genomics paper.
- **Evidence boundary:** Official condensed playback. Toy/demo paths (`127.0.0.1`, `/workspace/base/output`); not a claim about clinical interpretation.

<a href="https://openai.com/index/gpt-6-astra/"><img src="../media/openai-bcftools.jpg" alt="Bcftools substitutions in MultiQC" width="100%"></a>

Second frame: Bcftools Stats substitutions for `variants.filtered`.

## Cell-tracking workflow (Jupyter)

<a href="https://openai.com/index/gpt-6-astra/"><img src="../media/jupyter-cell-tracking.jpg" alt="Jupyter cell tracking" width="100%"></a>

- **Author:** OpenAI
- **Original:** https://openai.com/index/gpt-6-astra/ (tab: Cell-tracking workflow) · video https://videos.ctfassets.net/kftzwdyauwt9/3B1VXBpOI7aZb1kKLGcJrH/d422b5898b375ec6b4abd9438eb75578/life-sciences-cell-tracking-30s-realtime-full-frame.mp4
- **Date:** 2026-09-03
- **Still:** Mid-demo JupyterLab frame — raw vs labeled masks, lineage export (`track_cells.py`, 36 tracks / division event).
- **What it is:** Builds & runs a cell-tracking workflow: microscopy frames → instance masks → tracks + lineage.
- **Why here:** Official condensed live-cell image desk demo, distinct from MultiQC. Vendor video, not a published tracking study.
- **Evidence boundary:** Official condensed demo; not an independent lab reproduction.

## FreeCAD five-speed transmission

<a href="https://openai.com/index/gpt-6-astra/"><img src="../media/openai-freecad.jpg" alt="FreeCAD transmission model" width="100%"></a>

- **Author:** OpenAI
- **Original:** https://openai.com/index/gpt-6-astra/ (FreeCAD model asset) · companion motion video on the same page
- **Date:** 2026-09-03
- **Still:** Official FreeCAD UI screenshot (`transmission-freecad.png` from launch assets).
- **What it is:** Written brief → detailed concept model of a five-speed automobile transmission in FreeCAD; Blender used later to animate gears.
- **Why here:** Engineering CAD computer use in a real desktop app — same class as instrument / hardware tooling labs use.
- **Evidence boundary:** Official demo asset.

## Related benchmarks (no still)

Cited on the launch page for science positioning (numbers are OpenAI-reported):

- GPQA Diamond (biology / chemistry / physics reasoning)
- Terminal-Bench Science 0.1
- FrontierMath Tier 4 / prime-gap follow-ups — see also https://openai.com/index/ten-advances-in-mathematics/

## BenchCAD · Vision2Code 95.9%

- **Author:** OpenAI (Professional table)
- **Original:** https://openai.com/index/gpt-6-astra/
- **Date:** 2026-09-03
- **What it is:** Reconstruct 3D objects from multi-view renders by generating CAD code — geometric-overlap **95.9%** (Sol 83.3%, Fable 5.1 84.3% with noted eval mods).
- **Why here:** Strongest published **engineering reconstruction** number; pairs with FreeCAD demos.
- **Evidence boundary:** Vendor bench; Claude rows used modified settings per footnote.
