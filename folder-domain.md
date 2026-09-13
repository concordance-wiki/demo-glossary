---
aliases: [domain folder, domain by folder]
broader: domain.md
---
# Folder domain

A [domain](domain.md) recognised by the name of a folder of the corpus rather than by glob patterns: `folder: true` claims every [note](note.md) with a directory named after the domain's identifier on its path, in any [source](source.md), and `folder: <name>` those under a folder of another name; the file name itself never counts. A subdomain declared this way claims only the notes under its parent's folder, or anywhere on a path the parent's globs match when the parent is declared by globs. Folders and globs combine on one domain with the same precedence, the deepest domain first, and a frontmatter `domain` still wins over both.
