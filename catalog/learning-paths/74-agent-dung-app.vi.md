# Lộ trình 74 — Agent và nền tảng dựng app bằng AI

Từ ứng dụng mẫu dựng app bằng trò chuyện, coding agent trong trình soạn mã, hệ nhiều agent, agent sửa lỗi nghiên cứu đến cổng mô hình và agent gửi pull request; chú ý khóa API và chi phí, sandbox, quyền GitHub, tình trạng bảo trì và cảnh báo của từng README.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Open Lovable: ứng dụng mẫu của Firecrawl để trò chuyện với AI dựng ứng dụng React ngay lập tức; cần khóa Firecrawl, khóa nhà cung cấp AI và sandbox Vercel hoặc E2B** (key 556, độ khó: Khó) — Ứng dụng mẫu dựng React bằng trò chuyện; cần nhiều khóa (khó).  
   Repo: [firecrawl/open-lovable](https://github.com/firecrawl/open-lovable) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
2. **Kilo Code: coding agent mã nguồn mở chạy trong VS Code, JetBrains và CLI, chọn trong hơn 500 mô hình; README có lệnh cài tải từ mạng và dịch vụ trả phí** (key 557, độ khó: Trung bình) — Coding agent trong VS Code, JetBrains, CLI (trung bình).  
   Repo: [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
3. **Claude Code Router: cổng mô hình cục bộ và bảng điều khiển cho coding agent, nối Claude Code, Codex, OpenCode và nhiều agent khác với nhà cung cấp bạn chọn, có định tuyến, dự phòng và quan sát** (key 560, độ khó: Khó) — Cổng mô hình cho nhiều agent; giữ khóa của bạn (khó).  
   Repo: [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
4. **SWE-agent: agent do nhà nghiên cứu Princeton và Stanford làm để mô hình ngôn ngữ tự dùng công cụ sửa lỗi trong kho GitHub thật; README nói mini-swe-agent đã thay thế và khuyến nghị dùng thay** (key 559, độ khó: Rất khó) — Agent sửa lỗi nghiên cứu; README khuyên dùng bản mini (rất khó).  
   Repo: [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
5. **ChatDev 2.0 (DevAll): nền tảng đa tác tử không cần mã, nay là bản 2.0 'phát triển mọi thứ'; bản 1.0 'công ty phần mềm ảo' chuyển sang nhánh riêng** (key 558, độ khó: Rất khó) — Nền tảng nhiều agent 2.0 (rất khó).  
   Repo: [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
6. **Open SWE: agent kỹ sư phần mềm mã nguồn mở của LangChain, điều tra kho mã, triển khai thay đổi trong sandbox và gửi pull request; README nói đang phát triển mạnh, không nhận issue hay đóng góp ngoài** (key 561, độ khó: Rất khó) — Agent gửi PR; đang phát triển mạnh, quyền GitHub rộng (rất khó).  
   Repo: [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe) · Bản nháp: `content-drafts/2026-11-03-agent-dung-app/content.json`
