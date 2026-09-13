---
aliases: [entity type, note type]
---
# Type

One of the kinds of [entity](../../inference/model/entity.md) the [profile](../configuration/profile.md) declares: a screen, a rule, a business object, an API, an operation, a process, a decision, a term, a document among others, each with a label per locale, a glyph, a group, its attributes, the sections whose heading produces a relation, and its display rules. A type is `active` when the first version renders it and `planned` otherwise; a project profile adds one without a code change, and a [type module](type-module.md) carries one from a plugin or a folder of the project. The type of a note is decided by the [type cascade](type-cascade.md), and a type the profile does not know yields `W-TYPE-UNKNOWN`.
