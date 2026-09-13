---
aliases: [documents family]
broader: quality/checks/check-family.md
---
# Document checks

The [check family](check-family.md) of the [documents](../../ingestion/documents/document.md) that are not notes: `W-CONV-FAILED`, an office document the [converter](../../ingestion/documents/converter.md) could not turn into a PDF; `W-CONV-SUSPECT`, a converted PDF without extractable text although the document is large; `W-DOC-NOMD`, a document without a markdown [representation](../../ingestion/sources/representation.md), which the to-do page lists; `W-DUP-CANDIDATE`, two resources that look like [twin resources](../../ingestion/sources/twin-resources.md) without reaching the merge score.
