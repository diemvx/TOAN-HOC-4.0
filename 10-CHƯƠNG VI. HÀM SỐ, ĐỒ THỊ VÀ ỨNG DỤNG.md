---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 ÔN TẬP CHƯƠNG VI: HÀM SỐ, ĐỒ THỊ VÀ ỨNG DỤNG

## 1. 📂 Đại cương về Hàm số
### ✅ Định nghĩa và Tập xác định ($D$)
- **Khái niệm:** Quy tắc $y = f(x)$ sao cho mỗi $x \in D$ tương ứng với duy nhất một $y \in \mathbb{R}$.
- **Tìm tập xác định:**
    - Hàm phân thức: Mẫu số $\neq 0$.
    - Hàm căn thức bậc hai: Biểu thức trong căn $\ge 0$.
    - Ví dụ: $f(x) = \frac{\sqrt{x-1}}{x-2} \Rightarrow D = [1; +\infty) \setminus \{2\}$.
### ✅ Sự biến thiên (Đồng biến/Nghịch biến)
- **Đồng biến:** $x_1 < x_2 \Rightarrow f(x_1) < f(x_2)$ (Đồ thị đi lên).
- **Nghịch biến:** $x_1 < x_2 \Rightarrow f(x_1) > f(x_2)$ (Đồ thị đi xuống).

## 2. 📊 Hàm số bậc hai $y = ax^2 + bx + c$ ($a \neq 0$)
### ✅ Đồ thị (Parabol)
- **Đỉnh $I$:** $I\left( -\frac{b}{2a}; -\frac{\Delta}{4a} \right)$.
- **Trục đối xứng:** Đường thẳng $x = -\frac{b}{2a}$.
- **Bề lõm:** $a > 0$ quay lên, $a < 0$ quay xuống.
### ✅ Các dạng toán trọng tâm
- **Dạng 1: Vẽ đồ thị:** Xác định đỉnh, trục đối xứng, giao điểm $Ox, Oy$.
- **Dạng 2: Tìm công thức hàm số:** Dựa vào tọa độ đỉnh, điểm đi qua hoặc trục đối xứng.
- **Dạng 3: Cực trị:** Giá trị lớn nhất (GTLN) / nhỏ nhất (GTNN) là tung độ đỉnh $y_I$.

## 🛠️ 3. Dấu của tam thức bậc hai & Bất phương trình
### ✅ Tam thức bậc hai $f(x) = ax^2 + bx + c$
- **Định lý về dấu:**
    - $\Delta < 0$: $f(x)$ cùng dấu $a$ với mọi $x \in \mathbb{R}$.
    - $\Delta = 0$: $f(x)$ cùng dấu $a$ với mọi $x \neq -\frac{b}{2a}$.
    - $\Delta > 0$: $f(x)$ có 2 nghiệm $x_1, x_2$. "Trong trái, ngoài cùng" so với dấu của $a$.
### ✅ Giải phương trình chứa căn
- Dạng $\sqrt{f(x)} = \sqrt{g(x)} \Rightarrow$ Bình phương, giải và thử lại nghiệm.
- Dạng $\sqrt{f(x)} = g(x) \Rightarrow$ ĐK $g(x) \ge 0$, bình phương 2 vế.

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý & Chuyển động
- Quỹ đạo ném xiên: $h(t) = -\frac{1}{2}gt^2 + v_0t + h_0$.
- Xác định độ cao cực đại (tọa độ đỉnh Parabol).
### ✅ Kinh doanh & Tối ưu hóa
- Hàm doanh thu $R(x)$, hàm chi phí $C(x) \Rightarrow$ Hàm lợi nhuận $L(x) = R(x) - C(x)$.
- Tìm mức sản lượng $x$ để lợi nhuận đạt tối đa.
### ✅ Kiến trúc
- Thiết kế hình dạng cổng Parabol, tính toán khoảng cách và chiều cao xây dựng.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Khảo sát hàm bậc hai (Menu 9 - 2 - 2)
- Nhập hệ số $a, b, c$.
- Nhấn `=` để xem: Nghiệm $x_1, x_2$; Hoành độ đỉnh ($x$-Value Minimum/Maximum); Tung độ đỉnh ($y$-Value).
### ✅ Giải Bất phương trình (Menu A)
- Chọn bậc 2, chọn chiều bất phương trình ($>, <, \ge, \le$).
- Máy xuất tập nghiệm trực tiếp.
### ✅ Lập bảng giá trị (Menu 8 - Table)
- Nhập hàm $f(x)$.
- Quan sát sự tăng/giảm của cột $f(x)$ để kết luận khoảng đồng biến, nghịch biến.

## ⚠️ Lưu ý của Giáo viên
- Phải luôn kiểm tra điều kiện của phương trình chứa căn để loại nghiệm ngoại lai.
- Khi tịnh tiến đồ thị theo vectơ $\overrightarrow{v} = (p; q)$, phương trình mới có dạng $y - q = f(x - p)$.
- Trong bài toán thực tế, cần đặt điều kiện cho biến số (ví dụ: $x > 0$, $t > 0$).