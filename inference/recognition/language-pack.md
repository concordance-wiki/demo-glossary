---
aliases: [pack, locale pack]
---
# Language pack

The data that describes a language to the engine, never code: a folder holding `pack.yaml` (the name of the language, its apostrophes, its collation options, its plural suffix rules, validated by `language-pack.schema.json`) and `stopwords.txt`. The engine ships `en` and `fr`; a regional variant such as `fr-CA` uses the pack of its language until a plugin registers a more specific one; another language comes as a pack shipped by a [plugin](../../quality/plugins/plugin.md). Each [source](../../ingestion/sources/source.md) selects its pack through its BCP 47 locale, which decides its [comparison form](comparison-form.md), its [stopwords](stopword.md), its word segmentation and the collation of its index.
