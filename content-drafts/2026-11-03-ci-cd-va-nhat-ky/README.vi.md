# Nhóm "CI/CD và nhật ký" — bản nháp 03/11/2026

7 bài, key 346–352, `batch: 61`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 346 | Gitea: dịch vụ lưu mã Git tự host trọn gói, có kanban, wiki, kho gói và CI/CD dùng lại được GitHub Actions | [go-gitea/gitea](https://github.com/go-gitea/gitea) | MIT | 58841 | 2026-11-03 |
| 347 | Woodpecker CI: công cụ CI/CD gọn nhẹ chạy được với SQLite, mở rộng bằng plugin, được Codeberg dùng | [woodpecker-ci/woodpecker](https://github.com/woodpecker-ci/woodpecker) | Apache-2.0 | 8099 | 2026-11-03 |
| 348 | Jenkins: máy chủ tự động hóa mã nguồn mở viết bằng Java với hơn 2.000 plugin, dùng để dựng, kiểm thử và triển khai | [jenkinsci/jenkins](https://github.com/jenkinsci/jenkins) | MIT | 26721 | 2026-11-03 |
| 349 | Grafana Loki: hệ thống gom nhật ký lấy cảm hứng từ Prometheus, chỉ lập chỉ mục nhãn chứ không lập chỉ mục toàn văn | [grafana/loki](https://github.com/grafana/loki) | AGPL-3.0 | 29112 | 2026-11-03 |
| 350 | Vector: ống dẫn dữ liệu quan sát viết bằng Rust, thu thập, biến đổi và định tuyến nhật ký và số liệu tới nhiều đích | [vectordotdev/vector](https://github.com/vectordotdev/vector) | MPL-2.0 | 22786 | 2026-11-03 |
| 351 | Fluentd: bộ thu thập nhật ký mã nguồn mở thuộc CNCF, README nêu nhánh master cho v1 và v0.12 đã ngừng hỗ trợ | [fluent/fluentd](https://github.com/fluent/fluentd) | Apache-2.0 | 13611 | 2026-11-02 |
| 352 | Alertmanager: nhận cảnh báo từ Prometheus, loại trùng, gom nhóm và gửi tới đúng người nhận | [prometheus/alertmanager](https://github.com/prometheus/alertmanager) | Apache-2.0 | 8677 | 2026-11-01 |

## Repo đã xem nhưng không đưa vào nhóm này

- **gitlabhq/gitlabhq**, **elastic/elasticsearch**: GitHub trả giấy phép `NOASSERTION` nên bài không nêu giấy phép khi chưa đọc rõ; gitlabhq còn là bản sao (mô tả "GitLab CE Mirror"); loại.
- **open-telemetry/opentelemetry-collector**: README đã đọc nhưng chưa đưa vào đợt này, có thể làm sau.
- **harness/drone**: tìm kiếm GitHub không truy cập được ở thời điểm kiểm tra.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập (nhóm này đều ở mức khó).
- Fluentd: README không nêu CNCF; thông tin này lấy từ mô tả kho trên GitHub và đã ghi rõ trong bài.
- Loki: README nhắc "GEL" chưa giải thích; bài không khẳng định ý nghĩa. README cảnh báo chuyển Helm chart từ 16/3/2026.
- Vector: các tuyên bố "nhanh hơn 10 lần" và giảm chi phí là của README, chưa kiểm chứng.
- Jenkins, Gitea, Woodpecker: README ngắn về cách cài; chi tiết ở tài liệu chưa đọc.

