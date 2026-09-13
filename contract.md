---
aliases: [interface contract, API contract]
---
# Contract

The machine-readable description of an API that a note declares in its `contract` attribute, as a URL or a path: an OpenAPI 3 document or a WSDL. The build imports it through a [plugin](plugin.md), produces one [operation](operation.md) per operation it declares, caches it by the fingerprint of its bytes and records its title, version and import date in the [model](model.md). The page of the API shows the contract without copying it into the [note](note.md): its operations as a plain list, a link to download the original, and a viewer that loads the signatures and schemas on demand.
