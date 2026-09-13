---
aliases: [frontmatter attribute, declared attribute, property]
---
# Attribute

A key of the [frontmatter](../documents/frontmatter.md) that the [profile](../configuration/profile.md) declares, either for every [type](type.md) (`id`, `title`, `aliases`, `status`, `summary` among the common ones) or for one type (`url_pattern` of a screen, `severity` of a rule, `broader` of a term). A typed attribute carries a string, a date, an enum, a list or a reference; a reference produces a [link](../../inference/links/link.md) whose relation the profile names. The page shows the attributes in its side panel and highlights the first ones the type's display rules list; a key nothing declares yields `W-ATTRIBUTE-UNKNOWN`.
