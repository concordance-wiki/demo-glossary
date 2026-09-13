---
aliases: [cooccurrence, shared paragraph]
---
# Co-occurrence

Two [entities](../model/entity.md) named in the same paragraph, counted once per paragraph however many times each is mentioned there. Every pair gives one undirected `related` [link](link.md) at the `cooccurrence` [confidence](confidence.md) of 0.40, emitted once from the lower identifier, with the number of shared paragraphs as the count of its single [provenance](provenance.md); the [relation](relation.md) typing may refine `related` from the type pair. Co-occurrence is accumulated per node in a bounded [neighbourhood](neighbourhood.md) of fifty neighbours, never as a full matrix, and feeds the [accompanying words](accompanying-word.md) of a keyword page.
