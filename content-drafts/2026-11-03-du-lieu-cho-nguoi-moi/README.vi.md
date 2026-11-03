# Nhóm "Dữ liệu cho người mới" — bản nháp 03/11/2026

6 bài, key 160–165, `batch: 27`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 160 | pandas: thư viện Python xử lý bảng dữ liệu, nền của hầu hết mã phân tích do AI viết | [pandas-dev/pandas](https://github.com/pandas-dev/pandas) | BSD-3-Clause | 50302 | 2026-11-02 |
| 161 | Polars: công cụ xử lý bảng dữ liệu nhanh, kể cả dữ liệu lớn hơn bộ nhớ | [pola-rs/polars](https://github.com/pola-rs/polars) | MIT | 40254 | 2026-11-02 |
| 162 | JupyterLab: môi trường notebook để viết mã, xem kết quả và ghi chú cùng một chỗ | [jupyterlab/jupyterlab](https://github.com/jupyterlab/jupyterlab) | BSD-3-Clause | 15385 | 2026-11-02 |
| 163 | marimo: notebook Python 'phản ứng' tự cập nhật kết quả và triển khai thành ứng dụng | [marimo-team/marimo](https://github.com/marimo-team/marimo) | Apache-2.0 | 23411 | 2026-11-03 |
| 164 | Dash: dựng bảng điều khiển dữ liệu bằng Python, không cần viết JavaScript | [plotly/dash](https://github.com/plotly/dash) | MIT | 24478 | 2026-11-02 |
| 165 | Vega-Altair: vẽ biểu đồ bằng cách mô tả bạn muốn thấy gì thay vì chỉ cách vẽ | [vega/altair](https://github.com/vega/altair) | BSD-3-Clause | 10510 | 2026-11-02 |

## Điểm cần lưu ý
- **Dash**: README quảng bá nhiều cho Dash Enterprise (trả phí); bài tách rõ phần mở và phần trả phí.
- **Polars, marimo**: các tuyên bố hiệu năng/thay thế công cụ khác là của tác giả, bài nói rõ chưa kiểm chứng.
- **JupyterLab**: README cảnh báo JupyterLab 3 đã hết hỗ trợ từ 15/5/2024.
- **Altair**: README nói không liên kết với công ty Altair Engineering.

## Repo bị loại hoặc cân nhắc
- **matplotlib/matplotlib**: GitHub không ghi license; **numpy**, **sqlite**: NOASSERTION; **kedro**: NOASSERTION.
- **scikit-learn**: không tải được README qua nhánh `main`, chưa xác minh.
- **dbt-core**, **great_expectations**: không tìm được qua tên đã dùng.
- **evidence-dev/evidence**: README rất ngắn, chưa đọc tài liệu nên chưa viết.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy repo nào, không chép lệnh cài. Một số README chỉ đọc phần đầu và các mục chính.
