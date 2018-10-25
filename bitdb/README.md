# Bitquery examples for BitDB

You can try the examples by going to [bitdb explorer](https://bitdb.network/v3/explorer) and copy and pasting the example JSON below

## Basic

### 1. Query only

Just basic queries with no processing step

- [Exact match](basic/query/exact_match.json): Exact match query
- [Exact match + Full text search](basic/query/exact_match_full_text.json): Combine exact match and full text search
- [Hex query](basic/query/hex_query.json): Filter push data as hex value
- [Multisig TX](basic/query/multisig_tx.json): Find multisig transactions
- [OP_RETURN TX](basic/query/opreturn_tx.json): Find only OP_RETURN transactions
- [Projection](basic/query/projection.json): Use MongoDB's `project` operator to narrow down attributes
- [Query by address](basic/query/query_by_address.json): Query transactions by address
- [Query by multiple addresses](basic/query/query_by_multi_address.json): Query transactions by both incoming and outgoing addresses
- [Full text search](basic/query/regex_full_text_search.json): Perform full text search

### 2. Query + Process

Query + processing to transform the query result.

- [Conditional](basic/process/conditional.json): if-then-else-then to filter out attributes
- [Filter](basic/process/filter.json): `select` method to filter
- [Local variable](basic/process/local_variable.json): Local variable usage within the processing function
- [map](basic/process/map.json): Regular mapping function
- [Construct String](basic/process/string_construction.json): String construction
- [String interpolation](basic/process/string_interpolation.json): Build strings with string interpolation

---

## Apps

Let's add bitquery for some bitcoin apps here (Please feel free to add your own as well):

1. [Memo.cash](apps/memo.json): All the protocol implementations of Memo.cash, written in Bitquery
