# Lộ trình 61 — Mạng riêng và truyền thông riêng tư

Từ chặn quảng cáo cho cả nhà, VPN tự dựng đến mạng xã hội và nhắn tin liên thông; chú ý cổng quản trị mở ra Internet, lệnh cài tải từ mạng, luật về mã hóa và trách nhiệm khi tự vận hành.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **AdGuard Home: máy chủ DNS chặn quảng cáo và theo dõi cho cả mạng gia đình; README nêu rõ giới hạn của chặn ở mức DNS** (key 471, độ khó: Khó) — Chặn quảng cáo ở mức DNS, biết giới hạn (khó).  
   Repo: [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
2. **wg-easy: cài và quản lý WireGuard trên máy Linux bằng giao diện web, tạo mã QR cho từng máy khách** (key 470, độ khó: Khó) — VPN WireGuard có giao diện web; bật 2FA (khó).  
   Repo: [wg-easy/wg-easy](https://github.com/wg-easy/wg-easy) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
3. **Headscale: máy chủ điều khiển Tailscale mã nguồn mở tự host cho một mạng riêng (tailnet) dùng cá nhân hoặc tổ chức nhỏ** (key 469, độ khó: Rất khó) — Máy chủ điều khiển Tailscale tự host (rất khó).  
   Repo: [juanfont/headscale](https://github.com/juanfont/headscale) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
4. **Signal Android: mã nguồn ứng dụng nhắn tin Signal cho Android, README nêu thông báo về mật mã học và quy định xuất khẩu** (key 474, độ khó: Rất khó) — Mã nguồn ứng dụng nhắn tin; đọc mục pháp lý (rất khó).  
   Repo: [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
5. **Mastodon: máy chủ mạng xã hội mã nguồn mở theo ActivityPub, thuộc Fediverse; README nêu yêu cầu Ruby, PostgreSQL, Redis, Node.js, FFmpeg** (key 472, độ khó: Rất khó) — Mạng xã hội liên thông; tự vận hành rất nặng (rất khó).  
   Repo: [mastodon/mastodon](https://github.com/mastodon/mastodon) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
6. **Synapse: máy chủ Matrix mã nguồn mở của Element, README nói không có hỗ trợ trừ khi có thuê bao Element và có giấy phép thương mại thay thế** (key 473, độ khó: Rất khó) — Máy chủ Matrix; tự vận hành rất nặng (rất khó).  
   Repo: [element-hq/synapse](https://github.com/element-hq/synapse) · Bản nháp: `content-drafts/2026-11-03-mang-rieng-tu/content.json`
