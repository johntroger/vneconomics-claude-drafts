# Nhóm "Kiểm thử và giả lập" — bản nháp 03/11/2026

7 bài, key 586–592, `batch: 97`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 586 | Robot Framework: khung tự động hóa mã nguồn mở cho kiểm thử chấp nhận, phát triển hướng kiểm thử chấp nhận (ATDD) và tự động hóa quy trình bằng robot (RPA), cú pháp văn bản thuần, mở rộng bằng thư viện Python | [robotframework/robotframework](https://github.com/robotframework/robotframework) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 11981 | 2026-11-03 |
| 587 | Cucumber.js: bản JavaScript của Cucumber chạy kiểm thử tự động viết bằng ngôn ngữ thường (Gherkin) cho Node.js, để cả nhóm đều đọc được kịch bản kiểm thử | [cucumber/cucumber-js](https://github.com/cucumber/cucumber-js) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 5405 | 2026-11-03 |
| 588 | nock: thư viện giả lập máy chủ HTTP và kiểm tra kỳ vọng cho Node.js, kiểm thử mô-đun gọi HTTP một cách cô lập bằng cách ghi đè http.request; README rất dài | [nock/nock](https://github.com/nock/nock) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 13137 | 2026-10-30 |
| 589 | Moto: thư viện Python giả lập các dịch vụ AWS để kiểm thử, dùng bộ trang trí @mock_aws để mọi lệnh gọi dịch vụ bị chặn trong tài khoản AWS ảo | [getmoto/moto](https://github.com/getmoto/moto) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 8732 | 2026-11-03 |
| 590 | Schemathesis: kiểm thử API OpenAPI, GraphQL và gRPC bằng cách sinh đầu vào từ lược đồ, thích ứng với phản hồi máy chủ và nối các thao tác thành quy trình thực tế; README cảnh báo yêu cầu thật tạo, sửa và xóa dữ liệu | [schemathesis/schemathesis](https://github.com/schemathesis/schemathesis) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 3739 | 2026-11-03 |
| 591 | Spectral: trình kiểm tra (linter) cho JSON và YAML, có sẵn bộ quy tắc cho OpenAPI, AsyncAPI và Arazzo, tự viết quy tắc và hàm riêng; README nêu ảnh Docker gửi telemetry ẩn danh | [stoplightio/spectral](https://github.com/stoplightio/spectral) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 3247 | 2026-11-03 |
| 592 | Keploy: công cụ kiểm thử API và tích hợp tự sinh kiểm thử và dữ liệu giả bằng cách ghi lại lệnh gọi API, truy vấn cơ sở dữ liệu và sự kiện, dùng eBPF ở tầng mạng, rồi phát lại thành kiểm thử | [keploy/keploy](https://github.com/keploy/keploy) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 19212 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **testcontainers/testcontainers-java** (README khoảng 1,7 KB), **microsoft/playwright-python** (2,3 KB), **tox-dev/tox** (1,8 KB), **stryker-mutator/stryker-js** (2,6 KB), **pytest-dev/pytest-xdist** (1,2 KB), **pytest-dev/pytest-asyncio** (2,6 KB): README quá ngắn hoặc chủ yếu là liên kết; loại.
- **faker-js/faker**, **HypothesisWorks/hypothesis**, **behave/behave**, **sinonjs/sinon**: GitHub không trả giấy phép SPDX rõ (NOASSERTION); loại. **testing-library/react-testing-library**: commit gần nhất 2026-08-27, quá 60 ngày; loại. **lost-pixel/lost-pixel**: đã lưu trữ; loại. **httpie/cli**, **postmanlabs/httpbin**: commit gần nhất năm 2024; loại.
- **oasdiff/oasdiff**, **pytest-dev/pytest-mock**, **getmoto** các repo khác: chưa xét trong nhóm này.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Coding agent và cách làm dự án', nhãn gần nhất trong 9 nhãn có sẵn.
- Robot Framework (Apache License 2.0, tài liệu CC BY 3.0) và Schemathesis (MIT), nock (MIT), Spectral (Apache License 2.0) nêu giấy phép trong README. Cucumber.js, Moto, Keploy: README phần đã đọc không nêu giấy phép bằng văn bản, giấy phép lấy theo GitHub (MIT, Apache-2.0, Apache-2.0).
- README nock rất dài (khoảng 62 KB), bài đọc phần đầu và các mục chính. README Keploy có lệnh cài tải tập lệnh từ mạng; bài không chép lệnh và khuyên đọc tập lệnh trước. Mô tả eBPF, AI và độ phủ của Keploy là tuyên bố của tác giả, bài không kiểm chứng. Schemathesis gửi yêu cầu thật tạo, sửa, xóa dữ liệu theo cảnh báo của README. README Spectral nêu ảnh Docker gửi telemetry ẩn danh.

