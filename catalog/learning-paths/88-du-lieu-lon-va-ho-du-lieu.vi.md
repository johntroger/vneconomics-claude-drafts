# Lộ trình 88 — Dữ liệu lớn và hồ dữ liệu

Từ định dạng trao đổi dữ liệu, xử lý phân tán, xử lý luồng, bộ máy truy vấn SQL xuyên nhiều nguồn đến các định dạng bảng của hồ dữ liệu (Iceberg, Delta Lake, Hudi); chú ý chi phí đám mây, tuyên bố của tác giả, dữ liệu nhạy cảm và việc phần lớn người học không cần cụm.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Apache Arrow: định dạng cột phổ quát và bộ công cụ đa ngôn ngữ cho trao đổi dữ liệu nhanh và phân tích trong bộ nhớ, gồm định dạng cột, IPC, ADBC, Flight RPC và thư viện C++; giấy phép Apache 2.0** (key 663, độ khó: Khó) — Định dạng cột trao đổi dữ liệu (khó).  
   Repo: [apache/arrow](https://github.com/apache/arrow) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
2. **Apache Spark: công cụ phân tích hợp nhất cho xử lý dữ liệu quy mô lớn với API Scala, Java, Python và R, Spark SQL, pandas API, MLlib, GraphX, Structured Streaming; README nêu đây chỉ là hướng dẫn thiết lập cơ bản** (key 661, độ khó: Khó) — Phân tích dữ liệu quy mô lớn (khó).  
   Repo: [apache/spark](https://github.com/apache/spark) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
3. **Ray: khung hợp nhất để mở rộng ứng dụng AI và Python, gồm runtime phân tán lõi và các thư viện AI (Data, Train, Tune, RLlib, Serve), có Tasks, Actors, Objects, bảng điều khiển và trình gỡ lỗi phân tán** (key 664, độ khó: Khó) — Mở rộng Python và AI (khó).  
   Repo: [ray-project/ray](https://github.com/ray-project/ray) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
4. **Apache Flink: khung xử lý luồng mã nguồn mở có khả năng xử lý luồng và lô mạnh, runtime ưu tiên luồng, hỗ trợ thời gian sự kiện, cửa sổ linh hoạt và xử lý đúng một lần theo tuyên bố của dự án** (key 660, độ khó: Rất khó) — Xử lý luồng (rất khó).  
   Repo: [apache/flink](https://github.com/apache/flink) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
5. **Trino: bộ máy truy vấn SQL phân tán nhanh cho phân tích dữ liệu lớn; README chủ yếu hướng dẫn phát triển, xây, chạy trong IDE và chính sách bảo mật; hỗ trợ bản dựng tái lập** (key 662, độ khó: Rất khó) — Truy vấn SQL xuyên nhiều nguồn (rất khó).  
   Repo: [trinodb/trino](https://github.com/trinodb/trino) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
6. **Apache Iceberg: định dạng hiệu năng cao cho bảng phân tích khổng lồ, đưa độ tin cậy và đơn giản của bảng SQL vào dữ liệu lớn, cho phép nhiều bộ máy (Spark, Trino, Flink, Presto, Hive, Impala) làm việc trên cùng bảng** (key 665, độ khó: Rất khó) — Định dạng bảng hồ dữ liệu (rất khó).  
   Repo: [apache/iceberg](https://github.com/apache/iceberg) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
7. **Delta Lake: khung lưu trữ mã nguồn mở để dựng kiến trúc Lakehouse với các bộ máy tính toán như Spark, PrestoDB, Flink, Trino và Hive, có các trình kết nối, giao thức giao dịch và kiểm soát đồng thời; giấy phép Apache 2** (key 666, độ khó: Rất khó) — Lakehouse trên Delta (rất khó).  
   Repo: [delta-io/delta](https://github.com/delta-io/delta) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
8. **Apache Hudi: nền tảng hồ dữ liệu mở dựng trên định dạng bảng mở hiệu năng cao để nạp, lập chỉ mục, lưu, phục vụ, biến đổi và quản lý dữ liệu trên nhiều môi trường đám mây; có công cụ nạp cho Spark và Flink** (key 667, độ khó: Rất khó) — Lakehouse với cập nhật theo bản ghi (rất khó).  
   Repo: [apache/hudi](https://github.com/apache/hudi) · Bản nháp: `content-drafts/2026-11-03-du-lieu-lon-va-ho-du-lieu/content.json`
