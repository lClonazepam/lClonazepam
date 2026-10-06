# Methylrx

C++ and small systems tools. Privacy-leaning clients, local utilities, and header-only data structures.

Site: [pct.monster](https://pct.monster)

## Larger project

- [cpp-tsdb](https://github.com/lClonazepam/cpp-tsdb) — single-node time-series engine: WAL, tag index, delta/XOR segments, crash recovery, aggregating queries

## C++ libraries

| Repo | What it is |
| --- | --- |
| [cpp-bloom](https://github.com/lClonazepam/cpp-bloom) | Bloom filter, tunable false-positive rate |
| [cpp-lru](https://github.com/lClonazepam/cpp-lru) | LRU cache with per-key TTL |
| [cpp-hll](https://github.com/lClonazepam/cpp-hll) | HyperLogLog cardinality sketch |
| [cpp-jsonlite](https://github.com/lClonazepam/cpp-jsonlite) | Tiny JSON parser and serializer |
| [cpp-radix](https://github.com/lClonazepam/cpp-radix) | Compressed radix tree |
| [cpp-cron](https://github.com/lClonazepam/cpp-cron) | Five-field cron matcher |
| [cpp-ulid](https://github.com/lClonazepam/cpp-ulid) | Sortable ULID ids |

Also: lock-free rings, arena alloc, WAL kv, limit order book, epoll reactor, tiny VM, work-stealing pool.

## Build

Each library is CMake + C++20. The header-only repos have a `ctest` target and no third-party deps.
