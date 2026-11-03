# Lộ trình 12 — Đưa ứng dụng lên mạng và quản lý máy chủ

Từ khái niệm container đến nơi triển khai, proxy HTTPS và truy cập từ xa an toàn.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Docker Compose: mô tả nhiều phần của ứng dụng trong một tệp để chạy cùng nhau** (key 183, độ khó: Trung bình) — Gói nhiều phần của ứng dụng vào một tệp.  
   Repo: [docker/compose](https://github.com/docker/compose) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
2. **Coolify: tự dựng nơi đưa ứng dụng lên mạng thay cho Vercel hay Heroku** (key 116, độ khó: Trung bình đến khó) — Nền tảng triển khai có giao diện (tự host).  
   Repo: [coollabsio/coolify](https://github.com/coollabsio/coolify) · Bản nháp: `content-drafts/2026-11-03-ai-agent-nen-tang/content.json`
3. **Dokku: PaaS nhỏ tự dựng trên một máy chủ, đưa ứng dụng lên bằng Git như Heroku** (key 185, độ khó: Trung bình đến khó) — Nền tảng triển khai kiểu Heroku nhỏ.  
   Repo: [dokku/dokku](https://github.com/dokku/dokku) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
4. **Caddy: máy chủ web tự bật HTTPS, cấu hình ngắn gọn cho dự án nhỏ** (key 182, độ khó: Trung bình) — Máy chủ web tự bật HTTPS.  
   Repo: [caddyserver/caddy](https://github.com/caddyserver/caddy) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
5. **Traefik: reverse proxy tự tìm các dịch vụ chạy trong Docker và tạo đường dẫn cho chúng** (key 188, độ khó: Trung bình đến khó) — Proxy tự tìm dịch vụ trong Docker.  
   Repo: [traefik/traefik](https://github.com/traefik/traefik) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
6. **Portainer CE: giao diện web quản lý Docker, nhưng README nói rõ chỉ dành cho nhà và học tập** (key 184, độ khó: Trung bình) — Giao diện xem container; chỉ cho nhà và học tập.  
   Repo: [portainer/portainer](https://github.com/portainer/portainer) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
7. **Tailscale: nối các thiết bị của bạn thành một mạng riêng an toàn dựa trên WireGuard** (key 186, độ khó: Trung bình) — Mạng riêng để truy cập từ xa mà không mở cổng.  
   Repo: [tailscale/tailscale](https://github.com/tailscale/tailscale) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
8. **cloudflared: đưa dịch vụ trên máy bạn ra internet qua Cloudflare Tunnel mà không mở cổng** (key 187, độ khó: Trung bình) — Công khai dịch vụ qua Cloudflare Tunnel.  
   Repo: [cloudflare/cloudflared](https://github.com/cloudflare/cloudflared) · Bản nháp: `content-drafts/2026-11-03-dua-ung-dung-len-mang/content.json`
