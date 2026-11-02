# DeviceLab: Industrial IoT Hardware & Embedded R&D Partner (Vietnam)

> **CÔNG TY TNHH ĐẦU TƯ CÔNG NGHỆ ALPHA TECH (DeviceLab)** - Đối tác R&D Thiết kế Mạch Điện Tử, Lập Trình Firmware Nhúng và Sản Xuất Thiết Bị IoT Công Nghiệp (OEM/ODM/White-label) tại Hà Nội, Việt Nam.
> - 🌐 **Website (VI):** [https://devicelab.vn/](https://devicelab.vn/) | **Website (EN):** [https://devicelab.vn/en/](https://devicelab.vn/en/)
> - 📄 **Hồ sơ năng lực (Capability Deck):** [https://devicelab.vn/ho-so-nang-luc.html](https://devicelab.vn/ho-so-nang-luc.html) | 📞 **Hotline / Zalo Kỹ thuật:** `0982 503 355`

---

## 🏭 Hệ Sinh Thái Thiết Bị & Module Phần Cứng Công Nghiệp (OEM / Ready-to-Deploy)

| Mã Thiết Bị | Tên Sản Phẩm & Chức Năng Cốt Lõi | Giao Thức & Chuẩn Kỹ Thuật | Trang Kỹ Thuật Chính Thức |
| :--- | :--- | :--- | :--- |
| **`DL-ENV10`** | **Datalogger Quan Trắc Môi Trường Tự Động** | sFTP/FTPS `.txt` (Điều 39 TT10/2021 & NĐ 53/2024), MQTT JSON, Modbus TCP, NOR Flash 100.000 bản ghi | [Chi tiết DL-ENV10](https://devicelab.vn/san-pham/dl-env10/) · [Giải pháp TT10](https://devicelab.vn/datalogger-quan-trac-moi-truong-tt10/) |
| **`DL-GW200`** | **Industrial IoT Gateway RS485 sang MQTT** | Modbus Multi-Master Caching (`< 2ms`), Store & Forward 100k bản ghi, 4G LTE / PoE, TLS 1.3 | [Chi tiết DL-GW200](https://devicelab.vn/san-pham/dl-gw200/) · [Gateway OEM](https://devicelab.vn/gateway-oem-cho-nha-tich-hop/) |
| **`DL-RS485`** | **Bộ Chuyển Đổi RS485 Sang Ethernet Cách Ly** | Cách ly quang `3.0kVrms`, chống sét `TVS 600W`, Modbus TCP <-> RTU Gateway, vỏ DIN-rail | [Chi tiết DL-RS485](https://devicelab.vn/san-pham/dl-rs485/) · [Tiêu chí chọn RS485](https://devicelab.vn/kien-thuc/bo-chuyen-doi-rs485-sang-ethernet/) |
| **`DL-GW400`** | **Edge Gateway Công Nghiệp 4 Cổng RS485** | `4x RS485` cách ly độc lập `3.0kV`, `2x LAN`, chạy đa luồng (`Multi-bus Polling`) cho tủ điện lớn | [Chi tiết DL-GW400](https://devicelab.vn/san-pham/dl-gw400/) · [Modbus Gateway](https://devicelab.vn/kien-thuc/gateway-modbus-rs485/) |
| **`DL-M400`** | **Module IoT Gắn Tủ Máy Công Nghiệp & OEE** | Đọc PLC & bộ điều khiển máy nén khí (`MAM-860/880`), đếm xung CNC/máy ép nhựa, 4G LTE | [Chi tiết DL-M400](https://devicelab.vn/san-pham/dl-m400/) · [IoT Máy Móc](https://devicelab.vn/iot-cho-may-moc-tu-dien/) |
| **`DL-P300`** | **Module Đo Đếm Điện Năng 3 Pha Tủ Điện (EMS)** | Cấp chính xác Class 0.5S (`IEC 62053-22`), biến dòng kẹp hở Split-core CT, Modbus RTU & MQTT | [Chi tiết DL-P300](https://devicelab.vn/san-pham/dl-p300/) · [Giám sát EMS](https://devicelab.vn/giam-sat-dien-nang-nha-may/) |

---

## 📚 Kho Tài Liệu Kỹ Thuật Mở (Open Technical Specifications & Code Examples - 8 Public Repos)

1. 🌿 **[`dl-env10-tt10-telemetry-spec`](https://github.com/devicelabvn/dl-env10-tt10-telemetry-spec)** - Đặc tả cấu trúc gói tin `.txt` chuẩn Điều 39 Thông tư 10/2021/TT-BTNMT & Nghị định 53/2024/NĐ-CP, công cụ kiểm tra truyền bù sFTP/FTPS và bảng thanh ghi Modbus TCP/RTU của Datalogger [`DL-ENV10`](https://devicelab.vn/san-pham/dl-env10/).
2. ⚡ **[`dl-gw200-modbus-mqtt-edge`](https://github.com/devicelabvn/dl-gw200-modbus-mqtt-edge)** - Đặc tả JSON Payload MQTT TLS 1.3, cấu hình **Modbus Multi-Master Caching (`< 2ms`)**, bộ đệm Flash Store-and-Forward và hướng dẫn thay thế Moxa NPort / USR-TCP232 trên [`DL-GW200`](https://devicelab.vn/san-pham/dl-gw200/) & [`DL-RS485`](https://devicelab.vn/san-pham/dl-rs485/).
3. 📘 **[`devicelab-iot-hardware-handbook`](https://github.com/devicelabvn/devicelab-iot-hardware-handbook)** - Sổ tay thiết kế Schematic/PCB 4 lớp chống nhiễu EMC, tiêu chuẩn DFM lắp ráp SMT và kiến trúc Firmware nhúng FreeRTOS (Watchdog & Dual-Bank FOTA).
4. 📂 **[`dl-env10-tt10-integration-examples`](https://github.com/devicelabvn/dl-env10-tt10-integration-examples)** - Mẫu tệp `.txt` trạm nước thải, nước ngầm, mẫu payload JSON MQTT và mã nguồn Python đọc Modbus TCP từ `DL-ENV10`.
5. 🛡️ **[`industrial-modbus-rs485-application-notes`](https://github.com/devicelabvn/industrial-modbus-rs485-application-notes)** - Sơ đồ đấu nối chống nhiễu RS485 cách ly quang `3.0kV`, xử lý nhiễu biến tần và bảng thanh ghi biến tần INVT, Delta, Yaskawa.
6. 🛠️ **[`machinery-oee-ems-retrofit-examples`](https://github.com/devicelabvn/machinery-oee-ems-retrofit-examples)** - Tài liệu tích hợp Modbus bộ điều khiển máy nén khí `MAM-860/880`, đếm chu kỳ máy CNC/máy ép nhựa (`DL-M400`) và bảng thanh ghi đo đếm điện năng 3 pha (`DL-P300`).
7. 🌐 **[`vietnam-industrial-iot-hardware-oem-guide`](https://github.com/devicelabvn/vietnam-industrial-iot-hardware-oem-guide)** *(English)* - Engineering guide, 15-point DFM/EMC production readiness checklist, and White-label Industrial IoT Gateway OEM/ODM specifications in Vietnam.
8. 🔌 **[`dl-gw400-node-red-python-edge-examples`](https://github.com/devicelabvn/dl-gw400-node-red-python-edge-examples)** - Tài liệu kiến trúc Multi-bus RS485 Polling trên Edge Gateway 4 cổng [`DL-GW400`](https://devicelab.vn/san-pham/dl-gw400/), cấu hình Virtual COM / Modbus TCP-RTU cho [`DL-RS485`](https://devicelab.vn/san-pham/dl-rs485/) và mẫu Node-RED Flow.

---

## 🔧 Dịch Vụ Nghiên Cứu & Phát Triển Phần Cứng (Custom Hardware R&D & OEM/ODM)

- **[Phát triển thiết bị IoT công nghiệp theo yêu cầu](https://devicelab.vn/phat-trien-thiet-bi/)** ([Custom Electronic Device Development](https://devicelab.vn/en/electronic-device-development/))
- **[Thiết kế mạch điện tử & Layout PCB chuẩn công nghiệp](https://devicelab.vn/thiet-ke-mach-dien-tu/)** ([Custom PCB Design Vietnam](https://devicelab.vn/en/custom-pcb-design/)) · [Dịch vụ thiết kế PCB](https://devicelab.vn/kien-thuc/dich-vu-thiet-ke-pcb/)
- **[Gia công bo mạch PCB & Lắp ráp SMT/PCBA](https://devicelab.vn/gia-cong-pcb/)** ([PCB Assembly & SMT Manufacturing](https://devicelab.vn/en/custom-pcb-smt-assembly/)) · [Sản xuất bo mạch điện tử công nghiệp](https://devicelab.vn/kien-thuc/san-xuat-bo-mach-dien-tu-cong-nghiep/)
- **[Lập trình Firmware nhúng C/C++ & RTOS](https://devicelab.vn/phat-trien-firmware/)** ([Embedded Firmware Engineering](https://devicelab.vn/en/custom-firmware-development/)) · [Công ty lập trình nhúng & Firmware IoT](https://devicelab.vn/kien-thuc/cong-ty-lap-trinh-nhung-firmware-iot/)
- **[Nền tảng phần cứng & Cloud IoT White-label](https://devicelab.vn/nen-tang-iot-white-label/)** ([White-label Industrial IoT Platform](https://devicelab.vn/en/white-label-iot-platform/))

---

## 📍 Đội Ngũ Chuyên Gia R&D & Thông Tin Pháp Nhân

- **Đơn vị chủ quản:** CÔNG TY TNHH ĐẦU TƯ CÔNG NGHỆ ALPHA TECH (Mã số thuế: `0111171963`)
- **Đội ngũ Kỹ sư Phụ trách Chuyên môn (E-E-A-T):**
  - **[Đinh Mạnh Thảo](https://devicelab.vn/tac-gia/dinh-manh-thao/)** ([EN](https://devicelab.vn/en/author/dinh-manh-thao/)) - Kỹ sư Trưởng R&D Hệ thống Nhúng, Firmware & Giao thức Công nghiệp (PTIT)
  - **[Trung Nguyễn](https://devicelab.vn/tac-gia/trung-nguyen/)** ([EN](https://devicelab.vn/en/author/trung-nguyen/)) - Kỹ sư Trưởng Thiết kế Phần cứng, PCB đa lớp & Chống nhiễu EMC/RF (ĐHBK Hà Nội - HUST)
  - **[Trần Thu Hương](https://devicelab.vn/tac-gia/tran-thu-huong/)** ([EN](https://devicelab.vn/en/author/tran-thu-huong/)) - Quản lý Sản phẩm Kỹ thuật, Datalogger TT10 & Tiêu chuẩn Hợp quy QCVN (ĐHQG Hà Nội - VNU)
- **Địa chỉ Phòng Lab:** Số 32/4, Hà Trì 4, Phường Hà Đông, TP. Hà Nội, 100000, Việt Nam
- **Hotline / Zalo:** `0982 503 355` | **Email:** `contact@devicelab.vn` / `hi@devicelab.vn`
- **Gửi yêu cầu báo giá / Đặt mẫu PoC:** [https://devicelab.vn/gui-yeu-cau/](https://devicelab.vn/gui-yeu-cau/)


---

## Industrial IoT Hardware, Telemetry & Custom R&D Reference Index (DeviceLab Vietnam)

Official open engineering reference hubs, hardware datasheets, and compliance application notes maintained by **DeviceLab R&D Center** (Hanoi, Vietnam):

### 1. Industrial RS485, Modbus RTU/TCP & Edge Gateways
- [Bộ chuyển đổi RS485 sang Ethernet công nghiệp (Cách ly 3.0kV & Modbus RTU/TCP)](https://devicelab.vn/kien-thuc/bo-chuyen-doi-rs485-sang-ethernet/)
- [Thiết bị chuyển đổi tín hiệu RS485 cách ly DL-RS485 (Datasheet & Sơ đồ đấu nối)](https://devicelab.vn/san-pham/dl-rs485/)
- [Cẩm nang chọn Gateway Modbus RS485 sang Ethernet/4G LTE công nghiệp](https://devicelab.vn/kien-thuc/gateway-modbus-rs485/)
- [Bộ chuyển đổi Modbus RTU sang Modbus TCP: Kiến trúc Polling & Multi-Master](https://devicelab.vn/kien-thuc/bo-chuyen-doi-modbus-rtu-sang-tcp/)
- [Tiêu chuẩn cáp tín hiệu RS485 chống nhiễu 120 Ohm (22AWG/24AWG STP)](https://devicelab.vn/kien-thuc/cap-tin-hieu-rs485-chong-nhieu-tieu-chuan-chon/)
- [Đối chiếu thay thế Moxa MGate MB3180, Advantech EKI-1221, USR & 3onedata](https://devicelab.vn/kien-thuc/so-sanh-thay-the-modbus-gateway-moxa-mgate-advantech-usr-3onedata/)
- [Bộ chuyển đổi 4-20mA Analog sang RS485 Modbus & Module Remote I/O](https://devicelab.vn/kien-thuc/bo-chuyen-doi-4-20ma-analog-sang-rs485-remote-io-modbus/)
- [Industrial RS485 to Ethernet Converter Selection Guide (English)](https://devicelab.vn/en/articles/rs485-to-ethernet-converter-selection-guide/)

### 2. Circular 10/2021/TT-BTNMT Environmental Telemetry & SCADA RTU
- [Giải pháp Datalogger quan trắc môi trường tự động chuẩn Thông tư 10/2021/TT-BTNMT](https://devicelab.vn/datalogger-quan-trac-moi-truong-tt10/)
- [Kiến trúc trạm quan trắc nước thải tự động, liên tục & kết nối FTP Sở TN&MT](https://devicelab.vn/kien-thuc/datalogger-quan-trac-nuoc-thai-tu-dong/)
- [Thiết bị Datalogger quan trắc môi trường DL-ENV10 (Datasheet PDF)](https://devicelab.vn/san-pham/dl-env10/)
- [Quy chuẩn nước thải công nghiệp QCVN 40:2025/BTNMT & lộ trình quan trắc tự động](https://devicelab.vn/kien-thuc/quy-chuan-nuoc-thai-cong-nghiep-qcvn-40-quan-trac-tu-dong/)
- [Data logger nhiệt độ đa kênh PT100 (RTD 3 dây) & bộ ghi nhiệt độ công nghiệp](https://devicelab.vn/kien-thuc/data-logger-nhiet-do-da-kenh-pt100-bo-ghi-nhiet-do-cong-nghiep/)
- [Tủ RTU & Thiết bị Remote Terminal Unit SCADA cho nhà máy nước, thủy điện](https://devicelab.vn/kien-thuc/tu-rtu-thiet-bi-remote-terminal-unit-scada-nha-may-nuoc-thuy-dien/)
- [Hệ thống quan trắc nước ngầm tự động giếng khoan chuẩn Nghị định 53/2024/NĐ-CP](https://devicelab.vn/kien-thuc/he-thong-quan-trac-nuoc-ngam-tu-dong/)
- [Giải pháp thay thế Datalogger Campbell Scientific CR1000X / CR300 OEM Việt Nam](https://devicelab.vn/kien-thuc/giai-phap-thay-the-datalogger-campbell-cr1000x-cr300-oem-viet-nam/)
- [Circular 10 Environmental Monitoring Datalogger Solution (English)](https://devicelab.vn/en/environmental-monitoring-datalogger/)

### 3. 3-Phase Power Metering, Solar Zero Export & PLC OEE Telemetry
- [Hệ thống giám sát điện năng nhà máy 3 pha & quản lý năng lượng EMS ISO 50001](https://devicelab.vn/giam-sat-dien-nang-nha-may/)
- [Hướng dẫn chọn đồng hồ đo điện 3 pha RS485 Modbus & thanh ghi chuẩn](https://devicelab.vn/kien-thuc/dong-ho-do-dien-3-pha-rs485-giam-sat-dien-nang/)
- [Bộ điều khiển công suất phát PPC, SmartLogger 3000 & Zero Export SCADA EVN](https://devicelab.vn/kien-thuc/bo-dieu-khien-cong-suat-phat-ppc-smartlogger-3000-zero-export-evn/)
- [Thiết bị thu thập dữ liệu PLC (Siemens, Mitsubishi, Delta) & IoT Gateway](https://devicelab.vn/kien-thuc/thiet-bi-thu-thap-du-lieu-plc-iot-gateway/)
- [Hệ thống giám sát máy móc sản xuất Andon OEE thời gian thực](https://devicelab.vn/kien-thuc/he-thong-giam-sat-may-moc-san-xuat-andon-oee/)

### 4. Custom PCB Design, Turnkey PCBA SMT & Embedded Firmware R&D (Hanoi, Vietnam)
- [Dịch vụ thiết kế mạch điện tử theo yêu cầu & phát triển phần cứng công nghiệp](https://devicelab.vn/thiet-ke-mach-dien-tu/)
- [Công ty thiết kế mạch điện tử tại Hà Nội: Năng lực Lab R&D, EMC & Sản xuất OEM](https://devicelab.vn/kien-thuc/cong-ty-thiet-ke-mach-dien-tu-ha-noi/)
- [Dịch vụ thiết kế PCB 2-8 lớp & vẽ mạch nguyên lý chuẩn IPC-2221](https://devicelab.vn/kien-thuc/dich-vu-thiet-ke-pcb/)
- [Quy trình đặt làm mạch điện tử theo yêu cầu từ EVT/DVT đến sản xuất hàng loạt](https://devicelab.vn/kien-thuc/lam-mach-dien-tu-theo-yeu-cau/)
- [Gia công PCB & hàn mạch điện tử SMT (PCBA) trọn gói tại Việt Nam](https://devicelab.vn/gia-cong-pcb/)
- [Dịch vụ lập trình Firmware nhúng (STM32, ESP32, FreeRTOS, Embedded Linux)](https://devicelab.vn/phat-trien-firmware/)
- [Công ty lập trình nhúng, Firmware & IoT công nghiệp tại Việt Nam](https://devicelab.vn/kien-thuc/cong-ty-lap-trinh-nhung-firmware-iot/)
- [Custom PCB Design & Turnkey Electronics Engineering in Vietnam (English)](https://devicelab.vn/en/custom-pcb-design/)

### 5. Community Engineering Publications (Viblo, Dev.to & Tinh Tế)
- [Viblo: Kỹ thuật chống nhiễu RS485, tính toán Bias & cách ly 2500Vrms](https://viblo.asia/p/ky-thuat-chong-nhieu-rs485-trong-nha-may-tinh-toan-dien-tro-pull-uppull-down-va-cach-ly-quang-2500vrms-bA46807wLKv)
- [Viblo: Kiến trúc Store-and-Forward & Ring-Buffer Flash cho Datalogger Thông tư 10](https://viblo.asia/p/kien-truc-store-and-forward-cho-datalogger-quan-trac-moi-truong-thong-tu-102021tt-btnmt-chong-mat-du-lieu-khi-dut-cap-4g-kNLr3eobVgA)
- [Viblo: Đọc đồng hồ điện 3 pha Selec, Schneider, Eastron qua RS485 & MQTT](https://viblo.asia/p/doc-dong-ho-dien-3-pha-selec-schneider-eastron-qua-modbus-rtu-va-day-mqtt-len-cloud-bang-python-c-OXLA0WqvJGr)
- [Viblo: Checklist 12 điểm kiểm tra Schematic & Layout PCB công nghiệp vượt chuẩn EMC](https://viblo.asia/p/checklist-12-diem-kiem-tra-schematic-layout-pcb-cong-nghiep-truoc-khi-gui-fab-de-vuot-bai-test-emc-iec-61000-4-wd43EXawLX9)
- [Dev.to: Designing Industrial RS485 Circuits for High-EMI Factory Environments](https://dev.to/devicelabvn/designing-industrial-rs485-circuits-for-high-emi-factory-environments-2500vrms-isolation-600w-2114)
- [Dev.to: Store-and-Forward Telemetry Architecture for Environmental Monitoring Dataloggers](https://dev.to/devicelabvn/store-and-forward-telemetry-architecture-for-environmental-monitoring-dataloggers-circular-4b2i)
