# Lộ trình 100 — Âm thanh và giọng nói

Từ quản lý và phát thư viện nhạc (beets, Navidrome), phân tích âm thanh (librosa), tách nguồn (Spleeter), phát hiện giọng nói (Silero VAD), phân tách người nói (pyannote.audio) đến sáng tác bằng mã (SuperCollider); chú ý bản quyền nhạc, dữ liệu giọng nói cá nhân, mã thông báo Hugging Face và tuyên bố của tác giả.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **beets: hệ thống quản lý thư viện nhạc cho người mê nhạc kỹ tính, lập danh mục bộ sưu tập, tự cải thiện siêu dữ liệu khi nhập và cung cấp bộ công cụ thao tác thư viện; mã nguồn mở, giấy phép MIT theo GitHub** (key 739, độ khó: Trung bình) — Quản lý thư viện nhạc và sửa thẻ (trung bình).  
   Repo: [beetbox/beets](https://github.com/beetbox/beets) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
2. **Navidrome: máy chủ và bộ phát nhạc mã nguồn mở trên web, nghe bộ sưu tập nhạc từ trình duyệt hoặc thiết bị di động như Spotify cá nhân; hỗ trợ bộ sưu tập rất lớn, nhiều người dùng, tương thích máy khách Subsonic; README ghi nhánh master có thể không ổn định** (key 740, độ khó: Dễ đến trung bình) — Máy chủ phát nhạc cá nhân (dễ đến trung bình).  
   Repo: [navidrome/navidrome](https://github.com/navidrome/navidrome) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
3. **librosa: thư viện Python xử lý tín hiệu âm thanh và âm nhạc, cung cấp các thuật toán và công cụ nền tảng để dựng hệ thống truy xuất thông tin âm nhạc (MIR); có tài liệu, hướng dẫn, nhật ký thay đổi; giấy phép ISC theo huy hiệu** (key 741, độ khó: Trung bình) — Phân tích âm thanh bằng Python (trung bình).  
   Repo: [librosa/librosa](https://github.com/librosa/librosa) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
4. **Spleeter: thư viện tách nguồn âm thanh của Deezer có mô hình huấn luyện sẵn viết bằng Python và TensorFlow, tách giọng hát khỏi phần đệm (2, 4, 5 phần), dùng được từ dòng lệnh, Docker hoặc thư viện; README nhắc xin phép chủ bản quyền; mã giấy phép MIT** (key 742, độ khó: Trung bình đến khó) — Tách giọng và nhạc nền; chú ý bản quyền (khó).  
   Repo: [deezer/spleeter](https://github.com/deezer/spleeter) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
5. **Silero VAD: bộ phát hiện hoạt động giọng nói huấn luyện sẵn cấp doanh nghiệp theo mô tả, chạy trên PyTorch và ONNX, yêu cầu hệ thống nhẹ, README tuyên bố không có telemetry, không cần khóa, không đăng ký; giấy phép MIT** (key 743, độ khó: Trung bình) — Phát hiện khúc có tiếng nói (trung bình).  
   Repo: [snakers4/silero-vad](https://github.com/snakers4/silero-vad) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
6. **pyannote.audio: bộ công cụ mã nguồn mở bằng Python cho phân tách người nói (speaker diarization), xây trên PyTorch, có pipeline huấn luyện sẵn trên Hugging Face, hỗ trợ dịch vụ trả phí pyannoteAI; yêu cầu chấp nhận điều kiện mô hình và mã thông báo Hugging Face; giấy phép MIT theo GitHub** (key 744, độ khó: Khó) — Ai nói khi nào; dữ liệu giọng nhạy cảm (khó).  
   Repo: [pyannote/pyannote-audio](https://github.com/pyannote/pyannote-audio) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
7. **SuperCollider: nền tảng tổng hợp âm thanh và sáng tác thuật toán cho nhạc sĩ, nghệ sĩ và nhà nghiên cứu, gồm máy chủ âm thanh thời gian thực scsynth, supernova, ngôn ngữ sclang và môi trường scide; mã C++17, giấy phép GPL v3** (key 745, độ khó: Khó) — Sáng tác âm thanh bằng mã (khó).  
   Repo: [supercollider/supercollider](https://github.com/supercollider/supercollider) · Bản nháp: `content-drafts/2026-11-03-am-thanh-va-giong-noi/content.json`
