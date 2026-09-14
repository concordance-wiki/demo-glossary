---
aliases: [release tag, published version]
---
# Release

One version of the tool, cut by merging the version pull request the pipeline keeps open from the changesets: the merge commit is tagged `v<major>.<minor>.<patch>`, every published package is packed and attached to a release with the standalone binaries of the [linter](linter.md), the checksums and the licence inventory, and the same tarballs go to npm, the container image to its registry and the action and the component to their mirrors once the maintainer has enabled each publication. Every form of a version names the same commit, so a version pinned in a pipeline, a hook or an image is one registry of [checks](../checks/check.md) with one behaviour, and the [version](../../ingestion/sources/version.md) of the tool written in the site and the model is that of the release.
