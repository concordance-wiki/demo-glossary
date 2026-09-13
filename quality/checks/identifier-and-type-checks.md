---
aliases: [identifiers and types family]
broader: quality/checks/check-family.md
---
# Identifier and type checks

The [check family](check-family.md) of the reading and typing of a file: `E-ENCODING`, a file that is not UTF-8; `E-FM-INVALID`, a [frontmatter](../../ingestion/documents/frontmatter.md) that does not parse; `E-ID-INVALID` and `E-ID-DUP`, an [identifier](../../ingestion/typing/identifier.md) that breaks the pattern or that two files share; `E-TYPE-CONFLICT`, a frontmatter type contradicting the suffix; `E-META-REL`, a declared [relation](../../inference/links/relation.md) the profile forbids between two types; `W-TYPE-UNKNOWN`, a [type](../../ingestion/typing/type.md) the profile does not declare; `W-ATTRIBUTE-UNKNOWN`, a frontmatter key neither the type nor the common attributes declare.
