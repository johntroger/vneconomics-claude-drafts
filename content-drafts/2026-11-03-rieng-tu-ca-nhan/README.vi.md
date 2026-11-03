# Nhóm "Quyền riêng tư cá nhân" — bản nháp 03/11/2026

6 bài, key 199–204, `batch: 34`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 199 | Vaultwarden: máy chủ quản lý mật khẩu tự host, tương thích ứng dụng Bitwarden (không phải của Bitwarden) | [dani-garcia/vaultwarden](https://github.com/dani-garcia/vaultwarden) | AGPL-3.0 | 70138 | 2026-11-02 |
| 200 | Cryptomator: mã hóa tệp trước khi đưa lên Google Drive, Dropbox hay OneDrive | [cryptomator/cryptomator](https://github.com/cryptomator/cryptomator) | GPL-3.0 | 16426 | 2026-11-02 |
| 201 | age: công cụ mã hóa tệp đơn giản, hiện đại, ít tùy chọn để khỏi cấu hình sai | [FiloSottile/age](https://github.com/FiloSottile/age) | BSD-3-Clause | 24175 | 2026-08-29 |
| 202 | uBlock Origin: chặn quảng cáo và theo dõi trong trình duyệt, và tình trạng trên Chrome | [gorhill/uBlock](https://github.com/gorhill/uBlock) | GPL-3.0 | 69041 | 2026-11-02 |
| 203 | Aegis Authenticator: ứng dụng mã xác thực hai bước cho Android, có mã hóa và sao lưu | [beemdevelopment/Aegis](https://github.com/beemdevelopment/Aegis) | GPL-3.0 | 13450 | 2026-09-06 |
| 204 | Mullvad VPN (ứng dụng): mã nguồn ứng dụng của một dịch vụ VPN, cần phân biệt ứng dụng và dịch vụ | [mullvad/mullvadvpn-app](https://github.com/mullvad/mullvadvpn-app) | GPL-3.0 | 7743 | 2026-11-03 |

## Điểm cần lưu ý
- **uBlock Origin**: README ghi bản này đã bị gỡ khỏi Chrome Web Store ngày 2026-08-31 (mốc Manifest V2); ở Edge nêu việc đổi người đăng tải ở phiên bản 1.64; bài nhắc luôn kiểm tra nhà phát hành.
- **Vaultwarden**: dự án không chính thức, không liên kết với Bitwarden Inc.; tự host kho mật khẩu có rủi ro cao.
- **Cryptomator**: giấy phép hai lớp (GPLv3 và thương mại); mất mật khẩu két là mất dữ liệu.
- **Mullvad**: mã nguồn mở của ứng dụng không chứng minh được chính sách ghi nhật ký của dịch vụ; bài không đánh giá dịch vụ.

## Repo bị loại hoặc cân nhắc
- **keepassxc**, **bitwarden/clients**, **veracrypt**, **personal-security-checklist**, **privacybadger**: GitHub trả NOASSERTION; chưa đọc đủ để kết luận giấy phép.
- **sherlock-project/sherlock**: công cụ tìm tài khoản theo tên người dùng, dễ bị lạm dụng để theo dõi cá nhân; chưa viết.
- **lissy93/web-check**: README không tải được qua đường dẫn đã thử.
- **ente**, **2fauth**, **proton-bridge**: không tìm được qua tên đã dùng.
- **signal-android**, **element-web**: đủ điều kiện, chưa ưu tiên trong lượt này.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Không đánh giá bảo mật độc lập của công cụ nào.

