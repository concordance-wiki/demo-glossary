---
aliases: [generated site, site block]
---
# Site

What the [build](build.md) writes under `dist/` after the model: the home page, one page per [entity](entity.md) at the address of its [identifier](identifier.md), the [alphabetical index](alphabetical-index.md), the to-do page, the results page with the [search index](search-index.md) next to it, and the assets. Every link is relative and every page sits in its own folder as `index.html`, so the site reads over `file://` as behind a server and under any prefix. The `site:` block of the [configuration](configuration.md) holds the options of the pages, `neighbourhood.size`, the number of nodes of the neighbourhood map, six by default and twelve at most.
