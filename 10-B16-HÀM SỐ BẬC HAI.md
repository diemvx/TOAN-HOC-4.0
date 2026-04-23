---
markmap:
  colorScheme: google
  math: katex
---

# 📐 HÀM SỐ BẬC HAI <BR> $y = ax^2 + bx + c$ ($a \neq 0$)

## 1. 📂 Định nghĩa và Các thành phần cơ bản
### ✅ Công thức tổng quát
- Dạng: $y = f(x) = ax^2 + bx + c$ ($a, b, c \in \mathbb{R}, a \neq 0$).
- Tập xác định: $D = \mathbb{R}$.
### ✅ Đồ thị (Parabol)
- **Đỉnh $I$:** $I\left( -\frac{b}{2a}; -\frac{\Delta}{4a} \right)$ với $\Delta = b^2 - 4ac$.
- **Trục đối xứng:** Đường thẳng $x = -\frac{b}{2a}$.
- **Bề lõm:**
    - $a > 0$: Bề lõm quay lên trên (Đồ thị có điểm thấp nhất).
    - $a < 0$: Bề lõm quay xuống dưới (Đồ thị có điểm cao nhất).
### ✅ Bảng biến thiên
- **Nếu $a > 0$:** Hàm số nghịch biến trên $(-\infty; -\frac{b}{2a})$ và đồng biến trên $(-\frac{b}{2a}; +\infty)$.
- **Nếu $a < 0$:** Hàm số đồng biến trên $(-\infty; -\frac{b}{2a})$ và nghịch biến trên $(-\frac{b}{2a}; +\infty)$.

## 🛠️ 2. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định các yếu tố của Parabol
- **Phương pháp:** Sử dụng công thức tọa độ đỉnh, trục đối xứng và <BR>tìm giao điểm với các trục tọa độ  ($Ox: y=0, Oy: x=0$).
### 🔹 Dạng 2: Tìm công thức hàm số bậc hai
- **Cách 1:** Đi qua 3 điểm $A, B, C \Rightarrow$ Giải hệ phương trình 3 ẩn $a, b, c$.
- **Cách 2:** Biết tọa độ đỉnh $I$ và 1 điểm $M \Rightarrow$ Dùng dạng $y = a(x-x_I)^2 + y_I$.
- **Cách 3:** Biết trục đối xứng và điểm đi qua.
### 🔹 Dạng 3: Bài toán tương giao
- **Phương pháp:** Lập phương trình hoành độ giao điểm $ax^2 + bx + c = mx + n$.
- Số giao điểm tương ứng với số nghiệm của phương trình bậc hai.
### 🔹 Dạng 4: Tìm Giá trị lớn nhất (GTLN) / Nhỏ nhất (GTNN)
- Nếu $a > 0$: $\min y = -\frac{\Delta}{4a}$ tại $x = -\frac{b}{2a}$.
- Nếu $a < 0$: $\max y = -\frac{\Delta}{4a}$ tại $x = -\frac{b}{2a}$.

## 🌍 3. Ứng dụng thực tế
### ✅ Vật lý (Chuyển động)
- **Tầm bay cao / Tầm bay xa:** Quỹ đạo vật ném xiên $h(t) = -\frac{1}{2}gt^2 + v_0 \sin(\alpha)t + h_0$.
- Tìm thời điểm vật đạt độ cao cực đại (tọa độ đỉnh).
### ✅ Kinh tế (Tối ưu hóa)
- **Lợi nhuận:** $L(x) = R(x) - C(x)$ (thường là hàm bậc hai).
- Tìm mức sản lượng $x$ để lợi nhuận đạt mức tối đa.
### ✅ Kiến trúc
- Thiết kế hình dạng cổng chào, cầu treo, gương hội tụ (Paraboloid).
- Ví dụ: Tính chiều cao của cổng Parabol khi biết chiều rộng và một điểm trên cổng.

## ⌨️ 4. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tìm đỉnh Parabol nhanh (Menu 9-2-2)
- **Thao tác:** `Menu` $\rightarrow$ `9` $\rightarrow$ `2` $\rightarrow$ `2`.
- Nhập các hệ số $a, b, c$ và nhấn `=`.
- Sau khi hiện nghiệm $x_1, x_2$, nhấn tiếp `=` máy sẽ hiện:
- `X-Value Minimum/Maximum`: Hoành độ đỉnh $x_I$.
- `Y-Value Minimum/Maximum`: Tung độ đỉnh $y_I$.
### ✅ Lập bảng giá trị (Menu 8 - Table)
- **Thao tác:** `Menu` $\rightarrow$ `8`.
- Nhập hàm $f(x)$, thiết lập `Start`, `End`, `Step`.
- Giúp xác định các điểm đặc biệt để vẽ đồ thị chính xác hơn.
### ✅ Tính toán với Vectơ tọa độ
- Khi bài toán liên quan đến dịch chuyển đồ thị theo $\overrightarrow{u}(p; q)$:
- Hàm số mới: $y = a(x-p)^2 + b(x-p) + c + q$.

## ⚠️ Lưu ý của Giáo viên
- Luôn kiểm tra điều kiện $a \neq 0$ trước khi khẳng định là hàm số bậc hai.
- Khi vẽ đồ thị, cần lấy ít nhất 5 điểm (Đỉnh $I$, 2 điểm bên trái, 2 điểm bên phải) để đường cong mượt mà.
- Giá trị $c$ luôn là tung độ giao điểm của Parabol với trục $Oy$.