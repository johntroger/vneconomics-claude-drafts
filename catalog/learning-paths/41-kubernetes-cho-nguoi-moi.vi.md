# Lộ trình 41 — Làm quen Kubernetes từ cụm cục bộ

Học Kubernetes từ cụm nhỏ trên máy trước khi chạm môi trường thật; đây là chủ đề khó, đừng vội dùng cho sản xuất.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Kubernetes (K8s): hệ thống điều phối ứng dụng đóng gói container trên nhiều máy, README nói không hỗ trợ dùng mã làm thư viện** (key 339, độ khó: Rất khó) — Hiểu Kubernetes là gì và khi nào cần.  
   Repo: [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
2. **minikube: chạy cụm Kubernetes cục bộ trên macOS, Linux, Windows để học và phát triển ứng dụng** (key 340, độ khó: Khó) — Cụm cục bộ để học.  
   Repo: [kubernetes/minikube](https://github.com/kubernetes/minikube) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
3. **kind: dựng cụm Kubernetes cục bộ bằng container Docker làm nút, thiết kế ban đầu để kiểm thử Kubernetes** (key 341, độ khó: Khó) — Cụm tạm bằng Docker để thử và CI.  
   Repo: [kubernetes-sigs/kind](https://github.com/kubernetes-sigs/kind) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
4. **k3s: bản Kubernetes gọn nhẹ đóng trong một tệp, hợp thiết bị biên, IoT, CI và phòng thí nghiệm tại nhà** (key 342, độ khó: Khó) — Kubernetes gọn nhẹ cho máy nhỏ.  
   Repo: [k3s-io/k3s](https://github.com/k3s-io/k3s) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
5. **Helm: trình quản lý gói cho Kubernetes, đóng cấu hình ứng dụng thành chart; README nêu thời hạn hỗ trợ Helm v3** (key 343, độ khó: Khó) — Cài ứng dụng bằng chart.  
   Repo: [helm/helm](https://github.com/helm/helm) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
6. **K9s: giao diện terminal để duyệt, theo dõi và quản lý cụm Kubernetes, README rất dài với nhiều phím tắt** (key 344, độ khó: Khó) — Xem cụm bằng giao diện terminal.  
   Repo: [derailed/k9s](https://github.com/derailed/k9s) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
7. **Argo CD: công cụ triển khai liên tục theo kiểu GitOps cho Kubernetes, mô tả ứng dụng bằng cấu hình trong Git** (key 345, độ khó: Rất khó) — GitOps, bước nâng cao.  
   Repo: [argoproj/argo-cd](https://github.com/argoproj/argo-cd) · Bản nháp: `content-drafts/2026-11-03-kubernetes-cho-nguoi-moi/content.json`
