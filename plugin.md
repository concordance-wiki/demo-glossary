---
aliases: [extension]
---
# Plugin

A package that contributes to the tool through a versioned API: a reader for a file format, a converter, a source of entities such as a contract importer, an inference method, a [check](check.md), a projection, a user interface component. The core reads markdown and produces JSON; everything that needs a format or a system tool is a plugin. A plugin whose system dependency is missing disables itself with a [finding](finding.md).
