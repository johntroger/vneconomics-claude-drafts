# Lộ trình 83 — Tài chính định lượng và dữ liệu thị trường (chỉ để học)

Từ lấy dữ liệu thị trường cho bài tập, nền tảng nghiên cứu định lượng, đến các bot giao dịch, thư viện kết nối sàn và sổ cái phân tán; chỉ giới thiệu kỹ thuật, không phải lời khuyên đầu tư; chú ý điều khoản dữ liệu, rủi ro mất tiền, khóa API và kết quả kiểm thử lại không đảm bảo tương lai.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **yfinance: công cụ Python lấy dữ liệu tài chính và thị trường từ API công khai của Yahoo Finance, dành cho nghiên cứu và giáo dục, không liên kết với Yahoo; README nhắc đọc điều khoản của Yahoo và API chỉ cho dùng cá nhân** (key 624, độ khó: Dễ đến trung bình) — Dữ liệu giá cho bài tập (dễ đến trung bình).  
   Repo: [ranaroussi/yfinance](https://github.com/ranaroussi/yfinance) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
2. **Qlib: nền tảng đầu tư định lượng hướng AI của Microsoft, quy trình học máy đầy đủ từ xử lý dữ liệu, huấn luyện đến kiểm thử lại; README cảnh báo thay đổi phá vỡ về nạp artifact chưa phát hành và nêu RD-Agent** (key 625, độ khó: Rất khó) — Nền tảng nghiên cứu đầu tư định lượng (rất khó).  
   Repo: [microsoft/qlib](https://github.com/microsoft/qlib) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
3. **XRP Ledger (xrpld/rippled): sổ cái mật mã phi tập trung do mạng nút ngang hàng vận hành, phần mềm máy chủ xrpld theo giấy phép ISC, README nêu đặc tính như đồng thuận 4 đến 5 giây; bài chỉ giới thiệu kỹ thuật, không phải lời khuyên đầu tư** (key 629, độ khó: Rất khó) — Sổ cái phi tập trung, chỉ để hiểu kỹ thuật (rất khó).  
   Repo: [XRPLF/rippled](https://github.com/XRPLF/rippled) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
4. **CCXT: thư viện giao diện thống nhất để kết nối và giao dịch với hơn 100 sàn tiền mã hóa và thị trường dự đoán, nhiều ngôn ngữ, README rất dài và có mục Disclaimer về phần mềm không lưu ký tiền** (key 627, độ khó: Khó) — Giao diện chung tới nhiều sàn (khó).  
   Repo: [ccxt/ccxt](https://github.com/ccxt/ccxt) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
5. **Freqtrade: bot giao dịch tiền mã hóa mã nguồn mở viết bằng Python, điều khiển qua Telegram hoặc giao diện web, có chế độ chạy giả lập, kiểm thử lại, tối ưu bằng học máy; README cảnh báo chỉ dùng cho giáo dục và có thể mất tiền** (key 626, độ khó: Rất khó) — Bot giao dịch tiền mã hóa, chỉ dry-run (rất khó).  
   Repo: [freqtrade/freqtrade](https://github.com/freqtrade/freqtrade) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
6. **Hummingbot: khung mã nguồn mở thiết kế và triển khai chiến lược giao dịch tự động (bot) trên nhiều sàn tập trung và phi tập trung, chiến lược kịch bản, bộ điều khiển, bộ thực thi, dòng lệnh hbot và Condor (khung AI), Apache 2.0** (key 628, độ khó: Rất khó) — Khung bot giao dịch tự động (rất khó).  
   Repo: [hummingbot/hummingbot](https://github.com/hummingbot/hummingbot) · Bản nháp: `content-drafts/2026-11-03-tai-chinh-dinh-luong-va-du-lieu-thi-truong/content.json`
