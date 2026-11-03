# Lộ trình 81 — Bản đồ và dữ liệu địa lý

Từ vẽ bản đồ nhanh, hình học và dữ liệu địa lý bằng Python, phần mềm GIS đến chỉ mục lục giác và tìm đường; chú ý hệ tọa độ, quyền riêng tư của dữ liệu vị trí và điều khoản dữ liệu OpenStreetMap.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **leafmap: gói Python phân tích địa không gian và vẽ bản đồ tương tác trong Jupyter với ít mã, chuyển đổi giữa nhiều backend (ipyleaflet, folium, kepler.gl, pydeck, bokeh), giấy phép MIT** (key 613, độ khó: Dễ đến trung bình) — Bản đồ tương tác trong Jupyter (dễ đến trung bình).  
   Repo: [opengeos/leafmap](https://github.com/opengeos/leafmap) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
2. **kepler.gl: ứng dụng web hiệu năng cao không phụ thuộc loại dữ liệu để khám phá trực quan tập dữ liệu vị trí quy mô lớn, xây trên MapLibre GL và deck.gl, đồng thời là thành phần React dùng Redux, giấy phép MIT** (key 609, độ khó: Trung bình) — Khám phá dữ liệu vị trí lớn trên web (trung bình).  
   Repo: [keplergl/kepler.gl](https://github.com/keplergl/kepler.gl) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
3. **Shapely: gói Python thao tác và phân tích đối tượng hình học phẳng, dùng thư viện GEOS (công cụ của PostGIS), có giao diện Geometry và hàm ufunc NumPy hiệu năng cao, giấy phép BSD 3 điều khoản** (key 611, độ khó: Trung bình) — Hình học phẳng trong Python (trung bình).  
   Repo: [shapely/shapely](https://github.com/shapely/shapely) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
4. **GeoPandas: công cụ Python cho dữ liệu địa lý, thêm kiểu GeoSeries và GeoDataFrame vào pandas để thao tác hình học; phép toán theo hệ tọa độ phẳng, hệ quy chiếu lưu trong thuộc tính, tài trợ qua NumFOCUS** (key 610, độ khó: Trung bình) — Dữ liệu địa lý trong pandas (trung bình).  
   Repo: [geopandas/geopandas](https://github.com/geopandas/geopandas) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
5. **H3: hệ lập chỉ mục địa không gian theo lưới lục giác phân cấp của Uber, chia nhỏ dần thành lưới lục giác mịn hơn, có thư viện C và nhiều liên kết ngôn ngữ, giấy phép Apache 2.0** (key 615, độ khó: Trung bình) — Chỉ mục lưới lục giác (trung bình).  
   Repo: [uber/h3](https://github.com/uber/h3) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
6. **QGIS: hệ thống thông tin địa lý (GIS) đầy đủ tính năng, thân thiện, miễn phí và mã nguồn mở chạy trên Unix, Windows và macOS, có QGIS Server và API Python; giấy phép GPL phiên bản 2 trở lên** (key 614, độ khó: Trung bình) — Phần mềm GIS đầy đủ (trung bình).  
   Repo: [qgis/QGIS](https://github.com/qgis/QGIS) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
7. **OSRM (Open Source Routing Machine): công cụ tìm đường hiệu năng cao viết bằng C++ chạy trên dữ liệu OpenStreetMap, dịch vụ gần nhất, tuyến đường, bảng thời gian, khớp vết GPS, chuyến đi; dùng qua HTTP, thư viện C++ hoặc NodeJs** (key 612, độ khó: Khó) — Công cụ tìm đường trên dữ liệu OpenStreetMap (khó).  
   Repo: [Project-OSRM/osrm-backend](https://github.com/Project-OSRM/osrm-backend) · Bản nháp: `content-drafts/2026-11-03-ban-do-va-du-lieu-dia-ly/content.json`
