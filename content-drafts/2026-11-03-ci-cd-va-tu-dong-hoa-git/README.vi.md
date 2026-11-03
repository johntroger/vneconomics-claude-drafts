# Nhóm "CI/CD và tự động hóa Git" — bản nháp 03/11/2026

6 bài, key 228–233, `batch: 39`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 228 | act: chạy thử quy trình GitHub Actions ngay trên máy để khỏi commit lên rồi mới biết lỗi | [nektos/act](https://github.com/nektos/act) | MIT | 72522 | 2026-11-03 |
| 229 | git-cliff: tự tạo nhật ký thay đổi (changelog) từ lịch sử Git | [orhun/git-cliff](https://github.com/orhun/git-cliff) | Apache-2.0 | 12354 | 2026-11-02 |
| 230 | semantic-release: tự động hóa cả quy trình phát hành, từ số phiên bản đến đăng gói | [semantic-release/semantic-release](https://github.com/semantic-release/semantic-release) | MIT | 24151 | 2026-10-31 |
| 231 | ntfy: gửi thông báo tới điện thoại hoặc máy tính từ script bằng một lệnh HTTP | [binwiederhier/ntfy](https://github.com/binwiederhier/ntfy) | Apache-2.0 | 35254 | 2026-11-03 |
| 232 | zizmor: soát lỗi bảo mật trong quy trình GitHub Actions trước khi bị khai thác | [zizmorcore/zizmor](https://github.com/zizmorcore/zizmor) | MIT | 6861 | 2026-11-02 |
| 233 | lychee: quét liên kết hỏng trong website và tài liệu Markdown rất nhanh | [lycheeverse/lychee](https://github.com/lycheeverse/lychee) | Apache-2.0 | 4085 | 2026-11-02 |

## Điểm cần lưu ý
- **ntfy**: README nói gửi thông báo không cần đăng ký; bài nhắc chủ đề cần được giữ kín và không đưa dữ liệu nhạy cảm (suy luận biên tập, chưa đọc tài liệu kiểm soát truy cập). Gói Pro trả phí của tác giả (README nêu từ 5 USD/tháng).
- **semantic-release**: tự động đăng gói nên cấu hình sai có thể phát hành bản sai; bài xếp mức Khó.
- **act**: cần Docker; kết quả cục bộ có thể khác môi trường GitHub (suy luận, chưa kiểm chứng).
- **zizmor** và **lychee**: README ngắn hoặc rất dài, chỉ đọc phần đầu và các mục chính.

## Repo bị loại hoặc cân nhắc
- **pre-commit/pre-commit**: README chỉ vài dòng dẫn sang pre-commit.com; chưa đọc đủ.
- **gotify/server**: GitHub trả NOASSERTION; **hadolint**: GPL-3.0 nhưng nhắm Docker nâng cao.
- **lazydocker** (commit cuối 2026-04-19), **actionlint** (2026-07-16): ít hoạt động hơn.
- **commitlint**, **release-please**, **super-linter**, **dive**: đủ điều kiện, chưa ưu tiên.
- **home-assistant/core**: lớn và nằm ngoài chủ đề lượt này; có thể làm riêng.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài.

