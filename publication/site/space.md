---
aliases: [space of a page, tree of the space]
---
# Space

A [source](../../ingestion/sources/source.md) as a reader browses it in the generated [site](site.md): the top bar links to the spaces page, which lists them all with what each holds, its page count and its newest change; every space has a page of its own, `<source>/index.html`, where the rows of the home page lead, with its [categories](category.md), the top-level folders of its repository, its latest changes and the words its notes cite most, counted in the space only, under a search field confined to it; the breadcrumb of an [entity](../../inference/model/entity.md) page starts with its space, and the left column of that page shows the tree of the space, its head leading to the page of the space, its folders with their page counts, each leading to its category, the folder of the page open and the page marked. The tree appears there only, so that nothing has to be unfolded from the home page. A space is named by the `title` its source declares, its name standing in without one and staying the first segment of every address.

## Not to be confused with

A [source](../../ingestion/sources/source.md), the same repository seen from the configuration: its path or git address, its ref and its typing rules. A space is that source once published, named as the configuration names it.
