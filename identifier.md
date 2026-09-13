---
aliases: [entity identifier, id]
---
# Identifier

The name of an [entity](entity.md) in the [model](model.md) and the address of its page: the name of its [source](source.md), then its path relative to the source root without the extension or the type suffix, slugified segment by segment (lowercase, accents removed, every other run of characters replaced by one hyphen), `glossary/keyword-page` for this repository's `keyword-page.md`. A frontmatter `id` takes precedence when it follows the pattern, lowercase with hyphens and at least one slash, and yields `E-ID-INVALID` otherwise; two files resolving to one identifier yield `E-ID-DUP` and the first in source and path order is kept. Nothing random, nothing that depends on the order of processing.
