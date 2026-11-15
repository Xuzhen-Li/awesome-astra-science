# Contributing

This list collects AI projects in science that anyone can open and inspect. It has two parts:

- The science sections (Proteins and DNA, Math and algorithms, and so on): projects with a paper or maker's page and a resource to open, such as a repo, database, web tool, or API.
- Model showcases: works produced by a single model on its own, taken from the maker's own pages and accompanied by a still. GPT-6 Astra is currently the only model listed there.

## A science entry needs

- A `###` heading: project name, followed by maker and year in brackets.
- One or two lines describing what the AI did. Include numbers only if the paper or source page states them; copy them directly rather than rounding up.
- `Paper:` or `Preprint:` with a link you have read.
- `Code:`, `Open it:`, `Data:`, or `API:` with a link people can use. If there is nothing to open, mention that in the PR.
- The same entry in both [README.md](README.md) and [README.zh.md](README.zh.md).
- One row per page you read in [SOURCES_READ.tsv](SOURCES_READ.tsv): URL, entry, date read, and note.

A blank template is available in [templates/ENTRY.md](templates/ENTRY.md).

## A model showcase entry needs

Follow the rules in [templates/CASE.md](templates/CASE.md): the maker's own page showing where the model produced the work, a still in `media/` (new stills go in `media/<model-slug>/<work-slug>.<ext>`; the existing Astra stills sit directly in `media/`), the prompt only if it was published, and one or two lines on what the model made.

## Please do not send

- "I used model X to..." posts from third parties
- Benchmark scores without an underlying project
- News articles or commentary
- Claims not supported by the source
