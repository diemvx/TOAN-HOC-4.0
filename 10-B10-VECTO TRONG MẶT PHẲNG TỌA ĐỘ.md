---
markmap:
  colorScheme: default
  math: katex
---

# 📍 BÀI 10. VECTƠ TRONG MẶT PHẲNG TỌA ĐỘ (TOÁN 10)

## 1. 📘 Hệ trục tọa độ và Tọa độ Vectơ
### ✅ Hệ trục tọa độ Oxy
- Gồm hai trục vuông góc: Trục hoành $Ox$ (vectơ đơn vị $\overrightarrow{i}$) và trục tung $Oy$ (vectơ đơn vị $\overrightarrow{j}$).
- $\overrightarrow{i}^2 = \overrightarrow{j}^2 = 1$ và $\overrightarrow{i} \cdot \overrightarrow{j} = 0$.
### ✅ Tọa độ của một vectơ
- $\overrightarrow{u} = x\overrightarrow{i} + y\overrightarrow{j} \Leftrightarrow \overrightarrow{u} = (x; y)$.
- Hai vectơ bằng nhau: $\overrightarrow{u}(x; y) = \overrightarrow{u'}(x'; y') \Leftrightarrow \begin{cases} x = x' \\ y = y' \end{cases}$.
### ✅ Tọa độ của một điểm
- Tọa độ điểm $M$ là tọa độ của vectơ $\overrightarrow{OM}$.
- Cho $A(x_A; y_A)$ và $B(x_B; y_B) \Rightarrow \overrightarrow{AB} = (x_B - x_A; y_B - y_A)$.

## 2. 📋 Biểu thức tọa độ của các phép toán
### ✅ Phép toán vectơ
Cho $\overrightarrow{u} = (x; y), \overrightarrow{v} = (x'; y')$ và số thực $k$:
- Tổng/Hiệu: $\overrightarrow{u} \pm \overrightarrow{v} = (x \pm x'; y \pm y')$.
- Tích với một số: $k\overrightarrow{u} = (kx; ky)$.
- Vectơ cùng phương: $\overrightarrow{v} = k\overrightarrow{u} \Leftrightarrow \begin{cases} x' = kx \\ y' = ky \end{cases}$.
### ✅ Tọa độ các điểm đặc biệt
- Trung điểm $I$ của $AB$: $x_I = \frac{x_A + x_B}{2}, y_I = \frac{y_A + y_B}{2}$.
- Trọng tâm $G$ của $\triangle ABC$: $x_G = \frac{x_A + x_B + x_C}{3}, y_G = \frac{y_A + y_B + y_C}{3}$.

## 🧩 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Tìm tọa độ điểm, vectơ cơ bản
- **Phương pháp:** Áp dụng trực tiếp các công thức cộng, trừ, nhân số với vectơ và công thức tính tọa độ vectơ $\overrightarrow{AB}$.
### 🔹 Dạng 2: Tìm điểm thỏa mãn đẳng thức vectơ
- **Phương pháp:** Gọi tọa độ điểm cần tìm là $M(x; y)$. Biến đổi đẳng thức vectơ thành hệ phương trình hai ẩn $x, y$.
- **Ví dụ:** Tìm $D$ để $ABCD$ là hình bình hành $\Leftrightarrow \overrightarrow{AD} = \overrightarrow{BC}$.
### 🔹 Dạng 3: Chứng minh ba điểm thẳng hàng, điểm thuộc đường thẳng
- **Phương pháp:** $A, B, C$ thẳng hàng $\Leftrightarrow \overrightarrow{AB}$ và $\overrightarrow{AC}$ cùng phương $\Leftrightarrow \frac{x_B - x_A}{x_C - x_A} = \frac{y_B - y_A}{y_C - y_A}$.
### 🔹 Dạng 4: Phân tích một vectơ theo hai vectơ không cùng phương
- **Phương pháp:** Giải hệ phương trình $x\overrightarrow{a} + y\overrightarrow{b} = \overrightarrow{c}$ để tìm hệ số $x, y$.

## 🌍 4. Ứng dụng thực tế
### ✅ Bản đồ và GPS
- Xác định vị trí các điểm trên mặt phẳng dựa trên kinh độ và vĩ độ đã được chuẩn hóa về hệ tọa độ phẳng.
### ✅ Đồ họa máy tính (Computer Graphics)
- Biểu diễn các hình ảnh, đối tượng dưới dạng tập hợp các điểm tọa độ. Phép tịnh tiến hình ảnh tương ứng với phép cộng vectơ.
### ✅ Vật lý (Phân tích lực)
- Đặt các lực tác động vào vật lên hệ trục $Oxy$ để tính lực tổng hợp bằng cách cộng các tọa độ thành phần $F_x, F_y$.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Chế độ Vectơ (Menu 5)
- **Thao tác:** `Menu` -> `5` (Vectơ).
- **Khai báo:** Chọn `1: VctA`, chọn kích thước `2` (cho $Oxy$). Nhập tọa độ $x, y$.
### ✅ Tính toán nhanh
- Sau khi nhập `VctA` và `VctB`:
  - Nhấn `AC` để thoát màn hình nhập.
  - Tính $2\overrightarrow{a} - 3\overrightarrow{b}$: Nhập `2` `OPTN` `3` `-` `3` `OPTN` `4`.
### ✅ Tìm tọa độ điểm (Giải hệ phương trình)
- Đối với bài toán tìm điểm hoặc phân tích vectơ:
- Sử dụng `Menu 9` -> `1` (Hệ phương trình) -> `2` ẩn.

## ⚠️ Lưu ý của Giáo viên
- Cần phân biệt rõ tọa độ điểm $M(x; y)$ và tọa độ vectơ $\overrightarrow{u} = (x; y)$.
- Khi tính tọa độ vectơ $\overrightarrow{AB}$, luôn lấy tọa độ **điểm sau** trừ tọa độ **điểm trước**.
- Chú ý điều kiện chia cho 0 khi xét tỉ lệ cùng phương của hai vectơ.
- Vectơ $\vec{0}$ có tọa độ là $(0; 0)$.