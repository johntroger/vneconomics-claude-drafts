# Nhóm "Bảo mật web và đăng nhập" — bản nháp 03/11/2026

6 bài, key 400–405, `batch: 69`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 400 | Helmet: middleware giúp bảo mật ứng dụng Node/Express bằng cách đặt các tiêu đề phản hồi HTTP như CSP và HSTS | [helmetjs/helmet](https://github.com/helmetjs/helmet) | MIT | 10744 | 2026-11-01 |
| 401 | ZAP (Zed Attack Proxy): công cụ quét bảo mật ứng dụng web miễn phí, chỉ quét hệ thống của chính bạn | [zaproxy/zaproxy](https://github.com/zaproxy/zaproxy) | Apache-2.0 | 16096 | 2026-11-02 |
| 402 | jose: mô-đun JavaScript cho JWT, JWS, JWE và JWK, không phụ thuộc gói khác, chạy trên nhiều môi trường | [panva/jose](https://github.com/panva/jose) | MIT | 7863 | 2026-11-02 |
| 403 | Better Auth: khung xác thực và phân quyền cho TypeScript, không gắn với một framework, có hệ plugin | [better-auth/better-auth](https://github.com/better-auth/better-auth) | MIT | 30558 | 2026-11-01 |
| 404 | Keycloak: hệ thống quản lý danh tính và truy cập mã nguồn mở, thêm đăng nhập cho ứng dụng mà không tự lưu người dùng | [keycloak/keycloak](https://github.com/keycloak/keycloak) | Apache-2.0 | 37666 | 2026-11-03 |
| 405 | OWASP Web Security Testing Guide: bộ hướng dẫn kiểm thử bảo mật ứng dụng web với mã kịch bản WSTG chuẩn, tài liệu theo CC BY-SA 4.0 | [OWASP/wstg](https://github.com/OWASP/wstg) | CC-BY-SA-4.0 | 10179 | 2026-11-01 |

## Repo đã xem nhưng không đưa vào nhóm này

- **supertokens/supertokens-core**: GitHub trả giấy phép `NOASSERTION`; loại.
- **nextauthjs/next-auth**, **lucia-auth/lucia**, **ory/kratos**, **auth0/node-jsonwebtoken**, **expressjs/cors**: commit gần nhất trước 2026-09-01 (từ tháng 4 đến tháng 8); chưa đưa vào, có thể làm sau.
- **OWASP/CheatSheetSeries**: đã có bài trong kho.
- **expressjs/express-rate-limit**, **OWASP wstg**: wstg đã đưa vào; express-rate-limit tìm kiếm GitHub không truy cập được.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập.
- ZAP: lưu ý chỉ quét hệ thống của bạn và rủi ro quét chủ động là nguyên tắc chung của bài; README không nói.
- Keycloak: README nói chạy ở chế độ phát triển; việc chế độ này không dành cho sản xuất là cách hiểu của bài theo tên lệnh.
- jose: README có quảng cáo nhà tài trợ Auth0, bài không đánh giá.
- Better Auth: README rất ngắn, quan điểm của tác giả chưa kiểm chứng.
- WSTG: tài liệu, không phải công cụ; bản 5.0 đang làm.
- Giấy phép Helmet và jose lấy theo GitHub vì README phần đã đọc không nêu.

