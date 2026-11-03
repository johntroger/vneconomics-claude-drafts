# Nhóm "Container và hạ tầng" — bản nháp 03/11/2026

7 bài, key 540–546, `batch: 91`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 540 | Moby: dự án mã nguồn mở do Docker tạo ra, bộ khối dựng container (công cụ dựng, đăng ký, điều phối, runtime); README nói không phải nơi hỗ trợ sản phẩm Docker và mô-đun Go github.com/docker/docker đã lỗi thời từ Docker v29 | [moby/moby](https://github.com/moby/moby) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 72240 | 2026-11-03 |
| 541 | NGINX: máy chủ web, cân bằng tải, reverse proxy, API gateway và bộ nhớ đệm nội dung; README có phần giới thiệu cho người mới về mô-đun, cấu hình, tiến trình, SSL, cân bằng tải, giới hạn tốc độ, giấy phép BSD 2 điều khoản | [nginx/nginx](https://github.com/nginx/nginx) | {'key': 'bsd-2-clause', 'name': 'BSD 2-Clause "Simplified" License', 'spdx_id': 'BSD-2-Clause', 'url': 'https://api.github.com/licenses/bsd-2-clause', 'node_id': 'MDc6TGljZW5zZTQ='} | 32041 | 2026-10-29 |
| 542 | Lima (Linux Machines): chạy máy ảo Linux có chia sẻ tệp và chuyển tiếp cổng tự động, kiểu WSL2, để dùng container (containerd/nerdctl, Docker, Podman, Kubernetes) trên macOS và các hệ khác | [lima-vm/lima](https://github.com/lima-vm/lima) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 22234 | 2026-11-02 |
| 543 | dive: công cụ khám phá ảnh Docker/OCI theo từng lớp, tìm cách giảm dung lượng; README ghi chất lượng beta và có chế độ CI | [wagoodman/dive](https://github.com/wagoodman/dive) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 54695 | 2026-11-02 |
| 544 | Dagger: nền tảng tự động hóa giao phần mềm lập trình được, chạy cục bộ, trên CI hoặc đám mây, SDK cho 8 ngôn ngữ, mọi thao tác chạy trong container và phát dấu vết OpenTelemetry | [dagger/dagger](https://github.com/dagger/dagger) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 16575 | 2026-11-03 |
| 545 | Pulumi: hạ tầng dưới dạng mã bằng ngôn ngữ lập trình bạn quen, triển khai lên AWS, Azure, Google Cloud, Kubernetes và hơn 300 nhà cung cấp; tạo tài nguyên đám mây thật có thể tốn tiền | [pulumi/pulumi](https://github.com/pulumi/pulumi) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 25839 | 2026-11-03 |
| 546 | Kong Gateway: cổng API, LLM và MCP cloud-native mở rộng bằng plugin, định tuyến, cân bằng tải, xác thực; README có bản đám mây Kong Konnect trả phí | [Kong/kong](https://github.com/Kong/kong) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 44345 | 2026-10-19 |

## Repo đã xem nhưng không đưa vào nhóm này

- **apache/apisix**: README mở đầu bằng tiêu đề giấy phép Apache và mục lục dài, chưa đọc đủ; loại, có thể làm sau.
- **jesseduffield/lazydocker**: commit gần nhất 2026-04-19, quá 60 ngày; loại.
- **containers/podman**, **skaffold/skaffold**: tìm kiếm GitHub không trả kết quả ở thời điểm kiểm tra.
- **crossplane/crossplane**, **fluxcd/flux2**, **istio/istio**, **envoyproxy/envoy**, **cilium/cilium**, **tilt-dev/tilt**, **GoogleContainerTools/skaffold**, **docker/buildx**, **earthly/earthly**: đủ điều kiện nhưng thiên về Kubernetes và hạ tầng nâng cao, chưa đưa vào nhóm này.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Lưu trữ và công cụ cá nhân', nhãn gần nhất trong 9 nhãn có sẵn.
- Moby, Lima, Dive, Dagger, Pulumi: README phần đã đọc không nêu giấy phép hoặc chỉ có huy hiệu (README Dive ghi nhãn 'MIT 2.0'); giấy phép lấy theo GitHub (Apache-2.0, MIT). NGINX, Moby và Kong nêu giấy phép trong README.
- Moby: README nói mô-đun Go github.com/docker/docker lỗi thời từ Docker v29; hỗ trợ theo nỗ lực tốt nhất.
- Pulumi: tài nguyên đám mây tạo ra tính phí; chưa đọc phần dịch vụ Pulumi Cloud nếu có. Ví dụ README mở cổng 80 cho mọi địa chỉ chỉ để minh họa.
- Dive: README ghi chất lượng beta; chạy qua Docker cần gắn socket Docker.
- Kong: tuyên bố '60+ tính năng AI' là của README; Kong Konnect trả phí. NGINX: 'phổ biến nhất thế giới' là của README; bản F5 trả phí.
- Lệnh cài và lệnh chạy trong README (Lima, Dive, Pulumi, Kong, Dagger) không được chép vào bài.

