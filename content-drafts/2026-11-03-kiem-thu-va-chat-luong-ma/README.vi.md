# Nhóm "Kiểm thử và chất lượng mã" — bản nháp 03/11/2026

5 bài, key 205–209, `batch: 35`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 205 | ESLint: công cụ soát lỗi và quy tắc viết mã JavaScript, thường có sẵn trong dự án do AI dựng | [eslint/eslint](https://github.com/eslint/eslint) | MIT | 27605 | 2026-11-02 |
| 206 | Prettier: tự động dàn mã cho đồng nhất để khỏi tranh cãi về cách trình bày | [prettier/prettier](https://github.com/prettier/prettier) | MIT | 52404 | 2026-11-02 |
| 207 | Ruff: công cụ soát lỗi và định dạng mã Python rất nhanh, gom nhiều công cụ vào một | [astral-sh/ruff](https://github.com/astral-sh/ruff) | MIT | 50403 | 2026-11-03 |
| 208 | Jest: framework kiểm thử JavaScript phổ biến, có chế độ theo dõi và kiểm thử snapshot | [jestjs/jest](https://github.com/jestjs/jest) | MIT | 45471 | 2026-11-02 |
| 209 | Cypress: kiểm thử website như người dùng thật trên trình duyệt, có dịch vụ đám mây trả phí | [cypress-io/cypress](https://github.com/cypress-io/cypress) | MIT | 51018 | 2026-11-03 |

## Điểm cần lưu ý
- **Ruff**: con số 'nhanh gấp 10–100 lần' là tuyên bố của tác giả; do Astral phát triển (cùng hãng với uv).
- **Cypress**: có dịch vụ đám mây trả phí Cypress Cloud; README rất ngắn.
- **ESLint**: README nêu yêu cầu Node.js cụ thể và chính sách hỗ trợ phiên bản (sáu tháng hạn chế cho bản trước).
- **Jest** và **Vitest**: hai lựa chọn tương tự; bài nhắc dự án dùng Vite có thể hợp Vitest hơn.

## Repo bị loại hoặc cân nhắc
- **pytest-dev/pytest**, **renovatebot/renovate**: README.md không tải được qua đường dẫn đã thử; chưa xác minh.
- **typicode/husky**: commit gần nhất 2026-03-19, ít hoạt động; **lefthook**, **biome**, **black**, **msw**, **mockoon**, **dependabot-core**, **sonarqube**: đủ điều kiện, chưa ưu tiên.
- **mypy**, **facebook/jest**: không tìm được qua tên đã dùng.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Nhiều README ngắn, thông tin chính ở tài liệu chưa đọc.

