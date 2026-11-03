# Nhóm "Thu thập và xử lý dữ liệu" — bản nháp 03/11/2026

6 bài, key 509–514, `batch: 87`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 509 | Scrapy: khung thu thập dữ liệu web bằng Python để trích xuất dữ liệu có cấu trúc từ website, do Zyte duy trì; README yêu cầu Python 3.11+ | [scrapy/scrapy](https://github.com/scrapy/scrapy) | {'key': 'bsd-3-clause', 'name': 'BSD 3-Clause "New" or "Revised" License', 'spdx_id': 'BSD-3-Clause', 'url': 'https://api.github.com/licenses/bsd-3-clause', 'node_id': 'MDc6TGljZW5zZTU='} | 65190 | 2026-11-02 |
| 510 | Crawlee: thư viện Node.js thu thập và cào dữ liệu web đầu cuối với trình duyệt không giao diện (Playwright, Puppeteer); README nói crawler 'trông như người thật' và yêu cầu Node.js 22.13+ | [apify/crawlee](https://github.com/apify/crawlee) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 26324 | 2026-11-02 |
| 511 | Cheerio: thư viện JavaScript phân tích và thao tác HTML hoặc XML với cú pháp giống jQuery, chạy trên máy chủ và trình duyệt | [cheeriojs/cheerio](https://github.com/cheeriojs/cheerio) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 30539 | 2026-11-03 |
| 512 | dlt: thư viện Python nạp dữ liệu từ nguồn lộn xộn vào bộ dữ liệu có cấu trúc, hơn 20 đích đến, thiết kế cho cả LLM và coding agent; có nền tảng thương mại dltHub | [dlt-hub/dlt](https://github.com/dlt-hub/dlt) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 6051 | 2026-10-31 |
| 513 | Mage OSS: môi trường tự host dựng pipeline dữ liệu bằng Python, SQL, R với giao diện kiểu notebook; có bản Mage Pro trả phí | [mage-ai/mage-ai](https://github.com/mage-ai/mage-ai) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 8841 | 2026-10-23 |
| 514 | PyGWalker: biến bảng dữ liệu pandas, polars, pyarrow thành giao diện kéo thả để khám phá và vẽ biểu đồ trong Jupyter hoặc Streamlit | [Kanaries/pygwalker](https://github.com/Kanaries/pygwalker) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 16005 | 2026-09-05 |

## Repo đã xem nhưng không đưa vào nhóm này

- **evidence-dev/evidence** (README khoảng 1,9 KB), **PrefectHQ/marvin** (README khoảng 2,1 KB): README quá ngắn, chủ yếu liên kết; loại, có thể làm sau.
- **metabase/metabase**, **airbytehq/airbyte**: GitHub trả giấy phép NOASSERTION; loại.
- **dbt-labs/dbt-core**, **ydataai/ydata-profiling**, **great-expectations/great_expectations**: tìm kiếm GitHub không trả kết quả ở thời điểm kiểm tra; chưa đọc.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập.
- Scrapy: README là README.rst rất ngắn, phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub (BSD-3-Clause). Mage OSS: README chỉ có huy hiệu giấy phép (lấy theo GitHub). Cheerio: README dùng tên Readme.md.
- Crawlee: README tuyên bố crawler 'trông giống người' và qua mặt chống bot; bài nêu như tuyên bố, không kiểm chứng và không khuyến khích. Pháp lý thu thập dữ liệu (điều khoản, bản quyền, dữ liệu cá nhân) là nguyên tắc chung của bài, README không bàn.
- Cheerio: nhận định rằng thư viện không chạy JavaScript của trang là suy luận từ README.
- dltHub, Mage Pro: sản phẩm thương mại, giá chưa kiểm tra. PyGWalker: commit gần nhất 2026-09-05 (59 ngày trước ngày kiểm tra), sát ngưỡng 60 ngày.

