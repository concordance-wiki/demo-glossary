---
aliases: [canonical model, model.json]
---
# Model

The result of a build: every [entity](entity.md), every [link](../links/link.md) with its [provenance](../links/provenance.md), every [finding](../../quality/findings/finding.md), the term candidates and the neighbourhoods, serialised to a single `model.json` file in canonical order. Two builds on the same sources produce the same file byte for byte. The site is rendered from it without reading the sources again.
