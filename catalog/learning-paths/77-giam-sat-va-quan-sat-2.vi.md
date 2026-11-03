# Lộ trình 77 — Giám sát và quan sát hệ thống (phần 2)

Từ thu thập log và số liệu đến lưu vết phân tán, lưu số liệu dài hạn và giám sát hiệu năng ứng dụng; chú ý giấy phép AGPL của Tempo và OpenObserve, phần Enterprise, tuyên bố hiệu năng của tác giả và dữ liệu nhạy cảm trong log và vết.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Fluent Bit: tác tử thu thập, xử lý và chuyển tiếp log, số liệu và vết gọn nhẹ hiệu năng cao, thuộc hệ sinh thái Fluentd và CNCF, hơn 70 plugin dựng sẵn, giấy phép Apache v2.0** (key 582, độ khó: Khó) — Thu thập và chuyển tiếp log (khó).  
   Repo: [fluent/fluent-bit](https://github.com/fluent/fluent-bit) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
2. **Grafana Alloy: bản phân phối OpenTelemetry Collector mã nguồn mở có sẵn pipeline Prometheus, hỗ trợ số liệu, log, vết và profile, cấu hình bằng cú pháp lập trình được** (key 583, độ khó: Rất khó) — Bản phân phối OpenTelemetry Collector của Grafana (rất khó).  
   Repo: [grafana/alloy](https://github.com/grafana/alloy) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
3. **VictoriaMetrics: cơ sở dữ liệu chuỗi thời gian nhanh, tiết kiệm và mở rộng được cho giám sát, thay thế hoặc lưu trữ dài hạn cho Prometheus, có bản đơn nút và cụm mã nguồn mở và bản Enterprise** (key 580, độ khó: Khó) — Cơ sở dữ liệu chuỗi thời gian (khó).  
   Repo: [VictoriaMetrics/VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
4. **Thanos: bộ thành phần dựng hệ số liệu sẵn sàng cao và lưu trữ không giới hạn, đặt trên Prometheus hiện có, lưu dữ liệu lịch sử vào kho đối tượng, dự án CNCF ở giai đoạn ươm** (key 584, độ khó: Rất khó) — Mở rộng Prometheus, lưu dài hạn (rất khó).  
   Repo: [thanos-io/thanos](https://github.com/thanos-io/thanos) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
5. **Jaeger: nền tảng lưu vết phân tán do Uber tạo ra và tặng cho CNCF, dự án tốt nghiệp từ 2019, bản v2 dùng nhiều thành phần của OpenTelemetry Collector, giấy phép Apache 2.0** (key 579, độ khó: Rất khó) — Lưu vết phân tán, Apache 2.0 (rất khó).  
   Repo: [jaegertracing/jaeger](https://github.com/jaegertracing/jaeger) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
6. **Grafana Tempo: hệ thống lưu vết phân tán mã nguồn mở, chỉ cần lưu trữ đối tượng để vận hành, tích hợp với Grafana, Prometheus và Loki, giấy phép AGPL-3.0 có ngoại lệ Apache-2.0** (key 578, độ khó: Rất khó) — Lưu vết phân tán, AGPL-3.0 (rất khó).  
   Repo: [grafana/tempo](https://github.com/grafana/tempo) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
7. **OpenObserve: nền tảng quan sát cho log, số liệu, vết, giám sát người dùng thật và AI, tự tả là thay thế Datadog mã nguồn mở, giấy phép AGPL-3.0 và có bản Enterprise** (key 581, độ khó: Khó) — Gom log, số liệu, vết trong một nơi (khó).  
   Repo: [openobserve/openobserve](https://github.com/openobserve/openobserve) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
8. **Apache SkyWalking: hệ thống giám sát hiệu năng ứng dụng (APM) cho vi dịch vụ và kiến trúc đám mây, có lưu vết phân tán, nhiều tác tử ngôn ngữ, eBPF, cơ sở dữ liệu BanyanDB, giấy phép Apache 2.0** (key 585, độ khó: Rất khó) — Giám sát hiệu năng ứng dụng (rất khó).  
   Repo: [apache/skywalking](https://github.com/apache/skywalking) · Bản nháp: `content-drafts/2026-11-03-giam-sat-va-quan-sat-2/content.json`
