---
aliases: [privacy block]
---
# Privacy

The `privacy:` block of the [configuration](../configuration/configuration.md): `exclude`, the globs of what is never read, applied before any content (an [excluded file](../../quality/linter/excluded-file.md), like the ones a repository excludes itself or git ignores); `pseudonymize`, the [pseudonymisation](pseudonymisation.md) of transcripts with its dictionary and scope; and `publish_transcripts`, `false` by default, so that a [transcript](../documents/transcript.md) is indexed only when a decision asks for it. The configuration never carries a credential either: a private source gets its token from the git environment of the machine or of the pipeline.
