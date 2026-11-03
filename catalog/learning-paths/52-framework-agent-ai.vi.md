# Lộ trình 52 — Framework agent AI

Từ công cụ kéo thả đến các framework Python dựng agent, nhóm agent, đồ thị trạng thái và bộ nhớ; chú ý chi phí gọi mô hình, quyền riêng tư và rủi ro chạy mã do AI sinh.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Langflow: nền tảng kéo thả dựng agent và quy trình AI, có thể xuất thành API hoặc máy chủ MCP, có bản Desktop cho Windows và macOS** (key 413, độ khó: Trung bình) — Dựng quy trình AI bằng giao diện kéo thả.  
   Repo: [langflow-ai/langflow](https://github.com/langflow-ai/langflow) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
2. **smolagents: thư viện nhỏ gọn chạy agent trong vài dòng mã, agent viết hành động bằng mã (CodeAgent)** (key 418, độ khó: Khó) — Thư viện nhỏ; CodeAgent chạy mã do AI sinh, cần cô lập.  
   Repo: [huggingface/smolagents](https://github.com/huggingface/smolagents) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
3. **OpenAI Agents SDK (Python): framework nhẹ để dựng quy trình đa agent, không giới hạn nhà cung cấp mô hình, có guardrail và người duyệt** (key 417, độ khó: Khó) — Framework nhẹ với guardrail và tracing (khó).  
   Repo: [openai/openai-agents-python](https://github.com/openai/openai-agents-python) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
4. **CrewAI: framework Python dựng nhóm agent AI cộng tác (Crews) và quy trình điều khiển theo sự kiện (Flows), có gói doanh nghiệp trả phí** (key 414, độ khó: Khó) — Nhóm agent theo vai; chú ý chi phí (khó).  
   Repo: [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
5. **LangGraph: framework điều phối cấp thấp để dựng agent có trạng thái, chạy lâu, có thể phục hồi sau lỗi và có người duyệt** (key 416, độ khó: Rất khó) — Điều phối cấp thấp, trạng thái bền (rất khó).  
   Repo: [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
6. **LlamaIndex: framework mã nguồn mở dựng ứng dụng agent, README nói trọng tâm công ty đã chuyển sang LlamaParse** (key 415, độ khó: Khó) — Đọc ghi chú về trọng tâm của công ty trước khi chọn (khó).  
   Repo: [run-llama/llama_index](https://github.com/run-llama/llama_index) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
7. **Mem0: lớp bộ nhớ cho agent AI, lưu và truy xuất ký ức của người dùng; README có số liệu đánh giá của hãng cần đọc thận trọng** (key 419, độ khó: Khó) — Bộ nhớ cho agent; số liệu là của hãng, cần quan tâm quyền riêng tư (khó).  
   Repo: [mem0ai/mem0](https://github.com/mem0ai/mem0) · Bản nháp: `content-drafts/2026-11-03-framework-agent-ai/content.json`
