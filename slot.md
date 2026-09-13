---
aliases: [named slot, site slot]
---
# Slot

One of the eleven named parts of the generated [site](site.md), each with a typed view model that is the contract between the build and a [theme](theme.md): `Shell`, `Header` and `Footer` around every page, then `Home`, `EntityPage`, `KeywordPage`, `SearchResults`, `Index` and `Todo` for the pages, `MentionsPanel` and `Neighbourhood` for the panels of an entity page. The default theme implements every slot; a plugin theme replaces any of them with a component receiving the same props, and the slots it does not provide stay default. The gallery renders every slot with fixture data so that a theme is styled without building a corpus.
