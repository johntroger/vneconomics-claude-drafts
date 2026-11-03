# Lộ trình 53 — Cơ sở dữ liệu vector và đánh giá LLM

Từ kho vector nhỏ để thử đến máy chủ và hệ phân tán, kèm công cụ kiểm thử câu trả lời AI; chú ý cảnh báo bảo mật của Qdrant và chi phí đám mây.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Chroma: cơ sở dữ liệu vector mã nguồn mở cho ứng dụng AI, API cốt lõi chỉ 4 hàm, có dịch vụ đám mây trả phí** (key 420, độ khó: Trung bình) — Kho vector nhỏ, API 4 hàm, dễ thử.  
   Repo: [chroma-core/chroma](https://github.com/chroma-core/chroma) · Bản nháp: `content-drafts/2026-11-03-vector-db-llm-eval/content.json`
2. **promptfoo: công cụ dòng lệnh đánh giá và kiểm thử đối kháng (red teaming) ứng dụng LLM, chạy cục bộ; README nói dự án nay thuộc OpenAI** (key 423, độ khó: Trung bình) — Đánh giá và red teaming ứng dụng LLM.  
   Repo: [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) · Bản nháp: `content-drafts/2026-11-03-vector-db-llm-eval/content.json`
3. **Qdrant: công cụ tìm kiếm vector viết bằng Rust, có bản Edge chạy trong ứng dụng; README cảnh báo lệnh Docker mẫu không có xác thực** (key 421, độ khó: Khó) — Máy chủ tìm kiếm vector; Docker mẫu không xác thực (khó).  
   Repo: [qdrant/qdrant](https://github.com/qdrant/qdrant) · Bản nháp: `content-drafts/2026-11-03-vector-db-llm-eval/content.json`
4. **Milvus: cơ sở dữ liệu vector phân tán dưới LF AI & Data, có chế độ Standalone và Milvus Lite cho người mới** (key 422, độ khó: Rất khó) — Phân tán quy mô lớn; bắt đầu bằng Milvus Lite (rất khó).  
   Repo: [milvus-io/milvus](https://github.com/milvus-io/milvus) · Bản nháp: `content-drafts/2026-11-03-vector-db-llm-eval/content.json`
