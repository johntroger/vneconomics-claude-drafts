# Lộ trình 94 — Ngôn ngữ, tiếng Việt và quốc tế hóa

Từ xử lý văn bản tiếng Việt, tách token cho mô hình ngôn ngữ đến quốc tế hóa ứng dụng; chú ý khóa API và dữ liệu văn bản gửi ra ngoài, bản dịch máy cần kiểm tra, bản phát hành thử của Tokenizers và dịch vụ trả phí đi kèm.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **i18next: khung quốc tế hóa phổ biến cho trình duyệt và môi trường JavaScript khác (Node.js, Deno), nạp bản dịch từ nhiều nguồn, phát hiện ngôn ngữ, số nhiều, ngữ cảnh, lồng nhau, thay biến; README có phần giới thiệu dịch vụ Locize của chính nhóm tác giả** (key 705, độ khó: Trung bình) — Quốc tế hóa cho JavaScript (trung bình).  
   Repo: [i18next/i18next](https://github.com/i18next/i18next) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-tieng-viet-va-quoc-te-hoa/content.json`
2. **Lingui: thư viện quốc tế hóa (i18n) nhẹ, mã nguồn mở cho JavaScript và TypeScript, dùng macro lúc biên dịch và công cụ dòng lệnh trích chuỗi cho React, React Native; lõi khoảng 2 KB nén gzip, giấy phép MIT** (key 706, độ khó: Trung bình) — Quốc tế hóa nhẹ cho React (trung bình).  
   Repo: [lingui/js-lingui](https://github.com/lingui/js-lingui) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-tieng-viet-va-quoc-te-hoa/content.json`
3. **Underthesea: bộ công cụ xử lý ngôn ngữ tiếng Việt mã nguồn mở của Việt Nam, từ phiên bản 9.3.0 là bộ công cụ tác tử AI có sẵn khả năng NLP tiếng Việt, hỗ trợ tách câu, tách từ, gán nhãn từ loại, nhận diện thực thể, phân loại, phân tích cảm xúc, dịch và đọc văn bản** (key 704, độ khó: Trung bình) — Bộ công cụ NLP tiếng Việt (trung bình).  
   Repo: [undertheseanlp/underthesea](https://github.com/undertheseanlp/underthesea) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-tieng-viet-va-quoc-te-hoa/content.json`
4. **SentencePiece: bộ tách và ghép token không giám sát nhanh và gọn cho hệ sinh văn bản dùng mạng nơ-ron (như mô hình ngôn ngữ lớn) với từ vựng cố định, cài đặt BPE và mô hình unigram, README nhấn mạnh không phải sản phẩm chính thức của Google; giấy phép Apache 2.0** (key 708, độ khó: Khó) — Tách token từ văn bản thô (khó).  
   Repo: [google/sentencepiece](https://github.com/google/sentencepiece) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-tieng-viet-va-quoc-te-hoa/content.json`
5. **Hugging Face Tokenizers: thư viện tách token tự nhận là chuẩn mực cho mọi ngôn ngữ, mô hình và phần cứng, lõi Rust với liên kết Python, Node.js, WebAssembly; README ghi đang chuyển từ 0.23 sang bản v1.0.0 phát hành thử** (key 707, độ khó: Khó) — Tách token cho mô hình ngôn ngữ (khó).  
   Repo: [huggingface/tokenizers](https://github.com/huggingface/tokenizers) · Bản nháp: `content-drafts/2026-11-03-ngon-ngu-tieng-viet-va-quoc-te-hoa/content.json`
