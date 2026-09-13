---
aliases: [contribution, manifest key]
---
# Contribution point

One of the ways a [plugin](plugin.md) adds to the tool, named by a key of its manifest: `readers` (a [reader](../../ingestion/documents/reader.md) per file format), `converters` (a [converter](../../ingestion/documents/converter.md)), `sources` (a source of entities such as a [contract import](../../inference/contracts/contract-import.md)), `inferenceMethods` (a method that produces links), `checks` (a [check](../checks/check.md) with its identifier, severity, remediation and page), `projections` (a rendering of the model), `uiComponents` (a bundle a [slot](../../publication/site/slot.md) loads on demand), `themes` (a [theme](../../publication/site/theme.md) with components by slot) and `types` (a [type module](../../ingestion/typing/type-module.md) per folder, merged into the profile). The data around each contribution is validated by the plugin schema; the functions are called with their input and an injected context, and never read the clock or the network on their own.
