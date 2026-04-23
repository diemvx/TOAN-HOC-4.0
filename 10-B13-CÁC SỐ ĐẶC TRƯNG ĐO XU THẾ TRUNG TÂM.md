---
markmap:
  colorScheme: default
  math: katex
---

# 📊 BÀI 13. CÁC SỐ ĐẶC TRƯNG ĐO XU THẾ TRUNG TÂM (TOÁN 10)

## 1. 📂 Số trung bình cộng (Mean)
### ✅ Công thức
- **Mẫu số liệu không ghép nhóm:** $\bar{x} = \frac{x_1 + x_2 + \dots + x_n}{n} = \frac{\sum_{i=1}^{n} x_i}{n}$.
- **Mẫu số liệu có tần số:** $\bar{x} = \frac{n_1 x_1 + n_2 x_2 + \dots + n_k x_k}{n}$ (với $n = \sum n_i$).
### ✅ Ý nghĩa
- Đại diện cho các giá trị của mẫu số liệu.
- Được dùng để so sánh các tập dữ liệu cùng loại.
- **Hạn chế:** Bị ảnh hưởng lớn bởi các giá trị bất thường (quá lớn hoặc quá nhỏ).

## 2. 📂 Trung vị (Median - $M_e$)
### ✅ Cách xác định
- **Bước 1:** Sắp xếp mẫu số liệu theo thứ tự không giảm.
- **Bước 2:**
    - Nếu $n$ lẻ: $M_e$ là giá trị đứng ở vị trí thứ $\frac{n+1}{2}$.
    - Nếu $n$ chẵn: $M_e$ là trung bình cộng của hai giá trị đứng ở vị trí thứ $\frac{n}{2}$ và $\frac{n}{2} + 1$.
### ✅ Ý nghĩa
- Chia mẫu số liệu thành hai phần bằng nhau.
- Không bị ảnh hưởng bởi giá trị bất thường.

## 3. 📂 Tứ phân vị (Quartiles)
### ✅ Công thức xác định
- **Tứ phân vị thứ hai ($Q_2$):** Chính là trung vị $M_e$.
- **Tứ phân vị thứ nhất ($Q_1$):** Là trung vị của nửa bên trái $Q_2$ (không bao gồm $Q_2$ nếu $n$ lẻ).
- **Tứ phân vị thứ ba ($Q_3$):** Là trung vị của nửa bên phải $Q_2$ (không bao gồm $Q_2$ nếu $n$ lẻ).
### ✅ Ý nghĩa
- Chia mẫu số liệu thành 4 phần, mỗi phần chứa khoảng 25% số liệu.
- Dùng để xác định các giá trị ngoại lệ.

## 4. 📂 Mốt (Mode - $M_o$)
### ✅ Định nghĩa
- Là giá trị có tần số xuất hiện lớn nhất trong mẫu số liệu.
- Một mẫu số liệu có thể có nhiều mốt hoặc không có mốt.
### ✅ Ý nghĩa
- Cho biết giá trị nào có khả năng xuất hiện cao nhất (ví dụ: cỡ giày bán chạy nhất, món ăn yêu thích nhất).

## 🌍 5. Ứng dụng thực tế
### ✅ Trong giáo dục
- Tính điểm trung bình môn để đánh giá học lực của học sinh.
### ✅ Trong kinh tế & thị trường
- Xác định mức thu nhập trung bình của người dân.
- Tìm mức giá (Mốt) mà khách hàng sẵn sàng chi trả nhiều nhất cho một sản phẩm.
### ✅ Trong y sinh
- Theo dõi sự tăng trưởng trung bình của trẻ em theo độ tuổi.
- Sử dụng trung vị để đánh giá thời gian sống sót của bệnh nhân (tránh ảnh hưởng bởi trường hợp sống quá dài hoặc quá ngắn).

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Kích hoạt chế độ thống kê (Menu 6)
- **Thao tác:** `Menu` -> `6` (Statistics) -> `1` (1-Variable).
- **Bật cột tần số (nếu cần):** `Shift` + `Menu` -> Vuốt xuống chọn `Statistics` -> `On`.
### ✅ Nhập dữ liệu và Tính toán
- Nhập giá trị vào cột $X$, tần số vào cột $Freq$.
- Nhấn `AC` sau khi nhập xong.
- Nhấn `OPTN` -> `2` (1-Variable Calc).
### ✅ Đọc kết quả
- $\bar{x}$: Số trung bình cộng.
- $Med$: Trung vị ($Q_2$).
- $Q_1, Q_3$: Các tứ phân vị.
- $minX, maxX$: Giá trị nhỏ nhất và lớn nhất.

## ⚠️ Lưu ý của Giáo viên
- Khi tính Trung vị và Tứ phân vị, **bắt buộc** phải sắp xếp dãy số liệu trước.
- Cần phân biệt khi nào dùng Số trung bình (dữ liệu tập trung) và khi nào dùng Trung vị (dữ liệu có giá trị đột biến).
