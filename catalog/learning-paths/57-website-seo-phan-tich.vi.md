# Lộ trình 57 — Website, SEO và phân tích

Từ đo tốc độ trang đến phân tích lượt truy cập, gửi bản tin và thương mại điện tử; chú ý quyền riêng tư, luật gửi thư, mật khẩu mặc định và phần nào chỉ dành cho nhà phát triển.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Lighthouse: công cụ kiểm tra hiệu năng và thực hành tốt của trang web, chạy trong Chrome DevTools, tiện ích mở rộng hoặc dòng lệnh Node; README nói kết quả không gửi lên máy chủ từ xa** (key 442, độ khó: Cơ bản) — Đo tốc độ ngay trong Chrome.  
   Repo: [GoogleChrome/lighthouse](https://github.com/GoogleChrome/lighthouse) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
2. **sitespeed.io: công cụ mã nguồn mở đo hiệu năng web bằng trình duyệt thật, cho báo cáo Core Web Vitals, video tải trang và HAR waterfall** (key 443, độ khó: Khó) — Đo lặp lại, theo dõi liên tục (khó).  
   Repo: [sitespeedio/sitespeed.io](https://github.com/sitespeedio/sitespeed.io) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
3. **Matomo: nền tảng phân tích web mã nguồn mở viết bằng PHP và MySQL, thay thế Google Analytics, có dịch vụ Matomo Cloud dùng thử 21 ngày** (key 446, độ khó: Trung bình) — Phân tích tự host, quen với PHP và MySQL (trung bình).  
   Repo: [matomo-org/matomo](https://github.com/matomo-org/matomo) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
4. **Plausible Analytics: phân tích web nhẹ, không cookie, có bản đám mây trả phí và bản Community Edition tự host theo AGPLv3 phát hành 2 lần mỗi năm** (key 445, độ khó: Trung bình) — Phân tích nhẹ, đám mây hoặc tự host (trung bình).  
   Repo: [plausible/analytics](https://github.com/plausible/analytics) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
5. **Umami: nền tảng phân tích web ưu tiên riêng tư, không cookie, tự host hoặc dùng đám mây; README nhắc tài khoản mặc định admin/umami** (key 444, độ khó: Khó) — Tự host, nhớ đổi mật khẩu mặc định (khó).  
   Repo: [umami-software/umami](https://github.com/umami-software/umami) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
6. **listmonk: trình quản lý thư tin và danh sách gửi mail tự host, một tệp nhị phân Go dùng PostgreSQL, giấy phép AGPLv3** (key 447, độ khó: Khó) — Gửi bản tin tự host; chú ý luật thư rác (khó).  
   Repo: [knadh/listmonk](https://github.com/knadh/listmonk) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
7. **WooCommerce (kho mã): monorepo dành cho nhà phát triển plugin WooCommerce, README nói kho này không hỗ trợ người dùng** (key 449, độ khó: Rất khó) — Kho dành cho nhà phát triển, không phải cho chủ cửa hàng (rất khó).  
   Repo: [woocommerce/woocommerce](https://github.com/woocommerce/woocommerce) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
8. **Saleor: nền tảng thương mại điện tử headless chỉ có GraphQL API, README nói nhánh main là bản phát triển có thể không ổn định** (key 448, độ khó: Rất khó) — Thương mại headless GraphQL (rất khó).  
   Repo: [saleor/saleor](https://github.com/saleor/saleor) · Bản nháp: `content-drafts/2026-11-03-website-seo-phan-tich/content.json`
