# Lộ trình 16 — Kiểm thử và giữ chất lượng mã khi có AI viết

Lưới an toàn khi AI sửa mã: định dạng, soát lỗi, kiểm thử từng hàm và kiểm thử luồng người dùng.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Prettier: tự động dàn mã cho đồng nhất để khỏi tranh cãi về cách trình bày** (key 206, độ khó: Dễ đến trung bình) — Định dạng mã đồng nhất.  
   Repo: [prettier/prettier](https://github.com/prettier/prettier) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-chat-luong-ma/content.json`
2. **ESLint: công cụ soát lỗi và quy tắc viết mã JavaScript, thường có sẵn trong dự án do AI dựng** (key 205, độ khó: Trung bình) — Soát lỗi JavaScript và TypeScript.  
   Repo: [eslint/eslint](https://github.com/eslint/eslint) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-chat-luong-ma/content.json`
3. **Ruff: công cụ soát lỗi và định dạng mã Python rất nhanh, gom nhiều công cụ vào một** (key 207, độ khó: Trung bình) — Soát lỗi và định dạng Python.  
   Repo: [astral-sh/ruff](https://github.com/astral-sh/ruff) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-chat-luong-ma/content.json`
4. **Vitest: viết bài kiểm thử nhỏ để biết mã AI viết có chạy đúng không** (key 152, độ khó: Trung bình) — Kiểm thử đơn vị cho dự án dùng Vite.  
   Repo: [vitest-dev/vitest](https://github.com/vitest-dev/vitest) · Bản nháp: `content-drafts/2026-11-03-cong-nghe-web-ai-hay-dung/content.json`
5. **Jest: framework kiểm thử JavaScript phổ biến, có chế độ theo dõi và kiểm thử snapshot** (key 208, độ khó: Trung bình) — Kiểm thử đơn vị JavaScript phổ biến.  
   Repo: [jestjs/jest](https://github.com/jestjs/jest) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-chat-luong-ma/content.json`
6. **Playwright: tự động kiểm thử và điều khiển trình duyệt, cả cho coding agent** (key 148, độ khó: Trung bình) — Kiểm thử luồng người dùng, có thể cho agent.  
   Repo: [microsoft/playwright](https://github.com/microsoft/playwright) · Bản nháp: `content-drafts/2026-11-03-cong-nghe-web-ai-hay-dung/content.json`
7. **Cypress: kiểm thử website như người dùng thật trên trình duyệt, có dịch vụ đám mây trả phí** (key 209, độ khó: Trung bình) — Kiểm thử luồng người dùng bằng Cypress.  
   Repo: [cypress-io/cypress](https://github.com/cypress-io/cypress) · Bản nháp: `content-drafts/2026-11-03-kiem-thu-va-chat-luong-ma/content.json`
8. **Gitleaks: dò mật khẩu và khóa API lỡ để lại trong mã nguồn** (key 136, độ khó: Trung bình) — Chặn khóa bí mật lỡ commit.  
   Repo: [gitleaks/gitleaks](https://github.com/gitleaks/gitleaks) · Bản nháp: `content-drafts/2026-11-03-bao-mat-co-ban/content.json`
