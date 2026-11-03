# Nhóm "Máy chủ tìm kiếm và chỉ mục" — bản nháp 03/11/2026

5 bài, key 734–738, `batch: 118`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 734 | Sonic: máy chủ hậu cảnh tìm kiếm nhanh, nhẹ, không lược đồ, nhận văn bản tìm kiếm và cặp mã định danh rồi truy vấn trong chớp mắt, thay thế đơn giản cho Elasticsearch trong một số trường hợp; README ghi dự án đang viết lại lớn ở nhánh v2 | [valeriansaliou/sonic](https://github.com/valeriansaliou/sonic) | {'key': 'mpl-2.0', 'name': 'Mozilla Public License 2.0', 'spdx_id': 'MPL-2.0', 'url': 'https://api.github.com/licenses/mpl-2.0', 'node_id': 'MDc6TGljZW5zZTE0'} | 21375 | 2026-10-30 |
| 735 | Apache Lucene: thư viện công cụ tìm kiếm văn bản hiệu năng cao, đầy đủ tính năng viết bằng Java, nền của nhiều hệ tìm kiếm khác; README chỉ có hướng dẫn thiết lập cơ bản, tài liệu đầy đủ ở trang dự án; giấy phép Apache 2.0 | [apache/lucene](https://github.com/apache/lucene) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 3605 | 2026-11-02 |
| 736 | Apache Solr: nền tảng tìm kiếm đa phương thức mã nguồn mở xây trên Apache Lucene, tuyên bố cực nhanh; README có hướng dẫn tải, chạy trên máy, Docker, Kubernetes, cách dùng, hỗ trợ và nhà phát triển; giấy phép Apache 2.0 | [apache/solr](https://github.com/apache/solr) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 1696 | 2026-11-02 |
| 737 | ParadeDB: nâng cấp Postgres bằng chỉ mục riêng cho tìm kiếm toàn văn và vector, điểm BM25, bộ lọc, aggregation và join, xây như phần mở rộng Postgres trên Tantivy và DataFusion; bản Community AGPL-3.0, bản Enterprise bán riêng; README có lệnh cài tải tập lệnh từ mạng | [paradedb/paradedb](https://github.com/paradedb/paradedb) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 9473 | 2026-11-03 |
| 738 | USearch: công cụ tìm kiếm tương tự và phân cụm một tệp, nhỏ gọn, tự nhận nhanh hơn FAISS 10 lần cho HNSW, thư viện một tiêu đề C++11, tối ưu SIMD, hỗ trợ số liệu tùy biến, xem chỉ mục lớn từ đĩa; README rất dài | [unum-cloud/usearch](https://github.com/unum-cloud/usearch) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 4368 | 2026-10-31 |

## Repo đã xem nhưng không đưa vào nhóm này

- **dottxt-ai/outlines** (Apache-2.0, README khoảng 24 KB): để dành, README nhiều phần quảng bá giải pháp doanh nghiệp; có thể đưa vào đợt sau.
- Nhóm gồm năm repo để dành từ đợt trước (Sonic, Lucene, Solr, ParadeDB, USearch); nhóm có 5 bài.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Dữ liệu và giao diện ứng dụng', nhãn gần nhất trong 9 nhãn có sẵn.
- Lucene và Solr (thông báo Apache License 2.0 ở đầu README), ParadeDB (AGPL-3.0 cho Community, thương mại cho Enterprise) nêu giấy phép trong README. Sonic và USearch: README phần đã đọc không nêu giấy phép, lấy theo GitHub (MPL-2.0, Apache-2.0).
- README Sonic ghi nhánh master chỉ nhận sửa lỗi vì dự án đang viết lại lớn ở nhánh v2, và liệt kê giới hạn rõ ràng. README ParadeDB có lệnh cài tải tập lệnh từ mạng: bài không chép lệnh và khuyên đọc tập lệnh trước; ParadeDB Enterprise và Cloud là sản phẩm trả phí. Tuyên bố của tác giả, bài không kiểm chứng: số liệu hiệu năng của Sonic (vài micro giây, nửa tỷ đối tượng), 'cực nhanh' của Solr, nhanh hơn FAISS 10 lần của USearch và bảng so sánh đi kèm. README USearch (khoảng 34 KB) và Sonic (khoảng 23 KB) rất dài: bài đọc phần đầu và các mục chính. Chỉ mục tìm kiếm có thể chứa dữ liệu nhạy cảm: bài nhắc xác thực và không phơi cổng ra Internet.

