---
aliases: [candidate term, term candidate, recurring expression]
---
# Candidate expression

An expression of one to four words that the keyword discovery kept because it recurs without a [note](note.md): at least three [occurrences](occurrence.md) in two distinct files, neither starting nor ending with a [stopword](stopword.md), not made only of digits, not shorter than three characters, absent from the [dictionary](dictionary.md) and from the rejected terms of the [lock](lock.md). Each candidate is scored by its C-value times its inverse document frequency; from `inference.candidate_score`, 4.0 by default, it yields `W-TERM-UNDEFINED`, and above the [publication threshold](publication-threshold.md) it gets a [keyword page](keyword-page.md). The candidates are listed under `candidates.terms` of the [model](model.md) with their score, counts and contexts.
