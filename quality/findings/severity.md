---
aliases: [severity level]
---
# Severity

What a [finding](finding.md) weighs: `error`, `warning` or `info`, the prefix of its [check](../checks/check.md) identifier (`E-`, `W-`, `I-`). Every check has a default severity in the catalogue; a project overrides it under `checks:` of the configuration, a repository under `checks:` of its `concordance-lint.yaml`, and a check can be disabled the same way. The build fails according to `build.fail_on`, on errors by default; the [linter](../linter/linter.md) fails from the severity `--fail-on` names, `error` by default.
