# Lộ trình 50 — Bảo mật web và đăng nhập

Tăng bảo mật bằng tiêu đề HTTP, kiểm tra bằng công cụ quét và hướng dẫn chuẩn, xử lý token và đăng nhập; chỉ thử trên hệ thống của bạn.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Helmet: middleware giúp bảo mật ứng dụng Node/Express bằng cách đặt các tiêu đề phản hồi HTTP như CSP và HSTS** (key 400, độ khó: Trung bình) — Đặt tiêu đề bảo mật cho Express.  
   Repo: [helmetjs/helmet](https://github.com/helmetjs/helmet) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
2. **OWASP Web Security Testing Guide: bộ hướng dẫn kiểm thử bảo mật ứng dụng web với mã kịch bản WSTG chuẩn, tài liệu theo CC BY-SA 4.0** (key 405, độ khó: Trung bình đến khó) — Danh sách kiểm thử bảo mật web chuẩn (tài liệu).  
   Repo: [OWASP/wstg](https://github.com/OWASP/wstg) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
3. **ZAP (Zed Attack Proxy): công cụ quét bảo mật ứng dụng web miễn phí, chỉ quét hệ thống của chính bạn** (key 401, độ khó: Khó) — Quét bảo mật ứng dụng của chính bạn (khó).  
   Repo: [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
4. **jose: mô-đun JavaScript cho JWT, JWS, JWE và JWK, không phụ thuộc gói khác, chạy trên nhiều môi trường** (key 402, độ khó: Khó) — Xử lý JWT bằng thư viện (khó).  
   Repo: [panva/jose](https://github.com/panva/jose) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
5. **Better Auth: khung xác thực và phân quyền cho TypeScript, không gắn với một framework, có hệ plugin** (key 403, độ khó: Khó) — Khung đăng nhập cho TypeScript (khó).  
   Repo: [better-auth/better-auth](https://github.com/better-auth/better-auth) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
6. **Keycloak: hệ thống quản lý danh tính và truy cập mã nguồn mở, thêm đăng nhập cho ứng dụng mà không tự lưu người dùng** (key 404, độ khó: Khó) — Đăng nhập tập trung; chế độ dev không cho sản xuất (khó).  
   Repo: [keycloak/keycloak](https://github.com/keycloak/keycloak) · Bản nháp: `content-drafts/2026-11-03-bao-mat-web-va-dang-nhap/content.json`
