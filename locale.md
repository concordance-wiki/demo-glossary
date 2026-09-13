---
aliases: [BCP 47 tag, locale tag]
---
# Locale

The language of a [source](source.md) or of the [project](project.md), written as a BCP 47 tag, `en`, `fr`, `fr-CA`. The locale of a source selects its [language pack](language-pack.md), the type prefixes of the profile for that language and the collation of its indexes; the locale of the project is the language of the interface, whose labels come from a message catalogue per locale, and the default locale of every source. A tag with no pack is a build error.
