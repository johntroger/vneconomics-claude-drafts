# Lộ trình 42 — CI/CD, lưu mã tự host và nhật ký

Tự động hóa kiểm thử và triển khai, lưu mã tự host, thu thập nhật ký và cảnh báo; luôn giữ bí mật ngoài kho mã.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Gitea: dịch vụ lưu mã Git tự host trọn gói, có kanban, wiki, kho gói và CI/CD dùng lại được GitHub Actions** (key 346, độ khó: Khó) — Lưu mã Git tự host trọn gói.  
   Repo: [go-gitea/gitea](https://github.com/go-gitea/gitea) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
2. **Woodpecker CI: công cụ CI/CD gọn nhẹ chạy được với SQLite, mở rộng bằng plugin, được Codeberg dùng** (key 347, độ khó: Khó) — CI/CD gọn nhẹ.  
   Repo: [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
3. **Jenkins: máy chủ tự động hóa mã nguồn mở viết bằng Java với hơn 2.000 plugin, dùng để dựng, kiểm thử và triển khai** (key 348, độ khó: Khó) — CI/CD lâu đời nhiều plugin.  
   Repo: [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
4. **Fluentd: bộ thu thập nhật ký mã nguồn mở thuộc CNCF, README nêu nhánh master cho v1 và v0.12 đã ngừng hỗ trợ** (key 351, độ khó: Khó) — Thu nhật ký; chú ý nhánh v1 và v0.12.  
   Repo: [fluent/fluentd](https://github.com/fluent/fluentd) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
5. **Vector: ống dẫn dữ liệu quan sát viết bằng Rust, thu thập, biến đổi và định tuyến nhật ký và số liệu tới nhiều đích** (key 350, độ khó: Khó) — Ống dẫn dữ liệu quan sát (tuyên bố nhanh là của README).  
   Repo: [vectordotdev/vector](https://github.com/vectordotdev/vector) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
6. **Grafana Loki: hệ thống gom nhật ký lấy cảm hứng từ Prometheus, chỉ lập chỉ mục nhãn chứ không lập chỉ mục toàn văn** (key 349, độ khó: Khó) — Gom nhật ký theo nhãn.  
   Repo: [grafana/loki](https://github.com/grafana/loki) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
7. **Alertmanager: nhận cảnh báo từ Prometheus, loại trùng, gom nhóm và gửi tới đúng người nhận** (key 352, độ khó: Khó) — Gom và định tuyến cảnh báo của Prometheus.  
   Repo: [prometheus/alertmanager](https://github.com/prometheus/alertmanager) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-nhat-ky/content.json`
