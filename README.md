# 🖧 Đồ án Thiết kế Hệ thống Mạng Doanh Nghiệp

> Thiết kế hệ thống mạng hoàn chỉnh cho công ty O-UIT với hai cơ sở: trụ sở chính tại TP. Thủ Đức và chi nhánh tại Quận 3, đảm bảo hiệu suất, bảo mật và khả năng mở rộng.

---

## 📌 Mục tiêu dự án

- Xây dựng mô hình mạng logic và vật lý đầy đủ cho doanh nghiệp
- Phân chia VLAN theo phòng ban: CEO, HR, Developer, Tester,...
- Thiết lập kết nối **VPN Site-to-Site** giữa hai cơ sở
- Tích hợp hệ thống **Data Center** và mô hình **Cloud**
- Đảm bảo an toàn dữ liệu, phân tách mạng nội bộ và Wi-Fi công cộng

---

## 🧱 Mô hình kiến trúc mạng

<p align="center">
  <strong>📌 Mô hình tổng thể:</strong><br>
  
  ![TSC](https://github.com/Cuong312004/enterprise-network-design/blob/main/Picture1.png)

  <strong>🏢 Trụ sở chính – TP. Thủ Đức:</strong><br>
  ![TSC](https://github.com/Cuong312004/enterprise-network-design/blob/main/Picture2.png)

  <strong>🏬 Chi nhánh – Quận 3:</strong><br>
  ![CN](https://github.com/Cuong312004/enterprise-network-design/blob/main/Picture3.png)
</p>

---

## 🛠 Thành phần kỹ thuật

| Thành phần        | Mô tả |
|-------------------|------|
| Địa điểm triển khai | Trụ sở Thủ Đức & Chi nhánh Quận 3 |
| Công nghệ sử dụng | VPN IPsec, VLAN, DHCP, NAT, Wi-Fi |
| Công cụ thiết kế  | Cisco Packet Tracer, MS Visio |
| Thiết bị chính    | Router, Switch Layer 2/3, Access Point |
| Mô hình triển khai| Hybrid: On-Premise + Cloud |

---

## 📊 Bảng phân tích thiết bị

| Thiết bị           | Số lượng | Ghi chú |
|--------------------|----------|---------|
| Router Layer 3     | 2        | Mỗi cơ sở 1 thiết bị |
| Switch Layer 2     | 4        | Chia theo tầng, phòng ban |
| Access Point Wi-Fi | 2        | Công cộng & nội bộ |
| Firewall / NAT     | 1        | Thiết lập NAT nội bộ |

---

## 📁 Kết quả & Đánh giá

- Mô hình mạng trực quan, rõ ràng, có thể triển khai thực tế
- Có khả năng mở rộng cho các chi nhánh trong tương lai
- Áp dụng được các kỹ thuật định tuyến, phân quyền và bảo mật
- Bản vẽ sơ đồ mạng, bảng IP, bảng chi phí thiết bị đầy đủ

---

## 👨‍💻 Thực hiện bởi

- **Lưu Quốc Cường** – Vai trò: Trưởng nhóm, thiết kế sơ đồ mạng, phân chia IP, tính chi phí
- **Nhóm 04 – Môn NT113**

---

## 📝 Tài liệu đính kèm

- Báo cáo chi tiết: `enterprise-network-design.docx`
- Sơ đồ mạng: `enterprise-network-design.pkt` (Cisco Packet Tracer)

