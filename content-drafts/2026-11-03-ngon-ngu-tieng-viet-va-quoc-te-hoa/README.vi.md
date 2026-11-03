# Nhóm "Ngôn ngữ, tiếng Việt và quốc tế hóa" — bản nháp 03/11/2026

5 bài, key 704–708, `batch: 113`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 704 | Underthesea: bộ công cụ xử lý ngôn ngữ tiếng Việt mã nguồn mở của Việt Nam, từ phiên bản 9.3.0 là bộ công cụ tác tử AI có sẵn khả năng NLP tiếng Việt, hỗ trợ tách câu, tách từ, gán nhãn từ loại, nhận diện thực thể, phân loại, phân tích cảm xúc, dịch và đọc văn bản | [undertheseanlp/underthesea](https://github.com/undertheseanlp/underthesea) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 1815 | 2026-11-02 |
| 705 | i18next: khung quốc tế hóa phổ biến cho trình duyệt và môi trường JavaScript khác (Node.js, Deno), nạp bản dịch từ nhiều nguồn, phát hiện ngôn ngữ, số nhiều, ngữ cảnh, lồng nhau, thay biến; README có phần giới thiệu dịch vụ Locize của chính nhóm tác giả | [i18next/i18next](https://github.com/i18next/i18next) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 8660 | 2026-11-01 |
| 706 | Lingui: thư viện quốc tế hóa (i18n) nhẹ, mã nguồn mở cho JavaScript và TypeScript, dùng macro lúc biên dịch và công cụ dòng lệnh trích chuỗi cho React, React Native; lõi khoảng 2 KB nén gzip, giấy phép MIT | [lingui/js-lingui](https://github.com/lingui/js-lingui) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 5934 | 2026-11-03 |
| 707 | Hugging Face Tokenizers: thư viện tách token tự nhận là chuẩn mực cho mọi ngôn ngữ, mô hình và phần cứng, lõi Rust với liên kết Python, Node.js, WebAssembly; README ghi đang chuyển từ 0.23 sang bản v1.0.0 phát hành thử | [huggingface/tokenizers](https://github.com/huggingface/tokenizers) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 11217 | 2026-11-03 |
| 708 | SentencePiece: bộ tách và ghép token không giám sát nhanh và gọn cho hệ sinh văn bản dùng mạng nơ-ron (như mô hình ngôn ngữ lớn) với từ vựng cố định, cài đặt BPE và mô hình unigram, README nhấn mạnh không phải sản phẩm chính thức của Google; giấy phép Apache 2.0 | [google/sentencepiece](https://github.com/google/sentencepiece) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 12163 | 2026-11-02 |

## Repo đã xem nhưng không đưa vào nhóm này

- **WeblateOrg/weblate** (README khoảng 2,9 KB), **VinAIResearch/PhoWhisper** (khoảng 2 KB), **rhasspy/piper** (README 63 byte và đã lưu trữ): README ngắn hoặc dự án đã lưu trữ; loại. **VinAIResearch/PhoBERT** (commit 2026-08-04), **VinAIResearch/PhoGPT** (2024-11-12), **vncorenlp/VnCoreNLP** (2023-02-12), **coqui-ai/TTS** (2024-08-16), **argosopentech/argos-translate** (2026-08-08), **ChatTTS** (2026-04-10), **projectfluent/fluent** (2026-03-21), **gensim** (2025-11-01): commit gần nhất quá 60 ngày; loại.
- **formatjs/formatjs** (giấy phép None), **flairNLP/flair**, **stanfordnlp/stanza** (NOASSERTION): giấy phép không rõ; loại. **FunAudioLLM/CosyVoice**, **UKPLab/sentence-transformers**: tìm kiếm không trả kết quả. **ggml-org/whisper.cpp**: đã có trong catalog.
- Nhóm có 5 bài vì không đủ repo đạt chuẩn.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Skills và phương pháp làm việc', nhãn gần nhất trong 9 nhãn có sẵn.
- Lingui (MIT, mục License), SentencePiece (Apache 2.0), Tokenizers (huy hiệu giấy phép) nêu giấy phép trong README. Underthesea và i18next: README phần đã đọc không nêu giấy phép, lấy theo GitHub (Apache-2.0, MIT).
- README Underthesea có phần tác tử AI dùng khóa API của người dùng để gọi dịch vụ mô hình bên ngoài: tốn phí và văn bản có thể chứa thông tin riêng tư; bài không chép lệnh. README i18next có khung giới thiệu dịch vụ trả phí Locize và một lưu ý gửi trợ lý AI lập trình (không cài hay kết nối Locize trừ khi nhà phát triển yêu cầu): bài nêu như ghi chú của README và không làm theo. README Lingui có phần gói kỹ năng tác tử do bên thứ ba cung cấp: bài không cài. README Tokenizers ghi đang chuyển sang v1.0.0 phát hành thử với thay đổi không tương thích. Tuyên bố của tác giả, bài không kiểm chứng: 6 triệu lượt tải của Lingui, chuẩn mực và hiệu năng của Tokenizers, nhanh và gọn của SentencePiece, chất lượng mô hình tiếng Việt của Underthesea.

