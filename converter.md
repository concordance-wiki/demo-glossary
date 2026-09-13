---
aliases: [office converter]
broader: contribution-point.md
---
# Converter

A [contribution point](contribution-point.md) of the plugin API that turns a document into representations the pipeline reads: a PDF today, thumbnails and text later, written under the [fingerprint cache](fingerprint-cache.md) and never next to the source. A converter receives the bytes of the file, their SHA-256 and the limits of `conversion:` (`timeout_s`, `max_size_mb`), runs in a pool of `conversion.parallelism` workers, and reports a failed conversion as `W-CONV-FAILED`, the document staying a download. The official converter drives headless LibreOffice; no converter runs in this version.
