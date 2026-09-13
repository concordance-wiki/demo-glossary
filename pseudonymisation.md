---
aliases: [pseudonymization, pseudonymise]
---
# Pseudonymisation

The replacement of the speaker names of a [transcript](transcript.md), and of the personal mentions detected in it, by stable pseudonyms before anything else reads it: `privacy.pseudonymize` in the configuration, off by default, with the types concerned, the dictionary `pseudonyms.yaml` of real names to pseudonyms that is never published, and whether a known role stands in for the pseudonym. A name pattern found outside the dictionary yields `I-PII-DETECTED` for review. Pseudonymisation is a mechanism, not a permission: transcripts are published only when `privacy.publish_transcripts` asks for it.
