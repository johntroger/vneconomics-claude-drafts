# Nhóm "Chạy và tinh chỉnh mô hình AI" — bản nháp 03/11/2026

7 bài, key 484–490, `batch: 83`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 484 | LocalAI: engine AI mã nguồn mở chạy mọi loại mô hình (văn bản, ảnh, giọng nói, video) trên nhiều phần cứng, tương thích API OpenAI và Anthropic, không bắt buộc có GPU | [mudler/LocalAI](https://github.com/mudler/LocalAI) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 50149 | 2026-11-03 |
| 485 | exo: nối nhiều thiết bị (Mac, Linux) thành một cụm AI để chạy mô hình lớn hơn bộ nhớ một máy; README nêu yêu cầu macOS và tuyên bố benchmark | [exo-explore/exo](https://github.com/exo-explore/exo) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 48158 | 2026-11-03 |
| 486 | MLX LM: gói Python tạo văn bản và tinh chỉnh mô hình ngôn ngữ lớn trên chip Apple silicon bằng MLX, tích hợp Hugging Face Hub | [ml-explore/mlx-lm](https://github.com/ml-explore/mlx-lm) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 7538 | 2026-10-30 |
| 487 | vLLM: thư viện suy luận và phục vụ LLM nhanh, dễ dùng, từ Sky Computing Lab (UC Berkeley), có máy chủ API tương thích OpenAI và Anthropic | [vllm-project/vllm](https://github.com/vllm-project/vllm) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 96189 | 2026-11-03 |
| 488 | SGLang: framework suy luận mã nguồn mở cho mô hình ngôn ngữ, thị giác-ngôn ngữ và khuếch tán, tối ưu cho agent và phục vụ quy mô lớn | [sgl-project/sglang](https://github.com/sgl-project/sglang) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 38393 | 2026-11-03 |
| 489 | Unsloth: ứng dụng desktop để chạy và huấn luyện mô hình AI, tinh chỉnh nhanh gấp đôi và ít VRAM hơn 70% theo tuyên bố của hãng; giấy phép kép Apache 2.0 và AGPL-3.0 | [unslothai/unsloth](https://github.com/unslothai/unsloth) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 78991 | 2026-11-03 |
| 490 | Axolotl: công cụ tinh chỉnh mô hình AI bằng tệp cấu hình, hỗ trợ nhiều phương pháp (LoRA, DPO, GRPO) và mô hình; README có telemetry bật sẵn, tắt bằng biến môi trường | [axolotl-ai-cloud/axolotl](https://github.com/axolotl-ai-cloud/axolotl) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 12658 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **janhq/jan**, **lobehub/lobehub**, **open-webui/open-webui**, **mozilla-ai/llamafile**: GitHub trả giấy phép NOASSERTION; loại. **nomic-ai/gpt4all**: commit gần nhất 2025-05-27; **lm-sys/FastChat**: 2026-05-01; quá 60 ngày; loại.
- **danny-avila/LibreChat**, **oobabooga/text-generation-webui**, **hiyouga/LLaMA-Factory**: tìm kiếm GitHub không trả kết quả ở thời điểm kiểm tra; chưa đọc.
- **SillyTavern/SillyTavern**: đủ điều kiện nhưng lệch chủ đề (nhập vai), chưa đưa vào nhóm này.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào, chưa có GPU nào để thử; độ khó là đánh giá biên tập.
- Tất cả tuyên bố tốc độ, hiệu năng, tiết kiệm VRAM (exo, vLLM, SGLang, Unsloth) là của README hoặc bên thứ ba, bài không kiểm chứng.
- MLX LM, vLLM, SGLang: README phần đã đọc không nêu giấy phép bằng văn bản (SGLang chỉ có huy hiệu); giấy phép lấy theo GitHub.
- Unsloth: giấy phép kép Apache 2.0 và AGPL-3.0 theo README; Studio theo AGPL-3.0. Axolotl: telemetry bật sẵn theo README, mô tả không thu dữ liệu cá nhân là của README.
- exo: ứng dụng xin quyền thiết lập mạng Thunderbolt cần mật khẩu quản trị; bài chỉ nêu theo README. LocalAI: bản DMG macOS chưa ký theo README.
- Lệnh cài tải từ mạng trong README (LocalAI, Unsloth, exo) không được chép vào bài.

