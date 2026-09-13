# Concordance glossary

The vocabulary of Concordance, one note per term. This repository is a demonstration corpus for the tool and, at the same time, part of the project's own wiki: the site published from [demo-wiki](https://github.com/concordance-wiki/demo-wiki) reads it together with [demo-specs](https://github.com/concordance-wiki/demo-specs).

Every file is a term. The H1 is the term, the first paragraph its definition, `aliases` the other names people use, `broader` the term it is a kind of when there is one. Three pairs of homonyms are deliberate (`Source`, `Link` and `Index` each have two meanings, settled by a `## Not to be confused with` section) so that the tool's homonym handling has something to show.

## Layout

The terms are filed in thematic folders, and the folders are the domains of the wiki: the configuration declares `ingestion`, `inference`, `publication` and `quality` as folder domains, with `typing` a subdomain under `ingestion/` and `recognition` under `inference/`, so a term is filed by where it sits and nothing else. The second level groups the terms of a domain by subject and carries no meaning for the tool.

```
ingestion/     sources/  documents/  typing/  configuration/  pipeline/
inference/     links/  contracts/  model/  recognition/
publication/   site/  search/
quality/       checks/  findings/  linter/  plugins/
```

The identifier of a term is its path: `inference/recognition/dictionary.md` is `glossary/inference/recognition/dictionary`, and links between terms are relative paths that the tool resolves file by file. One term, `inference/recognition/keyword-page.md`, keeps the address it had before the folders existed through an `id:` in its frontmatter; the wiki's README says why.

The glossary covers every public concept of the tool: its vocabulary, every top-level key of `concordance.yaml`, every family of checks. The repository of the tool verifies that on every change (`scripts/parity.mjs`), and this repository lints itself on every push with the linter built from that repository (`.github/workflows/lint.yml`), then tells the wiki to rebuild. This README is not a term: the wiki's configuration excludes it.

Copy this repository's layout to start a glossary of your own: one folder per domain, one file per term, no frontmatter beyond `aliases` and `broader`.
