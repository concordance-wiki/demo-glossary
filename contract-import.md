---
aliases: [imported contract, contract importer]
---
# Contract import

The step of the build that reads the [contract](contract.md) an API note declares and adds what it describes to the [model](model.md): one [operation](operation.md) per operation of the contract, an `exposes` [link](link.md) from the API at the `contract_import` [confidence](confidence.md) of 0.95, the schemas as candidate objects, and one record per contract under `build.contracts` with its title, version, fingerprint and import date. The `contract-openapi` and `contract-wsdl` plugins read OpenAPI 3.x and WSDL documents, the text cached by its fingerprint; a contract that cannot be fetched, read or parsed yields `W-CONTRACT-UNREACHABLE` and the note keeps its hand-written operations.
