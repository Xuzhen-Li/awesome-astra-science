# Contributing

This repo collects **works that AI models actually produced**: demos and figures, each backed by a primary source (official page, paper, or repo) where the model produced a clear artifact. GPT-6 Astra is currently the only model section; Astra entries come from official OpenAI materials (launch page or OpenAI blogs/repos with a clear artifact).

Do **not** PR:

- Third-party social demos ("I used model X…")
- Benchmark score rows without a produced artifact
- News / commentary rooms
- Tools a model merely opened rather than a work it produced (e.g. MultiQC is not an Astra-built project)

PRs need, following the convention in the [README](README.md#adding-a-new-models-works):

- **Model section:** the work goes under `## <Model name> (<maker>)`; add that section if the model is new.
- **Kind-of-work heading:** a `###` heading such as Demos, Figures, 3D scenes, or Games; only add a kind when there is at least one real work for it.
- **Still:** an image of the artifact at `media/<model-slug>/<work-slug>.<ext>` (lowercase, hyphenated). Astra's existing stills stay at the top of `media/`.
- **Source:** the primary URL where the model produced the work.
- **Prompt:** the published prompt or brief, quoted or linked, only if one was published.
- **Description:** one or two lines on what the model produced, with no metrics or claims beyond the source.
- The same entry in both [README.md](README.md) and [README.zh.md](README.zh.md).
