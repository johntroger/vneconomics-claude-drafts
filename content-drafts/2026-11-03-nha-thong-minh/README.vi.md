# Nhóm "Nhà thông minh và IoT" — bản nháp 03/11/2026

5 bài, key 234–238, `batch: 40`. Không trùng repo với các đợt trước. **Bản nháp, chưa import, chưa xuất bản.**

| Key | Bài | Repo | License (GitHub) | Sao (2026-11-03) | Commit gần nhất |
|---|---|---|---|---:|---|
| 234 | Home Assistant: điều khiển nhà thông minh tại chỗ, ưu tiên quyền riêng tư và chạy trên Raspberry Pi | [home-assistant/core](https://github.com/home-assistant/core) | Apache-2.0 | 91923 | 2026-11-03 |
| 235 | Zigbee2MQTT: dùng thiết bị Zigbee mà không cần cổng kết nối riêng của hãng | [Koenkk/zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt) | GPL-3.0 | 15783 | 2026-11-01 |
| 236 | Tasmota: phần mềm thay thế cho ổ cắm và thiết bị ESP, kèm cảnh báo nguy hiểm điện giật | [arendst/Tasmota](https://github.com/arendst/Tasmota) | GPL-3.0 | 24961 | 2026-11-02 |
| 237 | Frigate: đầu ghi camera chạy tại nhà, nhận diện vật thể thời gian thực bằng AI cục bộ | [blakeblackshear/frigate](https://github.com/blakeblackshear/frigate) | MIT | 37165 | 2026-11-02 |
| 238 | Valetudo: cho robot hút bụi chạy cục bộ không cần đám mây, và lưu ý về mô hình phát triển | [Hypfer/Valetudo](https://github.com/Hypfer/Valetudo) | Apache-2.0 | 9898 | 2026-11-01 |

## Điểm cần lưu ý
- **Tasmota**: README có cảnh báo NGUY HIỂM ĐIỆN GIẬT khi thiết bị nối điện lưới và nói tác giả không chịu trách nhiệm; bài nhấn mạnh nhờ thợ điện, xếp mức Khó.
- **Frigate**: camera ghi hình người nên có vấn đề riêng tư và pháp lý; bài không tư vấn pháp lý.
- **Valetudo**: can thiệp thiết bị có thể mất bảo hành; README tự nói mô hình quản trị là 'freeware, source available' dù giấy phép Apache-2.0.
- **Home Assistant**: README rất ngắn, chi tiết ở trang chính thức chưa đọc.

## Repo bị loại hoặc cân nhắc
- **esphome/esphome**: README chỉ vài trăm byte, GitHub trả NOASSERTION.
- **eclipse-mosquitto**: NOASSERTION; **openhab-core**: sao thấp (1,2 nghìn); **go2rtc**, **zwave-js-ui**: đủ điều kiện, chưa ưu tiên.
- **home-assistant/addons**: không tìm được qua tên đã dùng.

## Điểm chưa chắc chắn
- Độ khó là nhận định biên tập. Câu lệnh mẫu cho AI chưa thử.
- Không chạy hay nạp firmware nào, không chép lệnh cài. Không đánh giá an toàn điện của bất kỳ thiết bị nào.

