---
aliases: [concordance build, build block]
---
# Build

One run of `concordance build`: it validates the [configuration](../configuration/configuration.md) and the [lock](../configuration/lock.md) it names, fetches the [sources](../sources/source.md), runs the [inference](../../inference/model/inference.md) chain and the [checks](../../quality/checks/check.md), writes the [model](../../inference/model/model.md), the [build log](../../quality/findings/build-log.md) and one [fragment](../../publication/site/fragment.md) per entity, then renders the [site](../../publication/site/site.md) from those files alone. The `build:` block of the configuration says where it writes (`output`, `./dist`), when it fails (`fail_on.errors`, `fail_on.unconverted_max`), how many mentions a page carries inline (`mentions_inline`, 20) and how much of a note enters the search index (`extracted_text_max_chars`, 20 000). The `build` block of the model is its only dated part.
