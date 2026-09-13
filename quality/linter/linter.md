---
aliases: [concordance lint, lint command]
---
# Linter

The `lint` command: it reads every markdown file of one knowledge repository, runs the [checks](../checks/check.md) that a repository can be held to alone, and prints one line per [finding](../findings/finding.md) with the address of its documentation page, then a count. In repo [scope](scope.md) it needs no network and writes nothing but the report `--output` names; in global scope it also reads the published [model](../../inference/model/model.md) of the wiki. The linter and the build produce the same findings for the [local checks](../checks/local-check.md), it fails from the [severity](../findings/severity.md) `--fail-on` gives, writes a [forge report](../findings/forge-report.md) on request, applies the safe fixes with `--fix`, and runs the same way as an npm package, a standalone binary, a GitHub action, a GitLab component, the container image or a pre-commit hook.
