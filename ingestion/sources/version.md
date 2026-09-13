---
aliases: [schema version, version key]
---
# Version

The first key of every file the tool reads, `version: 1` in this version: the [configuration](../configuration/configuration.md), the [profile](../configuration/profile.md), the [theme](../../publication/site/theme.md) and the [lock](../configuration/lock.md) each name the version of the schema they follow, and a file of another version is refused with the path of the key. The tool itself carries a version too, written in the footer of the site and in the `build` block of the [model](../../inference/model/model.md), and every published package shares it.
