---
aliases: [frontmatter ref, declared reference]
broader: inference/recognition/mention.md
---
# Frontmatter reference

A value of a reference-typed attribute of the [frontmatter](../../ingestion/documents/frontmatter.md), `reads`, `roles`, `rules`, `consumers`, `affects`, `broader` among others, that names another [note](../../ingestion/documents/note.md) by its [identifier](../../ingestion/typing/identifier.md), by its path relative to the source root, or by its exact title. The reference produces a [link](link.md) at [confidence](confidence.md) 0.90 whose relation the attribute declares, never overturned by inference. A value that matches nothing, or several notes by title, yields `W-REF-UNRESOLVED`; one that reaches a note of a type the relation does not allow yields `E-META-REL`.
