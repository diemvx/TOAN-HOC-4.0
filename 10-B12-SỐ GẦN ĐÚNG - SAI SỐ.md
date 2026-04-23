---
markmap:
  colorScheme: default
  math: katex
---

# 📏 BÀI 12. SỐ GẦN ĐÚNG VÀ SAI SỐ (TOÁN 10)

## 1. 📘 Khái niệm Số gần đúng & Sai số tuyệt đối
### ✅ Số gần đúng ($a$)
- Là số đại diện cho giá trị thực $a_0$ nhưng có một độ lệch nhất định.
- Ý nghĩa: Dùng trong đo đạc, tính toán khi không thể xác định chính xác giá trị thực.
### ✅ Sai số tuyệt đối ($\Delta_a$)
- Công thức: $\Delta_a = |a_0 - a|$.
- **Độ chính xác $d$:** Nếu $\Delta_a \le d$ thì ta viết $a_0 = a \pm d$.
- Khoảng giá trị của $a_0$: $a - d \le a_0 \le a + d$.
### ✅ Sai số tương đối ($\delta_a$)
- Công thức: $\delta_a = \frac{\Delta_a}{|a|} \le \frac{d}{|a|}$.
- Ý nghĩa: Đánh giá chất lượng của phép đo (càng nhỏ càng chính xác).

## 2. 📝 Quy tắc làm tròn số
### ✅ Làm tròn số căn cứ vào độ chính xác $d$
- **Quy tắc:** Nếu độ chính xác $d$ đến hàng nào thì ta làm tròn số gần đúng $a$ đến hàng **lớn hơn 1 đơn vị** so với hàng của $d$.
- **Ví dụ:** Cho $a = 15,318$ với $d = 0,05$ (hàng phần trăm) $\rightarrow$ Làm tròn đến hàng phần mười $\rightarrow$ Kết quả: $15,3$.
### ✅ Quy tắc làm tròn thông thường
- Chữ số ngay sau hàng làm tròn $< 5$: Giữ nguyên hàng làm tròn, thay các chữ số sau bằng số 0 (hoặc bỏ đi nếu sau dấu phẩy).
- Chữ số ngay sau hàng làm tròn $\ge 5$: Tăng hàng làm tròn thêm 1 đơn vị, thay các chữ số sau bằng số 0 (hoặc bỏ đi).

## 3. 🧩 Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định sai số tuyệt đối và sai số tương đối
- **Phương pháp:** Áp dụng công thức $\Delta_a$ (khi biết $a_0$) hoặc ước lượng qua $d$. Tính $\delta_a$ theo tỉ lệ phần trăm.
### 🔹 Dạng 2: Viết số quy tròn của số gần đúng
- **Phương pháp:** Xác định hàng làm tròn dựa vào $d$ hoặc theo yêu cầu cụ thể. Thực hiện quy tắc làm tròn số.
### 🔹 Dạng 3: Đánh giá độ chính xác của phép đo
- **Phương pháp:** So sánh sai số tương đối giữa các phép đo. Phép đo nào có $\delta_a$ nhỏ hơn thì chính xác hơn.

## 🌍 4. Ứng dụng thực tế
### ✅ Trong sản xuất công nghệ
- Các linh kiện điện tử (điện trở, tụ điện) luôn có sai số (ví dụ: $100\Omega \pm 5\%$).
- Xác định ngưỡng sai số cho phép để máy móc hoạt động đồng bộ.
### ✅ Trong đo đạc địa lý & xây dựng
- Đo khoảng cách giữa các hành tinh, chiều cao tòa tháp, diện tích đất đai.
- Tính toán lượng vật liệu cần thiết dựa trên kích thước gần đúng để tránh lãng phí hoặc thiếu hụt.
### ✅ Trong thống kê xã hội
- Các số liệu về dân số, GDP, tỉ lệ lạm phát thường là các số gần đúng được quy tròn để dễ quản lý.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Cài đặt định dạng số (Fix)
- **Mục đích:** Máy tự động làm tròn đến số chữ số thập phân mong muốn.
- **Thao tác (580VNX):** `SHIFT` + `MENU` $\rightarrow$ `3` (Number Format) $\rightarrow$ `1` (Fix) $\rightarrow$ Chọn số chữ số (0-9).
### ✅ Chuyển đổi số thập phân vô hạn sang gần đúng
- Sử dụng phím `S⇔D` để xem giá trị thập phân của các số như $\pi, \sqrt{2}, \frac{1}{3}$.
### ✅ Tính nhanh sai số tương đối (%)
- Nhập biểu thức: $\frac{d}{a} \times 100$.
- **Ví dụ:** $a = 200, d = 0,5 \rightarrow$ Nhập $\frac{0,5}{200} \times 100 \rightarrow$ Kết quả: $0,25\%$.

## ⚠️ Lưu ý của Giáo viên
- Sai số tuyệt đối $\Delta_a$ thường không biết chính xác vì $a_0$ chưa biết, nên ta thường dùng độ chính xác $d$ để chặn trên.
- Số chữ số có nghĩa: Những chữ số từ trái sang phải kể từ chữ số khác 0 đầu tiên.
- Khi nhân/chia các số gần đúng, sai số tương đối của tích/thương xấp xỉ tổng các sai số tương đối thành phần.