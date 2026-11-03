# Nhóm "Bảo mật cơ bản cho người vibe code" — bản nháp 03/11/2026

8 bài, key 136–143, `batch: 24`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.** Đây là nhóm hợp với đối tượng của website vì người vibe code hay lỡ để lộ khóa API và dùng nhiều thư viện do AI kéo vào.

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 136 | Gitleaks: dò mật khẩu và khóa API lỡ để lại trong mã nguồn | [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) | MIT | 30609 | 2026-10-28 |
| 137 | TruffleHog: tìm khóa rò rỉ và kiểm tra khóa nào còn dùng được | [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) | AGPL-3.0 | 28822 | 2026-11-03 |
| 138 | Semgrep: quét mã nguồn để tìm lỗi và lỗ hổng bằng các quy tắc đọc được | [semgrep/semgrep](https://github.com/semgrep/semgrep) | LGPL-2.1 | 17415 | 2026-11-03 |
| 139 | Trivy: một công cụ quét lỗ hổng, cấu hình sai và bí mật cho ứng dụng và container | [aquasecurity/trivy](https://github.com/aquasecurity/trivy) | Apache-2.0 | 38919 | 2026-11-02 |
| 140 | OSV-Scanner: kiểm tra thư viện bạn dùng có lỗ hổng đã được công bố không | [google/osv-scanner](https://github.com/google/osv-scanner) | Apache-2.0 | 11370 | 2026-11-03 |
| 141 | OWASP Cheat Sheet Series: bảng tóm tắt bảo mật ứng dụng ngắn gọn cho người xây dựng | [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) | CC-BY-SA-4.0 | 33853 | 2026-11-02 |
| 142 | dotenvx: mã hóa tệp .env để quản lý biến môi trường an toàn hơn | [dotenvx/dotenvx](https://github.com/dotenvx/dotenvx) | BSD-3-Clause | 5871 | 2026-10-30 |
| 143 | Infisical: nền tảng mã nguồn mở để quản lý bí mật, chứng chỉ và quyền truy cập | [Infisical/infisical](https://github.com/Infisical/infisical) | NOASSERTION | 30227 | 2026-11-03 |

## Phát hiện quan trọng khi đọc README
- **Gitleaks**: README ghi công cụ đã 'feature complete', chỉ vá bảo mật, tác giả chuyển sang dự án Betterleaks. Bài nói rõ điều này.
- **TruffleHog**: chức năng xác thực thử đăng nhập bằng bí mật tìm được; bài cảnh báo chỉ dùng với bí mật của chính mình. Giấy phép AGPL-3.0.
- **Semgrep**: README tự nói bản Community bỏ sót nhiều lỗi bảo mật thật; phần thương mại có điều khoản riêng.
- **Infisical**: GitHub trả NOASSERTION vì thư mục ee dùng giấy phép khác; bài giải thích.
- **OWASP Cheat Sheet Series**: README yêu cầu đọc và trích dẫn từ website chính thức, không từ tệp Markdown trong repo.

## Repo bị loại hoặc cân nhắc
- **OWASP/www-project-top-ten**: không có license theo GitHub, commit gần nhất 2025-12-24.
- **bitwarden/server**: GitHub trả NOASSERTION; là backend, ít hợp người mới; chưa đọc.
- **getsops/sops**: không tải được README qua nhánh `main`; chưa xác minh nên chưa viết.
- **OWASP/ASVS**: là tiêu chuẩn kiểm tra đầy đủ, nặng so với đối tượng người mới.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Một số README rất dài, chỉ đọc phần đầu và các mục chính.
- Chưa kiểm tra giá dịch vụ thương mại (Semgrep AppSec, Infisical Cloud/Enterprise, TruffleHog Enterprise).
- `category` và `need` gán về nhãn có sẵn trên site; nhóm này có thể xứng đáng một category riêng (ví dụ "Bảo mật cơ bản"), do chủ site quyết định.
