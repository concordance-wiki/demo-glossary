---
aliases: [conversion cache, pipeline cache]
---
# Fingerprint cache

The folder, `.concordance-cache` by default (`conversion.cache`), where the build keeps what it fetched or produced, keyed by the fingerprint of its input: a converted document under `convert/<sha256 of the file>`, so that an unchanged document is never reconverted even when it moves, and a [contract](../../inference/contracts/contract.md) by the SHA-256 of its text. The clones of the sources sit under it too. The cache never enters `dist/`; a pipeline keeps it between runs and deleting it forces a full reconversion.
