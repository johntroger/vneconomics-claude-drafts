# Lộ trình 20 — Quy trình tự động và phát hành an toàn

Từ chạy thử quy trình cục bộ đến phát hành có kiểm soát, thông báo và kiểm tra liên kết.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **act: chạy thử quy trình GitHub Actions ngay trên máy để khỏi commit lên rồi mới biết lỗi** (key 228, độ khó: Trung bình) — Chạy thử GitHub Actions cục bộ.  
   Repo: [nektos/act](https://github.com/nektos/act) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
2. **zizmor: soát lỗi bảo mật trong quy trình GitHub Actions trước khi bị khai thác** (key 232, độ khó: Trung bình đến khó) — Soát lỗi bảo mật trong workflow.  
   Repo: [zizmorcore/zizmor](https://github.com/zizmorcore/zizmor) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
3. **Gitleaks: dò mật khẩu và khóa API lỡ để lại trong mã nguồn** (key 136, độ khó: Trung bình) — Chặn khóa bí mật lọt vào kho.  
   Repo: [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
4. **git-cliff: tự tạo nhật ký thay đổi (changelog) từ lịch sử Git** (key 229, độ khó: Trung bình) — Changelog từ lịch sử commit.  
   Repo: [orhun/git-cliff](https://github.com/orhun/git-cliff) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
5. **semantic-release: tự động hóa cả quy trình phát hành, từ số phiên bản đến đăng gói** (key 230, độ khó: Khó) — Tự động hóa cả phát hành (khó, cẩn thận).  
   Repo: [semantic-release/semantic-release](https://github.com/semantic-release/semantic-release) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
6. **ntfy: gửi thông báo tới điện thoại hoặc máy tính từ script bằng một lệnh HTTP** (key 231, độ khó: Dễ đến trung bình) — Thông báo về điện thoại khi việc xong.  
   Repo: [binwiederhier/ntfy](https://github.com/binwiederhier/ntfy) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
7. **lychee: quét liên kết hỏng trong website và tài liệu Markdown rất nhanh** (key 233, độ khó: Trung bình) — Kiểm tra liên kết hỏng trong tài liệu và website.  
   Repo: [lycheeverse/lychee](https://github.com/lycheeverse/lychee) · Bản nháp: `content-drafts/2026-11-03-ci-cd-va-tu-dong-hoa-git/content.json`
