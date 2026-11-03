# Nhóm "Vector database và đánh giá LLM" — bản nháp 03/11/2026

4 bài, key 420–423, `batch: 72`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 420 | Chroma: cơ sở dữ liệu vector mã nguồn mở cho ứng dụng AI, API cốt lõi chỉ 4 hàm, có dịch vụ đám mây trả phí | [chroma-core/chroma](https://github.com/chroma-core/chroma) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 29624 | 2026-10-30 |
| 421 | Qdrant: công cụ tìm kiếm vector viết bằng Rust, có bản Edge chạy trong ứng dụng; README cảnh báo lệnh Docker mẫu không có xác thực | [qdrant/qdrant](https://github.com/qdrant/qdrant) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 35399 | 2026-11-02 |
| 422 | Milvus: cơ sở dữ liệu vector phân tán dưới LF AI & Data, có chế độ Standalone và Milvus Lite cho người mới | [milvus-io/milvus](https://github.com/milvus-io/milvus) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 46570 | 2026-11-03 |
| 423 | promptfoo: công cụ dòng lệnh đánh giá và kiểm thử đối kháng (red teaming) ứng dụng LLM, chạy cục bộ; README nói dự án nay thuộc OpenAI | [promptfoo/promptfoo](https://github.com/promptfoo/promptfoo) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 26770 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **langfuse/langfuse**, **BerriAI/litellm**, **pgvector/pgvector**, **weaviate/weaviate**: GitHub trả giấy phép NOASSERTION (không nhận diện được SPDX); loại để giữ quy tắc giấy phép rõ ràng, có thể làm sau sau khi đọc tệp LICENSE.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập.
- Chroma: 5 USD tín dụng và các mô tả 'nhanh, tiết kiệm' là của README. Qdrant: README cảnh báo lệnh Docker mẫu không xác thực; benchmark là của tác giả.
- Milvus: README rất dài, bài chỉ đọc phần giới thiệu và Why Milvus; quy mô 'hàng tỷ vector' là tuyên bố của README.
- promptfoo: README nói dự án nay thuộc OpenAI; 'hơn 10 triệu người dùng' là tuyên bố của README.

