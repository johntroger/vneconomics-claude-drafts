# Lộ trình 33 — Thư viện Python thường gặp khi AI viết mã

Gọi API, kiểm tra dữ liệu, viết công cụ dòng lệnh và kiểm thử: những thư viện hay xuất hiện trong mã do AI sinh.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **requests: thư viện Python gọi API và tải trang web chỉ bằng vài dòng, quen thuộc với mọi người học Python** (key 297, độ khó: Dễ đến trung bình) — Gọi API, dễ nhất.  
   Repo: [psf/requests](https://github.com/psf/requests) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
2. **pytest: viết kiểm thử Python ngắn gọn bằng câu lệnh assert thường, khi AI viết mã thì kiểm thử giúp bạn tin được mã** (key 302, độ khó: Trung bình) — Kiểm tra mã bằng test; tự đọc test do AI viết.  
   Repo: [pytest-dev/pytest](https://github.com/pytest-dev/pytest) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
3. **Pydantic: kiểm tra và làm sạch dữ liệu trong Python bằng chú thích kiểu, nền tảng của nhiều ứng dụng AI và API** (key 301, độ khó: Trung bình) — Kiểm tra dữ liệu bằng chú thích kiểu.  
   Repo: [pydantic/pydantic](https://github.com/pydantic/pydantic) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
4. **Click: bộ công cụ tạo giao diện dòng lệnh cho Python, ghép lệnh lồng nhau và tự sinh trang trợ giúp** (key 300, độ khó: Trung bình) — Công cụ dòng lệnh bằng decorator.  
   Repo: [pallets/click](https://github.com/pallets/click) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
5. **Typer: tạo chương trình dòng lệnh bằng Python chỉ với vài dòng, dựa trên chú thích kiểu, 'FastAPI của CLI'** (key 299, độ khó: Trung bình) — Công cụ dòng lệnh bằng chú thích kiểu.  
   Repo: [fastapi/typer](https://github.com/fastapi/typer) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
6. **HTTPX: ứng dụng khách HTTP đầy đủ cho Python, có async, HTTP/2 và dòng lệnh, API tương thích requests** (key 298, độ khó: Trung bình) — Gọi API async và HTTP/2 (khi cần).  
   Repo: [encode/httpx](https://github.com/encode/httpx) · Bản nháp: `content-drafts/2026-11-03-thu-vien-python-cho-nguoi-moi/content.json`
