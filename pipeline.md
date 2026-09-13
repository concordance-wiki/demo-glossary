---
aliases: [build steps]
---
# Pipeline

The chain of steps `concordance build` runs in a fixed order, each a pure function of the outputs of the previous ones: configuration, ingestion, parsing, reading and [conversion](conversion.md), typing, [contract import](contract-import.md), [dictionary](dictionary.md), scan, links, combination, relation typing, keyword discovery, [twin resources](twin-resources.md), checks, writing of the [model](model.md), theme, rendering, measurement. Every step reports its anomalies as [findings](finding.md) and nothing stops the chain. By extension, the job of the forge that runs the build on every push and publishes the site.
