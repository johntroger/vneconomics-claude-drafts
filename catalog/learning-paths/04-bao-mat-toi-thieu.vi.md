# Lộ trình 4 — Bảo mật tối thiểu cho người vibe code

Ba việc đáng làm đầu tiên: không lộ khóa, không dùng thư viện lỗi, biết nguyên tắc cơ bản.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **OWASP Cheat Sheet Series: bảng tóm tắt bảo mật ứng dụng ngắn gọn cho người xây dựng** (key 141, độ khó: Dễ để đọc) — Đọc nguyên tắc cơ bản trước khi nhờ AI viết chức năng nhạy cảm.  
   Repo: [OWASP/CheatSheetSeries](https://github.com/OWASP/CheatSheetSeries) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
2. **dotenvx: mã hóa tệp .env để quản lý biến môi trường an toàn hơn** (key 142, độ khó: Trung bình) — Giữ khóa API trong .env an toàn hơn.  
   Repo: [dotenvx/dotenvx](https://github.com/dotenvx/dotenvx) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
3. **Gitleaks: dò mật khẩu và khóa API lỡ để lại trong mã nguồn** (key 136, độ khó: Trung bình) — Dò khóa lỡ commit; lưu ý trạng thái dự án.  
   Repo: [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
4. **OSV-Scanner: kiểm tra thư viện bạn dùng có lỗ hổng đã được công bố không** (key 140, độ khó: Trung bình) — Kiểm tra thư viện có lỗ hổng đã công bố.  
   Repo: [google/osv-scanner](https://github.com/google/osv-scanner) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
5. **Semgrep: quét mã nguồn để tìm lỗi và lỗ hổng bằng các quy tắc đọc được** (key 138, độ khó: Trung bình) — Quét mã tìm lỗi bảo mật.  
   Repo: [semgrep/semgrep](https://github.com/semgrep/semgrep) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
6. **Trivy: một công cụ quét lỗ hổng, cấu hình sai và bí mật cho ứng dụng và container** (key 139, độ khó: Trung bình) — Quét thêm container và cấu hình khi bắt đầu đóng gói.  
   Repo: [aquasecurity/trivy](https://github.com/aquasecurity/trivy) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
7. **TruffleHog: tìm khóa rò rỉ và kiểm tra khóa nào còn dùng được** (key 137, độ khó: Trung bình đến khó) — Chỉ khi đã lỡ lộ khóa và cần biết khóa nào còn hoạt động.  
   Repo: [trufflesecurity/trufflehog](https://github.com/trufflesecurity/trufflehog) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
8. **Infisical: nền tảng mã nguồn mở để quản lý bí mật, chứng chỉ và quyền truy cập** (key 143, độ khó: Trung bình đến khó) — Khi cả nhóm dùng chung nhiều bí mật.  
   Repo: [Infisical/infisical](https://github.com/Infisical/infisical) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
