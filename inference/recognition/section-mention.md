---
aliases: [mapped section mention]
broader: inference/recognition/mention.md
---
# Section mention

A [recognised word](recognised-word.md) read in a section whose heading the [profile](../../ingestion/configuration/profile.md) maps to a [relation](../links/relation.md): an object named under `## Objects` of a screen is accessed by it, a rule under `## Rules` constrains it, a note under `## Affects` of a decision is affected by it. The section decides the relation, so the [link](../links/link.md) is typed on the first rung and carries the `section_mention` [confidence](../links/confidence.md) of 0.70, above a word read in prose. Headings are matched without regard to case or accents, in the language of the source.
