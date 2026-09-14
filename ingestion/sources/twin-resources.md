---
aliases: [twins, representations of a document]
---
# Twin resources

Several files that are forms of the same [document](../documents/document.md): a slide deck, its markdown notes, the transcript of the meeting where it was shown. The tool scores their likeness (same base name, same title, similar text, same commit, or an explicit declaration) and merges them into a single page when the score is high enough. Below that, it reports a candidate and waits for the [lock](../configuration/lock.md).

The template of the page follows the lead of the group: a markdown note keeps the template of its type and folds the other files under its text, each behind the line naming the file, its kind and its pages; a document without a note, or a note describing one, gets the document page, a transcript the meeting page. Whatever the template, the properties of the page say the same way which files were grouped and why, "3 files grouped — same base name", each file with its kind, and "Separate these files" leads to where the grouping is contested: the contribution address of the project, else the lock guide.
