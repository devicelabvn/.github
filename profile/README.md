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
