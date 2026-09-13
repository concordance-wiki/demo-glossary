---
aliases: [control, rule of consistency]
---
# Check

A pure function that reads the [model](../../inference/model/model.md) and returns [findings](../findings/finding.md). Checks live in one registry shared by the build and the linter, so both report the same thing on the same repository. Each check has an identifier, a default [severity](../findings/severity.md), a description, a [remediation](../findings/remediation.md) and a documentation page, and belongs to a [check family](check-family.md).
