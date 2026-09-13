---
aliases: [LOCAL_CHECKS, local scope check]
broader: quality/checks/check.md
---
# Local check

A [check](check.md) the linter computes on one repository alone, without the network and without the rest of the [model](../../inference/model/model.md): encoding, frontmatter, identifiers and internal links. The lint package lists them as `LOCAL_CHECKS`. For these checks the linter and the build produce the same [findings](../findings/finding.md) on the same repository, wording included; a parity test on the [golden corpus](../linter/golden-corpus.md) and on the faulty corpus holds them to it, and the JSON report of the linter repeats the list so that a forge report says what was checked.
