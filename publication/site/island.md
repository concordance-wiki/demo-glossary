---
aliases: [hydrated island, interactive island]
---
# Island

An interactive component of the [site](site.md) served as its static markup inside a `<concordance-island>` element carrying its props, and mounted again by one small bundle named after a hash of its content, loaded only by the pages that use it. The mentions panel, the search, the contract viewer, the document viewer, the [pinned pages](pinned-page.md) and the handles of the [side panels](side-panel.md) are islands; every one a page loads is a classic script so that it runs from a `file://` page. Without JavaScript the content stays reachable: the served HTML carries every page in full and an island only adds sorting, filtering, fetching on demand or a viewer.
