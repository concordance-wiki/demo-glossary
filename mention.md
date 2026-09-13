---
aliases: [citation, mentions panel entry]
---
# Mention

One place where another file cites an [entity](entity.md), as the entity page lists it: the citing file, the line, the words around the citation and a link to the passage. A mention is either a [link](markdown-link.md) an author wrote, in the text or in the frontmatter, or a [recognised word](recognised-word.md) the scan found in a mapped section or in prose; the mentions panel keeps the two apart, written links first, because the first is what someone asserted and the second what the tool inferred. Mentions are grouped by citing file. The first twenty of an entity are in its page and the rest in its [fragment](fragment.md), `fragments/<id>.mentions.json`, one file per entity and never a global index.

## Not to be confused with

An [occurrence](occurrence.md), which is the record of a matched word in the [model](model.md), whatever it points at; a mention is seen from the cited entity, and a written link is a mention without being an occurrence.
