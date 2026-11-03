# Lộ trình 91 — Công cụ quy trình của lập trình viên

Từ so sánh mã theo cấu trúc, hệ kiểm soát phiên bản mới, terminal và ghép kênh terminal, môi trường phát triển cô lập đến phát triển vi dịch vụ, tự động hóa phát hành và cập nhật phụ thuộc; chú ý lệnh cài tải tập lệnh từ mạng, web-client mở cổng terminal, bot cần quyền ghi vào kho và việc luôn xem lại thay đổi do công cụ tự tạo.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Difftastic: công cụ so sánh theo cấu trúc, so sánh tệp dựa trên cú pháp thay vì từng dòng, hỗ trợ hơn 30 ngôn ngữ lập trình, dùng được với git; README nêu rõ vấn đề đã biết về hiệu năng và độ vững** (key 682, độ khó: Trung bình) — So sánh mã theo cấu trúc (trung bình).  
   Repo: [Wilfred/difftastic](https://github.com/Wilfred/difftastic) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
2. **Alacritty: trình giả lập terminal hiện đại có mặc định hợp lý nhưng cấu hình sâu, tích hợp với ứng dụng khác thay vì làm lại chức năng, chạy trên BSD, Linux, macOS, Windows; README nêu ở mức beta, giấy phép Apache 2.0** (key 685, độ khó: Trung bình) — Terminal hiệu năng cao (trung bình).  
   Repo: [alacritty/alacritty](https://github.com/alacritty/alacritty) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
3. **Zellij: không gian làm việc cho nhà phát triển và người yêu terminal, thuộc loại chương trình ghép kênh terminal (terminal multiplexer), mặc định dễ dùng, bố cục tự động hóa, đa người dùng, có web-client tích hợp; giấy phép MIT** (key 684, độ khó: Trung bình) — Ghép kênh terminal; chú ý web-client (trung bình).  
   Repo: [zellij-org/zellij](https://github.com/zellij-org/zellij) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
4. **Release Please: tự động hóa tạo CHANGELOG, tạo bản phát hành GitHub và nâng phiên bản bằng cách phân tích lịch sử git theo Conventional Commits và tạo Release PR; không lo xuất bản lên trình quản lý gói; giấy phép Apache 2.0** (key 688, độ khó: Trung bình) — Tự động hóa phát hành (trung bình).  
   Repo: [googleapis/release-please](https://github.com/googleapis/release-please) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
5. **Renovate (Mend Renovate CLI): công cụ cập nhật phụ thuộc tự động, quét tệp gói và tạo yêu cầu gộp khi có phiên bản mới, hơn 90 trình quản lý gói, nhiều nền tảng; có bản đám mây cộng đồng và tự host; giấy phép AGPL-3.0-only** (key 689, độ khó: Trung bình) — Cập nhật phụ thuộc tự động (trung bình).  
   Repo: [renovatebot/renovate](https://github.com/renovatebot/renovate) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
6. **Jujutsu (jj): hệ kiểm soát phiên bản mạnh, dễ dùng, dùng kho Git làm lớp lưu trữ nên tương thích công cụ Git, bản sao làm việc tự động được commit, xung đột có thể ghi trong commit, tự động rebase; README nêu còn thiếu tính năng như submodule** (key 683, độ khó: Trung bình đến khó) — Hệ kiểm soát phiên bản dùng kho Git (trung bình đến khó).  
   Repo: [jj-vcs/jj](https://github.com/jj-vcs/jj) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
7. **Devbox: công cụ dòng lệnh tạo shell cô lập cho phát triển, khai báo danh sách gói và Devbox dựng môi trường riêng cho ứng dụng, dùng Nix bên dưới, hơn 400.000 phiên bản gói từ Nix Package Registry; giấy phép Apache 2.0** (key 686, độ khó: Trung bình đến khó) — Shell phát triển cô lập (trung bình đến khó).  
   Repo: [jetify-com/devbox](https://github.com/jetify-com/devbox) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
8. **Tilt: công cụ phát triển vi dịch vụ, tự động hóa từ thay đổi mã đến tiến trình mới (theo dõi tệp, dựng ảnh container, cập nhật môi trường), giống docker build và kubectl apply hay docker-compose up; README có lệnh cài tải tập lệnh từ mạng** (key 687, độ khó: Rất khó) — Phát triển vi dịch vụ (rất khó).  
   Repo: [tilt-dev/tilt](https://github.com/tilt-dev/tilt) · Bản nháp: `content-drafts/2026-11-03-cong-cu-quy-trinh-lap-trinh-vien/content.json`
