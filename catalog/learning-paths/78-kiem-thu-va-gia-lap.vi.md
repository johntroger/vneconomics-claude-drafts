# Lộ trình 78 — Kiểm thử và giả lập

Từ kiểm thử bằng ngôn ngữ thường, giả lập HTTP và dịch vụ AWS đến kiểm tra tệp mô tả API, kiểm thử API tự động và tự ghi, phát lại lưu lượng; chú ý yêu cầu thật tạo, sửa, xóa dữ liệu, bản ghi chứa dữ liệu nhạy cảm, telemetry của ảnh Docker và lệnh cài tải tập lệnh từ mạng.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Robot Framework: khung tự động hóa mã nguồn mở cho kiểm thử chấp nhận, phát triển hướng kiểm thử chấp nhận (ATDD) và tự động hóa quy trình bằng robot (RPA), cú pháp văn bản thuần, mở rộng bằng thư viện Python** (key 586, độ khó: Trung bình) — Kiểm thử chấp nhận bằng văn bản thuần (trung bình).  
   Repo: [robotframework/robotframework](https://github.com/robotframework/robotframework) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
2. **Cucumber.js: bản JavaScript của Cucumber chạy kiểm thử tự động viết bằng ngôn ngữ thường (Gherkin) cho Node.js, để cả nhóm đều đọc được kịch bản kiểm thử** (key 587, độ khó: Trung bình) — Kịch bản bằng ngôn ngữ thường cho Node.js (trung bình).  
   Repo: [cucumber/cucumber-js](https://github.com/cucumber/cucumber-js) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
3. **nock: thư viện giả lập máy chủ HTTP và kiểm tra kỳ vọng cho Node.js, kiểm thử mô-đun gọi HTTP một cách cô lập bằng cách ghi đè http.request; README rất dài** (key 588, độ khó: Trung bình) — Giả lập HTTP cho Node.js (trung bình).  
   Repo: [nock/nock](https://github.com/nock/nock) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
4. **Moto: thư viện Python giả lập các dịch vụ AWS để kiểm thử, dùng bộ trang trí @mock_aws để mọi lệnh gọi dịch vụ bị chặn trong tài khoản AWS ảo** (key 589, độ khó: Trung bình) — Giả lập AWS cho Python (trung bình).  
   Repo: [getmoto/moto](https://github.com/getmoto/moto) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
5. **Spectral: trình kiểm tra (linter) cho JSON và YAML, có sẵn bộ quy tắc cho OpenAPI, AsyncAPI và Arazzo, tự viết quy tắc và hàm riêng; README nêu ảnh Docker gửi telemetry ẩn danh** (key 591, độ khó: Trung bình) — Kiểm tra tệp OpenAPI và AsyncAPI (trung bình).  
   Repo: [stoplightio/spectral](https://github.com/stoplightio/spectral) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
6. **Schemathesis: kiểm thử API OpenAPI, GraphQL và gRPC bằng cách sinh đầu vào từ lược đồ, thích ứng với phản hồi máy chủ và nối các thao tác thành quy trình thực tế; README cảnh báo yêu cầu thật tạo, sửa và xóa dữ liệu** (key 590, độ khó: Khó) — Kiểm thử API tự sinh đầu vào; chỉ trên môi trường thử (khó).  
   Repo: [schemathesis/schemathesis](https://github.com/schemathesis/schemathesis) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
7. **Keploy: công cụ kiểm thử API và tích hợp tự sinh kiểm thử và dữ liệu giả bằng cách ghi lại lệnh gọi API, truy vấn cơ sở dữ liệu và sự kiện, dùng eBPF ở tầng mạng, rồi phát lại thành kiểm thử** (key 592, độ khó: Rất khó) — Ghi và phát lại lưu lượng thành kiểm thử (rất khó).  
   Repo: [keploy/keploy](https://github.com/keploy/keploy) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-gia-lap/content.json`
