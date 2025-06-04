# YSC 2024 - Kỹ Thuật Phân Tích Dữ Liệu Bảo Toàn Tính Riêng Tư cho Khảo Sát Thông Tin Bệnh Trầm Cảm

## 📋 Tổng quan

Nghiên cứu về việc ứng dụng kỹ thuật **Differential Privacy (DP)** để bảo vệ thông tin cá nhân trong các cuộc khảo sát về bệnh trầm cảm. Dự án giúp người tham gia khảo sát cảm thấy thoải mái hơn khi chia sẻ thông tin nhạy cảm thông qua việc thêm nhiễu vào câu trả lời.

## 🎯 Mục tiêu

- Phát hiện sớm và khoanh vùng bệnh trầm cảm qua khảo sát
- Bảo vệ tính riêng tư của người tham gia khảo sát
- Cân bằng giữa độ chính xác và mức độ riêng tư
- Ứng dụng kỹ thuật **Coin Toss Mechanism** trong Differential Privacy

## 🔬 Phương pháp nghiên cứu

### Kỹ thuật chính
- **Differential Privacy (DP)**: Thêm nhiễu ngẫu nhiên vào kết quả khảo sát
- **Coin Toss Mechanism**: Giao thức bảo mật thông qua tung đồng xu
- **Statistical Analysis**: Phân tích thống kê với ma trận nhầm lẫn

### Quy trình Coin Toss
1. **Lần tung thứ nhất**: Nếu ngửa → trả lời thật, nếu sấp → tung tiếp
2. **Lần tung thứ hai**: Ngửa → trả lời "Có", Sấp → trả lời "Không"

## 📊 Công thức toán học

```
P(B) = (2p + 1) / 4
```
Trong đó:
- `p`: Xác suất thực tế của sự kiện
- `P(B)`: Xác suất trả lời "Yes" sau khi áp dụng cơ chế

## 🛠️ Công nghệ sử dụng

- **Phân phối thống kê**: Laplace, Gaussian
- **Tham số epsilon (ε)**: Kiểm soát mức độ riêng tư
- **Ma trận nhầm lẫn**: Đánh giá độ chính xác

## 👥 Nhóm nghiên cứu

**Trường Đại học Công nghiệp TP.HCM:**
- Nguyễn Hồng Tuyết Quỳnh *(Trưởng nhóm)*
- Nguyễn Hoàng Ái Linh
- Nguyễn Thị Viên
- Nguyễn Minh Phúc
- Lê Hà Tú My
- Nguyễn Quang Mạnh
- Lê Phúc Lữ
- Nguyễn Hữu Tình

**Trường Đại học Việt Đức:**
- Huỳnh Thị Kim Quỳnh

## 🎯 Ý nghĩa thực tiễn

- **Y tế**: Hỗ trợ chẩn đoán sớm bệnh trầm cảm
- **Xã hội**: Giảm stigma khi chia sẻ thông tin tâm lý
- **An toàn thông tin**: Bảo vệ dữ liệu nhạy cảm trong nghiên cứu

## 📚 Từ khóa

`bệnh trầm cảm` `differential privacy` `coin toss mechanism` `statistical analysis` `privacy preservation` `mental health survey`
---

*Nghiên cứu thuộc lĩnh vực: Điện – Điện tử – Công nghệ thông tin*
