# Nhóm "Hiểu công nghệ web mà AI hay dùng" — bản nháp 03/11/2026

9 bài, key 144–152, `batch: 25`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.** Mục tiêu: giúp người vibe code nhận ra và hiểu các tên công nghệ xuất hiện trong dự án web do AI dựng.

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 144 | Next.js: framework web full-stack mà AI hay chọn khi dựng ứng dụng bằng React | [vercel/next.js](https://github.com/vercel/next.js) | MIT | 143238 | 2026-11-03 |
| 145 | Tailwind CSS: cách tạo kiểu giao diện bằng các lớp ngắn mà mã AI hay dùng | [tailwindlabs/tailwindcss](https://github.com/tailwindlabs/tailwindcss) | MIT | 98054 | 2026-11-02 |
| 146 | Vite: công cụ chạy thử và đóng gói dự án web nhanh, nền của nhiều dự án AI dựng | [vitejs/vite](https://github.com/vitejs/vite) | MIT | 83681 | 2026-11-02 |
| 147 | TypeScript: lớp kiểm tra kiểu giúp bắt lỗi trong mã JavaScript do AI viết | [microsoft/TypeScript](https://github.com/microsoft/TypeScript) | Apache-2.0 | 111723 | 2026-11-03 |
| 148 | Playwright: tự động kiểm thử và điều khiển trình duyệt, cả cho coding agent | [microsoft/playwright](https://github.com/microsoft/playwright) | Apache-2.0 | 99145 | 2026-11-03 |
| 149 | Astro: framework cho website nội dung (blog, giới thiệu, tài liệu) tải nhanh | [withastro/astro](https://github.com/withastro/astro) | NOASSERTION | 63680 | 2026-11-02 |
| 150 | Zod: kiểm tra dữ liệu từ bên ngoài có đúng dạng mong đợi, thường gặp trong mã TypeScript | [colinhacks/zod](https://github.com/colinhacks/zod) | MIT | 44246 | 2026-10-30 |
| 151 | Drizzle ORM: nói chuyện với cơ sở dữ liệu bằng TypeScript theo kiểu gần với SQL | [drizzle-team/drizzle-orm](https://github.com/drizzle-team/drizzle-orm) | Apache-2.0 | 36207 | 2026-11-03 |
| 152 | Vitest: viết bài kiểm thử nhỏ để biết mã AI viết có chạy đúng không | [vitest-dev/vitest](https://github.com/vitest-dev/vitest) | MIT | 17322 | 2026-11-03 |

## Cách lấy dữ liệu
Nhiều README của nhóm này rất ngắn hoặc chỉ là file trỏ (Next.js, Zod, Tailwind CSS, Vite), nên ngoài README còn đọc tài liệu chính thức bằng WebFetch (ghi trong `docsRead`): nextjs.org/docs, tailwindcss.com/docs/installation, vite.dev/guide, typescriptlang.org (TypeScript in 5 minutes), playwright.dev/docs/intro, docs.astro.build (Why Astro), zod.dev, orm.drizzle.team/docs/overview, vitest.dev/guide. Các tóm tắt tài liệu do công cụ WebFetch (mô hình nhỏ) tạo; cần đối chiếu lại bản gốc nếu dùng số liệu cụ thể (phiên bản Node.js, yêu cầu hệ thống).

## Repo bị loại hoặc cân nhắc
- **facebook/react**, **prisma/prisma**: không tìm được qua tên đã dùng trong tìm kiếm GitHub; chưa xác minh nên chưa viết.
- **nodejs/node**, **oven-sh/bun**: GitHub trả NOASSERTION (giấy phép phức hợp), chưa đọc kỹ nên chưa viết.
- Svelte, Hono, tRPC, TanStack Query, pnpm, Biome, Deno, Express: đủ điều kiện nhưng chưa ưu tiên; có thể làm đợt sau.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài.
- Yêu cầu phiên bản Node.js và hệ điều hành của Vite, Vitest, Playwright lấy từ trang tài liệu ngày 2026-11-03 và sẽ đổi theo thời gian.
- Astro: GitHub trả NOASSERTION, README ghi MIT; chưa đối chiếu giấy phép từng gói.
