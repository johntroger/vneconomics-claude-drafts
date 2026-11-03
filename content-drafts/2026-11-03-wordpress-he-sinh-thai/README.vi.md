# Nhóm "WordPress và hệ sinh thái" — bản nháp 03/11/2026

9 bài, key 523–531, `batch: 89`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 523 | WP-CLI: giao diện dòng lệnh cho WordPress, cài và quản lý plugin, đa site, cơ sở dữ liệu mà không cần trình duyệt; README yêu cầu PHP 7.2.24 trở lên | [wp-cli/wp-cli](https://github.com/wp-cli/wp-cli) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 5176 | 2026-11-02 |
| 524 | Bedrock: bộ khung WordPress cho nhà phát triển muốn quản lý dự án bằng Git và Composer, theo triết lý Twelve-Factor, cấu hình theo môi trường | [roots/bedrock](https://github.com/roots/bedrock) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 6585 | 2026-11-01 |
| 525 | Sage: theme khởi đầu WordPress lai dùng Laravel Blade, Vite và Tailwind CSS, tích hợp Acorn của Laravel và hỗ trợ block editor | [roots/sage](https://github.com/roots/sage) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 13280 | 2026-10-07 |
| 526 | WPGraphQL: API GraphQL mở rộng được cho mọi site WordPress, kho monorepo gồm plugin lõi và các tiện ích (IDE, Smart Cache, ACF) và website wpgraphql.com | [wp-graphql/wp-graphql](https://github.com/wp-graphql/wp-graphql) | {'key': 'gpl-3.0', 'name': 'GNU General Public License v3.0', 'spdx_id': 'GPL-3.0', 'url': 'https://api.github.com/licenses/gpl-3.0', 'node_id': 'MDc6TGljZW5zZTk='} | 3796 | 2026-11-02 |
| 527 | Query Monitor: bảng công cụ gỡ lỗi cho WordPress và WooCommerce, theo dõi truy vấn cơ sở dữ liệu, lỗi PHP, hook, script, lệnh gọi HTTP, REST API và nhiều thứ khác | [johnbillion/query-monitor](https://github.com/johnbillion/query-monitor) | {'key': 'gpl-2.0', 'name': 'GNU General Public License v2.0', 'spdx_id': 'GPL-2.0', 'url': 'https://api.github.com/licenses/gpl-2.0', 'node_id': 'MDc6TGljZW5zZTg='} | 1780 | 2026-10-27 |
| 528 | WordPress Playground: WordPress chạy ngay trong trình duyệt nhờ WebAssembly không cần máy chủ PHP; README nói bản nhúng iframe còn thử nghiệm và có thể đổi hoặc hỏng | [WordPress/wordpress-playground](https://github.com/WordPress/wordpress-playground) | {'key': 'gpl-2.0', 'name': 'GNU General Public License v2.0', 'spdx_id': 'GPL-2.0', 'url': 'https://api.github.com/licenses/gpl-2.0', 'node_id': 'MDc6TGljZW5zZTg='} | 1984 | 2026-11-03 |
| 529 | WP Rocket (kho mã): plugin tăng tốc WordPress bằng bộ nhớ đệm; README nói cần email và khóa API từ tài khoản WP Rocket để xác thực giấy phép nên là plugin trả phí | [wp-media/wp-rocket](https://github.com/wp-media/wp-rocket) | {'key': 'gpl-2.0', 'name': 'GNU General Public License v2.0', 'spdx_id': 'GPL-2.0', 'url': 'https://api.github.com/licenses/gpl-2.0', 'node_id': 'MDc6TGljZW5zZTg='} | 769 | 2026-11-03 |
| 530 | Elementor: trình dựng website kéo thả cho WordPress; README nêu lõi miễn phí mã nguồn mở và các gói trả phí Elementor One/Pro | [elementor/elementor](https://github.com/elementor/elementor) | {'key': 'gpl-3.0', 'name': 'GNU General Public License v3.0', 'spdx_id': 'GPL-3.0', 'url': 'https://api.github.com/licenses/gpl-3.0', 'node_id': 'MDc6TGljZW5zZTk='} | 7100 | 2026-11-03 |
| 531 | Composer: công cụ khai báo, quản lý và cài đặt phụ thuộc cho dự án PHP, tìm gói công khai trên Packagist; README nêu PHP 7.2.5 trở lên cho bản mới nhất | [composer/composer](https://github.com/composer/composer) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 29567 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **WordPress/gutenberg**, **wpengine/faustjs**, **Automattic/jetpack**, **yoast/wordpress-seo**: GitHub trả giấy phép NOASSERTION; loại để giữ quy tắc giấy phép rõ ràng.
- **Automattic/newspack-plugin**: kho đã lưu trữ; **WordPress/wporg-theme-directory**: GitHub không trả giấy phép SPDX; loại. **WordPress/openverse** và **symfony/symfony**: chưa đưa vào nhóm này.
- **roots/sage** (commit 2026-10-07) vẫn trong ngưỡng 60 ngày.

## Điều chưa biết

- Chưa cài hay chạy plugin hay công cụ nào; độ khó là đánh giá biên tập. Nhóm này dùng nhãn 'Dữ liệu và giao diện ứng dụng', nhãn gần nhất trong 9 nhãn có sẵn.
- WP-CLI, Bedrock, Sage, WPGraphQL, WordPress Playground, WP Rocket, Elementor: README phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub (MIT, GPL-3.0, GPL-2.0). Query Monitor và Composer nêu giấy phép trong README (GPLv2 trở lên, MIT).
- WP Rocket: README yêu cầu email và khóa API từ tài khoản để xác thực giấy phép, tức là plugin trả phí; giá và điều khoản chưa kiểm tra. Elementor: README nhắc gói Elementor One trả phí; giá chưa kiểm tra. Mô tả 'tiên tiến nhất', 'số 1' của Elementor là của README.
- WordPress Playground: README nói bản nhúng iframe còn thử nghiệm và có thể đổi hoặc hỏng không báo trước.
- Các nhận định về hiển thị thông tin gỡ lỗi (Query Monitor), gói giả mạo (Composer) và quyền API (WPGraphQL) là nguyên tắc chung của bài, README phần đã đọc không bàn. Lệnh tải tệp và cài đặt trong README không được chép vào bài.

