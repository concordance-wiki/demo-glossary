---
aliases: [office conversion, conversion block]
---
# Conversion

The transformation of an office document into a PDF at build, by a [converter](converter.md) plugin, so that its text is extracted from that PDF and nothing else, and the `conversion:` block of the [configuration](configuration.md) that bounds it: `timeout_s` (120) per document, `max_size_mb` (50) beyond which a file stays unconverted, `cache`, the [fingerprint cache](fingerprint-cache.md) outside `dist/`, and `parallelism`, the number of concurrent conversions, which changes the build time and never the output. A document that fails to convert yields `W-CONV-FAILED` and stays downloadable; no converter runs in this version.
