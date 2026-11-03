# Lộ trình 64 — Chạy và tinh chỉnh mô hình AI

Từ chạy mô hình trên Mac hay máy cá nhân đến phục vụ ở quy mô máy chủ và tinh chỉnh; chú ý yêu cầu phần cứng, giấy phép của mô hình, telemetry, quyền ứng dụng xin và các tuyên bố hiệu năng của hãng.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **MLX LM: gói Python tạo văn bản và tinh chỉnh mô hình ngôn ngữ lớn trên chip Apple silicon bằng MLX, tích hợp Hugging Face Hub** (key 486, độ khó: Trung bình) — Chạy và tinh chỉnh trên Mac Apple silicon (trung bình).  
   Repo: [ml-explore/mlx-lm](https://github.com/ml-explore/mlx-lm) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
2. **LocalAI: engine AI mã nguồn mở chạy mọi loại mô hình (văn bản, ảnh, giọng nói, video) trên nhiều phần cứng, tương thích API OpenAI và Anthropic, không bắt buộc có GPU** (key 484, độ khó: Khó) — Engine tương thích API OpenAI chạy cục bộ (khó).  
   Repo: [mudler/LocalAI](https://github.com/mudler/LocalAI) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
3. **Unsloth: ứng dụng desktop để chạy và huấn luyện mô hình AI, tinh chỉnh nhanh gấp đôi và ít VRAM hơn 70% theo tuyên bố của hãng; giấy phép kép Apache 2.0 và AGPL-3.0** (key 489, độ khó: Rất khó) — Chạy và tinh chỉnh bằng ứng dụng desktop; giấy phép kép (rất khó).  
   Repo: [unslothai/unsloth](https://github.com/unslothai/unsloth) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
4. **Axolotl: công cụ tinh chỉnh mô hình AI bằng tệp cấu hình, hỗ trợ nhiều phương pháp (LoRA, DPO, GRPO) và mô hình; README có telemetry bật sẵn, tắt bằng biến môi trường** (key 490, độ khó: Rất khó) — Tinh chỉnh bằng tệp cấu hình; telemetry bật sẵn (rất khó).  
   Repo: [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
5. **exo: nối nhiều thiết bị (Mac, Linux) thành một cụm AI để chạy mô hình lớn hơn bộ nhớ một máy; README nêu yêu cầu macOS và tuyên bố benchmark** (key 485, độ khó: Rất khó) — Gộp nhiều máy thành cụm; đọc kỹ quyền xin (rất khó).  
   Repo: [exo-explore/exo](https://github.com/exo-explore/exo) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
6. **vLLM: thư viện suy luận và phục vụ LLM nhanh, dễ dùng, từ Sky Computing Lab (UC Berkeley), có máy chủ API tương thích OpenAI và Anthropic** (key 487, độ khó: Rất khó) — Phục vụ mô hình quy mô máy chủ (rất khó).  
   Repo: [vllm-project/vllm](https://github.com/vllm-project/vllm) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
7. **SGLang: framework suy luận mã nguồn mở cho mô hình ngôn ngữ, thị giác-ngôn ngữ và khuếch tán, tối ưu cho agent và phục vụ quy mô lớn** (key 488, độ khó: Rất khó) — Phục vụ mô hình cho agent và nhiều phương thức (rất khó).  
   Repo: [sgl-project/sglang](https://github.com/sgl-project/sglang) · Bản nháp: `content-drafts/2026-11-03-chay-tinh-chinh-mo-hinh/content.json`
