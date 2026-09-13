---
aliases: [links family]
broader: check-family.md
---
# Link checks

The [check family](check-family.md) of what a [note](note.md) points at: `E-LINK-BROKEN`, a [markdown link](markdown-link.md) to a file that does not exist in its source; `W-LINK-CROSS-SOURCE`, a link into another source while `inference.cross_source_links` is off; `W-REF-UNRESOLVED`, a [frontmatter reference](frontmatter-reference.md) that matches no note, or several by title. The first is a [local check](local-check.md), the first two are also computed in the global [scope](scope.md) of the linter.
