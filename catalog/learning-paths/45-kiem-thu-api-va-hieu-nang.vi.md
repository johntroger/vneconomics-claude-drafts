# Lộ trình 45 — Kiểm thử API, tải và giả lập

Từ API giả để làm giao diện trước, đến kiểm thử bằng tệp chữ hay kịch bản, và thử tải; chỉ thử trên hệ thống của bạn.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Mockoon: thiết kế và chạy API giả ngay trên máy, không cần tài khoản, có ứng dụng desktop và dòng lệnh** (key 369, độ khó: Dễ đến trung bình) — API giả với giao diện, dễ nhất.  
   Repo: [mockoon/mockoon](https://github.com/mockoon/mockoon) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
2. **Hurl: chạy và kiểm thử yêu cầu HTTP viết trong tệp chữ đơn giản, nối yêu cầu và kiểm tra phản hồi bằng dòng lệnh** (key 368, độ khó: Trung bình đến khó) — Kiểm thử API bằng tệp chữ.  
   Repo: [Orange-OpenSource/hurl](https://github.com/Orange-OpenSource/hurl) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
3. **Prism: dựng máy chủ giả và proxy kiểm tra hợp đồng từ tệp OpenAPI hoặc Postman Collection** (key 371, độ khó: Khó) — Máy chủ giả từ tệp OpenAPI (khó).  
   Repo: [stoplightio/prism](https://github.com/stoplightio/prism) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
4. **WireMock: công cụ giả lập API HTTP phổ biến, chạy như thư viện hoặc máy chủ độc lập, dựng môi trường kiểm thử ổn định** (key 370, độ khó: Khó) — Giả lập API cho kiểm thử, gốc Java (khó).  
   Repo: [wiremock/wiremock](https://github.com/wiremock/wiremock) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
5. **Locust: viết kịch bản kiểm thử tải bằng Python thường, chạy từ dòng lệnh hoặc giao diện web, hỗ trợ phân tán** (key 367, độ khó: Trung bình đến khó) — Kiểm thử tải bằng Python.  
   Repo: [locustio/locust](https://github.com/locustio/locust) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
6. **k6: công cụ kiểm thử tải hiện đại viết kịch bản bằng JavaScript và chạy bằng Go, kiểm thử như mã** (key 366, độ khó: Khó) — Kiểm thử tải bằng JavaScript (khó).  
   Repo: [grafana/k6](https://github.com/grafana/k6) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
7. **Selenium: bộ công cụ tự động hóa trình duyệt theo chuẩn W3C WebDriver, README của kho dành cho người đóng góp** (key 365, độ khó: Khá khó) — Tự động hóa trình duyệt; README kho cho người đóng góp.  
   Repo: [SeleniumHQ/selenium](https://github.com/SeleniumHQ/selenium) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-api-va-hieu-nang/content.json`
