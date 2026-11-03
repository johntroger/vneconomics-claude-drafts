# Nhóm "Công cụ dòng lệnh và môi trường làm việc" — bản nháp 03/11/2026

7 bài, key 153–159, `batch: 26`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 153 | tldr pages: hướng dẫn lệnh dòng lệnh bằng ví dụ ngắn thay cho trang man dài | [tldr-pages/tldr](https://github.com/tldr-pages/tldr) | NOASSERTION | 64109 | 2026-11-03 |
| 154 | Visual Studio Code: trình soạn mã phổ biến và điều cần biết về 'Code - OSS' so với bản của Microsoft | [microsoft/vscode](https://github.com/microsoft/vscode) | MIT | 194514 | 2026-11-03 |
| 155 | GitHub CLI (gh): dùng GitHub bằng dòng lệnh, kể cả cho coding agent | [cli/cli](https://github.com/cli/cli) | MIT | 46848 | 2026-11-03 |
| 156 | lazygit: giao diện trong terminal giúp thao tác git bằng phím thay vì nhớ lệnh | [jesseduffield/lazygit](https://github.com/jesseduffield/lazygit) | MIT | 83617 | 2026-10-31 |
| 157 | uv: công cụ quản lý Python và thư viện Python nhanh, thay cho nhiều công cụ rời rạc | [astral-sh/uv](https://github.com/astral-sh/uv) | Apache-2.0 | 91485 | 2026-11-03 |
| 158 | nvm: chuyển đổi giữa các phiên bản Node.js, và điều người dùng Windows cần biết | [nvm-sh/nvm](https://github.com/nvm-sh/nvm) | MIT | 95740 | 2026-11-03 |
| 159 | Windows Terminal: cửa sổ dòng lệnh hiện đại cho người dùng Windows | [microsoft/terminal](https://github.com/microsoft/terminal) | MIT | 105315 | 2026-11-02 |

## Điểm cần lưu ý
- **VS Code**: repo là 'Code - OSS'; sản phẩm Visual Studio Code phát hành theo giấy phép sản phẩm riêng của Microsoft. Bài nói rõ.
- **nvm**: chính thức dành cho shell kiểu POSIX; Windows thuần cần dự án khác (nvm-windows). Bài nói rõ, chưa đánh giá nvm-windows.
- **tldr-pages**: GitHub trả NOASSERTION; README ghi CC BY 4.0 cho nội dung.
- **uv**: số liệu 'nhanh gấp 10–100 lần pip' là của tác giả.

## Repo bị loại hoặc cân nhắc
- **git/git**: là bản sao chỉ đọc của mã nguồn, license NOASSERTION; không phù hợp bài giới thiệu.
- **ohmyzsh/ohmyzsh**, **fzf**, **ripgrep**: đủ điều kiện nhưng nhắm người dùng terminal có kinh nghiệm; có thể làm đợt sau. ripgrep đã đọc README (MIT hoặc Unlicense).
- **devcontainers/spec**: là đặc tả, ít hoạt động hơn (commit 2026-03-20).

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. README của nvm và lazygit rất dài, chỉ đọc phần đầu và các mục chính.
