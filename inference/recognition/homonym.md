---
aliases: [homonyms, shared form]
---
# Homonym

Two [entities](../model/entity.md) whose title or [alias](alias.md) share one [comparison form](comparison-form.md): a term and a business object both called "Source", or two terms whose aliases meet. The tool keeps both, reports `I-TERM-HOMONYM` with the form and the identifiers, and links every [occurrence](occurrence.md) of the form to each entity at half the [confidence](../links/confidence.md) it would have with one target, glossary entities first. A `## Not to be confused with` section in each note tells the reader which is which; this glossary carries three such pairs on purpose, [source](../../ingestion/sources/source.md), [link](../links/link.md) and [index](../../publication/search/alphabetical-index.md).
