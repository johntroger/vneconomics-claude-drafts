# Lộ trình 70 — WordPress và hệ sinh thái

Từ dòng lệnh, Composer, khung Bedrock và theme Sage đến API GraphQL, gỡ lỗi, tăng tốc và trình dựng trang; thử trên bản sao, sao lưu trước khi đổi dữ liệu, chú ý plugin trả phí (WP Rocket, Elementor Pro) và tính thử nghiệm của Playground.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **WordPress Playground: WordPress chạy ngay trong trình duyệt nhờ WebAssembly không cần máy chủ PHP; README nói bản nhúng iframe còn thử nghiệm và có thể đổi hoặc hỏng** (key 528, độ khó: Cơ bản) — Thử WordPress ngay trong trình duyệt; bản nhúng còn thử nghiệm (cơ bản).  
   Repo: [WordPress/wordpress-playground](https://github.com/WordPress/wordpress-playground) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
2. **WP-CLI: giao diện dòng lệnh cho WordPress, cài và quản lý plugin, đa site, cơ sở dữ liệu mà không cần trình duyệt; README yêu cầu PHP 7.2.24 trở lên** (key 523, độ khó: Trung bình) — Quản lý WordPress bằng dòng lệnh (trung bình).  
   Repo: [wp-cli/wp-cli](https://github.com/wp-cli/wp-cli) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
3. **Query Monitor: bảng công cụ gỡ lỗi cho WordPress và WooCommerce, theo dõi truy vấn cơ sở dữ liệu, lỗi PHP, hook, script, lệnh gọi HTTP, REST API và nhiều thứ khác** (key 527, độ khó: Trung bình) — Gỡ lỗi truy vấn và hook (trung bình).  
   Repo: [johnbillion/query-monitor](https://github.com/johnbillion/query-monitor) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
4. **Elementor: trình dựng website kéo thả cho WordPress; README nêu lõi miễn phí mã nguồn mở và các gói trả phí Elementor One/Pro** (key 530, độ khó: Cơ bản) — Trình dựng trang kéo thả; nhiều tính năng trả phí (cơ bản).  
   Repo: [elementor/elementor](https://github.com/elementor/elementor) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
5. **WP Rocket (kho mã): plugin tăng tốc WordPress bằng bộ nhớ đệm; README nói cần email và khóa API từ tài khoản WP Rocket để xác thực giấy phép nên là plugin trả phí** (key 529, độ khó: Trung bình) — Bộ nhớ đệm; cần giấy phép trả phí (trung bình).  
   Repo: [wp-media/wp-rocket](https://github.com/wp-media/wp-rocket) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
6. **Composer: công cụ khai báo, quản lý và cài đặt phụ thuộc cho dự án PHP, tìm gói công khai trên Packagist; README nêu PHP 7.2.5 trở lên cho bản mới nhất** (key 531, độ khó: Trung bình) — Quản lý phụ thuộc PHP (trung bình).  
   Repo: [composer/composer](https://github.com/composer/composer) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
7. **Bedrock: bộ khung WordPress cho nhà phát triển muốn quản lý dự án bằng Git và Composer, theo triết lý Twelve-Factor, cấu hình theo môi trường** (key 524, độ khó: Khó) — Khung WordPress dùng Git và Composer (khó).  
   Repo: [roots/bedrock](https://github.com/roots/bedrock) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
8. **WPGraphQL: API GraphQL mở rộng được cho mọi site WordPress, kho monorepo gồm plugin lõi và các tiện ích (IDE, Smart Cache, ACF) và website wpgraphql.com** (key 526, độ khó: Khó) — WordPress làm CMS không giao diện (khó).  
   Repo: [wp-graphql/wp-graphql](https://github.com/wp-graphql/wp-graphql) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
9. **Sage: theme khởi đầu WordPress lai dùng Laravel Blade, Vite và Tailwind CSS, tích hợp Acorn của Laravel và hỗ trợ block editor** (key 525, độ khó: Rất khó) — Theme dùng Blade, Vite, Tailwind (rất khó).  
   Repo: [roots/sage](https://github.com/roots/sage) · Bản nháp: `content-drafts/2026-11-03-wordpress-he-sinh-thai/content.json`
