# ``Trait``

## Topics

### Enabling and disabling

- ``Trait/enabled(if:_:fileID:filePath:line:column:)``
- ``Trait/enabled(_:fileID:filePath:line:column:_:)``
- ``Trait/disabled(_:fileID:filePath:line:column:)``
- ``Trait/disabled(if:_:fileID:filePath:line:column:)``
- ``Trait/disabled(_:fileID:filePath:line:column:_:)``

### Limiting the running time of tests

- ``Trait/timeLimit(_:)``

<!--
HIDDEN: .serial is experimental SPI pending feature review.
### Running tests serially or in parallel
- ``Trait/serial``
 -->
 
### Categorizing tests

- ``Trait/tags(_:)-505n9``
- ``Trait/tags(_:)-yg0i``

### Associating issues

- ``Trait/bug(_:relationship:_:)-86mmm``
- ``Trait/bug(_:relationship:_:)-3hsi5``

<!-- FIXME: Uncomment this section if/when the `.comment(...)` trait is promoted
  to non-experimental SPI.
- ``Trait/comment(_:)`` -->

### Preparing internal state

- ``prepare(for:)-3s3zo`` <!-- func prepare(for test: Test) async throws -->
