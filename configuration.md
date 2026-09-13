---
aliases: [concordance.yaml, configuration file]
---
# Configuration

The file `concordance.yaml` of the [configuration repository](configuration-repository.md), validated by the published configuration schema and read first by every command: its [version](version.md), the [project](project.md), the [profile](profile.md), the [plugins](plugin.md), the [applications](application.md), the [domains](domain.md), the [privacy](privacy.md) block, the [sources](source.md), the [staleness](staleness.md) thresholds, the [inference](inference.md) options, the [conversion](conversion.md) limits, the [build](build.md) block, the [site](site.md) options, the [checks](check.md) overrides and the [lock](lock.md). `concordance validate-config` prints one line per faulty key; `concordance init` writes a commented one.
