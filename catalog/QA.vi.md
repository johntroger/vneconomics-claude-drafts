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
