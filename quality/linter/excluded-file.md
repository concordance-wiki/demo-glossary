---
aliases: [exclude, excluded file, ignored file, gitignore]
---
# Excluded file

A file of a [knowledge repository](../../ingestion/sources/knowledge-repository.md) that is never read, never counted and never reported, by the [linter](linter.md) and by the build alike: what `privacy.exclude` of the [privacy block](../../ingestion/sources/privacy.md) names for the whole wiki, what `exclude` of the repository's own `concordance-lint.yaml` names for that repository, both as globs relative to its root, and what git ignores, read from every `.gitignore` of the repository with the rules git applies. A vendored folder, a generated site or a cloned tool thus stay out of the [checks](../checks/check.md) and out of the link resolution, so that a link towards an excluded file is a broken link; `concordance lint --no-gitignore` reads the ignored files anyway, for the rare repository that keeps notes in an ignored folder. Because both sides list the files the same way, the [local checks](../checks/local-check.md) keep their parity file for file.
