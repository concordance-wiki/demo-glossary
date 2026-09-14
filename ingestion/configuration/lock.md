---
aliases: [lock file]
---
# Lock

A versioned file in the configuration repository, `concordance.lock.yaml`, named by the `lock` key of the [configuration](configuration.md), that records human decisions: accepted and rejected [links](../../inference/links/link.md), merged and separated [twin resources](../sources/twin-resources.md), rejected [candidate expressions](../../inference/recognition/candidate-expression.md). The [build](../pipeline/build.md) reads it, validates it against the published lock schema and stops on a missing or invalid file as on a configuration error. It applies the rejected terms, compared on the normalised form of the language pack, so that a rejected expression has no candidate, no finding, no [keyword page](../../inference/recognition/keyword-page.md) and no mark in the text, and the merged and separated pairs, a merged pair grouped under the criterion `lock file` whatever its score, a separated pair never reported. The links are recorded, not read. The [build log](../../quality/findings/build-log.md) counts the decisions applied. Nothing is ever written into a knowledge repository.
