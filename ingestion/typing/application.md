---
aliases: [applications, application container]
---
# Application

A container of first level, declared under `applications:` of the [configuration](../configuration/configuration.md) with an `id`, a `title` and a `status` (`active`, `legacy` or `target`). Every [entity](../../inference/model/entity.md) is resolved to one in increasing precedence: the `application` of its [source](../sources/source.md), the `set: { application }` of a typing rule, the `application` of its frontmatter. An entity without one yields `W-APP-MISSING`, one naming an undeclared identifier `W-APP-UNKNOWN`; the search results and the breadcrumb of a page show the application an entity is filed under.
