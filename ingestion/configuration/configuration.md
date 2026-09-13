---
aliases: [concordance.yaml, configuration file]
---
# Configuration

The file `concordance.yaml` of the [configuration repository](configuration-repository.md), validated by the published configuration schema and read first by every command: its [version](../sources/version.md), the [project](project.md), the [profile](profile.md), the [plugins](../../quality/plugins/plugin.md), the [applications](../typing/application.md), the [domains](../typing/domain.md), the [privacy](../sources/privacy.md) block, the [sources](../sources/source.md), the [staleness](../sources/staleness.md) thresholds, the [inference](../../inference/model/inference.md) options, the [conversion](../documents/conversion.md) limits, the [build](../pipeline/build.md) block, the [site](../../publication/site/site.md) options, the [checks](../../quality/checks/check.md) overrides and the [lock](lock.md). `concordance validate-config` prints one line per faulty key; `concordance init` writes a commented one.
