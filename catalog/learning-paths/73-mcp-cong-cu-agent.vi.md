# Lộ trình 73 — MCP và công cụ nối AI với thế giới ngoài

Từ giao thức MCP, khung dựng máy chủ, máy chủ GitHub, điều khiển trình duyệt đến chuyển tài liệu, quy trình có cấu trúc và đóng gói kho mã cho AI; cấp quyền tối thiểu, giữ mã truy cập an toàn, dùng tài khoản thử, tắt thống kê khi cần và đừng gửi dữ liệu nhạy cảm cho AI.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **MCP Python SDK: bộ công cụ chính thức bằng Python để dựng máy chủ và máy khách theo Model Context Protocol, nối ứng dụng LLM với dữ liệu và chức năng; README nêu Python 3.11+ và bản v2** (key 547, độ khó: Khó) — SDK chính thức để dựng máy chủ MCP (khó).  
   Repo: [modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
2. **FastMCP: khung ứng dụng MCP đầy đủ bằng Python cho máy chủ, máy khách và ứng dụng tương tác, do Prefect duy trì; README quảng bá FastMCP Gateway trả phí cho doanh nghiệp** (key 548, độ khó: Khó) — Khung dựng máy chủ MCP nhanh; Gateway trả phí (khó).  
   Repo: [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
3. **MarkItDown: tiện ích Python chuyển PDF, PowerPoint, Word, Excel, ảnh, âm thanh, HTML, ZIP, YouTube... sang Markdown cho LLM; README cảnh báo thực hiện I/O với quyền tiến trình và dặn làm sạch đầu vào** (key 553, độ khó: Trung bình) — Chuyển tài liệu sang Markdown; làm sạch đầu vào (trung bình).  
   Repo: [microsoft/markitdown](https://github.com/microsoft/markitdown) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
4. **Repomix: đóng gói cả kho mã thành một tệp thân thiện với AI để đưa cho LLM, có đếm token, tôn trọng .gitignore và dùng Secretlint để loại tệp có khóa; README có cảnh báo về cấu hình từ kho từ xa** (key 555, độ khó: Trung bình) — Đóng gói kho mã cho AI; cẩn thận bí mật (trung bình).  
   Repo: [yamadashy/repomix](https://github.com/yamadashy/repomix) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
5. **Spec Kit: bộ công cụ mã nguồn mở của GitHub cho coding agent có quy trình có cấu trúc (phát triển dựa trên đặc tả, sửa lỗi, đánh giá ý tưởng), mẫu và kết quả được ghi lại** (key 554, độ khó: Trung bình) — Quy trình phát triển dựa trên đặc tả cho agent (trung bình).  
   Repo: [github/spec-kit](https://github.com/github/spec-kit) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
6. **GitHub MCP Server: máy chủ MCP chính thức của GitHub cho AI đọc kho, quản lý issue và PR, theo dõi Actions, phân tích mã; README hướng dẫn giữ mã truy cập cá nhân (PAT) an toàn** (key 549, độ khó: Khó) — AI đọc và quản lý GitHub; giữ PAT an toàn (khó).  
   Repo: [github/github-mcp-server](https://github.com/github/github-mcp-server) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
7. **Playwright MCP: máy chủ MCP cho AI điều khiển trình duyệt qua cây khả năng truy cập (accessibility tree) của Playwright, không cần mô hình thị giác; README so sánh với Playwright CLI cho coding agent** (key 550, độ khó: Khó) — AI điều khiển trình duyệt qua cây khả năng truy cập (khó).  
   Repo: [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
8. **Chrome DevTools cho agent (chrome-devtools-mcp): cho coding agent điều khiển và kiểm tra Chrome thật qua MCP hoặc CLI; README nêu Google thu thống kê sử dụng mặc định và cách tắt** (key 551, độ khó: Khó) — AI gỡ lỗi Chrome; có thống kê mặc định (khó).  
   Repo: [ChromeDevTools/chrome-devtools-mcp](https://github.com/ChromeDevTools/chrome-devtools-mcp) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
9. **Stagehand: khung tự động hóa trình duyệt bằng AI của Browserbase với act, observe, extract; chạy cục bộ hoặc trên nền tảng đám mây Browserbase trả phí; README có cảnh báo về khóa và mô hình** (key 552, độ khó: Khó) — AI điều khiển trình duyệt bằng act, observe, extract (khó).  
   Repo: [browserbase/stagehand](https://github.com/browserbase/stagehand) · Bản nháp: `content-drafts/2026-11-03-mcp-cong-cu-agent/content.json`
