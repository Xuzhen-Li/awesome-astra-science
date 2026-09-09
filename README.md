# Awesome Astra Science

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[中文](README.zh.md) · English

**Only projects GPT-6 Astra itself produced** — official OpenAI demos and write-ups where Astra builds an artifact. No third-party X demos, no benchmark scoreboards, no journalism.

Source of truth: [GPT-6 Astra launch](https://openai.com/index/gpt-6-astra/) and linked OpenAI posts. Stills are frames or official assets; copyright stays with OpenAI / listed authors.

---

## Official builds

### 1 · Cell-tracking workflow (Jupyter)

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/jupyter-cell-tracking.jpg" alt="Cell-tracking in JupyterLab" width="100%"></a>

**OpenAI** · [launch · Cell-tracking workflow](https://openai.com/index/gpt-6-astra/)

Astra builds and runs a microscopy cell-tracking workflow in JupyterLab (masks → tracks / lineage). Condensed official computer-use demo — not a journal paper.

### 2 · KiCad PCB (`chip_design`)

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-kicad.jpg" alt="KiCad PCB layout and 3D board" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · video `chip_design_no_captions_15s.mp4`

Astra places components and routes a manufacturable PCB in KiCad (2D layout + 3D board). This is the launch electronics desk — **not** MultiQC / sequencing QC.

### 3 · FreeCAD five-speed transmission

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/openai-freecad.jpg" alt="FreeCAD transmission" width="100%"></a>

**OpenAI** · [launch · Car transmission](https://openai.com/index/gpt-6-astra/)

Written brief → detailed five-speed transmission concept in FreeCAD.

### 4 · Gear motion (FreeCAD → Blender)

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/freecad-motion.jpg" alt="Transmission gears in motion" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · video `gear-motion.mp4`

Same transmission line: gears animated in motion (Blender follow-through on the FreeCAD design).

### 5 · Unity city scene

<a href="https://openai.com/index/gpt-6-astra/"><img src="media/unity-city.jpg" alt="Unity city assembled by Astra" width="100%"></a>

**OpenAI** · [launch](https://openai.com/index/gpt-6-astra/) · asset `Unity-City-high-res.png`

Aerial city scene assembled in Unity (official computer-use / game-assembly still).

### 6 · Solace house (Blender → Unreal)

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-hero.jpg" alt="Solace architectural visualization" width="100%"></a>

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/solace-ue5.jpg" alt="Solace in Unreal Engine" width="100%"></a>

**OpenAI Developers** · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

Astra-driven arch-viz pipeline: research / modeling in Blender through to Unreal presentation (Solace).

### 7 · HELIOS Dyson collector

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/helios-dyson.jpg" alt="HELIOS Dyson collector concept" width="100%"></a>

**OpenAI Developers** · same [architectural visualization](https://developers.openai.com/blog/architectural-visualization-with-astra) post

Concept build in the same official arch-viz write-up (HELIOS / Dyson-style collector).


### 8 · Void Explorer ship (Blender)

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/void-explorer-ship.jpg" alt="AURORA ship modeled in Blender" width="100%"></a>

**OpenAI Developers** · [Building games with Astra](https://developers.openai.com/blog/how-to-build-games-with-astra)

Astra builds an editable Blender ship (AURORA: 193 meshes → runtime asset) for the Void Explorer game.

### 9 · Sunwake ocean + boat

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/sunwake-water.jpg" alt="Sunwake procedural ocean and boat" width="100%"></a>

**OpenAI Developers** · same [games](https://developers.openai.com/blog/how-to-build-games-with-astra) post

Astra builds a custom Three.js water renderer and a Blender boat brought into Sunwake.


### 10 · Shipyard · AURELION-07 cruiser

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/aurelion-shipyard.jpg" alt="AURELION-07 cruiser in Blender" width="100%"></a>

**OpenAI Developers** · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

Astra builds AURELION-07 in Blender (Shipyard project): tapered hull, segmented ring, four drives — editable geometry/materials.


### 11 · Hollowflux water RPG

<a href="https://developers.openai.com/blog/how-to-build-games-with-astra"><img src="media/hollowflux-water.jpg" alt="Hollowflux glowing river" width="100%"></a>

**OpenAI Developers** · [Building games with Astra](https://developers.openai.com/blog/how-to-build-games-with-astra)

Astra iterates a code-drawn 2D action RPG around a simulated underground river (water grid, currents, combat coupling).

### 12 · Giverny water garden

<a href="https://developers.openai.com/blog/architectural-visualization-with-astra"><img src="media/giverny-garden.jpg" alt="Monet-inspired Giverny garden" width="100%"></a>

**OpenAI Developers** · [Architectural visualization with Astra](https://developers.openai.com/blog/architectural-visualization-with-astra)

Astra builds a Monet/Giverny-inspired garden scene (lily pond, bridge, planting) in the same official arch-viz write-up.


---

## Out of scope (removed)

- Third-party X / blog “I used Astra to…” demos  
- Benchmark tables (GeneBench, OSWorld, EEBench, …) — scores, not projects  
- Journalism / “reality check” rooms  
- Wrong MultiQC attribution (never an Astra-built project; launch electronics desk is KiCad)
- Ten Lean math essay (OpenAI text says **internal** Astra, not clearly public GPT-6 Astra builds)

Broader Astra link dump: [helloianneo/awesome-gpt6-astra](https://github.com/helloianneo/awesome-gpt6-astra).

---

**Curator:** [Xuzhen Li](https://github.com/Xuzhen-Li) · [ORCID](https://orcid.org/0000-0003-3670-6657)
