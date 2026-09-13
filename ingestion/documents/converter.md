---
aliases: [office converter]
broader: quality/plugins/contribution-point.md
---
# Converter

A [contribution point](../../quality/plugins/contribution-point.md) of the plugin API that turns a document into representations the pipeline reads: a PDF today, thumbnails and text later, written under the [fingerprint cache](../sources/fingerprint-cache.md) and never next to the source. A converter receives the bytes of the file, their SHA-256 and the limits of `conversion:` (`timeout_s`, `max_size_mb`), runs in a pool of `conversion.parallelism` workers, and reports a failed conversion as `W-CONV-FAILED`, the document staying a download. The official converter drives headless LibreOffice; no converter runs in this version.
