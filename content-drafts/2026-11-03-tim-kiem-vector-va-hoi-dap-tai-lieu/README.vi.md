# Nhóm "Tìm kiếm, vector và hỏi đáp trên tài liệu" — bản nháp 03/11/2026

7 bài, key 727–733, `batch: 117`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 727 | Tantivy: thư viện tìm kiếm toàn văn nhanh viết bằng Rust, gần Apache Lucene hơn Elasticsearch, là thư viện (crate) để dựng công cụ tìm kiếm chứ không phải máy chủ có sẵn; có BM25, bộ tách từ cấu hình được, thời gian khởi động dưới 10 ms; giấy phép MIT | [quickwit-oss/tantivy](https://github.com/quickwit-oss/tantivy) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 16388 | 2026-11-02 |
| 728 | Faiss: thư viện tìm kiếm tương tự và phân cụm hiệu quả cho vector dày, có thuật toán cho tập vector mọi kích thước kể cả không vừa bộ nhớ, có bản cài GPU; README nêu giấy phép MIT | [facebookresearch/faiss](https://github.com/facebookresearch/faiss) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 41253 | 2026-11-03 |
| 729 | LanceDB: nền tảng dữ liệu đa phương thức cho AI xây trên định dạng cột Lance, tìm kiếm vector nhanh trên hàng tỷ vector, tìm toàn văn và SQL, có bản nhúng mã nguồn mở và bản Enterprise; giấy phép Apache 2.0 theo GitHub | [lancedb/lancedb](https://github.com/lancedb/lancedb) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 11838 | 2026-11-03 |
| 730 | Vespa: tìm kiếm, suy luận và tổ chức vector, tensor, văn bản và dữ liệu có cấu trúc lúc phục vụ ở mọi quy mô; kho chứa toàn bộ mã dựng và chạy Vespa, phát hành mỗi sáng Thứ Hai đến Thứ Năm; giấy phép Apache 2.0 | [vespa-engine/vespa](https://github.com/vespa-engine/vespa) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 7158 | 2026-11-03 |
| 731 | Quickwit: công cụ tìm kiếm mã nguồn mở cho quan sát hệ thống (log, vết, sắp có số liệu), tuyên bố nhanh nhất trên kho đám mây, API tương thích Elasticsearch, gốc Jaeger và OpenTelemetry; giấy phép Apache 2.0 | [quickwit-oss/quickwit](https://github.com/quickwit-oss/quickwit) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 11763 | 2026-11-03 |
| 732 | Hnswlib: thư viện C++ chỉ gồm tiêu đề cài đặt HNSW để tìm láng giềng gần đúng nhanh, có liên kết Python, chèn và cập nhật; README ghi bản 0.10.0rc2 là bản thử, chưa phải bản ổn định; giấy phép Apache 2.0 theo GitHub | [nmslib/hnswlib](https://github.com/nmslib/hnswlib) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 5365 | 2026-09-15 |
| 733 | RAGFlow: công cụ RAG (sinh có truy xuất) mã nguồn mở hàng đầu theo tự mô tả, kết hợp RAG với khả năng tác tử, chia đoạn theo mẫu, trích dẫn có căn cứ, nhiều nguồn dữ liệu; README có yêu cầu cấu hình, triển khai bằng Docker và đám mây của chính họ; giấy phép Apache 2.0 | [infiniflow/ragflow](https://github.com/infiniflow/ragflow) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 93425 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **marqo-ai/marqo** (README khoảng 1,4 KB): README ngắn; loại. **spotify/annoy** (commit 2025-10-29, quá 60 ngày): loại. **zincsearch/zincsearch**, **pgvector/pgvector**, **weaviate/weaviate**, **langgenius/dify**: GitHub không trả giấy phép SPDX rõ (NOASSERTION); loại.
- **valeriansaliou/sonic** (MPL-2.0, README khoảng 23 KB), **apache/lucene**, **apache/solr**, **paradedb/paradedb** (AGPL-3.0), **unum-cloud/usearch**: đủ điều kiện nhưng chưa đưa vào nhóm này (README Sonic ghi dự án đang viết lại lớn, chỉ nhận sửa lỗi ở nhánh master; có thể đưa vào đợt sau).
- Nhóm có 7 bài.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Dữ liệu và giao diện ứng dụng', nhãn gần nhất trong 9 nhãn có sẵn.
- Tantivy (huy hiệu MIT), Faiss (mục Legal MIT), Vespa (Apache 2.0), Quickwit (huy hiệu và FAQ Apache 2.0), RAGFlow (huy hiệu Apache 2.0) nêu giấy phép trong README. LanceDB và Hnswlib: README phần đã đọc không nêu, lấy theo GitHub (Apache-2.0).
- README Hnswlib ghi bản mới nhất 0.10.0rc2 là bản thử, chưa ổn định. README RAGFlow có khuyến nghị cấu hình (4 lõi CPU, 16 GB RAM), tham số vm.max_map_count khi dùng Elasticsearch và dịch vụ đám mây riêng của họ; LanceDB có bản Enterprise trả phí. Tuyên bố của tác giả, bài không kiểm chứng: hiệu năng Tantivy, tốc độ và chi phí Quickwit, quy mô LanceDB, giảm ảo giác của RAGFlow, 'hàng đầu' của RAGFlow. Dữ liệu và tài liệu nạp vào chỉ mục có thể nhạy cảm: bài nhắc xác thực, quyền truy cập và kiểm chứng câu trả lời.

