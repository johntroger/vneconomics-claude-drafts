# Lộ trình 86 — Framework máy chủ và API

Từ framework tối giản bằng Python và Node.js, API an toàn kiểu, GraphQL đến framework C++ hiệu năng cao; chú ý tuyên bố hiệu năng của tác giả, an toàn của API mở ra Internet, và bảo mật bộ nhớ khi dùng C++.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Koa: framework phần mềm trung gian HTTP biểu cảm cho Node.js để viết ứng dụng web và API dễ chịu hơn, ngăn xếp phần mềm trung gian chạy kiểu ngăn xếp, lõi nhỏ khoảng 570 dòng mã, không đi kèm phần mềm trung gian nào, giấy phép MIT** (key 646, độ khó: Trung bình) — Phần mềm trung gian tối giản cho Node.js (trung bình).  
   Repo: [koajs/koa](https://github.com/koajs/koa) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
2. **aiohttp: khung client và máy chủ HTTP bất đồng bộ cho Python, hỗ trợ cả client và máy chủ WebSocket, máy chủ web có phần mềm trung gian và định tuyến cắm thêm được, giấy phép Apache 2.0** (key 647, độ khó: Trung bình) — Client và máy chủ HTTP bất đồng bộ cho Python (trung bình).  
   Repo: [aio-libs/aiohttp](https://github.com/aio-libs/aiohttp) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
3. **Falcon: framework web ASGI và WSGI tối giản để xây API REST và vi dịch vụ quan trọng, ưu tiên độ tin cậy, đúng đắn và hiệu năng ở quy mô lớn, ít phụ thuộc, chạy trên CPython 3.9+ và PyPy 3.9+, giấy phép Apache 2.0** (key 651, độ khó: Trung bình) — API REST tối giản cho Python (trung bình).  
   Repo: [falconry/falcon](https://github.com/falconry/falcon) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
4. **Strawberry GraphQL: thư viện GraphQL cho Python dựa trên dataclass, định nghĩa kiểu bằng chú thích kiểu, có tích hợp Django và công cụ dòng lệnh, giấy phép MIT** (key 649, độ khó: Trung bình) — GraphQL cho Python (trung bình).  
   Repo: [strawberry-graphql/strawberry](https://github.com/strawberry-graphql/strawberry) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
5. **NestJS: framework xây ứng dụng máy chủ Node.js hiệu quả và co giãn, viết bằng TypeScript, kiến trúc lấy cảm hứng từ Angular, dùng Express bên dưới và tương thích Fastify, giấy phép MIT** (key 645, độ khó: Trung bình đến khó) — Framework Node.js có kiến trúc (trung bình đến khó).  
   Repo: [nestjs/nest](https://github.com/nestjs/nest) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
6. **tRPC: xây và dùng API an toàn kiểu hoàn toàn không cần lược đồ hay sinh mã, client không nhập mã từ máy chủ mà chỉ dùng khai báo kiểu; adapter cho React, Next.js, Express, Fastify, giấy phép MIT** (key 648, độ khó: Trung bình đến khó) — API an toàn kiểu cho TypeScript (trung bình đến khó).  
   Repo: [trpc/trpc](https://github.com/trpc/trpc) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
7. **GraphQL.js: bản cài đặt tham chiếu bằng JavaScript của GraphQL, ngôn ngữ truy vấn cho API do Facebook tạo ra, dùng làm nền cho nhiều thư viện; README có phần hỗ trợ phiên bản và lịch hết hỗ trợ, giấy phép MIT** (key 650, độ khó: Khó) — Bản tham chiếu GraphQL bằng JavaScript (khó).  
   Repo: [graphql/graphql-js](https://github.com/graphql/graphql-js) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
8. **Drogon: framework ứng dụng HTTP viết bằng C++17/20, I/O không chặn dựa trên epoll, hoàn toàn bất đồng bộ, hỗ trợ WebSocket, JSON, đọc ghi cơ sở dữ liệu bất đồng bộ, công cụ dòng lệnh drogon_ctl, đa nền tảng** (key 652, độ khó: Rất khó) — Framework web C++ (rất khó).  
   Repo: [drogonframework/drogon](https://github.com/drogonframework/drogon) · Bản nháp: `content-drafts/2026-11-03-framework-may-chu-va-api/content.json`
