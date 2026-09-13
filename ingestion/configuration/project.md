---
aliases: [project block, wiki project]
---
# Project

The wiki being built, as the `project:` block of the [configuration](configuration.md) declares it: its `name`, shown in the site; its `locale`, the language of the interface and the default locale of the sources; its `theme`, the [theme](../../publication/site/theme.md) file relative to the configuration, `theme.yaml` next to it when the key is absent; its `edit_url`, the pattern of the edit link with `{source}`, `{path}` and `{commit}` placeholders, derived from the forge of a GitHub or GitLab source when absent; and its `contribute_url`, the HTTPS address every call to action of the [site](../../publication/site/site.md) leads to when no forge link can be built for it, "Propose a definition" or "Edit this page", which the site leaves out rather than shows inert when neither is known. The project locale, the project profile and the project stylesheet are the ones this block, the [profile](profile.md) and the theme name.
