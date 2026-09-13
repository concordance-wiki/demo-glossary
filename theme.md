---
aliases: [theme.yaml, site theme]
---
# Theme

The file that decides how the generated site looks: the name and logo of the site, its favicon, its font families, its corner radius, its light and dark palettes, its footer and an additional stylesheet loaded after the tool's own. The build validates it against the theme schema and reports a faulty key by its path. A [plugin](plugin.md) may ship a theme of its own, with components replacing parts of the site; the project's file wins over a plugin's. A theme that names the organisation and not the tool is a [white label](white-label.md).
