# Methylrx

C++ and small systems tools. Privacy-leaning clients, local utilities, and header-only data structures.

Site: [pct.monster](https://pct.monster)

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

Each library is CMake + C++20, header-only, with a `ctest` target. No third-party deps.
