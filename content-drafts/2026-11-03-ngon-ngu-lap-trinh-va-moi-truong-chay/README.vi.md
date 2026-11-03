# Nhóm "Ngôn ngữ lập trình và môi trường chạy mã" — bản nháp 03/11/2026

6 bài, key 721–726, `batch: 116`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 721 | Ngôn ngữ V: ngôn ngữ lập trình đơn giản học được trong một cuối tuần, biên dịch nhanh, hiệu năng như C (backend chính biên dịch ra mã C dễ đọc), an toàn (không null, không biến toàn cục), dịch C sang V, tải lại mã nóng; README ghi sẽ còn thay đổi trước bản 1.0 | [vlang/v](https://github.com/vlang/v) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 38088 | 2026-11-03 |
| 722 | Luau: ngôn ngữ kịch bản nhúng nhanh, nhỏ, an toàn, có kiểu dần dần, dẫn xuất từ Lua, tương thích Lua 5.1, được Roblox dùng; kèm công cụ dòng lệnh luau (REPL) và luau-analyze (kiểm tra kiểu và lint), giấy phép MIT | [luau-lang/luau](https://github.com/luau-lang/luau) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 6052 | 2026-11-02 |
| 723 | Wasmer: chạy ứng dụng trong hộp cát nhanh, an toàn, nhẹ, tại máy, trên đám mây hoặc trong trình duyệt; kiểm soát quyền tệp, mạng, môi trường, chạy Python, JavaScript, Bash từ kho gói, có Wasmer SDK nhúng; README có lệnh cài tải tập lệnh từ mạng | [wasmerio/wasmer](https://github.com/wasmerio/wasmer) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 21221 | 2026-11-03 |
| 724 | Wasmtime: môi trường chạy WebAssembly nhanh, an toàn của Bytecode Alliance xây trên bộ sinh mã Cranelift, tập trung vào đúng đắn và bảo mật, kiểm thử fuzz 24/7, hỗ trợ nhiều ngôn ngữ nhúng; README có lệnh cài tải tập lệnh từ mạng | [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 18823 | 2026-11-02 |
| 725 | Roc: ngôn ngữ lập trình hàm đang trong giai đoạn đang làm dở (README ghi chưa sẵn sàng cho bản 0.1) với hướng dẫn cài, bài hướng dẫn, tài liệu thư viện chuẩn, ví dụ, hỏi đáp và nhóm trò chuyện; giấy phép UPL-1.0 theo GitHub | [roc-lang/roc](https://github.com/roc-lang/roc) | {'key': 'upl-1.0', 'name': 'Universal Permissive License v1.0', 'spdx_id': 'UPL-1.0', 'url': 'https://api.github.com/licenses/upl-1.0', 'node_id': 'MDc6TGljZW5zZTMz'} | 6184 | 2026-11-03 |
| 726 | Erlang/OTP: ngôn ngữ Erlang và hệ thống chạy để xây hệ thống thời gian thực mềm có khả năng mở rộng lớn và tính sẵn sàng cao, cùng thư viện OTP; README có ví dụ Hello World, cài đặt, báo lỗi, đóng góp; giấy phép Apache 2.0 | [erlang/otp](https://github.com/erlang/otp) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 12353 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **scala/scala3** (README khoảng 1,3 KB), **tree-sitter/tree-sitter** (khoảng 1,2 KB), **racket/racket** (khoảng 1,9 KB), **purescript/purescript** (khoảng 1,8 KB), **grain-lang/grain** (khoảng 2 KB), **ziglang/zig** (README 119 byte): README ngắn; loại. **JetBrains/kotlin**, **clojure/clojure** (giấy phép None, không tìm thấy README ở tên tệp chuẩn), **nim-lang/Nim**, **oven-sh/bun**, **racket/racket** (NOASSERTION): giấy phép không rõ; loại. **microsoft/typescript-go**: GitHub ghi đã lưu trữ; loại. **carbon-language/carbon**: tìm kiếm không trả kết quả.

## Điều chưa biết

- Chưa cài hay chạy ngôn ngữ hoặc môi trường nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Coding agent và cách làm dự án', nhãn gần nhất trong 9 nhãn có sẵn.
- Luau (MIT), Wasmer (MIT), Erlang/OTP (Apache License 2.0) nêu giấy phép trong README. V, Wasmtime (README phần đã đọc không nêu) và Roc (README không nêu; GitHub nhận diện UPL-1.0) lấy giấy phép theo GitHub (MIT, Apache-2.0, UPL-1.0).
- README V ghi còn thay đổi trước bản 1.0 và có tuyên bố tốc độ, an toàn, 'như C' là của tác giả, bài không kiểm chứng; README Roc ghi chưa sẵn sàng cho bản 0.1. README Wasmer và Wasmtime có lệnh cài tải tập lệnh từ mạng; bài không chép lệnh và khuyên đọc tập lệnh trước. Tuyên bố 'an toàn theo mặc định' của Wasmer, 'nhanh và an toàn' của Wasmtime là của dự án. Hộp cát chỉ an toàn khi cấu hình đúng quyền. README V (khoảng 25 KB) chủ yếu hướng dẫn cài.

