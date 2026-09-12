---
aliases: [control, rule of consistency]
---
# Check

A pure function that reads the [model](model.md) and returns [findings](finding.md). Checks live in one registry shared by the build and the linter, so both report the same thing on the same repository. Each check has an identifier, a default severity, a description, a remediation and a documentation page.
