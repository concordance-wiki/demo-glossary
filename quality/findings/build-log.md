---
aliases: [build.log.json, log]
---
# Build log

The file `build.log.json` the build writes next to the site: its summary (sources, files, entities per type, links per method, keyword pages and expressions under the threshold, twin resources, the decisions of the [lock](../../ingestion/configuration/lock.md) applied, findings per severity and per check, the contracts imported) and every [finding](finding.md), sorted by check, source, path, line and message. Its `findings` array is the same as the one embedded in the [model](../../inference/model/model.md), and its only timestamp is its `at` field. The log is written before the verdict of `build.fail_on`, so a failing build still leaves it for inspection.
