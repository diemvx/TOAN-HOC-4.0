---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 ÔN TẬP CHƯƠNG II <BR> BẤT PHƯƠNG TRÌNH & HỆ BẤT PHƯƠNG TRÌNH BẬC NHẤT HAI ẨN

## 1. 📘 Bất phương trình bậc nhất hai ẩn
### ✅ Định nghĩa
- **Dạng tổng quát:** $ax + by < c$ (hoặc $\le, >, \ge$).
- Trong đó $a, b, c$ là các số thực đã cho, $a^2 + b^2 \neq 0$.
### ✅ Biểu diễn miền nghiệm
- **Bước 1:** Vẽ đường thẳng $d: ax + by = c$.
- **Bước 2:** Lấy một điểm $M_0(x_0; y_0) \notin d$ (thường chọn $O(0;0)$ nếu $c \neq 0$).
- **Bước 3:** Tính $P = ax_0 + by_0$. So sánh $P$ với $c$ để kết luận miền nghiệm.
### ✅ Ý nghĩa hình học
- Đường thẳng $d$ chia mặt phẳng tọa độ thành hai nửa mặt phẳng, một trong hai là miền nghiệm.

## 📚 2. Hệ bất phương trình bậc nhất hai ẩn
### ✅ Định nghĩa
- Là một tập hợp gồm hai hay nhiều bất phương trình bậc nhất hai ẩn.
### ✅ Cách giải (Tìm miền nghiệm)
- Vẽ tất cả các đường thẳng tương ứng với các bất phương trình trong hệ.
- Xác định miền nghiệm của từng bất phương trình.
- **Phần giao** của các miền nghiệm trên chính là miền nghiệm của hệ (thường là một miền đa giác).

## 🚀 3. Bài toán tối ưu hóa (Quy hoạch tuyến tính)
### ✅ Bài toán tìm GTLN, GTNN
- Cho biểu thức $F(x; y) = ax + by$ với $(x; y)$ thuộc miền nghiệm của hệ bất phương trình.
- **Định lý:** Giá trị lớn nhất hoặc nhỏ nhất của $F(x; y)$ luôn đạt được tại một trong các **đỉnh của đa giác** miền nghiệm.
### ✅ Các bước thực hiện
- **Bước 1:** Xác định hệ bất phương trình từ dữ kiện bài toán.
- **Bước 2:** Vẽ miền đa giác nghiệm.
- **Bước 3:** Tìm tọa độ các đỉnh của đa giác.
- **Bước 4:** Thay tọa độ các đỉnh vào $F(x; y)$ để so sánh.

## 🌍 4. Ứng dụng thực tế
### ✅ Kinh doanh & Sản xuất
- Tối ưu hóa lợi nhuận: Sản xuất bao nhiêu sản phẩm loại A, loại B để lãi cao nhất với nguồn lực hạn chế (vốn, nhân công, nguyên liệu).
### ✅ Dinh dưỡng & Khẩu phần ăn
- Lập thực đơn sao cho đảm bảo lượng Vitamin tối thiểu nhưng chi phí mua thực phẩm là thấp nhất.
### ✅ Lập kế hoạch vận tải
- Phân bổ số lượng chuyến xe từ kho đến các cửa hàng để chi phí vận chuyển tối thiểu.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tìm tọa độ đỉnh đa giác (Menu 9 - 1 - 2)
- Miền nghiệm đa giác được tạo bởi giao điểm các đường thẳng.
- **Thao tác:** Sử dụng chức năng giải hệ phương trình bậc nhất hai ẩn để tìm tọa độ các giao điểm một cách chính xác và nhanh chóng.
### ✅ Tính giá trị biểu thức $F(x; y)$ (Phím CALC)
- Nhập biểu thức $ax + by$ vào máy tính.
- Nhấn `CALC`, nhập tọa độ $x, y$ của từng đỉnh để tính giá trị nhanh, tránh nhầm lẫn dấu.
### ✅ Kiểm tra điểm thuộc miền nghiệm
- Nhập biểu thức vế trái của bất phương trình (VD: $x - 2y$).
- Nhấn `CALC`, nhập tọa độ điểm cần thử. So sánh kết quả với vế phải.

## ⚠️ Lưu ý của Giáo viên
- Khi vẽ đường thẳng: Nếu bất phương trình có dấu "=" ($\le$ hoặc $\ge$) thì vẽ nét liền (lấy cả biên). Nếu không có dấu "=" ($<$ hoặc $>$) thì vẽ nét đứt (không lấy biên).
- Luôn cẩn thận khi xác định các điều kiện ẩn (ví dụ: số sản phẩm $x, y$ phải là số nguyên không âm $x \ge 0, y \ge 0, x, y \in \mathbb{Z}$).
- Trong các bài toán thực tế, cần quy đổi các đơn vị đo lường về cùng một đơn vị trước khi lập hệ.