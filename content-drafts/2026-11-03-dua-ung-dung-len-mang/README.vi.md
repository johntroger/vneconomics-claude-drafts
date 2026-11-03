# Nhóm "Đưa ứng dụng lên mạng và quản lý máy chủ" — bản nháp 03/11/2026

7 bài, key 182–188, `batch: 31`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 182 | Caddy: máy chủ web tự bật HTTPS, cấu hình ngắn gọn cho dự án nhỏ | [caddyserver/caddy](https://github.com/caddyserver/caddy) | Apache-2.0 | 78667 | 2026-11-02 |
| 183 | Docker Compose: mô tả nhiều phần của ứng dụng trong một tệp để chạy cùng nhau | [docker/compose](https://github.com/docker/compose) | Apache-2.0 | 38582 | 2026-11-02 |
| 184 | Portainer CE: giao diện web quản lý Docker, nhưng README nói rõ chỉ dành cho nhà và học tập | [portainer/portainer](https://github.com/portainer/portainer) | Zlib | 38767 | 2026-11-02 |
| 185 | Dokku: PaaS nhỏ tự dựng trên một máy chủ, đưa ứng dụng lên bằng Git như Heroku | [dokku/dokku](https://github.com/dokku/dokku) | MIT | 32220 | 2026-11-02 |
| 186 | Tailscale: nối các thiết bị của bạn thành một mạng riêng an toàn dựa trên WireGuard | [tailscale/tailscale](https://github.com/tailscale/tailscale) | BSD-3-Clause | 38547 | 2026-11-02 |
| 187 | cloudflared: đưa dịch vụ trên máy bạn ra internet qua Cloudflare Tunnel mà không mở cổng | [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) | Apache-2.0 | 16412 | 2026-10-30 |
| 188 | Traefik: reverse proxy tự tìm các dịch vụ chạy trong Docker và tạo đường dẫn cho chúng | [traefik/traefik](https://github.com/traefik/traefik) | MIT | 65445 | 2026-11-02 |

## Điểm cần lưu ý
- **Portainer CE**: README nói rõ bản Community dành cho homelab, học tập và dự án cá nhân, không dành cho môi trường sản xuất và không có hỗ trợ; bài nói rõ.
- **Dokku**: script cài chạy với quyền sudo trên máy ảo mới; bài cảnh báo.
- **Cloudflared**: cần tài khoản Cloudflare và đổi nameserver; lưu lượng đi qua Cloudflare.
- **Tailscale**: README dẫn tới trang giải thích phần nào mở nguồn; bài chưa đọc trang đó nên không kết luận.
- **Docker Compose**: điều khoản Docker Desktop chưa kiểm tra.

## Repo bị loại hoặc cân nhắc
- **caprover/caprover**: GitHub trả NOASSERTION; **fail2ban**: NOASSERTION.
- **moby/moby**, **nginx/nginx**: đủ điều kiện nhưng nhắm người vận hành có kinh nghiệm; chưa ưu tiên.
- **netdata**, **prometheus**, **beszel**, **crowdsec**: nhóm giám sát và bảo mật máy chủ, có thể làm đợt sau.
- **grafana**, **uptime-kuma**, **coolify**: đã có trong các đợt trước.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. README nhiều repo chỉ đọc phần đầu và các mục chính.

