# sql-plsql-samples
Project work

A collection of SQL and PL/SQL examples demonstrating database development
and performance tuning. All data is synthetic and for demonstration only.

## Contents
- `analytical_queries.sql` — reporting queries using analytical functions
- `order_processor.pks` / `.pkb` — a packaged procedure with exception handling

## Highlights
- Report query tuned from ~45s to ~2s using an analytical function
  and a covering index (see `analytical_queries.sql`).
- Package with `PRAGMA AUTONOMOUS_TRANSACTION` for reliable logging
  (see `order_processor.pkb`).

## Environment
Oracle 19c · PL/SQL · SQL*Plus
