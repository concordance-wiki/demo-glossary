---
aliases: [lint scope, repo scope, global scope]
---
# Scope

What the [linter](linter.md) sees: `--scope repo`, the default, checks the current repository alone, file by file, without the network; `--scope global` also reads the last published [model](model.md) of the wiki, from its cache or fetched with the validators the server gave, and checks the local notes against the remote entities with the [global checks](global-check.md), without rebuilding anything. When no model can be read, the global scope degrades to the local one, says so on one line and in its reports, and exits according to the local findings.
