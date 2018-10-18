# Changelog

## v 0.2.4

@gerbal added the ability to pass Xandra's authentication configuration to Triton.

## v 0.2.3

Added ability to allow filtering on any query.

## v 0.2.2

Fixed a bug accidentally introduced in 0.2 with delete queries.  They should now work properly.

## v 0.2.1 (Retired)

pablohirafuji PR: #8 - fix validation type coercion for comparison queries in issue #7

## v 0.2.0 (Retired)

Fixed a type coercion issue in comparison queries during the validation step.

## v 0.1.10

**Breaking** - Table.streamed renamed to Table.stream

Added more documentation for range queries and streaming to readme.

## v 0.1.9

Change supervision tree so that clusters cannot interrupt each other.

## v 0.1.8

Make Triton.Monitor more stable by using one_for_all strategy.

## v 0.1.7

Fixed a bug with Triton.Monitor from 1.6.

## v 0.1.6 (Retired)

Added Triton.Monitor to cleanly reconnect to DB in the event db_connection becomes disconnected.

## v 0.1.5

Added field validation to updates.

## v 0.1.4

Added ability to define a transform function on any field (used for select statements)

## v 0.1.3

Fix DateTimes and change how streams work

## v 0.1.1

Remove MIX.env from codebase

## v 0.1.0

Initial Release
