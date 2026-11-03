# Lộ trình 43 — Công cụ API, ảnh, PDF và OCR cho người làm web

Thử API, xử lý ảnh, tạo PDF, nhận dạng chữ và điều khiển trình duyệt; thử trên bản sao tệp và không mở dịch vụ ra mạng khi chưa bảo vệ.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Hoppscotch: hệ sinh thái phát triển API mã nguồn mở nhẹ, gửi yêu cầu và xem phản hồi ngay, có tự host** (key 354, độ khó: Dễ đến trung bình) — Thử API nhanh trên web.  
   Repo: [hoppscotch/hoppscotch](https://github.com/hoppscotch/hoppscotch) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
2. **Bruno: ứng dụng khách API mã nguồn mở lưu bộ sưu tập ngay trong thư mục, làm việc ngoại tuyến và cộng tác bằng Git** (key 353, độ khó: Trung bình) — Thử API và lưu bộ sưu tập trong Git.  
   Repo: [usebruno/bruno](https://github.com/usebruno/bruno) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
3. **sharp: thư viện Node.js xử lý ảnh tốc độ cao, co ảnh lớn thành JPEG, PNG, WebP, GIF, AVIF thân thiện web** (key 355, độ khó: Trung bình) — Co ảnh cho web bằng Node.js.  
   Repo: [lovell/sharp](https://github.com/lovell/sharp) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
4. **libvips: thư viện xử lý ảnh chạy nhanh và tốn ít bộ nhớ, nền của nhiều công cụ như sharp** (key 356, độ khó: Khó) — Động cơ xử lý ảnh bên dưới (khó).  
   Repo: [libvips/libvips](https://github.com/libvips/libvips) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
5. **Tesseract: động cơ nhận dạng chữ OCR mã nguồn mở hỗ trợ hơn 100 ngôn ngữ, không có giao diện đồ họa** (key 359, độ khó: Khó) — Động cơ OCR (khó).  
   Repo: [tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
6. **OCRmyPDF: thêm lớp chữ tìm kiếm được vào PDF quét, giữ nguyên ảnh gốc, dùng Tesseract nhận dạng hơn 100 ngôn ngữ** (key 358, độ khó: Khá khó) — Làm PDF quét tìm kiếm được (khá khó).  
   Repo: [ocrmypdf/OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
7. **Gotenberg: API chạy bằng Docker chuyển HTML, URL và tệp Office sang PDF, gộp, tách và đóng dấu PDF** (key 357, độ khó: Khó) — API tạo PDF bằng Docker (khó).  
   Repo: [gotenberg/gotenberg](https://github.com/gotenberg/gotenberg) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
8. **Puppeteer: thư viện JavaScript điều khiển Chrome hoặc Firefox không giao diện qua DevTools Protocol hoặc WebDriver BiDi** (key 360, độ khó: Trung bình đến khó) — Điều khiển trình duyệt bằng mã.  
   Repo: [puppeteer/puppeteer](https://github.com/puppeteer/puppeteer) · Bản nháp: `content-drafts/2026-11-03-api-anh-pdf-va-ocr/content.json`
