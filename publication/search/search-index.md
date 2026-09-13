---
aliases: [index]
---
# Search index

The files the build writes under `search/` so that a page searches the whole corpus without a server: an entity table and one shard per two-character prefix, holding the words of every [entity](../../inference/model/entity.md), its title, aliases, summary, [note](../../ingestion/documents/note.md) text, type, application, domain, status and [source](../../ingestion/sources/source.md), each with a weight. The page loads the table when the search field takes focus and one shard per word typed, so that a query matches by prefix as the reader types, over `file://` as behind a server.

## Not to be confused with

The [alphabetical index](alphabetical-index.md), the page that lists every word by initial letter; the search index is a set of files no reader opens.
