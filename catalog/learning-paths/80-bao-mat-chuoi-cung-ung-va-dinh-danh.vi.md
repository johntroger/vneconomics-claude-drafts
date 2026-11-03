# Lộ trình 80 — Bảo mật chuỗi cung ứng và định danh

Từ đánh giá thực hành bảo mật của thư viện, tạo SBOM, quét lỗ hổng, ký ảnh container, quét hạ tầng dưới dạng mã đến phát hiện hành vi bất thường và quản lý đăng nhập; chú ý tài khoản mặc định, lệnh cài tải tập lệnh từ mạng, bảng so sánh của tác giả và giới hạn của mọi công cụ quét.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **OpenSSF Scorecard: công cụ tự động chấm điểm 0 đến 10 cho từng kiểm tra về thực hành bảo mật của một dự án mã nguồn mở, giúp người bảo trì cải thiện và người dùng đánh giá rủi ro phụ thuộc; có CLI, GitHub Action, REST API và máy chủ MCP** (key 608, độ khó: Trung bình) — Chấm điểm thực hành bảo mật của dự án (trung bình).  
   Repo: [ossf/scorecard](https://github.com/ossf/scorecard) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
2. **Syft: công cụ dòng lệnh và thư viện Go tạo SBOM (danh sách thành phần phần mềm) từ ảnh container và hệ tệp, nhiều định dạng đầu ra (CycloneDX, SPDX), dùng tốt cùng Grype, giấy phép Apache 2.0** (key 605, độ khó: Trung bình) — Tạo SBOM (trung bình).  
   Repo: [anchore/syft](https://github.com/anchore/syft) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
3. **Grype: công cụ quét lỗ hổng cho ảnh container và hệ tệp, hỗ trợ SBOM, nhiều hệ gói hệ điều hành và ngôn ngữ, xếp hạng rủi ro theo EPSS và KEV, hỗ trợ OpenVEX, giấy phép Apache 2.0** (key 604, độ khó: Trung bình) — Quét lỗ hổng ảnh container (trung bình).  
   Repo: [anchore/grype](https://github.com/anchore/grype) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
4. **Checkov: công cụ phân tích mã tĩnh cho hạ tầng dưới dạng mã (Terraform, CloudFormation, Kubernetes, Dockerfile, GitHub Actions...) và phân tích thành phần phần mềm, hơn 1000 chính sách dựng sẵn, cung cấp sức mạnh cho Prisma Cloud** (key 607, độ khó: Khó) — Quét hạ tầng dưới dạng mã (khó).  
   Repo: [bridgecrewio/checkov](https://github.com/bridgecrewio/checkov) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
5. **Cosign: ký, xác minh và lưu chữ ký cho ảnh container và các tệp khác theo Sigstore, ký không khóa với Fulcio và Rekor, hỗ trợ khóa phần cứng, KMS và PKI riêng; README rất dài** (key 606, độ khó: Rất khó) — Ký và xác minh ảnh container (rất khó).  
   Repo: [sigstore/cosign](https://github.com/sigstore/cosign) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
6. **Falco: công cụ bảo mật thời gian chạy cloud native cho Linux, tác tử giám sát nhân phát hiện hành vi bất thường theo quy tắc, dự án tốt nghiệp CNCF do Sysdig tạo, giấy phép Apache 2.0** (key 603, độ khó: Rất khó) — Phát hiện hành vi bất thường thời gian chạy (rất khó).  
   Repo: [falcosecurity/falco](https://github.com/falcosecurity/falco) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
7. **Casdoor: máy chủ đăng nhập một lần (SSO) và xác thực có bảng điều khiển web, hỗ trợ OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, SCIM; README có tài khoản demo mặc định built-in/admin/123** (key 602, độ khó: Rất khó) — Đăng nhập một lần; đổi tài khoản mặc định (rất khó).  
   Repo: [casdoor/casdoor](https://github.com/casdoor/casdoor) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
8. **ZITADEL: nền tảng quản lý định danh và truy cập (IAM) mã nguồn mở, ưu tiên API, đa thuê bao ở cấp hạ tầng, nhật ký sự kiện bất biến; giấy phép AGPL-3.0 kèm ngoại lệ Apache 2.0 và MIT cho một số thư mục** (key 601, độ khó: Rất khó) — Quản lý định danh và truy cập (rất khó).  
   Repo: [zitadel/zitadel](https://github.com/zitadel/zitadel) · Bản nháp: `content-drafts/2026-11-03-bao-mat-chuoi-cung-ung-va-dinh-danh/content.json`
