---
aliases: [GLOBAL_CHECKS, global scope check]
---
# Global check

A [check](check.md) the linter computes on one repository against the published [model](model.md) of the whole wiki, without rebuilding it: a [markdown link](markdown-link.md) into another [source](source.md), a frontmatter reference whose relation the [profile](profile.md) must allow between the two types, or a title shared with an [entity](entity.md) of another type. The lint package lists them as `GLOBAL_CHECKS` (`E-LINK-BROKEN`, `E-META-REL`, `I-TERM-HOMONYM`, `W-LINK-CROSS-SOURCE`). The model is fetched once and kept in a local cache for a configurable number of hours; when it cannot be read, the linter says so and falls back to the [local checks](local-check.md) instead of failing. Each [finding](finding.md) names the remote entity and the build timestamp of the model it was compared with.
