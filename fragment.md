---
aliases: [JSON fragment, entity fragment]
---
# Fragment

The file the build writes next to the [model](model.md) for one [entity](entity.md), under `fragments/<id>.json`: the [note](note.md) rendered to sanitised HTML, one section per heading, its written [links](link.md) already turned into page links, or the passages of a [keyword page](keyword-page.md). The rendering reads the model and the fragments and nothing else, so `concordance render` rebuilds the site without cloning a [source](source.md). A fragment belongs to one entity and never gathers several. An entity another note cites has a second one, `fragments/<id>.mentions.json`, holding every [mention](mention.md) of it; its page carries the first twenty and loads the rest from there.
