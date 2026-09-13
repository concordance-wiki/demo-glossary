---
aliases: [reproducible build, byte-identical]
---
# Determinism

Two builds of unchanged sources write the same bytes: every list of the [model](../../inference/model/model.md), of the [build log](../findings/build-log.md), of the fragments and of the site is sorted canonically before it is written, a parallel step sorts its results, nothing random is written and the only timestamp is the `at` field of the log and of the `build` block of the model, pinned by `SOURCE_DATE_EPOCH` as reproducible-builds tooling does. The repository builds its [golden corpus](golden-corpus.md) twice on every change and compares every file, so that `dist/` can be committed and diffed.
