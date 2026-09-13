---
aliases: [relation type, relation name]
---
# Relation

The name a [link](link.md) carries, taken from the [profile](profile.md): `accesses`, `constrains`, `serves`, `related`. Each relation lists the pairs of types it may join and a label for each direction, so that a screen reads "accesses" an object and the object reads "is accessed by" the screen. A relation is decided on four rungs, the first that applies winning: a mapped section, a typed frontmatter attribute, a type pair that admits a single relation, then `related`, the fallback capped at 0.60 and reported as ambiguous. A relation the profile does not allow between two types never enters the [model](model.md).
