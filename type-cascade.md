---
aliases: [typing cascade, cascade]
---
# Type cascade

The order in which the type of a [note](note.md) is decided: the default type of the [source](source.md), then the type forced by the source, then the source's rules in order (folder, suffix, extension, frontmatter key), then the note's own frontmatter. The most specific wins, and the origin of the decision is kept on the [entity](entity.md) and shown in the site.
