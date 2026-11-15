# Contributing

This list collects AI projects in science that people can open and check. There are two parts:

- The science sections (Proteins and DNA, Math and algorithms, and so on): projects with a paper or maker's page and something to open, such as a repo, database, web tool or API.
- Model showcases: works one model made by itself, from the maker's own pages, with a still. GPT-6 Astra is the only model there now.

## A science entry needs

- A `###` title: project name, then maker and year in brackets.
- One or two lines on what the AI did. Numbers only if the paper or page says them; copy them, do not round them up.
- `Paper:` or `Preprint:` with a link you have read.
- `Code:`, `Open it:`, `Data:` or `API:` with a link people can use. If there is nothing to open, say so in the PR.
- The same entry in [README.md](README.md) and [README.zh.md](README.zh.md).
- One row per page you read in [SOURCES_READ.tsv](SOURCES_READ.tsv): URL, entry, date read, note.

A blank entry is in [templates/ENTRY.md](templates/ENTRY.md).

## A model showcase entry needs

The rules in [templates/CASE.md](templates/CASE.md): the maker's own page where the model produced the work, a still in `media/` (new stills go in `media/<model-slug>/<work-slug>.<ext>`; the existing Astra stills sit directly in `media/`), the prompt only if it was published, and one or two lines on what the model made.

## Please do not send

- "I used model X to..." posts from third parties
- Benchmark scores with no project behind them
- News stories or commentary
- Claims you could not find in the source
