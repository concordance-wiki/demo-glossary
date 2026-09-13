# Concordance glossary

The vocabulary of Concordance, one note per term. This repository is a demonstration corpus for the tool and, at the same time, part of the project's own wiki: the site published from [demo-wiki](https://github.com/concordance-wiki/demo-wiki) reads it together with [demo-specs](https://github.com/concordance-wiki/demo-specs).

Every file is a term. The H1 is the term, the first paragraph its definition, `aliases` the other names people use, `broader` the term it is a kind of when there is one. Three pairs of homonyms are deliberate (`Source`, `Link` and `Index` each have two meanings, settled by a `## Not to be confused with` section) so that the tool's homonym handling has something to show.

The glossary covers every public concept of the tool: its vocabulary, every top-level key of `concordance.yaml`, every family of checks. The repository of the tool verifies that on every change (`scripts/parity.mjs`), and this repository lints itself on every push with the linter built from that repository (`.github/workflows/lint.yml`), then tells the wiki to rebuild.

Copy this repository's layout to start a glossary of your own: one folder, one file per term, no frontmatter beyond `aliases` and `broader`.
