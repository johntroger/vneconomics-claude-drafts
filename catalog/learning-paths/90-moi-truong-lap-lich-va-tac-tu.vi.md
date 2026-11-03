# Lộ trình 90 — Môi trường, lập lịch và tác tử

Từ quản lý phiên bản Python và môi trường, quản lý dự án, lập lịch tác vụ, pipeline dữ liệu đến khung tác tử AI; chú ý lệnh cài tải tập lệnh từ mạng, bản thử trước phát hành của APScheduler v4, telemetry mặc định, nhờ AI tự chạy mã từ kho ngoài và chi phí gọi mô hình.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **pyenv: quản lý nhiều phiên bản Python đơn giản, đổi phiên bản toàn cục hoặc theo từng dự án, thuần tập lệnh shell, dùng thư mục shims trên PATH; README có lệnh cài tự động tải tập lệnh từ mạng, giấy phép MIT** (key 676, độ khó: Trung bình) — Nhiều phiên bản Python (trung bình).  
   Repo: [pyenv/pyenv](https://github.com/pyenv/pyenv) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
2. **Hatch: trình quản lý dự án Python hiện đại, mở rộng được, có hệ dựng chuẩn hóa với bản dựng tái lập, quản lý môi trường kèm UV, quản lý bản phân phối Python, chạy kiểm thử, phân tích tĩnh, chạy tập lệnh Python, xuất bản lên PyPI và sinh dự án mẫu** (key 675, độ khó: Trung bình) — Quản lý dự án Python (trung bình).  
   Repo: [pypa/hatch](https://github.com/pypa/hatch) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
3. **Mamba: cài đặt lại trình quản lý gói conda bằng C++, tải song song, dùng libsolv giải phụ thuộc nhanh hơn, tương thích với conda; có bản micromamba liên kết tĩnh không phụ thuộc, hợp CI/CD và container; giấy phép BSD-3-Clause** (key 677, độ khó: Trung bình) — conda nhanh hơn (trung bình).  
   Repo: [mamba-org/mamba](https://github.com/mamba-org/mamba) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
4. **APScheduler: bộ lập lịch tác vụ và hệ hàng đợi tác vụ cho Python, dùng riêng như hàng đợi cũng được, có bản đồng bộ và bất đồng bộ, lưu lịch bền vững; README cảnh báo loạt v4.0 chỉ là bản thử trước phát hành, đừng dùng cho sản xuất** (key 678, độ khó: Trung bình) — Lập lịch tác vụ; v4 là bản thử (trung bình).  
   Repo: [agronholm/apscheduler](https://github.com/agronholm/apscheduler) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
5. **Pydantic AI: SDK AI cho Python với vòng lặp tác tử có kiểu, mở rộng được, chuyển đổi mô hình bằng chuỗi, kèm Harness, Evals và Logfire; README có lệnh cài, ví dụ tác tử lập trình dùng shell và lệnh trình hướng dẫn tải từ mạng, bài không chép** (key 679, độ khó: Khó) — SDK tác tử AI có kiểu (khó).  
   Repo: [pydantic/pydantic-ai](https://github.com/pydantic/pydantic-ai) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
6. **Agno: nền tảng tác tử tự vận hành, xây tác tử bằng các SDK, chạy như dịch vụ bền vững trên AgentOS có API và MCP, tự động hóa vận hành công ty với Company OS; README có hướng dẫn nhờ tác tử lập trình tự dựng nền tảng và mục telemetry** (key 681, độ khó: Rất khó) — Nền tảng tác tử; chú ý telemetry (rất khó).  
   Repo: [agno-agi/agno](https://github.com/agno-agi/agno) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
7. **Apache Beam: mô hình hợp nhất định nghĩa pipeline xử lý dữ liệu song song cả lô và luồng, cùng các SDK theo ngôn ngữ (Java, Python, Go) và runner thực thi; README có phần Quick Start cho người mới** (key 680, độ khó: Rất khó) — Pipeline lô và luồng (rất khó).  
   Repo: [apache/beam](https://github.com/apache/beam) · Bản nháp: `content-drafts/2026-11-03-moi-truong-lap-lich-va-tac-tu/content.json`
