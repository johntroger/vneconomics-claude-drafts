# Lộ trình 97 — Ngôn ngữ lập trình và môi trường chạy mã

Từ ngôn ngữ kịch bản nhúng, ngôn ngữ mới còn thay đổi, ngôn ngữ cho hệ thống chạy liên tục đến hộp cát WebAssembly để chạy mã lạ; chú ý lệnh cài tải tập lệnh từ mạng, ngôn ngữ chưa ổn định, tuyên bố tốc độ và an toàn của tác giả, và việc hộp cát chỉ an toàn khi cấu hình đúng quyền.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Luau: ngôn ngữ kịch bản nhúng nhanh, nhỏ, an toàn, có kiểu dần dần, dẫn xuất từ Lua, tương thích Lua 5.1, được Roblox dùng; kèm công cụ dòng lệnh luau (REPL) và luau-analyze (kiểm tra kiểu và lint), giấy phép MIT** (key 722, độ khó: Trung bình) — Ngôn ngữ kịch bản nhúng (trung bình).  
   Repo: [luau-lang/luau](https://github.com/luau-lang/luau) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
2. **Ngôn ngữ V: ngôn ngữ lập trình đơn giản học được trong một cuối tuần, biên dịch nhanh, hiệu năng như C (backend chính biên dịch ra mã C dễ đọc), an toàn (không null, không biến toàn cục), dịch C sang V, tải lại mã nóng; README ghi sẽ còn thay đổi trước bản 1.0** (key 721, độ khó: Trung bình) — Ngôn ngữ V; còn thay đổi trước 1.0 (trung bình).  
   Repo: [vlang/v](https://github.com/vlang/v) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
3. **Roc: ngôn ngữ lập trình hàm đang trong giai đoạn đang làm dở (README ghi chưa sẵn sàng cho bản 0.1) với hướng dẫn cài, bài hướng dẫn, tài liệu thư viện chuẩn, ví dụ, hỏi đáp và nhóm trò chuyện; giấy phép UPL-1.0 theo GitHub** (key 725, độ khó: Khó) — Ngôn ngữ hàm đang làm dở (khó).  
   Repo: [roc-lang/roc](https://github.com/roc-lang/roc) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
4. **Erlang/OTP: ngôn ngữ Erlang và hệ thống chạy để xây hệ thống thời gian thực mềm có khả năng mở rộng lớn và tính sẵn sàng cao, cùng thư viện OTP; README có ví dụ Hello World, cài đặt, báo lỗi, đóng góp; giấy phép Apache 2.0** (key 726, độ khó: Khó) — Hệ thống chạy liên tục (khó).  
   Repo: [erlang/otp](https://github.com/erlang/otp) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
5. **Wasmtime: môi trường chạy WebAssembly nhanh, an toàn của Bytecode Alliance xây trên bộ sinh mã Cranelift, tập trung vào đúng đắn và bảo mật, kiểm thử fuzz 24/7, hỗ trợ nhiều ngôn ngữ nhúng; README có lệnh cài tải tập lệnh từ mạng** (key 724, độ khó: Khó) — Chạy WebAssembly (khó).  
   Repo: [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
6. **Wasmer: chạy ứng dụng trong hộp cát nhanh, an toàn, nhẹ, tại máy, trên đám mây hoặc trong trình duyệt; kiểm soát quyền tệp, mạng, môi trường, chạy Python, JavaScript, Bash từ kho gói, có Wasmer SDK nhúng; README có lệnh cài tải tập lệnh từ mạng** (key 723, độ khó: Khó) — Hộp cát chạy mã; chú ý lệnh cài (khó).  
   Repo: [wasmerio/wasmer](https://github.com/wasmerio/wasmer) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-lap-trinh-va-moi-truong-chay/content.json`
