# Lộ trình 66 — Công cụ kinh doanh tự host

Từ chat nhóm, CRM, hỗ trợ khách hàng đến ERP và chữ ký điện tử; chú ý dữ liệu khách hàng và kế toán nhạy cảm, luật thuế và chữ ký điện tử, cấu hình demo không dùng cho sản xuất và chi phí ngoài phần mềm.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Zulip: ứng dụng chat nhóm mã nguồn mở với luồng hội thoại theo chủ đề (topic) kết hợp ưu điểm của email và chat, tự host hoặc dùng bản đám mây** (key 498, độ khó: Khó) — Chat nhóm theo chủ đề (khó).  
   Repo: [zulip/zulip](https://github.com/zulip/zulip) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
2. **EspoCRM: nền tảng CRM mã nguồn mở viết bằng PHP với giao diện một trang và REST API, tùy biến thực thể, trường, quan hệ; README nêu yêu cầu PHP 8.3–8.5** (key 502, độ khó: Trung bình) — CRM bằng PHP, quen với hosting WordPress (trung bình).  
   Repo: [espocrm/espocrm](https://github.com/espocrm/espocrm) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
3. **Frappe CRM: công cụ CRM mã nguồn mở đơn giản cho đội bán hàng, không giới hạn người dùng, có Kanban và tích hợp Twilio, WhatsApp, ERPNext; README nêu nhánh develop không ổn định** (key 500, độ khó: Khó) — CRM đơn giản; không dùng nhánh develop cho sản xuất (khó).  
   Repo: [frappe/crm](https://github.com/frappe/crm) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
4. **Frappe Helpdesk: công cụ quản lý ticket hỗ trợ khách hàng mã nguồn mở 100%, có cổng cho nhân viên và khách, SLA, quy tắc phân công, cơ sở tri thức** (key 504, độ khó: Khó) — Quản lý ticket hỗ trợ (khó).  
   Repo: [frappe/helpdesk](https://github.com/frappe/helpdesk) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
5. **Dolibarr ERP & CRM: bộ phần mềm mã nguồn mở viết bằng PHP quản lý liên hệ, báo giá, hóa đơn, đơn hàng, kho, nhân sự; có gói cài một cú nhấp cho Windows, Debian và Docker** (key 501, độ khó: Khó) — ERP và CRM nhẹ, có gói cài sẵn (khó).  
   Repo: [Dolibarr/dolibarr](https://github.com/Dolibarr/dolibarr) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
6. **Documenso: công cụ ký tài liệu mã nguồn mở thay thế DocuSign, tự host hoặc dùng dịch vụ; README nói không còn nhận pull request từ bên ngoài và nêu gói Enterprise** (key 503, độ khó: Khó) — Chữ ký điện tử; kiểm tra quy định pháp lý (khó).  
   Repo: [documenso/documenso](https://github.com/documenso/documenso) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
7. **ERPNext: hệ thống ERP mã nguồn mở 100% quản lý kế toán, đơn hàng, sản xuất, tài sản, dự án; README chỉ dẫn demo dùng một lần và dịch vụ Frappe Cloud** (key 499, độ khó: Rất khó) — ERP đầy đủ; cấu hình demo chỉ dùng một lần (rất khó).  
   Repo: [frappe/erpnext](https://github.com/frappe/erpnext) · Bản nháp: `content-drafts/2026-11-03-cong-cu-kinh-doanh/content.json`
