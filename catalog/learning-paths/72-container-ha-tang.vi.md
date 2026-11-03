# Lộ trình 72 — Container và hạ tầng

Từ máy chủ web, ảnh container, máy ảo cho container và tự động hóa giao phần mềm đến hạ tầng dưới dạng mã và cổng API; chú ý tài nguyên đám mây tốn tiền, cổng quản trị, socket Docker và bản trả phí.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **NGINX: máy chủ web, cân bằng tải, reverse proxy, API gateway và bộ nhớ đệm nội dung; README có phần giới thiệu cho người mới về mô-đun, cấu hình, tiến trình, SSL, cân bằng tải, giới hạn tốc độ, giấy phép BSD 2 điều khoản** (key 541, độ khó: Khó) — Máy chủ web và reverse proxy; cài từ gói chính thức (khó).  
   Repo: [nginx/nginx](https://github.com/nginx/nginx) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
2. **Lima (Linux Machines): chạy máy ảo Linux có chia sẻ tệp và chuyển tiếp cổng tự động, kiểu WSL2, để dùng container (containerd/nerdctl, Docker, Podman, Kubernetes) trên macOS và các hệ khác** (key 542, độ khó: Trung bình) — Máy ảo Linux cho container trên Mac (trung bình).  
   Repo: [lima-vm/lima](https://github.com/lima-vm/lima) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
3. **dive: công cụ khám phá ảnh Docker/OCI theo từng lớp, tìm cách giảm dung lượng; README ghi chất lượng beta và có chế độ CI** (key 543, độ khó: Trung bình) — Phân tích lớp ảnh Docker; chất lượng beta (trung bình).  
   Repo: [wagoodman/dive](https://github.com/wagoodman/dive) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
4. **Moby: dự án mã nguồn mở do Docker tạo ra, bộ khối dựng container (công cụ dựng, đăng ký, điều phối, runtime); README nói không phải nơi hỗ trợ sản phẩm Docker và mô-đun Go github.com/docker/docker đã lỗi thời từ Docker v29** (key 540, độ khó: Rất khó) — Dự án nguồn của Docker, dành cho kỹ sư (rất khó).  
   Repo: [moby/moby](https://github.com/moby/moby) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
5. **Dagger: nền tảng tự động hóa giao phần mềm lập trình được, chạy cục bộ, trên CI hoặc đám mây, SDK cho 8 ngôn ngữ, mọi thao tác chạy trong container và phát dấu vết OpenTelemetry** (key 544, độ khó: Rất khó) — Quy trình CI bằng mã (rất khó).  
   Repo: [dagger/dagger](https://github.com/dagger/dagger) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
6. **Pulumi: hạ tầng dưới dạng mã bằng ngôn ngữ lập trình bạn quen, triển khai lên AWS, Azure, Google Cloud, Kubernetes và hơn 300 nhà cung cấp; tạo tài nguyên đám mây thật có thể tốn tiền** (key 545, độ khó: Rất khó) — Hạ tầng dưới dạng mã; tốn phí đám mây (rất khó).  
   Repo: [pulumi/pulumi](https://github.com/pulumi/pulumi) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
7. **Kong Gateway: cổng API, LLM và MCP cloud-native mở rộng bằng plugin, định tuyến, cân bằng tải, xác thực; README có bản đám mây Kong Konnect trả phí** (key 546, độ khó: Rất khó) — Cổng API, LLM và MCP; bảo vệ cổng quản trị (rất khó).  
   Repo: [Kong/kong](https://github.com/Kong/kong) · Bản nháp: `content-drafts/2026-11-03-container-ha-tang/content.json`
