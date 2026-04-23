---
markmap:
  colorScheme: google
  math: katex
---

# 📊 ÔN TẬP CHƯƠNG V:<BR>CÁC SỐ ĐẶC TRƯNG CỦA MẪU SỐ LIỆU KHÔNG GHÉP NHÓM

## 1. 📏 Các số đặc trưng đo xu thế trung tâm
### ✅ Số trung bình (Mean)
- **Công thức:** $\bar{x} = \frac{x_1 + x_2 + \dots + x_n}{n} = \frac{1}{n} \sum_{i=1}^{k} n_i x_i$.
- **Ý nghĩa:** Đại diện cho các số liệu của mẫu, dùng để so sánh khi các mẫu có cùng quy mô.
### ✅ Trung vị (Median - $M_e$)
- **Cách tìm:** Sắp xếp mẫu số liệu theo thứ tự không giảm.
    - Nếu $n$ lẻ: $M_e$ là số đứng chính giữa (vị trí $\frac{n+1}{2}$).
    - Nếu $n$ chẵn: $M_e$ là trung bình cộng của hai số đứng giữa (vị trí $\frac{n}{2}$ và $\frac{n}{2} + 1$).
- **Ý nghĩa:** Chia mẫu số liệu thành hai phần bằng nhau, không bị ảnh hưởng bởi giá trị bất thường.
### ✅ Tứ phân vị (Quartiles)
- **Q2:** Chính là trung vị $M_e$.
- **Q1:** Trung vị của nửa bên trái $Q_2$ (không bao gồm $Q_2$ nếu $n$ lẻ).
- **Q3:** Trung vị của nửa bên phải $Q_2$ (không bao gồm $Q_2$ nếu $n$ lẻ).
### ✅ Mốt (Mode - $M_o$)
- **Định nghĩa:** Giá trị có tần số xuất hiện lớn nhất trong mẫu số liệu.
- **Lưu ý:** Một mẫu có thể có nhiều mốt hoặc không có mốt.

## 2. 📉 Các số đặc trưng đo độ phân tán
### ✅ Khoảng biến thiên ($R$) và Khoảng tứ phân vị ($\Delta_Q$)
- **Khoảng biến thiên:** $R = x_{max} - x_{min}$.
- **Khoảng tứ phân vị:** $\Delta_Q = Q_3 - Q_1$.
- **Ý nghĩa:** Độ lệch giữa các giá trị. $\Delta_Q$ dùng để xác định giá trị bất thường.
### ✅ Phương sai ($s^2$) và Độ lệch chuẩn ($s$)
- **Phương sai:** $s^2 = \frac{1}{n} \sum_{i=1}^{n} (x_i - \bar{x})^2$.
- **Độ lệch chuẩn:** $s = \sqrt{s^2}$.
- **Ý nghĩa:** Đo mức độ rời rạc của số liệu so với số trung bình. $s$ càng nhỏ, số liệu càng tập trung (ổn định).

## 🛠️ 3. Phương pháp xác định giá trị bất thường (Outliers)
- **Bước 1:** Tính $Q_1, Q_3$ và $\Delta_Q = Q_3 - Q_1$.
- **Bước 2:** Xác định khoảng an toàn $[Q_1 - 1,5\Delta_Q; Q_3 + 1,5\Delta_Q]$.
- **Bước 3:** Giá trị $x$ nằm ngoài khoảng này là giá trị bất thường.

## 🌍 4. Ứng dụng thực tế
### ✅ Trong Giáo dục
- So sánh điểm trung bình và độ lệch chuẩn của hai lớp để đánh giá lớp nào học đều hơn.
### ✅ Trong Kinh doanh
- Phân tích mức lương của nhân viên (dùng Trung vị tốt hơn Trung bình nếu có lương lãnh đạo quá cao).
- Thống kê cỡ giày, cỡ áo bán chạy nhất (dùng Mốt).
### ✅ Trong Nông nghiệp
- So sánh năng suất của hai giống cây trồng dựa trên độ lệch chuẩn để chọn giống có sản lượng ổn định.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Cài đặt Thống kê 1 biến
- **Bước 1:** `Menu` ⮕ `6` (Statistics) ⮕ `1` (1-Variable).
- **Bước 2 (Bật cột tần số nếu cần):** `Shift` ⮕ `Menu` ⮕ `Mũi tên xuống` ⮕ `Statistics` ⮕ `On`.
### ✅ Nhập dữ liệu & Xem kết quả
- Nhập số liệu vào bảng. Nhấn `AC`.
- **Xem tất cả kết quả:** `OPTN` ⮕ `2` (1-Variable Calc).
- **Các ký hiệu trên máy:**
    - $\bar{x}$: Số trung bình.
    - $\sigma^2 x$: Phương sai (trong chương trình phổ thông thường lấy $s^2$).
    - $\sigma x$: Độ lệch chuẩn ($s$).
    - $minX, Q_1, Med, Q_3, maxX$: Các giá trị vị trí.

## ⚠️ Lưu ý của Giáo viên
- Khi tính Trung vị và Tứ phân vị, **bắt buộc** phải sắp xếp mẫu số liệu theo thứ tự tăng dần trước.
- Hiểu rõ khi nào dùng Số trung bình (dữ liệu tập trung) và khi nào dùng Trung vị (dữ liệu có giá trị đột biến).
