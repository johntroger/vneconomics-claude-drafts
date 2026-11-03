# Lộ trình 89 — Công cụ Python hiện đại

Từ quản lý gói và phụ thuộc, định dạng mã, ghi log, viết lớp gọn đến giao diện terminal; chú ý lệnh cài tải tập lệnh từ mạng, cảnh báo diagnose của Loguru làm lộ dữ liệu nhạy cảm, so sánh do chính dự án viết và việc công cụ tự sửa mã.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Black: trình định dạng mã Python 'không khoan nhượng', bạn từ bỏ việc chỉnh định dạng bằng tay để đổi lấy tốc độ, tính xác định và thoát khỏi lời nhắc của pycodestyle; tạo bản khác biệt nhỏ nhất, giấy phép MIT** (key 669, độ khó: Dễ đến trung bình) — Định dạng mã tự động (dễ đến trung bình).  
   Repo: [psf/black](https://github.com/psf/black) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
2. **Loguru: thư viện ghi log dễ chịu cho Python, dùng ngay không cần cấu hình dài, một hàm thay cho handler, formatter, filter; xoay vòng, lưu giữ, nén tệp log; README cảnh báo diagnose=True mặc định có thể làm lộ dữ liệu nhạy cảm** (key 671, độ khó: Dễ) — Ghi log dễ chịu; chú ý diagnose (dễ).  
   Repo: [Delgan/loguru](https://github.com/Delgan/loguru) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
3. **attrs: gói Python mang lại niềm vui viết lớp bằng cách làm thay các phương thức đặc biệt, giúp viết phần mềm ngắn gọn và đúng mà không làm chậm mã; README có ví dụ bộ trang trí define và phần dành cho doanh nghiệp** (key 672, độ khó: Trung bình) — Viết lớp gọn (trung bình).  
   Repo: [python-attrs/attrs](https://github.com/python-attrs/attrs) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
4. **Poetry: công cụ đóng gói và quản lý phụ thuộc cho Python, thay setup.py, requirements.txt, setup.cfg, MANIFEST.in và Pipfile bằng một tệp pyproject.toml, có nhóm phụ thuộc, tập lệnh và khóa phiên bản** (key 668, độ khó: Trung bình) — Đóng gói và phụ thuộc (trung bình).  
   Repo: [python-poetry/poetry](https://github.com/python-poetry/poetry) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
5. **PDM: trình quản lý gói và phụ thuộc Python hiện đại hỗ trợ các chuẩn PEP mới nhất, bộ giải phụ thuộc nhanh, hệ plugin, tập lệnh người dùng, cài Python bằng python-build-standalone; README có so sánh với Pipenv, Poetry và Hatch** (key 673, độ khó: Trung bình) — Quản lý gói theo chuẩn PEP mới (trung bình).  
   Repo: [pdm-project/pdm](https://github.com/pdm-project/pdm) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
6. **Pixi: trình quản lý gói và công cụ quy trình đa nền tảng đa ngôn ngữ xây trên hệ sinh thái conda, có tệp khóa luôn cập nhật, giao diện dòng lệnh kiểu Cargo, viết bằng Rust; README có lệnh cài tải tập lệnh từ mạng** (key 674, độ khó: Trung bình) — Quản lý gói đa ngôn ngữ dựa trên conda (trung bình).  
   Repo: [prefix-dev/pixi](https://github.com/prefix-dev/pixi) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
7. **Textual: framework xây giao diện đa nền tảng bằng API Python đơn giản, chạy ứng dụng trong terminal hoặc trình duyệt web, kết hợp Python hiện đại với tinh hoa của web, có bộ thành phần, bảng lệnh và bảng điều khiển dev** (key 670, độ khó: Trung bình) — Giao diện trong terminal bằng Python (trung bình).  
   Repo: [Textualize/textual](https://github.com/Textualize/textual) · Bản nháp: `content-drafts/2026-11-03-cong-cu-python-hien-dai/content.json`
