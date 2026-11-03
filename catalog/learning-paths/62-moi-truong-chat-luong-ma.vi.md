# Lộ trình 62 — Môi trường nhất quán và chất lượng mã

Từ biến môi trường theo thư mục và quản lý phiên bản công cụ đến Git hook, quy ước commit, phát hành và công cụ kiểm tra mã nhanh; chú ý chỉ cho chạy cấu hình từ kho đáng tin và sao lưu cấu hình shell.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **direnv: tiện ích cho shell tự nạp và gỡ biến môi trường theo thư mục hiện tại qua tệp .envrc, có cơ chế bắt buộc cho phép trước khi chạy** (key 476, độ khó: Cơ bản) — Biến môi trường theo thư mục; cơ chế cho phép .envrc (cơ bản).  
   Repo: [direnv/direnv](https://github.com/direnv/direnv) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
2. **mise: quản lý công cụ phát triển, biến môi trường và tác vụ của dự án trong một tệp mise.toml, thay thế nhiều công cụ như nvm, asdf, direnv** (key 475, độ khó: Trung bình) — Quản lý công cụ, biến môi trường, tác vụ trong một tệp (trung bình).  
   Repo: [jdx/mise](https://github.com/jdx/mise) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
3. **Lefthook: trình quản lý Git hook nhanh, một tệp nhị phân không phụ thuộc, chạy lệnh song song, cấu hình bằng lefthook.yml** (key 477, độ khó: Trung bình) — Git hook nhanh (trung bình).  
   Repo: [evilmartians/lefthook](https://github.com/evilmartians/lefthook) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
4. **commitlint: kiểm tra thông điệp commit theo chuẩn Conventional Commits, cấu hình chia sẻ qua npm; README nêu yêu cầu Node.js 22.12+ và không hứa vá bản cũ** (key 479, độ khó: Trung bình) — Kiểm tra thông điệp commit (trung bình).  
   Repo: [conventional-changelog/commitlint](https://github.com/conventional-changelog/commitlint) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
5. **Oxc (Oxidation Compiler): bộ công cụ JavaScript và TypeScript viết bằng Rust hiệu năng cao gồm trình kiểm tra Oxlint, định dạng Oxfmt, parser, transformer, minifier, resolver** (key 480, độ khó: Trung bình) — Kiểm tra và định dạng mã nhanh viết bằng Rust (trung bình).  
   Repo: [oxc-project/oxc](https://github.com/oxc-project/oxc) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
6. **Changesets: công cụ quản lý phiên bản và nhật ký thay đổi cho kho nhiều gói (monorepo); README nói nhánh main là bản phát triển cho v3** (key 478, độ khó: Khó) — Quản lý phiên bản cho nhiều gói; chú ý v2 và v3 (khó).  
   Repo: [changesets/changesets](https://github.com/changesets/changesets) · Bản nháp: `content-drafts/2026-11-03-moi-truong-chat-luong-ma/content.json`
