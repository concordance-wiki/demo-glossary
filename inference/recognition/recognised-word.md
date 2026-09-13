---
aliases: [recognised mention, marked word]
broader: inference/recognition/mention.md
---
# Recognised word

A word of the text of a [note](../../ingestion/documents/note.md) that the occurrence scan matched against the dictionary, a title or an alias of an [entity](../model/entity.md), or a recurring expression that the discovery gave a [keyword page](keyword-page.md), read in a paragraph, a list item, a table cell or a quote. On the entity page the build turns it into a link to the page it names, drawn so that it is told apart from a [link](../links/markdown-link.md) the author wrote: a dotted underline in the accent when the entity has a note, grey dashes when the expression only has a keyword page and no note; a legend under the text says which is which, and every mark tells on hover which note it leads to or how many passages the expression has. A recognised word carries less weight than a written link: it is what the tool found, not what someone asserted, which is why the three are never drawn alike. A page is marked once per note, on the first occurrence of its word; the later occurrences stay plain text, and the counts of the model do not change.

## Not to be confused with

An [occurrence](occurrence.md), which is the record of the match in the model; the recognised word is its mark in the rendered page.
