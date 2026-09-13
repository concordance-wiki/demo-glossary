---
aliases: [SARIF log, JUnit report, lint report]
---
# Forge report

The report the [linter](../linter/linter.md) writes for a forge with `--format`: a SARIF log that GitHub code scanning shows in the margin of the diff, on the file and line of each [finding](finding.md); a JUnit report that a GitLab merge request lists as failed tests with the message, the [remediation](remediation.md) and the page of each; or JSON, which also names the [scope](../linter/scope.md), the checks that ran and whether the global scope was degraded. Every form carries the same findings as the text output, and `--output` writes it to a file, the only file the linter ever writes.
