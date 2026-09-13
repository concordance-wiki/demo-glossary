---
aliases: [entity identifier, id]
---
# Identifier

The name of an [entity](../../inference/model/entity.md) in the [model](../../inference/model/model.md) and the address of its page: the name of its [source](../sources/source.md), then its path relative to the source root without the extension or the type suffix, slugified segment by segment (lowercase, accents removed, every other run of characters replaced by one hyphen), `glossary/ingestion/typing/identifier` for this repository's `ingestion/typing/identifier.md`. A frontmatter `id` takes precedence when it follows the pattern, lowercase with hyphens and at least one slash, and yields `E-ID-INVALID` otherwise; two files resolving to one identifier yield `E-ID-DUP` and the first in source and path order is kept. Nothing random, nothing that depends on the order of processing.
