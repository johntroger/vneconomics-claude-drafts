# Lộ trình 31 — Sao lưu và đồng bộ dữ liệu

Hiểu khác biệt giữa sao lưu và đồng bộ, rồi chọn công cụ; luôn thử khôi phục trước khi tin tưởng.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Syncthing: đồng bộ tệp liên tục giữa các máy của bạn, đặt an toàn dữ liệu lên hàng đầu; đồng bộ không phải sao lưu** (key 289, độ khó: Trung bình) — Đồng bộ giữa máy của bạn; không phải sao lưu.  
   Repo: [syncthing/syncthing](https://github.com/syncthing/syncthing) · Bản nháp: `content-drafts/2026-11-03-sao-luu-va-dong-bo-du-lieu/content.json`
2. **Kopia: công cụ sao lưu mã hóa có cả dòng lệnh lẫn giao diện đồ họa, lưu lên đám mây hoặc máy của bạn** (key 290, độ khó: Trung bình) — Sao lưu mã hóa có giao diện đồ họa.  
   Repo: [kopia/kopia](https://github.com/kopia/kopia) · Bản nháp: `content-drafts/2026-11-03-sao-luu-va-dong-bo-du-lieu/content.json`
3. **restic: chương trình sao lưu nhanh, mã hóa sẵn, lưu được lên nhiều loại kho; mất mật khẩu là mất dữ liệu** (key 287, độ khó: Trung bình đến khó) — Sao lưu dòng lệnh, mã hóa sẵn; nhớ mật khẩu (khá khó).  
   Repo: [restic/restic](https://github.com/restic/restic) · Bản nháp: `content-drafts/2026-11-03-sao-luu-va-dong-bo-du-lieu/content.json`
4. **rclone: 'rsync cho đám mây', đồng bộ và sao chép tệp giữa máy bạn và hàng chục dịch vụ lưu trữ** (key 288, độ khó: Khá khó) — Chép và đồng bộ với đám mây; cẩn thận lệnh sync (khá khó).  
   Repo: [rclone/rclone](https://github.com/rclone/rclone) · Bản nháp: `content-drafts/2026-11-03-sao-luu-va-dong-bo-du-lieu/content.json`
