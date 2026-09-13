---
aliases: [pipeline step]
---
# Step

One module of the [pipeline](pipeline.md), a pure function of the outputs of the steps before it that reports its anomalies as [findings](finding.md) and never stops the chain. The [architecture guide of the tool](https://github.com/concordance-wiki/concordance/blob/main/docs/guides/architecture.md#the-build-pipeline) lists them in order; nothing after the writing of the [model](model.md) reads a source.
