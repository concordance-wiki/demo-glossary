---
aliases: [format reader]
broader: contribution-point.md
---
# Reader

A [contribution point](contribution-point.md) of the plugin API that reads a file format: it receives the path and the raw bytes of a file and returns its native metadata (title, author, dates, counts) and its text, the cues of a [transcript](transcript.md) for the VTT reader. A reader is synchronous and pure, reads nothing but the bytes it is given, and throws a plain error naming the file when it cannot, which the pipeline turns into a [finding](finding.md).

## Not to be confused with

The reader of the site, the person who opens a page; the specifications describe that reader as a role.
