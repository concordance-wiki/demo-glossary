---
aliases: [inference block, inference chain]
---
# Inference

The part of the pipeline that turns [occurrences](occurrence.md) into [links](link.md), [keyword pages](keyword-page.md) and [twin resources](twin-resources.md), and the `inference:` block of the [configuration](configuration.md) that tunes it: `glossary_sources`, `stopwords`, `short_terms` and `type_prefixes` for the [dictionary](dictionary.md); `cross_source_links` for links across sources; `ngrams` and `candidate_score` for the [candidate expressions](candidate-expression.md); `keyword_pages` for the [publication threshold](publication-threshold.md); `neighbours` for the bounded [neighbourhood](neighbourhood.md); `duplicates` for the reconciliation of twin resources. Inference reads the model and the profile and nothing else, so two builds infer the same links.
