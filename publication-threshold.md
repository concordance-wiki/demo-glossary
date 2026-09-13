---
aliases: [threshold, keyword page threshold]
---
# Publication threshold

The count a [candidate expression](candidate-expression.md) must reach to get a [keyword page](keyword-page.md): three [occurrences](occurrence.md) in at least two files, `inference.keyword_pages` in the configuration. Below the threshold the expression stays in the search index but has no page. The discovery has thresholds of its own, `inference.ngrams`, which decide which expressions are kept at all; the publication threshold decides which of those become pages, and the build summary reports the pages generated and the expressions under the threshold.
