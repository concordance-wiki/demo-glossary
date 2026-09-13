---
aliases: [stale, dormant source]
---
# Staleness

The age after which a [source](source.md) or a [note](note.md) is flagged `W-STALE`: `staleness.warn_after_days` in the configuration, a default and per-source overrides, the dates coming from git. The home page reads the same thresholds and marks a source dormant in its freshness entry when its newest change is older than its threshold at the instant of the build, 180 days without the key.
