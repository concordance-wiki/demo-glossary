---
aliases: [stop word, stopwords]
---
# Stopword

A word the recognition sets aside: it never enters the [dictionary](dictionary.md) as a title or an alias, a phrase made only of stopwords is never a term, and a [candidate expression](candidate-expression.md) never starts or ends with one. The defaults come from the [language pack](language-pack.md) of the source, `stopwords.txt`; `inference.stopwords` adds files of the project, one word per line, `#` opening a comment. Stopwords are compared in the same [comparison form](comparison-form.md) as terms. A default stopword names nothing on its own in any corpus: an article, a pronoun, a form of an auxiliary or light verb, an adverb of prose, a numeral, a noun that only counts or places; a word that could be a business term somewhere, or that ends a technical compound, is left to the project's own files.
