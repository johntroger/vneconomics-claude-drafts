# Nhóm "Agent và nền tảng dựng app bằng AI" — bản nháp 03/11/2026

6 bài, key 556–561, `batch: 93`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 556 | Open Lovable: ứng dụng mẫu của Firecrawl để trò chuyện với AI dựng ứng dụng React ngay lập tức; cần khóa Firecrawl, khóa nhà cung cấp AI và sandbox Vercel hoặc E2B | [firecrawl/open-lovable](https://github.com/firecrawl/open-lovable) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 28849 | 2026-10-09 |
| 557 | Kilo Code: coding agent mã nguồn mở chạy trong VS Code, JetBrains và CLI, chọn trong hơn 500 mô hình; README có lệnh cài tải từ mạng và dịch vụ trả phí | [Kilo-Org/kilocode](https://github.com/Kilo-Org/kilocode) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 27844 | 2026-11-03 |
| 558 | ChatDev 2.0 (DevAll): nền tảng đa tác tử không cần mã, nay là bản 2.0 'phát triển mọi thứ'; bản 1.0 'công ty phần mềm ảo' chuyển sang nhánh riêng | [OpenBMB/ChatDev](https://github.com/OpenBMB/ChatDev) | {'key': 'apache-2.0', 'name': 'Apache License 2.0', 'spdx_id': 'Apache-2.0', 'url': 'https://api.github.com/licenses/apache-2.0', 'node_id': 'MDc6TGljZW5zZTI='} | 34645 | 2026-10-30 |
| 559 | SWE-agent: agent do nhà nghiên cứu Princeton và Stanford làm để mô hình ngôn ngữ tự dùng công cụ sửa lỗi trong kho GitHub thật; README nói mini-swe-agent đã thay thế và khuyến nghị dùng thay | [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 20712 | 2026-11-02 |
| 560 | Claude Code Router: cổng mô hình cục bộ và bảng điều khiển cho coding agent, nối Claude Code, Codex, OpenCode và nhiều agent khác với nhà cung cấp bạn chọn, có định tuyến, dự phòng và quan sát | [musistudio/claude-code-router](https://github.com/musistudio/claude-code-router) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 37972 | 2026-10-10 |
| 561 | Open SWE: agent kỹ sư phần mềm mã nguồn mở của LangChain, điều tra kho mã, triển khai thay đổi trong sandbox và gửi pull request; README nói đang phát triển mạnh, không nhận issue hay đóng góp ngoài | [langchain-ai/open-swe](https://github.com/langchain-ai/open-swe) | {'key': 'mit', 'name': 'MIT License', 'spdx_id': 'MIT', 'url': 'https://api.github.com/licenses/mit', 'node_id': 'MDc6TGljZW5zZTEz'} | 11165 | 2026-11-03 |

## Repo đã xem nhưng không đưa vào nhóm này

- **Significant-Gravitas/AutoGPT**, **Pythagora-io/gpt-pilot**, **vercel/ai**: GitHub trả giấy phép NOASSERTION; loại.
- **AntonOsika/gpt-engineer**, **voideditor/void**: kho đã lưu trữ; **plandex-ai/plandex** (commit 2025-10-03), **FoundationAgents/MetaGPT** (2026-01-21), **bytedance/trae-agent** (2026-02-05): quá 60 ngày; loại.
- **coder/code-server**: README không ở tên README.md ở thư mục gốc (trả 404); chưa đọc. **stackblitz-labs/bolt.diy**, **gitpod-io/openvscode-server**: tìm kiếm GitHub không trả kết quả.

## Điều chưa biết

- Chưa cài hay chạy công cụ nào; độ khó là đánh giá biên tập. Nhóm dùng nhãn 'Coding agent và cách làm dự án'.
- ChatDev: README phần đã đọc không nêu giấy phép; giấy phép lấy theo GitHub (Apache-2.0). Open Lovable, Kilo Code, SWE-agent, Claude Code Router, Open SWE nêu giấy phép MIT trong README.
- SWE-agent: README khuyến nghị dùng mini-swe-agent thay; con số 65% và 'tiên tiến nhất' là của README. Open SWE: README cảnh báo đang phát triển mạnh, không nhận issue hay đóng góp ngoài, nguyên trạng cần Managed Deep Agents, quyền GitHub App của sandbox rộng; giấy phép MIT không gồm thư mục vendor.
- ChatDev: bản 1.0 đã chuyển sang nhánh chatdev1.0; README nhiều tin tức, bài không đọc hết. Hiệu quả đa tác tử chưa kiểm chứng.
- Claude Code Router: giữ khóa API và nhìn thấy mọi yêu cầu; điều khoản dùng tài khoản đăng ký sẵn với agent khác chưa kiểm tra. Kilo Code: giá và 'hơn 500 mô hình' chưa kiểm chứng.
- Lệnh cài, lệnh chạy và cấu hình khóa trong README không được chép vào bài.

