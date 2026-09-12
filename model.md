---
aliases: [canonical model, model.json]
---
# Model

The result of a build: every [entity](entity.md), every [link](link.md) with its [provenance](provenance.md), every [finding](finding.md), the term candidates and the neighbourhoods, serialised to a single `model.json` file in canonical order. Two builds on the same sources produce the same file byte for byte. The site is rendered from it without reading the sources again.
