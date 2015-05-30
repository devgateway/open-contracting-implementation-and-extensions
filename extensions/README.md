# Extensions

Some times you need to publish information within your Open Contracting Data Standard releases and records which is not covered by the core schema.

Subject to the [conformance section](http://ocds.open-contracting.org/standard/r/1__0__RC/en/key_concepts/conformance_and_extensions/) of the standard documentation, you can include additional fields within your OCDS files to meet your local needs.

To enable:

* Validation of this additional data;
* The emergence of common approaches to extending the standard;

the standard also supports the documentation of common extensions.

Agreed [extensions are held here](https://github.com/open-contracting/standard/tree/master/standard/schema/extensions).

## Proposed Extensions

A proposed extension is a directory with the prefix proposed_ contains:
* README.md - information about the extension including use cases, existing uses etc.
* schema.json - the schema for the extension in [jsonpatch](http://jsonpatch.com) format
* codelists - a directory that contains any relevant codelists, that would be added to the main schema/codelists directory on acceptance

As proposed extensions are being worked on there may be competing extensions that satisfy different use cases.

In this case, the format is as follows:
* README.md - identifies the separate use cases
* schema_usecase_1.json - a proposed extension that satisfies use case 1
* schema_usecase_2.json - a proposed extension that satisfies use case 2
* codelists

The schema suffixes that describe the use case can be more expressive than _1 _2
e.g. schema_usecase_deliveryOfItems.json


