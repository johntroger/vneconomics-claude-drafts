# Nhóm "Cơ sở dữ liệu chuyên biệt" — bản nháp 03/11/2026

6 bài, key 457–462, `batch: 78`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 457 | Dolt: cơ sở dữ liệu SQL có thể fork, clone, branch, merge như Git, kết nối như MySQL | [dolthub/dolt](https://github.com/dolthub/dolt) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 24806 | 2026-11-03 |
| 458 | libSQL: bản fork mã nguồn mở của SQLite có bản sao nhúng và truy cập từ xa; README khuyên dự án mới xem Turso viết lại bằng Rust | [tursodatabase/libsql](https://github.com/tursodatabase/libsql) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 17308 | 2026-10-17 |
| 459 | rqlite: cơ sở dữ liệu quan hệ phân tán chịu lỗi xây trên SQLite, một tệp nhị phân, API HTTP | [rqlite/rqlite](https://github.com/rqlite/rqlite) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 17909 | 2026-11-02 |
| 460 | QuestDB: cơ sở dữ liệu chuỗi thời gian mã nguồn mở độ trễ thấp, SQL mở rộng cho chuỗi thời gian; README có số liệu benchmark của hãng và bản Enterprise trả phí | [questdb/questdb](https://github.com/questdb/questdb) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 17496 | 2026-11-03 |
| 461 | Hasura GraphQL Engine: một điểm cuối API GraphQL an toàn tới nhiều nguồn dữ liệu; kho có hai phiên bản V2 ổn định và V3 (DDN) | [hasura/graphql-engine](https://github.com/hasura/graphql-engine) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 32125 | 2026-11-03 |
| 462 | Vitess: hệ cơ sở dữ liệu phân tán mở rộng ngang xây trên MySQL, từng là thành phần cốt lõi hạ tầng dữ liệu của YouTube | [vitessio/vitess](https://github.com/vitessio/vitess) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 21399 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **pocketbase/pocketbase**, **minio/minio**: kho đã lưu trữ (archived); loại.
- **windmill-labs/windmill**, **activepieces/activepieces**, **meilisearch/meilisearch**, **redis/redis**, **surrealdb/surrealdb**, **timescale/timescaledb**: GitHub trả giấy phép NOASSERTION; loại.
- **neondatabase/neon**, **electric-sql/electric**: commit gần nhất trước ngày 2026-09-04, quá 60 ngày; loại.
- **apache/spark**, **apache/flink**, **trinodb/trino**, **apache/cassandra**, **etcd-io/etcd**, **apache/doris**, **apache/iceberg**: đủ điều kiện về giấy phép và thời gian nhưng thuộc dữ liệu lớn và hạ tầng, ít phù hợp người mới vibe coding; chưa đưa vào nhóm này, có thể làm sau.

## Điều chưa biết

- Chưa cài hay chạy cơ sở dữ liệu nào; độ khó là đánh giá biên tập.
- rqlite: README phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub. libSQL: README chỉ có huy hiệu MIT và nói 'giấy phép mã nguồn mở' trong tệp LICENSE.md.
- QuestDB, Vitess, Dolt, Hasura: các số liệu hiệu năng, quy mô và tuyên bố 'tốt nhất' là của hãng, bài không kiểm chứng. Hasura V3 'dự định' theo Apache 2.0 theo README.
- libSQL: README nói tính năng mới phát triển ở Turso; chưa kiểm tra tình trạng bảo trì thực tế.
- Giá các dịch vụ riêng (Hosted Dolt, QuestDB Enterprise, Hasura DDN) chưa kiểm tra.

