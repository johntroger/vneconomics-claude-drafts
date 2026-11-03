# Lộ trình 82 — Đồ họa 3D và vật lý trên web

Từ vật lý 2D và động cơ trò chơi HTML5, hiển thị mô hình 3D, kết hợp React với three.js đến truy vấn không gian và động cơ vật lý Rust; chú ý ghép đúng phiên bản React, tuyên bố hiệu năng của tác giả, giấy phép mô hình và tài sản, và hiệu năng trên máy yếu.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **Matter.js: công cụ vật lý vật rắn 2D bằng JavaScript cho web, có vật thể ghép, đa giác lồi và lõm, va chạm đàn hồi, ví dụ, bộ phụ trợ và giấy phép MIT** (key 618, độ khó: Trung bình) — Vật lý 2D cho web (trung bình).  
   Repo: [liabru/matter-js](https://github.com/liabru/matter-js) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
2. **melonJS: động cơ trò chơi HTML5 hiện đại đầy đủ tính năng, mã nguồn mở cho 2D và 3D, kết xuất WebGPU, WebGL 2 hoặc Canvas2D, có vật lý, bản đồ ô, âm thanh, giấy phép MIT** (key 621, độ khó: Trung bình) — Động cơ trò chơi HTML5 (trung bình).  
   Repo: [melonjs/melonJS](https://github.com/melonjs/melonJS) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
3. **glTF Sample Viewer: trình xem chính thức của Khronos cho glTF 2.0 dùng WebGL 2.0, có bản xem trực tiếp, danh sách tiện ích mở rộng được hỗ trợ và các cách thay mô hình, bản đồ môi trường** (key 623, độ khó: Dễ đến trung bình) — Trình xem glTF chính thức (dễ đến trung bình).  
   Repo: [KhronosGroup/glTF-Sample-Viewer](https://github.com/KhronosGroup/glTF-Sample-Viewer) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
4. **model-viewer: kho chính của thành phần web <model-viewer> để hiển thị mô hình 3D và các dự án liên quan (hiệu ứng, trang tài liệu, công cụ đo độ trung thực kết xuất, tài sản dùng chung, trình soạn thảo)** (key 620, độ khó: Trung bình) — Nhúng mô hình 3D bằng thẻ HTML (trung bình).  
   Repo: [google/model-viewer](https://github.com/google/model-viewer) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
5. **react-three-fiber: bộ kết xuất React cho three.js, dựng cảnh 3D theo kiểu khai báo bằng các thành phần tái sử dụng phản ứng theo trạng thái; README nêu phải ghép đúng phiên bản React** (key 616, độ khó: Khó) — three.js kiểu React (khó).  
   Repo: [pmndrs/react-three-fiber](https://github.com/pmndrs/react-three-fiber) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
6. **drei: bộ sưu tập ngày càng lớn các tiện ích và thành phần dựng sẵn cho react-three-fiber (camera, điều khiển, gizmo...), dùng three-stdlib; tài liệu đã chuyển sang trang riêng** (key 617, độ khó: Khó) — Tiện ích dựng sẵn cho react-three-fiber (khó).  
   Repo: [pmndrs/drei](https://github.com/pmndrs/drei) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
7. **Rapier: bộ động cơ vật lý 2D và 3D viết bằng Rust cho trò chơi, hoạt ảnh và người máy, có liên kết cho C, Python, JavaScript và plugin Bevy; README có mục chính sách dùng AI viết mã** (key 619, độ khó: Khó) — Động cơ vật lý 2D và 3D bằng Rust (khó).  
   Repo: [dimforge/rapier](https://github.com/dimforge/rapier) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
8. **three-mesh-bvh: cài đặt cấu trúc cây bao thể tích (BVH) để tăng tốc bắn tia và truy vấn không gian trên lưới three.js, tuyên bố bắn 500 tia vào mô hình 80.000 đa giác ở 60 khung mỗi giây** (key 622, độ khó: Rất khó) — Tăng tốc bắn tia cho three.js (rất khó).  
   Repo: [gkjohnson/three-mesh-bvh](https://github.com/gkjohnson/three-mesh-bvh) · Bản nháp: `content-drafts/2026-11-03-do-hoa-3d-va-vat-ly-web/content.json`
