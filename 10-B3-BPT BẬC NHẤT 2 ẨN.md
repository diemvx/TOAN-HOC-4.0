---
markmap:
  colorScheme: default
  math: katex
---

# 📐 BÀI 3. BẤT PHƯƠNG TRÌNH BẬC NHẤT HAI ẨN (LỚP 10)

## 1. 📘 Đại cương về Bất phương trình (BPT)
### ✅ Định nghĩa
- Dạng tổng quát: $ax + by < c$ (hoặc $ax + by > c, ax + by \le c, ax + by \ge c$).
- Điều kiện: $a, b, c \in \mathbb{R}$ và $a^2 + b^2 \neq 0$.
### ✅ Miền nghiệm
- Khác với BPT một ẩn (là một khoảng/đoạn), miền nghiệm của BPT bậc nhất hai ẩn là một **nửa mặt phẳng** <BR> giới hạn bởi đường thẳng $d: ax + by = c$.
### ✅ Ví dụ
- $2x - y \le 3$ là một BPT bậc nhất hai ẩn với $a=2, b=-1, c=3$.

## 2. 🛠️ Các bước xác định miền nghiệm
### 🔹 Bước 1: Vẽ đường thẳng biên
- Vẽ đường thẳng $d: ax + by = c$ trên mặt phẳng tọa độ $Oxy$.
- **Lưu ý:** - Nếu BPT chứa dấu $\le, \ge$: Vẽ nét **liền** (lấy cả đường biên).
- Nếu BPT chứa dấu $<, >$: Vẽ nét **đứt** (không lấy đường biên).
### 🔹 Bước 2: Chọn điểm thử
- Lấy một điểm $M_0(x_0; y_0)$ không nằm trên $d$ (thường chọn gốc tọa độ $O(0;0)$ nếu $c \neq 0$).
### 🔹 Bước 3: Kiểm tra và Kết luận
- Tính giá trị $V = ax_0 + by_0$.
- So sánh $V$ với $c$:
    - Nếu khẳng định đúng: Miền nghiệm là nửa mặt phẳng chứa $M_0$.
    - Nếu khẳng định sai: Miền nghiệm là nửa mặt phẳng không chứa $M_0$.

## 📚 3. Hệ bất phương trình bậc nhất hai ẩn
### ✅ Định nghĩa
- Là một tập hợp gồm nhiều BPT bậc nhất hai ẩn.
### ✅ Miền nghiệm của hệ
- Là **phần giao** (phần chung) của các miền nghiệm của từng BPT trong hệ.
- Thường là một miền đa giác (tam giác, tứ giác...) hoặc miền không giới hạn.
### ✅ Bài toán tối ưu
- Tìm GTLN, GTNN của biểu thức $F(x; y) = mx + ny$ trên miền nghiệm đa giác.
- **Phương pháp:** Tọa độ $(x; y)$ làm cho $F$ đạt GTLN/GTNN luôn nằm tại một trong các **đỉnh** của đa giá miền nghiệm.

## 🌍 4. Ứng dụng thực tế
### ✅ Bài toán sản xuất
- Một xưởng sản xuất hai loại sản phẩm $A$ và $B$ với các giới hạn về nguyên liệu, thời gian máy, nhân công. <BR> Tìm số lượng mỗi loại để doanh thu cao nhất.
### ✅ Bài toán dinh dưỡng
- Kết hợp hai loại thực phẩm sao cho đảm bảo đủ lượng Protein, Vitamin cần thiết nhưng chi phí mua là thấp nhất.
### ✅ Bài toán quảng cáo
- Phân bổ ngân sách cho quảng cáo trên Facebook và Youtube sao cho tổng lượng tiếp cận khách hàng là lớn nhất.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Kiểm tra điểm thuộc miền nghiệm
- **Cách làm:** Nhập biểu thức $ax + by - c$ vào máy tính.
- **Thao tác:** Sử dụng phím `CALC`. Nhập tọa độ $x, y$ của điểm cần thử.
- **Kết quả:** Nếu kết quả cùng dấu với BPT thì điểm đó thuộc miền nghiệm.
### ✅ Tìm tọa độ đỉnh của miền đa giác
- Các đỉnh là giao điểm của các đường biên.
- **Thao tác:** Sử dụng tính năng giải hệ phương trình bậc nhất hai ẩn (`Menu 9` -> `1` -> `2`).
- Nhập các hệ số của hai đường thẳng cắt nhau để tìm $(x; y)$.
### ✅ Tính nhanh các giá trị tại đỉnh
- Nhập biểu thức $F(x; y)$ (ví dụ: $3X + 5Y$).
- Sử dụng `CALC` liên tiếp cho danh sách tọa độ các đỉnh để so sánh tìm GTLN/GTNN.

## ⚠️ Lưu ý của Giáo viên
- Khi vẽ hình, cần gạch bỏ phần **không phải** là nghiệm để phần trắng là miền nghiệm (giúp dễ nhìn phần giao của hệ BPT).
- Trong các bài toán kinh tế, đừng quên các điều kiện ẩn như $x \ge 0, y \ge 0$ (số lượng sản phẩm không thể âm).
