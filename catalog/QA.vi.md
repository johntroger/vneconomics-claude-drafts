# Báo cáo rà soát chất lượng kho bản nháp

Ngày rà soát: 2026-11-03. Phạm vi: toàn bộ `content-drafts/*/content.json` (138 bài, key 101–238) và `research/*.json`.

## Kết quả kiểm tra tự động
- JSON hợp lệ: tất cả các file `content.json`, `catalog.json`.
- Không trùng repo, slug, key hay tiêu đề giữa các nhóm; không trùng repo và slug với 100 bài của đợt 25/10/2026.
- `category` và `need` đều thuộc bộ nhãn đã có trên site (10 category, 10 need ở đợt cũ).
- Số sao trong bài khớp với file `research`; `runtimeValidated = false` và `review.needed = true` ở mọi bài.
- Các mục bắt buộc (hiểu nhanh bằng ví dụ đời thường, mức độ phù hợp, thuật ngữ, điều kiện, lối bắt đầu, giới hạn, sao GitHub và tình trạng nguồn, giấy phép và chi phí, nguồn) có mặt đủ ở các nhóm viết lại cho người mới.
- Cụm từ cấm ("đã chạy thử", "đã kiểm thử" khẳng định, "tăng nhanh", lệnh cài như pip, npm, docker, brew, npx): không có ở dạng khẳng định. Một cảnh báo là định nghĩa từ "sudo" trong bài Dokku, không phải lệnh.
- Cả 138 liên kết README nguồn (raw.githubusercontent.com) trả HTTP 200 tại thời điểm rà soát.

## Phân bố
- Giấy phép (theo GitHub): MIT 64, Apache-2.0 38, BSD-3-Clause 12, GPL-3.0 7, NOASSERTION 6, AGPL-3.0 3, LGPL-2.1 3, Zlib 2, còn lại 3 bài CC.
- Độ khó (biên tập): Bắt đầu 29, Cơ bản 71, Khá khó 22, Nâng cao 16.

## Hạn chế của đợt rà soát này
- Chỉ kiểm tra cấu trúc, nhất quán và các cụm từ cấm bằng máy; chưa có người đọc lại từng bài.
- Khẳng định trong bài được đối chiếu với README bằng tìm kiếm chuỗi, không thay cho đọc hiểu.
- Số sao, giấy phép, ngày commit là snapshot 2026-11-03.
- Độ khó và câu lệnh mẫu cho AI là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.
- Liên kết trang `github.com` (blob) không được kiểm tra vì bị proxy phiên cloud chặn; chỉ kiểm tra liên kết README raw.

## Bổ sung rà soát ngày 2026-11-03 (nhóm 23–26, key 244–259)

- Kiểm tra máy trên toàn danh mục (159 bài): không trùng key, slug hay repo; chỉ dùng nhãn danh mục và nhu cầu đã có.
- Số sao trong danh mục khớp với tệp nghiên cứu của 16 bài mới.
- Đường dẫn README thô của 16 bài mới đều trả mã 200.
- Mỗi bài mới đã được đối chiếu các ý chính với README bằng grep; không có cụm "đã chạy thử", "đã kiểm thử" hay lệnh cài đặt trong nội dung.
- Hạn chế như trước: đây là kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa bài nào được cài hay chạy thử.

## Bổ sung rà soát (nhóm 27–29, key 260–274)

- Danh mục 174 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu đã có.
- Đường dẫn README thô của 15 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Đối chiếu các ý chính với README bằng grep; không có cụm "đã chạy thử", "đã kiểm thử" hay lệnh cài đặt trong nội dung. Các README có lệnh cài kiểu tải script rồi chạy (Ollama, llama.cpp) được bài cảnh báo thay vì chép lệnh.
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 30–31, key 275–286)

- Danh mục 186 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 12 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Đã sửa một lỗi phát hiện khi đối chiếu: bài Nextcloud ban đầu gán cảnh báo "không dùng cho hệ thống thật" cho nhánh master, trong khi README nói về các nhánh stable*; đã sửa theo README.
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 32–33, key 287–296)

- Danh mục 196 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 10 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Đối chiếu các ý chính với README bằng grep (kể cả danh sách định dạng của Pandoc); không có cụm "đã chạy thử", "đã kiểm thử" hay lệnh cài đặt trong nội dung.
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.
- Đã sửa: các câu "xem bài ... trong đợt cũ" trong bài Zettlr, ArchiveBox, Mermaid... được viết lại; còn lại không bài nào trỏ tới bài chưa có trong kho. Các cụm tên công cụ khác (ví dụ ComfyUI, Subtitle Edit) chỉ nêu tên và ghi rõ là bài chưa tìm hiểu.

## Bổ sung rà soát (nhóm 34–35, key 297–307)

- Danh mục 207 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 11 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Quét toàn bộ kho: không còn cụm "đợt cũ"; cụm "đã chạy thử" xuất hiện 29 lần và đều nằm trong câu phủ định "chưa phải kết quả đã chạy thử"; không có cụm "đã kiểm thử".
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 36–37, key 312–322)

- Danh mục 222 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 11 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" xuất hiện 29 lần, cả 29 lần đều nằm trong câu phủ định "chưa phải kết quả đã chạy thử".
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 38–39, key 323–338; tổng 238 bài)

- Danh mục 238 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 10 bài mới (nhóm 40–41) đều trả mã 200; số sao khớp tệp nghiên cứu.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" xuất hiện 29 lần, đều trong câu phủ định "chưa phải kết quả đã chạy thử".
- Đã gỡ khỏi bài Ansible một mục thuật ngữ không có căn cứ trong README (idempotent), và ghi rõ mục playbook là hiểu biết chung cần kiểm tra trong tài liệu.
- Quy ước loại trừ đã áp dụng: repo có giấy phép `NOASSERTION` trên GitHub, repo đã lưu trữ, repo đã chuyển nơi phát triển (ví dụ BookStack, ghi "NOW MANAGED ON CODEBERG"), README gốc chỉ là một dòng trỏ, commit quá cũ.
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 42–43, key 339–352; tổng 252 bài)

- Danh mục 252 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu.
- Đường dẫn README thô của 14 bài mới đều trả mã 200; số sao khớp tệp nghiên cứu.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" xuất hiện 29 lần, đều trong câu phủ định.
- Lỗi phát hiện và đã sửa trong lúc làm: (1) bài K9s ban đầu gán huy hiệu giấy phép Apache 2.0 cho K9s trong khi huy hiệu đó trỏ tới thư viện khác; (2) bài Fluentd ban đầu nói README nêu CNCF, thực ra thông tin này nằm ở mô tả kho GitHub; (3) bài Alertmanager ban đầu mô tả sai các mục của README. Cả ba đã sửa theo README.
- Rà lại toàn kho các câu "README có huy hiệu giấy phép ...": các huy hiệu trỏ tới trang giấy phép chung (opensource.org, gnu.org) hoặc tệp LICENSE của chính dự án; không còn trường hợp trỏ nhầm sang dự án khác.
- Hạn chế như trước: kiểm tra bằng máy, chưa có người đọc duyệt; độ khó là nhận định biên tập; chưa cài hay chạy thử công cụ nào.

## Bổ sung rà soát (nhóm 44, key 353–360; tổng 260 bài)

- Danh mục 260 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Lỗi phát hiện và đã sửa: đường dẫn README của bài Bruno ghi `README.md` trong khi tệp thật là `readme.md` (trả mã 404); đã sửa trong `content.json` và `research/353.json`.
- Sau khi sửa, kiểm tra lại đường dẫn README thô trong toàn bộ 260 tệp nghiên cứu: cả 260 đều trả mã 200.

## Bổ sung rà soát (nhóm 45, key 361–364; tổng 264 bài)

- Danh mục 264 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ 264 đường dẫn README thô trong các tệp nghiên cứu: cả 264 đều trả mã 200.
- Quy ước loại trừ đã áp dụng thêm: repo ngừng bảo trì và chỉ đọc theo chính README (Continue), commit quá cũ (Aider), giấy phép `NOASSERTION` (HandBrake).

## Bổ sung rà soát (nhóm 46, key 365–371; tổng 271 bài)

- Danh mục 271 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ 271 đường dẫn README thô trong các tệp nghiên cứu: cả 271 đều trả mã 200.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" xuất hiện 29 lần, đều trong câu phủ định.
- Đã gỡ khỏi hai bài (WireMock, Prism) các câu về yêu cầu hệ thống (Java, Node.js) vì README phần đã đọc không nêu; và sửa danh sách mục README đã đọc cho khớp với tiêu đề thật.

## Bổ sung rà soát (nhóm 47, key 372–377; tổng 277 bài)

- Danh mục 277 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ đường dẫn README thô trong các tệp nghiên cứu (277 tệp): cả 277 đều trả mã 200.
- Đã gỡ khỏi bài OpenTelemetry Collector các khái niệm (receiver, processor, exporter) mà README không nêu.

## Bổ sung rà soát (nhóm 48, key 378–385; tổng 285 bài)

- Danh mục 285 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ 285 đường dẫn README thô trong các tệp nghiên cứu: cả 285 đều trả mã 200.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" xuất hiện 29 lần, đều trong câu phủ định.
- Đã gỡ khỏi bài PHP các chi tiết lấy từ kiến thức chung (WordPress, hệ quản trị nội dung) vì README không nêu; bài giờ chỉ dựa trên câu "từ blog tới các trang web nổi tiếng nhất" của README.
- Quy ước loại trừ áp dụng thêm: kho GitHub chỉ là bản sao của kho gốc ở nơi khác (Go, Lua).

## Bổ sung rà soát (nhóm 49, key 386–391; tổng 291 bài)

- Danh mục 291 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ đường dẫn README thô trong các tệp nghiên cứu (291 tệp): cả 291 đều trả mã 200.
- Bài Spring Boot dùng README.adoc (README.md không tồn tại ở kho này); đã kiểm tra đường dẫn đúng tên tệp.

## Bổ sung rà soát (nhóm 50, key 392–399; tổng 299 bài)

- Danh mục 299 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ đường dẫn README thô trong các tệp nghiên cứu (299 tệp): cả 299 đều trả mã 200.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" chỉ xuất hiện trong câu phủ định.

## Bổ sung rà soát (nhóm 51, key 400–405; tổng 305 bài)

- Danh mục 305 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ đường dẫn README thô trong các tệp nghiên cứu (305 tệp): cả 305 đều trả mã 200.
- Đã sửa trong bài WSTG: README chỉ có huy hiệu Creative Commons trỏ tới CC BY-SA 4.0; bài không còn trích cụm "Attribution-ShareAlike" như thể README viết.

## Bổ sung rà soát (nhóm 52, key 406–412; tổng 312 bài)

- Danh mục 312 bài: không trùng key, slug hay repo; vẫn đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu.
- Kiểm tra toàn bộ đường dẫn README thô trong các tệp nghiên cứu (312 tệp): cả 312 đều trả mã 200.
- Quét toàn kho: không còn cụm "đợt cũ" và "đã kiểm thử"; cụm "đã chạy thử" chỉ xuất hiện trong câu phủ định.
- Nhóm "Framework agent AI" (key 413–419): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả.
- Nhóm "Vector database và đánh giá LLM" (key 420–423): đã đối chiếu các cụm chính với README thô, cả 4 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại 4 repo do giấy phép NOASSERTION.
- Nhóm "Công cụ terminal hiện đại" (key 424–429): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200; quét cụm bị cấm (gồm curl, brew install, cargo install) không có kết quả; loại repo có giấy phép NOASSERTION, quá 60 ngày hoặc README không đọc được.
- Nhóm "Ảnh, video và AI tạo ảnh" (key 430–436): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo có giấy phép NOASSERTION hoặc quá 60 ngày. Lưu ý bản quyền và giấy phép mô hình được ghi trong từng bài.
- Nhóm "Khóa học AI và học tập" (key 437–441): đã đối chiếu các cụm chính với README thô, cả 5 đường dẫn trả mã 200; quét cụm bị cấm chỉ có một khớp giả (cụm "xem bài đầy đủ" trong mô tả website, không phải liên kết chéo); loại repo có giấy phép None/NOASSERTION hoặc quá 60 ngày.
- Nhóm "Website, SEO và phân tích" (key 442–449): đã đối chiếu các cụm chính với README thô, cả 8 đường dẫn trả mã 200 (Lighthouse dùng tên tệp readme.md); quét cụm bị cấm không có kết quả; loại repo có giấy phép NOASSERTION hoặc tìm kiếm GitHub không trả kết quả. Các tuyên bố riêng tư và tuân thủ luật ghi rõ là của README.
- Nhóm "Tự host ghi chú, việc và tri thức" (key 450–456): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200 (BookStack dùng readme.md); quét cụm bị cấm có một khớp là liên kết chéo "xem bài yt-dlp" đã sửa; loại repo có giấy phép NOASSERTION. BookStack: chưa xác nhận kho chính.
- Nhóm "Cơ sở dữ liệu chuyên biệt" (key 457–462): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo đã lưu trữ, giấy phép NOASSERTION hoặc quá 60 ngày. Số liệu hiệu năng và quy mô ghi rõ là của hãng.
- Nhóm "Coding agent trong terminal" (key 463–468): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả (các lệnh cài tải từ mạng của README không được chép); loại repo không có SPDX, NOASSERTION, đã lưu trữ hoặc quá 60 ngày. Cảnh báo trong README (Gemini CLI, Continue, OpenHands) được nêu rõ trong bài.
- Rà soát toàn kho (368 bài, 2026-11-03): không trùng key, slug hay repo; đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu và runtimeValidated=false ở cả 368 tệp; kiểm tra toàn bộ 368 đường dẫn README thô trong tệp nghiên cứu: cả 368 đều trả mã 200; quét toàn kho: hai tệp README.vi.md của nhóm có cụm "đợt cũ" (đã sửa thành số nhãn hiện tại), không còn cụm "đã kiểm thử", cụm "đã chạy thử" chỉ trong câu phủ định, không có lệnh cài đặt trong nội dung bài.
- Nhóm "Mạng riêng và truyền thông riêng tư" (key 469–474): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200 (Synapse dùng README.rst); quét cụm bị cấm có một khớp giả (tên tùy chọn trong văn xuôi, đã đổi cách diễn đạt); loại repo NOASSERTION hoặc tìm kiếm GitHub không trả kết quả. Lệnh cài tải từ mạng trong README không được chép.
- Nhóm "Môi trường và chất lượng mã" (key 475–480): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200; quét cụm bị cấm chỉ có ba khớp là tên công cụ npx trong văn xuôi (không phải lệnh cài); loại repo có README chỉ là dòng trỏ (pre-commit, biome) hoặc quá 60 ngày. Lệnh cài tải từ mạng của README không được chép.
- Nhóm "Ngôn ngữ và nền tảng chạy mã" (key 481–483): đã đối chiếu các cụm chính với README thô, cả 3 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo có README quá ngắn, giấy phép NOASSERTION hoặc không có SPDX. Các nhận xét ngoài README (đặc tính Go, hệ sinh thái Odin) được ghi rõ là hiểu biết chung trong giới hạn từng bài.
- Nhóm "Chạy và tinh chỉnh mô hình AI" (key 484–490): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo NOASSERTION, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Tuyên bố hiệu năng ghi rõ là của README hoặc bên thứ ba; lệnh cài tải từ mạng không được chép.
- Rà soát toàn kho (390 bài, 2026-11-03): không trùng key, slug hay repo; đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu và runtimeValidated=false ở cả 390 tệp; cả 390 đường dẫn README thô trong tệp nghiên cứu đều trả mã 200; quét toàn kho không còn cụm "đợt cũ" hay "đã kiểm thử".
- Nhóm "Bản đồ, biểu đồ, bảng và hoạt ảnh" (key 491–497): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo NOASSERTION hoặc quá 60 ngày. Thông điệp mở đầu README Leaflet được nêu như thông tin, không bình luận; phần miễn phí và trả phí (Motion+, Univer Pro) được ghi rõ.
- Nhóm "Công cụ kinh doanh tự host" (key 498–504): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả (các lệnh tải script và cài đặt của README không được chép); loại repo NOASSERTION hoặc tìm kiếm GitHub không trả kết quả. Nhãn danh mục là nhãn gần nhất trong 9 nhãn sẵn có; pháp lý (thuế, kế toán, chữ ký điện tử, dữ liệu cá nhân) không được đánh giá.
- Nhóm "Công cụ giảng dạy" (key 505–508): đã đối chiếu các cụm chính với README thô, cả 4 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo README quá ngắn, NOASSERTION, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Cảnh báo hai bản Manim được nêu rõ.
- Nhóm "Thu thập và xử lý dữ liệu" (key 509–514): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200 (Scrapy dùng README.rst, Cheerio dùng Readme.md); quét cụm bị cấm không có kết quả; loại repo README quá ngắn, NOASSERTION hoặc tìm kiếm GitHub không trả kết quả. Tuyên bố chống bot của Crawlee được nêu như tuyên bố của README, không khuyến khích.
- Rà soát toàn kho (414 bài, 2026-11-03): không trùng key, slug hay repo; đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu và runtimeValidated=false ở cả 414 tệp; cả 414 đường dẫn README thô trong tệp nghiên cứu đều trả mã 200; quét toàn kho không còn cụm "đợt cũ" hay "đã kiểm thử".
- Nhóm "Blockchain và tiền mã hóa (kỹ thuật)" (key 515–522): đã đối chiếu các cụm chính với README thô, cả 8 đường dẫn trả mã 200; quét cụm bị cấm chỉ có tên công cụ foundryup trong văn xuôi, tên lệnh forge init đã đổi cách diễn đạt; loại repo NOASSERTION, quá 60 ngày, README không phải README.md hoặc tìm kiếm GitHub không trả kết quả. Mọi bài ghi rõ chỉ là giới thiệu kỹ thuật, không phải lời khuyên đầu tư hay pháp lý.
- Nhóm "WordPress và hệ sinh thái" (key 523–531): đã đối chiếu các cụm chính với README thô, cả 9 đường dẫn trả mã 200; quét cụm bị cấm chỉ có một khớp là tên công cụ curl trong văn xuôi (đã đổi cách diễn đạt); loại repo NOASSERTION, đã lưu trữ hoặc không có SPDX. WP Rocket và Elementor ghi rõ có phần trả phí.
- Nhóm "Marketing tự host" (key 532–539): đã đối chiếu các cụm chính với README thô, cả 8 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo NOASSERTION, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Cảnh báo kutt.it, tài khoản mặc định Unleash, phê duyệt ứng dụng của Postiz và các phần trả phí được nêu rõ.
- Rà soát toàn kho (439 bài, 2026-11-03): không trùng key, slug hay repo; đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu và runtimeValidated=false ở cả 439 tệp; cả 439 đường dẫn README thô trong tệp nghiên cứu đều trả mã 200; quét toàn kho không còn cụm "đợt cũ" hay "đã kiểm thử".
- Nhóm "Container và hạ tầng" (key 540–546): đã đối chiếu các cụm chính với README thô, cả 7 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo quá 60 ngày, tìm kiếm GitHub không trả kết quả hoặc README chưa đọc đủ. Cảnh báo chi phí đám mây (Pulumi), cổng quản trị (Kong), socket Docker (dive) và phần trả phí được nêu rõ.
- Nhóm "MCP và công cụ nối AI với thế giới ngoài" (key 547–555): đã đối chiếu các cụm chính với README thô, cả 9 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo NOASSERTION, không có SPDX, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Thống kê mặc định của Chrome DevTools MCP, quyền của GitHub PAT và cảnh báo I/O của MarkItDown được nêu rõ.
- Nhóm "Agent và nền tảng dựng app bằng AI" (key 556–561): đã đối chiếu các cụm chính với README thô, cả 6 đường dẫn trả mã 200; quét cụm bị cấm có một khớp là tên lệnh vercel link (đã bỏ khỏi bài); loại repo NOASSERTION, đã lưu trữ, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Cảnh báo của README SWE-agent, Open SWE và quyền GitHub được nêu rõ.
- Rà soát toàn kho (461 bài, 2026-11-03): không trùng key, slug hay repo; đúng 9 nhãn danh mục và 9 nhãn nhu cầu; số sao khớp tệp nghiên cứu và runtimeValidated=false ở cả 461 tệp; cả 461 đường dẫn README thô trong tệp nghiên cứu đều trả mã 200; quét toàn kho không còn cụm "đợt cũ" hay "đã kiểm thử".
- Nhóm "Ứng dụng di động" (key 562–569): đã đối chiếu các cụm chính với README thô, cả 8 đường dẫn trả mã 200; quét cụm bị cấm không có kết quả; loại repo không có SPDX, quá 60 ngày hoặc tìm kiếm GitHub không trả kết quả. Yêu cầu kiến trúc mới của Reanimated 4 và FlashList v2, trạng thái Beta của Compose web được nêu rõ.
- 2026-11-03, batch 95 (key 570–577, Khoa học dữ liệu và học máy): 8 bài; quét cụm từ cấm chỉ gặp phủ định "chưa phải kết quả đã chạy thử"; 8 README trả HTTP 200; không chép lệnh cài, không chép lệnh tải tập lệnh của MLflow; catalog 477 bài, 76 lộ trình.
- 2026-11-03, batch 96 (key 578–585, Giám sát và quan sát hệ thống phần 2): 8 bài, 8 README HTTP 200, không chép lệnh cài.
- 2026-11-03, audit toàn bộ ở 485 bài: JSON hợp lệ, 485 key/repo không trùng, runtimeValidated=false ở mọi file research, 485/485 URL README trả HTTP 200. Quét cụm từ cấm chỉ còn tên công cụ trong văn xuôi (docker compose, curl, wget, npx), câu phủ định về chạy thử và cụm "xem bài đầy đủ/xem bài kiểm thử" không phải tham chiếu chéo. Đã gỡ 3 tham chiếu chéo còn sót: Overleaf (xem bài Typst), Material for MkDocs (xem bài Hugo), Payload CMS (xem bài riêng).
- 2026-11-03, batch 97 (key 586–592, Kiểm thử và giả lập): 7 bài; quét cụm từ cấm không phát hiện gì ngoài câu phủ định; 7 README HTTP 200; không chép lệnh cài hay lệnh tải tập lệnh từ mạng; catalog 492 bài, 78 lộ trình.
- 2026-11-03, batch 98 (key 593–600, Liên lạc và cộng đồng tự host): 8 bài; quét cụm từ cấm chỉ gặp câu phủ định; 8 README HTTP 200; không chép lệnh cài hay lệnh tải tập lệnh từ mạng; catalog 500 bài, 79 lộ trình.
- 2026-11-03, batch 99 (key 601–608, Bảo mật chuỗi cung ứng và định danh): 8 bài; quét cụm từ cấm chỉ gặp câu phủ định; 8 README HTTP 200; không chép lệnh cài, lệnh tải tập lệnh từ mạng hay tài khoản mặc định dạng lệnh; catalog 508 bài, 80 lộ trình.
- 2026-11-03, batch 100 (key 609–615, Bản đồ và dữ liệu địa lý): 7 bài; quét cụm từ cấm chỉ gặp câu phủ định; 7 README HTTP 200; không chép lệnh cài; catalog 515 bài, 81 lộ trình.
- 2026-11-03, batch 101 (key 616–623, Đồ họa 3D và vật lý trên web): 8 bài; quét cụm từ cấm chỉ gặp câu phủ định; 8 README HTTP 200; không chép lệnh cài; catalog 523 bài, 82 lộ trình.
- 2026-11-03, batch 102 (key 624–629, Tài chính định lượng và dữ liệu thị trường): 6 bài; quét cụm từ cấm chỉ gặp câu phủ định; 6 README HTTP 200; không chép lệnh cài; mọi bài có cảnh báo không phải lời khuyên đầu tư; catalog 529 bài, 83 lộ trình.
- 2026-11-03, batch 103 (key 630–636, Jupyter và giảng dạy trực tuyến): 7 bài; quét cụm từ cấm chỉ gặp câu phủ định; 7 README HTTP 200; không chép lệnh cài; catalog 536 bài, 84 lộ trình.
- 2026-11-03, batch 104 (key 637–644, Phần cứng nhúng và máy in 3D): 8 bài; quét cụm từ cấm chỉ gặp câu phủ định; 8 README HTTP 200; không chép lệnh cài hay lệnh nạp firmware; có cảnh báo an toàn vật lý; catalog 544 bài, 85 lộ trình.
