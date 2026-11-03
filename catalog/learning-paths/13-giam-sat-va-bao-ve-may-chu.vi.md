# Lộ trình 13 — Giám sát và bảo vệ máy chủ

Biết máy chủ đang khỏe hay yếu, và ai đang cố xâm nhập; chọn công cụ phù hợp mức kinh nghiệm.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Netdata: xem sức khỏe máy chủ theo thời gian thực, và lưu ý các thành phần có giấy phép khác nhau** (key 189, độ khó: Trung bình) — Đồng hồ sức khỏe máy chủ dựng sẵn.  
   Repo: [netdata/netdata](https://github.com/netdata/netdata) · Bản nháp: `content-drafts/2026-11-03-giam-sat-may-chu/content.json`
2. **Prometheus: hệ thống giám sát tiêu chuẩn của thế giới cloud, thu số liệu bằng cách hỏi từng dịch vụ** (key 190, độ khó: Khó) — Thu số liệu theo chuẩn của thế giới cloud (khó hơn).  
   Repo: [prometheus/prometheus](https://github.com/prometheus/prometheus) · Bản nháp: `content-drafts/2026-11-03-giam-sat-may-chu/content.json`
3. **CrowdSec: phát hiện và chặn IP độc hại dựa trên nhật ký và danh sách chia sẻ của cộng đồng** (key 191, độ khó: Trung bình đến khó) — Phát hiện và chặn IP độc hại, cân nhắc việc chia sẻ dữ liệu.  
   Repo: [crowdsecurity/crowdsec](https://github.com/crowdsecurity/crowdsec) · Bản nháp: `content-drafts/2026-11-03-giam-sat-may-chu/content.json`
4. **Tailscale: nối các thiết bị của bạn thành một mạng riêng an toàn dựa trên WireGuard** (key 186, độ khó: Trung bình) — Truy cập quản trị qua mạng riêng thay vì mở cổng.  
   Repo: [tailscale/tailscale](https://github.com/tailscale/tailscale) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
5. **Gitleaks: dò mật khẩu và khóa API lỡ để lại trong mã nguồn** (key 136, độ khó: Trung bình) — Nhớ giữ khóa bí mật khỏi mã nguồn.  
   Repo: [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
