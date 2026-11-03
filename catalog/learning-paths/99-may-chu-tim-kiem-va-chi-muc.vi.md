# Lộ trình 99 — Máy chủ tìm kiếm và chỉ mục

Từ thư viện tìm kiếm toàn văn nền tảng (Lucene), máy chủ tìm kiếm hoàn chỉnh (Solr), máy chủ hậu cảnh nhẹ (Sonic) đến tìm kiếm trong Postgres (ParadeDB) và chỉ mục vector nhỏ gọn (USearch); chú ý nhánh đang viết lại của Sonic, giấy phép AGPL của ParadeDB, lệnh cài tải tập lệnh từ mạng, tuyên bố hiệu năng của tác giả và việc bảo vệ cổng máy chủ tìm kiếm.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Apache Lucene: thư viện công cụ tìm kiếm văn bản hiệu năng cao, đầy đủ tính năng viết bằng Java, nền của nhiều hệ tìm kiếm khác; README chỉ có hướng dẫn thiết lập cơ bản, tài liệu đầy đủ ở trang dự án; giấy phép Apache 2.0** (key 735, độ khó: Khó) — Thư viện tìm kiếm Java nền tảng (khó).  
   Repo: [apache/lucene](https://github.com/apache/lucene) · Bản nháp: `content-drafts/2026-11-03-may-chu-tim-kiem-va-chi-muc/content.json`
2. **Apache Solr: nền tảng tìm kiếm đa phương thức mã nguồn mở xây trên Apache Lucene, tuyên bố cực nhanh; README có hướng dẫn tải, chạy trên máy, Docker, Kubernetes, cách dùng, hỗ trợ và nhà phát triển; giấy phép Apache 2.0** (key 736, độ khó: Khó) — Máy chủ tìm kiếm trên Lucene (khó).  
   Repo: [apache/solr](https://github.com/apache/solr) · Bản nháp: `content-drafts/2026-11-03-may-chu-tim-kiem-va-chi-muc/content.json`
3. **Sonic: máy chủ hậu cảnh tìm kiếm nhanh, nhẹ, không lược đồ, nhận văn bản tìm kiếm và cặp mã định danh rồi truy vấn trong chớp mắt, thay thế đơn giản cho Elasticsearch trong một số trường hợp; README ghi dự án đang viết lại lớn ở nhánh v2** (key 734, độ khó: Khó) — Hậu cảnh tìm kiếm nhẹ; nhánh đang viết lại (khó).  
   Repo: [valeriansaliou/sonic](https://github.com/valeriansaliou/sonic) · Bản nháp: `content-drafts/2026-11-03-may-chu-tim-kiem-va-chi-muc/content.json`
4. **USearch: công cụ tìm kiếm tương tự và phân cụm một tệp, nhỏ gọn, tự nhận nhanh hơn FAISS 10 lần cho HNSW, thư viện một tiêu đề C++11, tối ưu SIMD, hỗ trợ số liệu tùy biến, xem chỉ mục lớn từ đĩa; README rất dài** (key 738, độ khó: Khó) — Chỉ mục vector nhỏ gọn (khó).  
   Repo: [unum-cloud/usearch](https://github.com/unum-cloud/usearch) · Bản nháp: `content-drafts/2026-11-03-may-chu-tim-kiem-va-chi-muc/content.json`
5. **ParadeDB: nâng cấp Postgres bằng chỉ mục riêng cho tìm kiếm toàn văn và vector, điểm BM25, bộ lọc, aggregation và join, xây như phần mở rộng Postgres trên Tantivy và DataFusion; bản Community AGPL-3.0, bản Enterprise bán riêng; README có lệnh cài tải tập lệnh từ mạng** (key 737, độ khó: Khó) — Tìm kiếm trong Postgres; AGPL (khó).  
   Repo: [paradedb/paradedb](https://github.com/paradedb/paradedb) · Bản nháp: `content-drafts/2026-11-03-may-chu-tim-kiem-va-chi-muc/content.json`
