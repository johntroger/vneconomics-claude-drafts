# Nhóm "Giám sát và bảo mật máy chủ" — bản nháp 03/11/2026

3 bài, key 189–191, `batch: 32`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 189 | Netdata: xem sức khỏe máy chủ theo thời gian thực, và lưu ý các thành phần có giấy phép khác nhau | [netdata/netdata](https://github.com/netdata/netdata) | GPL-3.0 | 81256 | 2026-11-03 |
| 190 | Prometheus: hệ thống giám sát tiêu chuẩn của thế giới cloud, thu số liệu bằng cách hỏi từng dịch vụ | [prometheus/prometheus](https://github.com/prometheus/prometheus) | Apache-2.0 | 66916 | 2026-11-03 |
| 191 | CrowdSec: phát hiện và chặn IP độc hại dựa trên nhật ký và danh sách chia sẻ của cộng đồng | [crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) | MIT | 15437 | 2026-11-02 |

## Điểm cần lưu ý
- **Netdata**: ba thành phần có giấy phép khác nhau (Agent GPL v3+, UI NCUL1, Cloud là dịch vụ); các tuyên bố hiệu năng và tiết kiệm năng lượng là của tác giả.
- **CrowdSec**: cơ chế cộng đồng chia sẻ thông tin IP tấn công; có tính năng Console cao cấp trả phí; bài cảnh báo chặn nhầm.
- **Prometheus**: độ khó cao với người mới; bài gợi ý công cụ đơn giản hơn cho máy chủ nhỏ.

## Repo bị loại hoặc cân nhắc
- **henrygd/beszel**: không tải được README qua nhánh `main`; chưa xác minh.
- **fail2ban**: GitHub trả NOASSERTION.
- **grafana**, **uptime-kuma**: đã có trong đợt 100 bài cũ.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Netdata và Prometheus chỉ đọc phần đầu README và các mục chính.

