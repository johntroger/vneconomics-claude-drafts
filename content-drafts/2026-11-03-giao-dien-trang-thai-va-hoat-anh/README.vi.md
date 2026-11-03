# Nhóm "Giao diện và trạng thái" — bản nháp 03/11/2026

7 bài, key 653–659, `batch: 106`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 653 | React Hook Form: thư viện xử lý biểu mẫu cho React tập trung vào hiệu năng, trải nghiệm và dễ dùng, tận dụng kiểm tra hợp lệ HTML gốc, không phụ thuộc, tích hợp Yup, Zod, AJV, Superstruct; giấy phép MIT | [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 44898 | 2026-11-03 |
| 654 | Jotai: thư viện quản lý trạng thái nguyên tử cho React, lõi tối thiểu 2 KB, mở rộng từ thay thế useState đến ứng dụng TypeScript lớn, không dùng khóa chuỗi (so với Recoil), atom dẫn xuất và bất đồng bộ | [pmndrs/jotai](https://github.com/pmndrs/jotai) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 21304 | 2026-10-23 |
| 655 | MobX: thư viện quản lý trạng thái đơn giản và co giãn dựa trên tín hiệu, áp dụng lập trình phản ứng hàm minh bạch, mọi thứ có thể dẫn xuất từ trạng thái thì tự động dẫn xuất; README nhiều phần tài trợ | [mobxjs/mobx](https://github.com/mobxjs/mobx) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 28220 | 2026-11-01 |
| 656 | Pinia: kho trạng thái trực quan, an toàn kiểu và linh hoạt cho Vue, hỗ trợ devtools, mở rộng được, mô-đun hóa, rất nhẹ, có mô-đun Nuxt; README nêu là kế thừa của Vuex, giấy phép MIT | [vuejs/pinia](https://github.com/vuejs/pinia) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 14759 | 2026-11-03 |
| 657 | Stimulus: framework JavaScript khiêm tốn cho phần HTML bạn đã có, không lo kết xuất HTML mà thêm hành vi qua thuộc tính controller, target, action; của Basecamp, giấy phép MIT | [hotwired/stimulus](https://github.com/hotwired/stimulus) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 13102 | 2026-10-29 |
| 658 | Rolldown: công cụ đóng gói JavaScript và TypeScript viết bằng Rust, dự định làm công cụ đóng gói tương lai của Vite, tương thích API và plugin của Rollup nhưng nhanh hơn, của VoidZero, giấy phép MIT | [rolldown/rolldown](https://github.com/rolldown/rolldown) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 13994 | 2026-11-03 |
| 659 | Floating UI: thư viện nhỏ giúp tạo phần tử nổi như tooltip, popover, dropdown với hai tính năng neo vị trí và tương tác người dùng cho React; trước đây là Popper, giấy phép MIT | [floating-ui/floating-ui](https://github.com/floating-ui/floating-ui) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 32789 | 2026-10-27 |

## Repo đã xem nhưng không đưa vào nhóm này

- **motiondivision/motion** (Motion): đã có trong catalog từ nhóm trước (key 496); loại khỏi nhóm này để không trùng repo.

- **radix-ui/primitives** (README khoảng 1,7 KB), **hotwired/turbo** (khoảng 1 KB), **biomejs/biome** (README 35 byte), **reduxjs/redux-toolkit** (không tìm thấy README ở tên tệp chuẩn): README ngắn hoặc không đọc được; loại.
- **bigskysoftware/htmx**: GitHub không trả giấy phép SPDX rõ (NOASSERTION); loại. **tailwindlabs/headlessui**, **evanw/esbuild**, **formkit/auto-animate**, **emilkowalski/sonner**: commit gần nhất quá 60 ngày; loại. **11ty/eleventy**: tìm kiếm không trả kết quả. Các thư viện giao diện khác (shadcn/ui, Mantine, Chakra, MUI, Ant Design, Vite, Biome...) đã có trong catalog hoặc chưa xét.

## Điều chưa biết

- Chưa cài hay chạy thư viện nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Thiết kế và hình ảnh', nhãn gần nhất trong 9 nhãn có sẵn.
- Pinia (MIT), Stimulus (MIT), Rolldown (MIT), Floating UI (mục License), React Hook Form (huy hiệu MIT) nêu giấy phép trong README. Jotai và MobX: README phần đã đọc không nêu giấy phép, lấy theo GitHub (MIT).
- Tuyên bố của tác giả, bài không kiểm chứng: hiệu năng React Hook Form, tốc độ Rolldown. Phần tài trợ (MobX, React Hook Form, Pinia, Floating UI) là quảng bá, bài không đánh giá. README MobX (khoảng 13 KB) đọc phần đầu và các mục chính.

