# Nhóm "AI agent, backend và công cụ cho người vibe code" — bản nháp 03/11/2026

12 bài, key 111–122, `batch: 21`. Không trùng repo với 100 bài cũ và 10 bài nhóm tự động hóa. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 111 | Firecrawl: biến trang web thành dữ liệu sạch cho trợ lý AI đọc | [firecrawl/firecrawl](https://github.com/firecrawl/firecrawl) | AGPL-3.0 | 198050 | 2026-11-03 |
| 112 | Browser Use: cho trợ lý AI điều khiển trình duyệt để làm việc trên web | [browser-use/browser-use](https://github.com/browser-use/browser-use) | MIT | 119884 | 2026-11-02 |
| 113 | Context7: đưa tài liệu thư viện mới nhất cho AI khi nó viết code | [upstash/context7](https://github.com/upstash/context7) | MIT | 64105 | 2026-11-03 |
| 114 | Awesome MCP Servers: đọc danh mục server MCP và cách chọn an toàn | [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) | MIT | 97216 | 2026-11-02 |
| 115 | AI Agents for Beginners: lộ trình 18 bài học để hiểu agent AI từ đầu | [microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) | MIT | 78734 | 2026-11-02 |
| 116 | Coolify: tự dựng nơi đưa ứng dụng lên mạng thay cho Vercel hay Heroku | [coollabsio/coolify](https://github.com/coollabsio/coolify) | Apache-2.0 | 65563 | 2026-11-02 |
| 117 | Appwrite: nền tảng backend có đăng nhập, dữ liệu và lưu file cho ứng dụng của bạn | [appwrite/appwrite](https://github.com/appwrite/appwrite) | BSD-3-Clause | 57855 | 2026-11-03 |
| 118 | Crawl4AI: thu thập website thành Markdown sạch cho AI, tự chạy hoặc dùng đám mây | [unclecode/crawl4ai](https://github.com/unclecode/crawl4ai) | Apache-2.0 | 86802 | 2026-11-02 |
| 119 | Supabase: cơ sở dữ liệu Postgres kèm đăng nhập và API dựng sẵn cho ứng dụng | [supabase/supabase](https://github.com/supabase/supabase) | Apache-2.0 | 114461 | 2026-11-03 |
| 120 | LangChain: bộ khung nối model AI với công cụ và dữ liệu để xây agent | [langchain-ai/langchain](https://github.com/langchain-ai/langchain) | MIT | 148919 | 2026-11-03 |
| 121 | shadcn/ui: bộ thành phần giao diện bạn sở hữu mã nguồn để tự tùy biến | [shadcn-ui/ui](https://github.com/shadcn-ui/ui) | MIT | 127219 | 2026-11-02 |
| 122 | Dyad: ứng dụng tạo app bằng AI chạy ngay trên máy của bạn | [dyad-sh/dyad](https://github.com/dyad-sh/dyad) | NOASSERTION | 22173 | 2026-11-03 |

## Cách lấy dữ liệu
README qua raw.githubusercontent.com; số sao, license, ngày commit từ GitHub Search API; một số trang tài liệu chính thức đọc bằng WebFetch (ghi trong `docsRead` của từng file research): MCP intro, Coolify installation, shadcn/ui docs và installation, Dyad docs.

## Repo bị loại hoặc cân nhắc
- **BloopAI/vibe-kanban** (khoảng 28,6 nghìn sao): README ghi "Vibe Kanban is sunsetting"; trang thông báo của họ nói công ty bloop đóng cửa ngày 2026-04-10, dịch vụ từ xa dừng sau 30 ngày, dự án tiếp tục mã nguồn mở do cộng đồng duy trì. Chưa chắc chắn về tương lai nên loại.
- **microsoft/generative-ai-for-beginners**: đã có trong đợt 100 bài cũ.
- **modelcontextprotocol/servers**: GitHub trả NOASSERTION, chưa đọc kỹ nên chưa đưa vào.
- **asgeirtj/system_prompts_leaks**: prompt bị rò rỉ, rủi ro đạo đức và pháp lý.
- **datawhalechina/easy-vibe**: không có license, chưa dùng lại nội dung.
- Các repo mới tạo 2025–2026 có sao rất cao (openclaw, hermes-agent, cc-switch, claude-mem…): chưa viết vì không có lịch sử sao để đánh giá và nội dung dễ lỗi thời.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật. Câu lệnh mẫu cho AI chưa thử với trợ lý cụ thể.
- Không cài hay chạy repo nào; không có lệnh cài trong bài.
- Giá cloud/dịch vụ (Firecrawl, Browser Use, Crawl4AI cloud, Appwrite, Supabase, Coolify Cloud, LangSmith) lấy từ README nếu có, còn lại chưa kiểm tra; số liệu có thể đã đổi.
- Context7: chỉ một phần là mã nguồn mở (backend riêng tư), bài đã nói rõ.
- Awesome MCP Servers: README ~1,6 MB, chỉ đọc phần đầu và một số mục.
- Coolify: yêu cầu máy chủ lấy từ trang tài liệu (qua WebFetch tóm tắt), cần đối chiếu lại bản gốc.
- shadcn/ui: README chỉ vài dòng; trang tài liệu không nêu tiền đề cài đặt cụ thể.
- Dyad: giấy phép hỗn hợp (Apache 2.0 và FSL cho src/pro); chưa đọc quickstart.
- Không có `contentHash`; `review.needed = true` cho mọi bài.
- Giá trị `category` và `need` được gán về nhãn đã có trên site (9 category và 9 need); đây là gợi ý, importer/chủ site quyết định cuối.
