# Lộ trình 59 — Cơ sở dữ liệu chuyên biệt

Từ SQLite mở rộng và có quản lý phiên bản đến chuỗi thời gian, API GraphQL tự sinh và phân mảnh quy mô lớn; chú ý số liệu hiệu năng của hãng, cổng mở ra Internet và việc có thật sự cần quy mô đó không.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **libSQL: bản fork mã nguồn mở của SQLite có bản sao nhúng và truy cập từ xa; README khuyên dự án mới xem Turso viết lại bằng Rust** (key 458, độ khó: Khó) — Fork SQLite; README khuyên xem Turso cho dự án mới (khó).  
   Repo: [tursodatabase/libsql](https://github.com/tursodatabase/libsql) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
2. **Dolt: cơ sở dữ liệu SQL có thể fork, clone, branch, merge như Git, kết nối như MySQL** (key 457, độ khó: Khó) — Cơ sở dữ liệu có nhánh và gộp như Git (khó).  
   Repo: [dolthub/dolt](https://github.com/dolthub/dolt) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
3. **rqlite: cơ sở dữ liệu quan hệ phân tán chịu lỗi xây trên SQLite, một tệp nhị phân, API HTTP** (key 459, độ khó: Khó) — SQLite chịu lỗi qua cụm (khó).  
   Repo: [rqlite/rqlite](https://github.com/rqlite/rqlite) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
4. **QuestDB: cơ sở dữ liệu chuỗi thời gian mã nguồn mở độ trễ thấp, SQL mở rộng cho chuỗi thời gian; README có số liệu benchmark của hãng và bản Enterprise trả phí** (key 460, độ khó: Khó) — Chuỗi thời gian; số liệu benchmark là của hãng (khó).  
   Repo: [questdb/questdb](https://github.com/questdb/questdb) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
5. **Hasura GraphQL Engine: một điểm cuối API GraphQL an toàn tới nhiều nguồn dữ liệu; kho có hai phiên bản V2 ổn định và V3 (DDN)** (key 461, độ khó: Rất khó) — API GraphQL tự sinh; phân quyền cẩn thận (rất khó).  
   Repo: [hasura/graphql-engine](https://github.com/hasura/graphql-engine) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
6. **Vitess: hệ cơ sở dữ liệu phân tán mở rộng ngang xây trên MySQL, từng là thành phần cốt lõi hạ tầng dữ liệu của YouTube** (key 462, độ khó: Rất khó) — Phân mảnh MySQL quy mô rất lớn, hiếm khi cần (rất khó).  
   Repo: [vitessio/vitess](https://github.com/vitessio/vitess) · Bản nháp: `content-drafts/2026-11-03-csdl-chuyen-biet/content.json`
