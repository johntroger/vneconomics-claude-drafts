# Nhóm "Làm việc nhóm và tự động hóa" — bản nháp 03/11/2026

6 bài, key 698–703, `batch: 112`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 698 | WeKan: ứng dụng bảng kanban cộng tác mã nguồn mở theo giấy phép MIT, tự host, dịch ra 234 gói ngôn ngữ theo README, hỗ trợ nhiều cách đăng nhập; README nhắc cập nhật rất thường xuyên, sao lưu hằng ngày vì chưa có hoàn tác | [wekan/wekan](https://github.com/wekan/wekan) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 21150 | 2026-11-02 |
| 699 | Monica: hệ quản lý quan hệ cá nhân mã nguồn mở giúp ghi lại cuộc sống, quản lý liên hệ, nhắc sinh nhật, ghi chú, nhật ký, hoạt động; không phải mạng xã hội và không có AI tích hợp; README ghi nhánh này là bản beta đang phát triển | [monicahq/monica](https://github.com/monicahq/monica) | {'key': 'agpl-3.0', 'name': 'GNU Affero General Public License v3.0', 'spdx_id': 'AGPL-3.0', 'url': 'https://api.github.com/licenses/agpl-3.0', 'node_id': 'MDc6TGljZW5zZTE='} | 25658 | 2026-10-28 |
| 700 | Dependabot-Core: thư viện Ruby ở lõi Dependabot để tạo yêu cầu gộp tự động cập nhật phụ thuộc cho dự án Ruby, JavaScript, Python và nhiều ngôn ngữ khác; README chủ yếu hướng dẫn chạy riêng, đóng góp và phát triển | [dependabot/dependabot-core](https://github.com/dependabot/dependabot-core) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 5832 | 2026-11-03 |
| 701 | Dashy: bảng điều khiển tự host cho ứng dụng và dịch vụ của bạn, nhiều chủ đề, biểu tượng, chỉ báo trạng thái, tiện ích, chế độ xem, trình soạn cấu hình, sao lưu đám mây; xác thực bằng Keycloak hoặc OIDC và xác thực cơ bản | [Lissy93/dashy](https://github.com/Lissy93/dashy) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 26903 | 2026-11-02 |
| 702 | Grist: bảng tính quan hệ hiện đại kết hợp sự linh hoạt của bảng tính với độ vững của cơ sở dữ liệu; grist-core là bản cộng đồng chạy máy chủ lưu bảng tính, giấy phép Apache 2.0, công ty bán bản có thêm tính năng; README rất dài | [gristlabs/grist-core](https://github.com/gristlabs/grist-core) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 12043 | 2026-11-03 |
| 703 | just: cách tiện lợi để lưu và chạy các lệnh riêng của dự án, công thức viết trong tệp justfile với cú pháp lấy cảm hứng từ make; README cực dài (khoảng 166 KB) và nêu giấy phép CC0, hiện không nhận PR | [casey/just](https://github.com/casey/just) | {'key': 'cc0-1.0', 'name': 'Creative Commons Zero v1.0 Universal', 'spdx_id': 'CC0-1.0', 'url': 'https://api.github.com/licenses/cc0-1.0', 'node_id': 'MDc6TGljZW5zZTY='} | 36536 | 2026-11-02 |

## Repo đã xem nhưng không đưa vào nhóm này

- **kanboard/kanboard** (README khoảng 1,8 KB), **dullage/flatnotes** (không tìm thấy README ở tên tệp chuẩn): README ngắn hoặc không đọc được; loại. **plankanban/planka**, **twentyhq/twenty**, **sqlitebrowser/sqlitebrowser**, **outline/outline**: GitHub không trả giấy phép SPDX rõ (NOASSERTION); loại. **ether/etherpad-lite**, **openproject/openproject**: tìm kiếm không trả kết quả.
- Nhóm có 6 bài, gồm các repo đủ điều kiện được để dành từ đợt trước (Dashy, Grist, Dependabot-Core, just).

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Lưu trữ và công cụ cá nhân', nhãn gần nhất trong 9 nhãn có sẵn.
- WeKan (MIT), Dashy (MIT), Monica (AGPL), Grist (Apache License 2.0 cho grist-core), just (CC0) nêu giấy phép trong README. Dependabot-Core: README phần đã đọc không nêu giấy phép, lấy theo GitHub (MIT).
- README WeKan cảnh báo cập nhật rất thường xuyên vì bảo mật, sao lưu hằng ngày, hết ổ đĩa làm hỏng cơ sở dữ liệu, chưa có hoàn tác. README Monica ghi nhánh mặc định là beta đang phát triển (bản ổn định ở nhánh 4.x) và lưu thông tin cá nhân của người khác. Grist có phần tính năng chỉ ở bản trả phí của Grist Labs và hướng dẫn dùng OpenRouter với khóa API riêng. Dashy có xác thực cơ bản chỉ ở tầng ứng dụng. README just rất dài (khoảng 166 KB) và Grist (khoảng 56 KB), Dashy (khoảng 36 KB): bài đọc phần đầu và các mục chính. Con số người dùng và gói ngôn ngữ của WeKan là tuyên bố của dự án, bài không kiểm chứng. Phần Patreon, dịch vụ đám mây, bán bản đầy đủ là quảng bá, bài không đánh giá.

