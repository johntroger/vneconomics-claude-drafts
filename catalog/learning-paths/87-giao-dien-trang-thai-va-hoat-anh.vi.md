# Lộ trình 87 — Giao diện, trạng thái và hoạt ảnh

Từ thư viện hoạt ảnh, biểu mẫu, phần tử nổi, quản lý trạng thái cho React và Vue đến công cụ đóng gói và framework khiêm tốn cho HTML dựng phía máy chủ; chú ý tùy chọn giảm chuyển động, kiểm tra hợp lệ ở máy chủ, khả năng truy cập và phần trả phí.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Stimulus: framework JavaScript khiêm tốn cho phần HTML bạn đã có, không lo kết xuất HTML mà thêm hành vi qua thuộc tính controller, target, action; của Basecamp, giấy phép MIT** (key 658, độ khó: Dễ đến trung bình) — Thêm hành vi cho HTML có sẵn (dễ đến trung bình).  
   Repo: [hotwired/stimulus](https://github.com/hotwired/stimulus) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
2. **Pinia: kho trạng thái trực quan, an toàn kiểu và linh hoạt cho Vue, hỗ trợ devtools, mở rộng được, mô-đun hóa, rất nhẹ, có mô-đun Nuxt; README nêu là kế thừa của Vuex, giấy phép MIT** (key 657, độ khó: Dễ đến trung bình) — Kho trạng thái cho Vue (dễ đến trung bình).  
   Repo: [vuejs/pinia](https://github.com/vuejs/pinia) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
3. **Motion: thư viện hoạt ảnh mã nguồn mở cho JavaScript, React và Vue, động cơ lai dùng JavaScript kết hợp API trình duyệt gốc, cử chỉ, lò xo, chuyển tiếp bố cục, hiệu ứng theo cuộn; có gói Motion+ trả phí và công cụ AI, giấy phép MIT** (key 653, độ khó: Dễ đến trung bình) — Hoạt ảnh cho JavaScript, React, Vue (dễ đến trung bình).  
   Repo: [motiondivision/motion](https://github.com/motiondivision/motion) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
4. **React Hook Form: thư viện xử lý biểu mẫu cho React tập trung vào hiệu năng, trải nghiệm và dễ dùng, tận dụng kiểm tra hợp lệ HTML gốc, không phụ thuộc, tích hợp Yup, Zod, AJV, Superstruct; giấy phép MIT** (key 654, độ khó: Trung bình) — Biểu mẫu trong React (trung bình).  
   Repo: [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
5. **Floating UI: thư viện nhỏ giúp tạo phần tử nổi như tooltip, popover, dropdown với hai tính năng neo vị trí và tương tác người dùng cho React; trước đây là Popper, giấy phép MIT** (key 660, độ khó: Trung bình) — Tooltip, popover, dropdown (trung bình).  
   Repo: [floating-ui/floating-ui](https://github.com/floating-ui/floating-ui) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
6. **Jotai: thư viện quản lý trạng thái nguyên tử cho React, lõi tối thiểu 2 KB, mở rộng từ thay thế useState đến ứng dụng TypeScript lớn, không dùng khóa chuỗi (so với Recoil), atom dẫn xuất và bất đồng bộ** (key 655, độ khó: Trung bình) — Trạng thái nguyên tử cho React (trung bình).  
   Repo: [pmndrs/jotai](https://github.com/pmndrs/jotai) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
7. **MobX: thư viện quản lý trạng thái đơn giản và co giãn dựa trên tín hiệu, áp dụng lập trình phản ứng hàm minh bạch, mọi thứ có thể dẫn xuất từ trạng thái thì tự động dẫn xuất; README nhiều phần tài trợ** (key 656, độ khó: Trung bình đến khó) — Trạng thái phản ứng tự động (trung bình đến khó).  
   Repo: [mobxjs/mobx](https://github.com/mobxjs/mobx) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
8. **Rolldown: công cụ đóng gói JavaScript và TypeScript viết bằng Rust, dự định làm công cụ đóng gói tương lai của Vite, tương thích API và plugin của Rollup nhưng nhanh hơn, của VoidZero, giấy phép MIT** (key 659, độ khó: Khó) — Công cụ đóng gói bằng Rust (khó).  
   Repo: [rolldown/rolldown](https://github.com/rolldown/rolldown) · Bản nháp: `content-drafts/2026-11-03-giao-dien-trang-thai-va-hoat-anh/content.json`
