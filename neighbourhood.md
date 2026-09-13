---
aliases: [displayed neighbourhood, neighbourhood map]
---
# Neighbourhood

The [entities](entity.md) one [link](link.md) away from an entity, as the page shows them: six at most, each with its title, its type, the nature of the link and the [confidence](confidence.md) of the strongest link between the two. The order is type-driven: the [profile](profile.md) declares, for each type, which neighbour types come first (operations on an API, accessed objects on a screen, what it applies to on a rule); every neighbour carries the rank of its type, unlisted types and [keyword pages](keyword-page.md) come last, confidence decides within a group, and the list is cut after this ordering. A type without a declaration lists its neighbours by decreasing confidence. The neighbourhood is computed at build and written to the [model](model.md), never in the browser, and the page renders it in the order received, a separator marking each change of rank. Not to be confused with the bounded neighbourhood of co-occurrence, which keeps the fifty best co-occurring entities per node and feeds the links.
