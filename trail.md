---
aliases: [navigation trail, pinned trail]
---
# Trail

The list of the pages a reader visited, in order, each a link, shown under the header of every page of the generated site. It travels in the fragment of the URL, so that a link shares the path followed and a reload restores it; a reader who pins it keeps it in the browser between visits. Beyond twelve pages the oldest fold into one entry that opens on demand. A page the browser never saw is named by its identifier, an [entity](entity.md) being known by its identifier alone until its page is opened. Without JavaScript the trail is not there: the served HTML carries every page in full, as the [theme](theme.md) renders it.
