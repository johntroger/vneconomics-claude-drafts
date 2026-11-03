# Lộ trình 96 — SDK và thư viện cho dịch vụ AI

Từ chạy mô hình AI trên máy mình, SDK gọi API của OpenAI và Google đến kho mô hình Hugging Face và khung lập trình mô hình ngôn ngữ; chú ý khóa API, mã thông báo và hóa đơn, dữ liệu gửi tới dịch vụ đám mây, mô hình đám mây của Ollama, đoạn nhắn riêng cho tác tử AI trong README và lệnh cài tải tập lệnh từ mạng.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Thư viện Ollama cho Python: cách dễ nhất để tích hợp dự án Python 3.8+ với Ollama, cần Ollama đã cài và đang chạy, có trò chuyện, luồng, mô hình đám mây, máy khách tùy chỉnh và bất đồng bộ; giấy phép MIT** (key 717, độ khó: Dễ đến trung bình) — Chạy mô hình cục bộ từ Python (dễ đến trung bình).  
   Repo: [ollama/ollama-python](https://github.com/ollama/ollama-python) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
2. **Thư viện Ollama cho JavaScript: cách dễ nhất để tích hợp dự án JavaScript với Ollama, có trò chuyện, luồng, dùng trong trình duyệt, mô hình đám mây và các hàm API; giấy phép MIT** (key 718, độ khó: Dễ đến trung bình) — Chạy mô hình cục bộ từ JavaScript (dễ đến trung bình).  
   Repo: [ollama/ollama-js](https://github.com/ollama/ollama-js) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
3. **Thư viện OpenAI cho Python: truy cập thuận tiện API REST của OpenAI từ ứng dụng Python 3.10+, có kiểu cho mọi tham số, máy khách đồng bộ và bất đồng bộ, sinh từ đặc tả OpenAPI; README rất dài và có nhiều cách xác thực** (key 714, độ khó: Trung bình) — SDK OpenAI cho Python (trung bình).  
   Repo: [openai/openai-python](https://github.com/openai/openai-python) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
4. **Thư viện OpenAI cho TypeScript và JavaScript: truy cập thuận tiện API REST của OpenAI, sinh từ đặc tả OpenAPI, README có mục cài với Deno, Responses API, nhiều cách xác thực, xác minh webhook, xử lý lỗi, thử lại, hết thời gian** (key 715, độ khó: Trung bình) — SDK OpenAI cho TypeScript (trung bình).  
   Repo: [openai/openai-node](https://github.com/openai/openai-node) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
5. **huggingface_hub: thư viện tương tác với Hugging Face Hub (nền tảng mô hình và tập dữ liệu mã nguồn mở): tải và tải lên tệp, quản lý kho, chạy suy luận, chạy công việc trên hạ tầng của Hugging Face, tìm kiếm, thẻ mô hình, cộng đồng, có CLI hf dành cho người và tác tử AI** (key 719, độ khó: Trung bình) — Kho mô hình Hugging Face (trung bình).  
   Repo: [huggingface/huggingface_hub](https://github.com/huggingface/huggingface_hub) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
6. **Google Gen AI SDK cho Python: giao diện để tích hợp mô hình sinh của Google vào ứng dụng Python, hỗ trợ API Gemini Developer và nền tảng tác tử doanh nghiệp Gemini; README rất dài, cảnh báo thay đổi gọi hàm tự động và có mục Agent Skills cho trợ lý AI** (key 716, độ khó: Trung bình đến khó) — SDK Google Gen AI (trung bình đến khó).  
   Repo: [googleapis/python-genai](https://github.com/googleapis/python-genai) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
7. **DSPy: khung lập trình thay vì viết lời nhắc cho mô hình nền tảng, xây hệ thống AI dạng mô-đun và cung cấp thuật toán tối ưu lời nhắc và trọng số; tên là Declarative Self-improving Python; README ngắn trỏ tới tài liệu dspy.ai, giấy phép MIT** (key 720, độ khó: Khó) — Lập trình mô hình ngôn ngữ thay vì viết lời nhắc (khó).  
   Repo: [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy) · Bản nháp: `content-drafts/2026-11-03-sdk-va-thu-vien-dich-vu-ai/content.json`
