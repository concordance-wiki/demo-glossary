---
aliases: [build steps]
---
# Pipeline

The chain of steps `concordance build` runs in a fixed order, each a pure function of the outputs of the previous ones: configuration, ingestion, parsing, reading and [conversion](../documents/conversion.md), typing, [contract import](../../inference/contracts/contract-import.md), [dictionary](../../inference/recognition/dictionary.md), scan, links, combination, relation typing, keyword discovery, [twin resources](../sources/twin-resources.md), checks, writing of the [model](../../inference/model/model.md), theme, rendering, measurement. Every step reports its anomalies as [findings](../../quality/findings/finding.md) and nothing stops the chain. By extension, the job of the forge that runs the build on every push and publishes the site.
