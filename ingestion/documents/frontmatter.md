---
aliases: [YAML frontmatter]
---
# Frontmatter

The YAML block between two `---` lines at the top of a [note](note.md): the common attributes every entity may declare (`id`, `type`, `title`, `aliases`, `application`, `domain`, `status`, `tags`, `summary`, `superseded_by`, `locale`) and the attributes of its [type](../typing/type.md), a [frontmatter reference](../../inference/links/frontmatter-reference.md) among them. The frontmatter is the last rung of the [type cascade](../typing/type-cascade.md), is never scanned for occurrences, yields `E-FM-INVALID` when it does not parse and `W-ATTRIBUTE-UNKNOWN` for a key nothing declares. What qualifies goes in it; the rest is prose.
