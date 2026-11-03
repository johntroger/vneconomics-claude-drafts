# Lộ trình 15 — Quyền riêng tư và an toàn cá nhân

Ba việc nền tảng: giữ mật khẩu và mã 2FA, mã hóa dữ liệu nhạy cảm, bớt bị theo dõi khi duyệt web.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Aegis Authenticator: ứng dụng mã xác thực hai bước cho Android, có mã hóa và sao lưu** (key 203, độ khó: Dễ đến trung bình) — Giữ mã 2FA có sao lưu (Android).  
   Repo: [beemdevelopment/Aegis](https://github.com/beemdevelopment/Aegis) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
2. **Vaultwarden: máy chủ quản lý mật khẩu tự host, tương thích ứng dụng Bitwarden (không phải của Bitwarden)** (key 199, độ khó: Khó) — Kho mật khẩu tự host; chỉ cho người đã quen quản trị máy chủ.  
   Repo: [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
3. **Cryptomator: mã hóa tệp trước khi đưa lên Google Drive, Dropbox hay OneDrive** (key 200, độ khó: Trung bình) — Mã hóa dữ liệu trước khi đưa lên cloud.  
   Repo: [cryptomator/cryptomator](https://github.com/cryptomator/cryptomator) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
4. **age: công cụ mã hóa tệp đơn giản, hiện đại, ít tùy chọn để khỏi cấu hình sai** (key 201, độ khó: Trung bình) — Mã hóa tệp đơn giản bằng dòng lệnh.  
   Repo: [FiloSottile/age](https://github.com/FiloSottile/age) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
5. **uBlock Origin: chặn quảng cáo và theo dõi trong trình duyệt, và tình trạng trên Chrome** (key 202, độ khó: Dễ) — Bớt quảng cáo và theo dõi; lưu ý tình trạng trên Chrome.  
   Repo: [gorhill/uBlock](https://github.com/gorhill/uBlock) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
6. **Mullvad VPN (ứng dụng): mã nguồn ứng dụng của một dịch vụ VPN, cần phân biệt ứng dụng và dịch vụ** (key 204, độ khó: Trung bình) — VPN: hiểu bảo vệ gì và không bảo vệ gì.  
   Repo: [mullvad/mullvadvpn-app](https://github.com/mullvad/mullvadvpn-app) · Bản nháp: `content-drafts/2026-11-03-rieng-tu-ca-nhan/content.json`
7. **dotenvx: mã hóa tệp .env để quản lý biến môi trường an toàn hơn** (key 142, độ khó: Trung bình) — Giữ bí mật trong dự án.  
   Repo: [dotenvx/dotenvx](https://github.com/dotenvx/dotenvx) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
