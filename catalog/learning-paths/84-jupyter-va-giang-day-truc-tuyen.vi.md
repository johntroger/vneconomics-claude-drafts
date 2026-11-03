# Lộ trình 84 — Jupyter và giảng dạy trực tuyến

Từ trình bày công thức toán, sổ tay Jupyter, chạy Python ngay trong trình duyệt, quản lý sổ tay dưới Git đến máy chủ nhiều người dùng và chia sẻ môi trường bằng container; chú ý cách ly và xác thực khi nhiều người dùng chung, dữ liệu của người học và phiên bản mở rộng cũ không tương thích.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **KaTeX: thư viện JavaScript nhanh, dễ dùng để hiển thị công thức TeX trên web, kết xuất đồng bộ, chất lượng in, không phụ thuộc, hỗ trợ kết xuất phía máy chủ, giấy phép MIT** (key 630, độ khó: Dễ đến trung bình) — Công thức toán trên web (dễ đến trung bình).  
   Repo: [KaTeX/KaTeX](https://github.com/KaTeX/KaTeX) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
2. **Jupyter Notebook: môi trường sổ tay trên web để tính toán tương tác; README nêu hai phiên bản chính còn duy trì (Classic v6 và v7 xây trên JupyterLab) và lưu ý phần mở rộng cũ không tương thích với v7** (key 631, độ khó: Dễ đến trung bình) — Sổ tay tương tác (dễ đến trung bình).  
   Repo: [jupyter/notebook](https://github.com/jupyter/notebook) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
3. **JupyterLite: bản phân phối JupyterLab chạy hoàn toàn trong trình duyệt, nhân Python chạy trong Web Worker (Pyodide, Xeus Python), không cần máy chủ; không phải mọi tính năng JupyterLab đều chạy được** (key 633, độ khó: Trung bình) — Sổ tay Python chạy trong trình duyệt (trung bình).  
   Repo: [jupyterlite/jupyterlite](https://github.com/jupyterlite/jupyterlite) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
4. **Jupytext: lưu sổ tay Jupyter thành tài liệu văn bản thuần (Python, Markdown...) để chỉnh trong IDE và theo dõi thay đổi rõ ràng bằng kiểm soát phiên bản, có sổ tay ghép đôi và dòng lệnh, giấy phép MIT** (key 634, độ khó: Trung bình) — Sổ tay dạng văn bản cho Git (trung bình).  
   Repo: [jupytext/jupytext](https://github.com/jupytext/jupytext) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
5. **repo2docker: lấy một kho git và dựng ảnh container dựa trên các tệp cấu hình trong kho, nền cho Binder; yêu cầu Docker, Python 3.9+, hỗ trợ Linux và macOS; README có ghi chú nghiên cứu về tính bền vững** (key 635, độ khó: Khó) — Dựng môi trường container từ kho (khó).  
   Repo: [jupyterhub/repo2docker](https://github.com/jupyterhub/repo2docker) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
6. **JupyterHub: máy chủ nhiều người dùng sinh, quản lý và ủy quyền nhiều máy chủ Jupyter Notebook đơn người dùng, phục vụ lớp học, nhóm khoa học dữ liệu hay cụm tính toán; giấy phép BSD sửa đổi** (key 632, độ khó: Rất khó) — Máy chủ Jupyter nhiều người dùng (rất khó).  
   Repo: [jupyterhub/jupyterhub](https://github.com/jupyterhub/jupyterhub) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
7. **BinderHub: dựng và đăng ký ảnh Docker từ một kho git rồi kết nối với JupyterHub để người dùng tương tác với mã trong một phiên trực tiếp, nối JupyterHub và repo2docker, xây trên Python, Kubernetes** (key 636, độ khó: Rất khó) — Chạy kho mã trực tuyến cho nhiều người (rất khó).  
   Repo: [jupyterhub/binderhub](https://github.com/jupyterhub/binderhub) · Bản nháp: `content-drafts/2026-11-03-jupyter-va-giang-day-truc-tuyen/content.json`
