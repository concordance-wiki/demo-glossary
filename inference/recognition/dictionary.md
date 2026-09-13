---
aliases: [recognition dictionary]
---
# Dictionary

The list of the words the occurrence scan looks for: the titles and [aliases](alias.md) of every [entity](../model/entity.md) of a locale, keyed by their [comparison form](comparison-form.md), one dictionary per locale of the corpus. Glossary sources come first, so that their titles win when a form names several entities; a [stopword](stopword.md) never enters it, nor a form shorter than three characters unless `inference.short_terms` allows it; a form shared by several entities is flagged as a [homonym](homonym.md). The dictionary is built once per build, after typing and contract import, and before the scan.
