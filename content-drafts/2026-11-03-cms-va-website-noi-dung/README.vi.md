# Nhóm "CMS và website nội dung" — bản nháp 03/11/2026

5 bài, key 172–176, `batch: 29`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.** Viết cho người quen WordPress muốn hiểu các hướng khác (website tĩnh, headless CMS, nền tảng xuất bản).

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 172 | Hugo: tạo website tĩnh nhanh từ các tệp nội dung, không cần cơ sở dữ liệu | [gohugoio/hugo](https://github.com/gohugoio/hugo) | Apache-2.0 | 90327 | 2026-11-02 |
| 173 | Ghost: nền tảng xuất bản và bản tin có thành viên, mã nguồn mở và có dịch vụ host sẵn | [TryGhost/Ghost](https://github.com/TryGhost/Ghost) | MIT | 55658 | 2026-11-03 |
| 174 | Strapi: CMS không đầu (headless) để tạo API nội dung cho website hoặc ứng dụng của bạn | [strapi/strapi](https://github.com/strapi/strapi) | NOASSERTION | 73423 | 2026-11-02 |
| 175 | Payload: CMS và framework full-stack chạy ngay trong ứng dụng Next.js của bạn | [payloadcms/payload](https://github.com/payloadcms/payload) | MIT | 45634 | 2026-11-03 |
| 176 | Decap CMS: trang soạn nội dung cho website tĩnh, lưu thẳng vào Git | [decaporg/decap-cms](https://github.com/decaporg/decap-cms) | MIT | 19460 | 2026-11-01 |

## Điểm cần lưu ý
- **Strapi**: GitHub trả NOASSERTION và README chỉ dẫn tới tệp LICENSE; bài không kết luận giấy phép.
- **Ghost**: README quảng bá dịch vụ Ghost(Pro) trả phí và tuyển dụng; tên Ghost là nhãn hiệu.
- **Decap CMS**: README ngắn, chưa mô tả đăng nhập và phân quyền.
- **Payload**: gắn chặt với Next.js; mẫu triển khai một cú bấm kéo theo dịch vụ có thể tính phí.

## Repo bị loại hoặc cân nhắc
- **pocketbase/pocketbase**: README ghi đầu trang 'The repo has moved to ganigeorgiev.com/pocketbase/pocketbase' và cảnh báo chưa đảm bảo tương thích ngược trước v1.0.0; nguồn chính đã chuyển nên chưa viết bài giới thiệu repo GitHub này.
- **directus/directus** và **withastro/starlight**: README ở gốc repo chỉ là file trỏ ngắn; Directus GitHub trả NOASSERTION; chưa đọc đủ.
- **WordPress/WordPress** và **WordPress/gutenberg**: GitHub trả NOASSERTION; repo WordPress chỉ là bản sao ('Git-ified mirror'); chưa viết.
- **facebook/docusaurus**, **11ty/eleventy**: không tìm được qua tên đã dùng; chưa xác minh.
- **jekyll/jekyll** (commit 2026-10-13), **vuejs/vitepress**, **grav**: đủ điều kiện, chưa ưu tiên.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Nhận định 'Ghost nhỏ hơn hệ sinh thái WordPress' là của biên tập, chưa kiểm chứng.
