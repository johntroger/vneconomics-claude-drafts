# Nhóm "Mạng riêng và truyền thông riêng tư" — bản nháp 03/11/2026

6 bài, key 469–474, `batch: 80`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 469 | Headscale: máy chủ điều khiển Tailscale mã nguồn mở tự host cho một mạng riêng (tailnet) dùng cá nhân hoặc tổ chức nhỏ | [juanfont/headscale](https://github.com/juanfont/headscale) | {'key': 'bsd-3-clause', 'name': 'BSD 3-Clause "New" or "Revised" License', 'spdx_id': 'BSD-3-Clause', 'url': 'https://api.github.com/licenses/bsd-3-clause', 'node_id': 'MDc6TGljZW5zZTU='} | 45312 | 2026-11-03 |
| 470 | wg-easy: cài và quản lý WireGuard trên máy Linux bằng giao diện web, tạo mã QR cho từng máy khách | [wg-easy/wg-easy](https://github.com/wg-easy/wg-easy) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 27380 | 2026-11-02 |
| 471 | AdGuard Home: máy chủ DNS chặn quảng cáo và theo dõi cho cả mạng gia đình; README nêu rõ giới hạn của chặn ở mức DNS | [AdguardTeam/AdGuardHome](https://github.com/AdguardTeam/AdGuardHome) | {'key': 'gpl-3.0', 'name': 'GNU General Public License v3.0', 'spdx_id': 'GPL-3.0', 'url': 'https://api.github.com/licenses/gpl-3.0', 'node_id': 'MDc6TGljZW5zZTk='} | 38082 | 2026-11-02 |
| 472 | Mastodon: máy chủ mạng xã hội mã nguồn mở theo ActivityPub, thuộc Fediverse; README nêu yêu cầu Ruby, PostgreSQL, Redis, Node.js, FFmpeg | [mastodon/mastodon](https://github.com/mastodon/mastodon) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 50467 | 2026-11-03 |
| 473 | Synapse: máy chủ Matrix mã nguồn mở của Element, README nói không có hỗ trợ trừ khi có thuê bao Element và có giấy phép thương mại thay thế | [element-hq/synapse](https://github.com/element-hq/synapse) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 4755 | 2026-11-02 |
| 474 | Signal Android: mã nguồn ứng dụng nhắn tin Signal cho Android, README nêu thông báo về mật mã học và quy định xuất khẩu | [signalapp/Signal-Android](https://github.com/signalapp/Signal-Android) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 29569 | 2026-10-30 |

## Repo đã xem nhưng không đưa vào nhóm này

- **keepassxreboot/keepassxc**, **netbirdio/netbird**, **bitwarden/clients**, **pi-hole/pi-hole**, **fail2ban/fail2ban**: GitHub trả giấy phép NOASSERTION; loại để giữ quy tắc giấy phép rõ ràng, có thể làm sau sau khi đọc tệp LICENSE.
- **ente-io/ente**, **proton/WebClients**: tìm kiếm GitHub không trả kết quả ở thời điểm kiểm tra; chưa đọc.
- **tailscale/tailscale**: đã có trong kho.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập.
- Headscale, AdGuard Home: README phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub (BSD-3-Clause, GPL-3.0). Bảng so sánh AdGuard Home với Pi-hole do chính AdGuard viết.
- Synapse: README là tệp README.rst; giá ESS Pro và TI-M chưa kiểm tra. Bài chưa đọc tài liệu vận hành.
- wg-easy, AdGuard Home: README có lệnh cài tải script từ mạng, bài không chép. Headscale: README không khuyến khích reverse proxy và container.
- Signal Android: kho mã, không phải hướng dẫn người dùng; thông báo mật mã học là của README, bài không đánh giá pháp lý hay thiết kế mật mã.
- Mastodon: tài nguyên máy chủ cần thiết chưa kiểm tra.

