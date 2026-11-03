# Lộ trình 85 — Phần cứng nhúng và máy in 3D (chú ý an toàn)

Từ công cụ phát triển nhúng, bộ SDK cho bo mạch phổ biến, hệ điều hành thời gian thực đến giao diện điều khiển và firmware máy in 3D; chú ý nạp sai firmware làm hỏng bo mạch, nguy cơ cháy của máy in 3D, đổi mật khẩu mặc định và giấy phép GPL, AGPL.

> Bản nháp. Mỗi bước trỏ tới bài nháp trong `content-drafts/` (theo key). Độ khó là nhận định biên tập, chưa kiểm chứng bằng cách dùng thật.

1. **NodeMCU: firmware mã nguồn mở dựa trên Lua cho SoC Wi-Fi ESP8266, mô hình lập trình bất đồng bộ theo sự kiện giống Node.js, hơn 70 mô-đun C dựng sẵn, giấy phép MIT** (key 642, độ khó: Trung bình) — Lua cho ESP8266 (trung bình).  
   Repo: [nodemcu/nodemcu-firmware](https://github.com/nodemcu/nodemcu-firmware) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
2. **Raspberry Pi Pico SDK: tiêu đề, thư viện và hệ dựng để viết chương trình C, C++ hoặc hợp ngữ cho vi điều khiển dòng RP (Pico, Pico 2), có thư viện cho hẹn giờ, đồng bộ, Wi-Fi, Bluetooth, USB, đa nhân** (key 640, độ khó: Trung bình) — SDK C cho Raspberry Pi Pico (trung bình).  
   Repo: [raspberrypi/pico-sdk](https://github.com/raspberrypi/pico-sdk) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
3. **PlatformIO Core: hệ sinh thái phát triển phần mềm nhúng mã nguồn mở, hệ dựng đa nền tảng đa kiến trúc, gỡ lỗi thống nhất, phân tích mã tĩnh và kiểm thử từ xa, giấy phép Apache 2.0** (key 637, độ khó: Trung bình) — Hệ dựng nhúng đa nền tảng (trung bình).  
   Repo: [platformio/platformio-core](https://github.com/platformio/platformio-core) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
4. **OctoPrint: giao diện web nhanh gọn để điều khiển máy in 3D tiêu dùng, phần mềm tự do theo GNU Affero GPL phiên bản 3, có diễn đàn, FAQ, tài liệu và kho plugin chính thức** (key 643, độ khó: Trung bình) — Điều khiển máy in 3D qua web (trung bình).  
   Repo: [OctoPrint/OctoPrint](https://github.com/OctoPrint/OctoPrint) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
5. **ESP-IDF: khung phát triển chính thức của Espressif cho các SoC ESP (Windows, Linux, macOS), có lịch hỗ trợ phát hành, bảng tương thích với phiên bản chip, công cụ dòng lệnh để dựng, nạp và cấu hình** (key 639, độ khó: Khó) — Khung phát triển cho chip ESP (khó).  
   Repo: [espressif/esp-idf](https://github.com/espressif/esp-idf) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
6. **FreeRTOS Kernel: nhân hệ điều hành thời gian thực chứa mã nguồn và các bản chuyển (port) của nhân, là mô-đun con của kho FreeRTOS có sẵn dự án demo; README nêu bản V11.1.0 thuộc LTS 202406** (key 641, độ khó: Khó) — Nhân RTOS (khó).  
   Repo: [FreeRTOS/FreeRTOS-Kernel](https://github.com/FreeRTOS/FreeRTOS-Kernel) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
7. **Zephyr: hệ điều hành thời gian thực (RTOS) co giãn, hỗ trợ nhiều kiến trúc phần cứng, tối ưu cho thiết bị hạn chế tài nguyên và xây có chú trọng bảo mật, từ cảm biến đơn giản đến cổng IoT** (key 638, độ khó: Rất khó) — RTOS co giãn (rất khó).  
   Repo: [zephyrproject-rtos/zephyr](https://github.com/zephyrproject-rtos/zephyr) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
8. **Marlin: firmware mã nguồn mở cho máy in 3D, hỗ trợ cả bo ARM 32 bit và AVR 8 bit, tối đa 9 trục và 8 đầu đùn; README nêu nhánh bugfix 2.1 không dùng cho sản xuất, giấy phép GPL** (key 644, độ khó: Rất khó) — Firmware máy in 3D; chú ý nhiệt (rất khó).  
   Repo: [MarlinFirmware/Marlin](https://github.com/MarlinFirmware/Marlin) · Bản nháp: `content-drafts/2026-11-03-phan-cung-nhung-va-may-in-3d/content.json`
