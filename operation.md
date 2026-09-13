---
aliases: [endpoint, operation note]
broader: entity.md
---
# Operation

One callable unit of an API: a method and a path in an OpenAPI contract, a port and an operation name in a WSDL. The build imports every operation of a declared contract as an `endpoint` [entity](entity.md) with the properties the contract states. An author who has business to explain writes an operation note; the build attaches it to the imported operation on its declared identifier, then on its method and path, then on its title, and the note becomes the single page of the operation, showing its own markdown, the properties of the contract and its own [links](link.md).
