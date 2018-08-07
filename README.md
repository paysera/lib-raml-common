# lib-raml-common

A set of common RAML Types, Traits and other stuff.

### Usage
```yaml
uses:
  Paysera: https://raw.githubusercontent.com/paysera/lib-raml-common/{version}/rest.raml
```
Replace `{version}` with latest tag.

### Libraries

#### rest.raml
Provides mostly used items when building RESTful APIs 
* Types:
  * `Money` - holds amount ant currency.
  * `Result` - used for pagination, holds `items` - list of returned objects. Ofter used together with
  * `ResultMetadata` - gives info about `items` count, page number and other pagination related stuff.
* Traits:
  * `Filter` - provides SQL-like `Result` filtering.
* Annotation Types
  * `datetimeTimestamp` - used to mark `integer` property as DateTime instance
  * `enitityType` - user to mark Type recognisable as Entity
