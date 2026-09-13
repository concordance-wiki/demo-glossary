---
aliases: [type folder, types_dir]
---
# Type module

The distributable form of a [type](type.md): a folder named after the type slug that carries everything the type needs, `type.yaml` with its declaration (group, glyph, [attributes](attribute.md), the sections whose heading produces a relation, the display rules), `messages/<locale>.json` with the labels of the type, its attributes and its sections per interface language, `template.md` with its [note](../documents/note.md) template, and optionally `schema.json` for the items of its list attributes and `components/` for a page, an attribute value or a section rendered specially. The core types are modules and the default [profile](../configuration/profile.md) is assembled from them; a project keeps its own modules in the folder its profile names under `types_dir`, and a [plugin](../../quality/plugins/plugin.md) contributes modules through the `types` [contribution point](../../quality/plugins/contribution-point.md). The modules are merged before the keys of the project profile, plugins first; a module of a core type is refused, that type being extended through the profile, and two modules of one type are a configuration error.
