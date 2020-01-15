## Upcoming Features

#### Users management

- [x] Create users with encrypted passwords (_password_sha256_hex_ config setting).

#### Databases management

- [x] Specify cluster name for [distributed](https://clickhouse.yandex/docs/en/single/#distributed-ddl-queries-on-cluster-section) database creating/deleting.

#### Server configuration

- [ ] Configure HTTPS and SSL settings, generate self-signed certificates if needed;
- [x] Set up _remote_servers_ parameter for [Distributed](https://clickhouse.yandex/docs/en/single/#distributed) tables;
- [x] Manage _zookeeper_ and _macros_ config elements for [Replicated](https://clickhouse.yandex/docs/en/single/index.html#data-replication) tables;
- [x] Create _GraphiteMergeTree_ table engine related options.
