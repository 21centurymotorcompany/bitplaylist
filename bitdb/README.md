# Bitquery examples for BitDB

## 1. Basic

Just basic queries with no processing step

- [Exact match](exact_match.json): Exact match query
- [Exact match + Full text search](exact_match_full_text.json): Combine exact match and full text search
- [Hex query](hex_query.json): Filter push data as hex value
- [Multisig TX](multisig_tx.json): Find multisig transactions
- [OP_RETURN TX](opreturn_tx.json): Find only OP_RETURN transactions
- [Projection](projection.json): Use MongoDB's `project` operator to narrow down attributes
- [Query by address](query_by_address.json): Query transactions by address
- [Query by multiple addresses](query_by_multi_address.json): Query transactions by both incoming and outgoing addresses
- [Full text search](regex_full_text_search.json): Perform full text search

## 2. Process

Query + processing to transform the query result.

- [Conditional](process/conditional.json): if-then-else-then to filter out attributes
- [Filter](process/filter.json): `select` method to filter
- [Local variable](process/local_variable.json): Local variable usage within the processing function
- [map](process/map.json): Regular mapping function
- [Construct String](process/string_construction.json): String construction
- [String interpolation](process/string_interpolation.json): Build strings with string interpolation

## 3. Apps

Let's add bitquery for some bitcoin apps here (Please feel free to add your own as well):

1. [Memo.cash](apps/memo.json): All the protocol implementations of Memo.cash, written in Bitquery
