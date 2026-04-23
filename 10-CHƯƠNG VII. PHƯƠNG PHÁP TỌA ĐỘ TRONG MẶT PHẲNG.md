---
markmap:
  colorScheme: google
  math: katex
---

# 📍 ÔN TẬP CHƯƠNG VII: PHƯƠNG PHÁP TỌA ĐỘ TRONG MẶT PHẲNG

## 1. 🛣️ Đường thẳng trong mặt phẳng
### ✅ Vectơ đặc trưng
- **Vectơ chỉ phương (VTCP):** $\overrightarrow{u} = (u_1; u_2)$.
- **Vectơ pháp tuyến (VPTP):** $\overrightarrow{n} = (a; b)$.
- **Quan hệ:** $\overrightarrow{n} \perp \overrightarrow{u} \Rightarrow a \cdot u_1 + b \cdot u_2 = 0$. Nếu $\overrightarrow{n} = (a; b)$ thì $\overrightarrow{u} = (-b; a)$.
### ✅ Các dạng phương trình
- **Phương trình tham số:** $\begin{cases} x = x_0 + t u_1 \\ y = y_0 + t u_2 \end{cases}$ (Đường thẳng qua $M_0(x_0; y_0)$ có VTCP $\overrightarrow{u}$).
- **Phương trình tổng quát:** $a(x - x_0) + b(y - y_0) = 0 \Leftrightarrow ax + by + c = 0$ (Qua $M_0$ có VPTP $\overrightarrow{n}$).
### ✅ Khoảng cách và Góc
- **Khoảng cách từ $M(x_M; y_M)$ đến $\Delta: ax + by + c = 0$:** $d(M, \Delta) = \frac{|ax_M + by_M + c|}{\sqrt{a^2 + b^2}}$.
- **Góc $\varphi$ giữa hai đường thẳng:** $\cos \varphi = \frac{|a_1 a_2 + b_1 b_2|}{\sqrt{a_1^2 + b_1^2} \cdot \sqrt{a_2^2 + b_2^2}}$.

## 2. ⭕ Đường tròn
### ✅ Phương trình đường tròn
- **Dạng chính tắc:** $(x - a)^2 + (y - b)^2 = R^2$ (Tâm $I(a; b)$, bán kính $R$).
- **Dạng tổng quát:** $x^2 + y^2 - 2ax - 2by + c = 0$ (Điều kiện: $a^2 + b^2 - c > 0$).
### ✅ Phương trình tiếp tuyến
- **Tại điểm $M_0(x_0; y_0)$ thuộc đường tròn:** $(x_0 - a)(x - x_0) + (y_0 - b)(y - y_0) = 0$.
- **Dạng khác:** Sử dụng điều kiện khoảng cách từ tâm $I$ đến tiếp tuyến $\Delta$ bằng $R$: $d(I, \Delta) = R$.

## 3. 🛸 Ba đường Conic
### ✅ Elip (E)
- **Phương trình:** $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ ($a > b > 0$).
- **Thông số:** $c^2 = a^2 - b^2$. Tiêu điểm $F_1(-c; 0), F_2(c; 0)$. Trục lớn $2a$, trục nhỏ $2b$.
### ✅ Hypebol (H)
- **Phương trình:** $\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1$ ($a, b > 0$).
- **Thông số:** $c^2 = a^2 + b^2$. Tiêu điểm $F_1(-c; 0), F_2(c; 0)$. Trục thực $2a$, trục ảo $2b$.
### ✅ Parabol (P)
- **Phương trình:** $y^2 = 2px$ ($p > 0$).
- **Thông số:** Tiêu điểm $F(\frac{p}{2}; 0)$. Đường chuẩn $\Delta: x = -\frac{p}{2}$.

## 🛠️ 4. Phương pháp giải & Bài toán thực tế
### 🔹 Dạng toán hình học tọa độ
- **Viết phương trình:** Xác định các yếu tố (điểm, vectơ, bán kính, tham số tiêu).
- **Vị trí tương đối:** Giải hệ phương trình hoặc so sánh khoảng cách.
- **Bài toán cực trị:** Sử dụng tính chất hình học hoặc bất đẳng thức tọa độ.
### 🔹 Ứng dụng thực tế
- **Giao thông:** Xác định tọa độ giao điểm các cung đường, khoảng cách từ nhà đến quốc lộ.
- **Viễn thông:** Xác định vùng phủ sóng của trạm phát (đường tròn).
- **Kiến trúc:** Thiết kế vòm cầu Parabol, bồn hoa hình Elip.
- **Thiên văn:** Quỹ đạo hành tinh (Elip), quỹ đạo vệ tinh.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Giải hệ phương trình (Menu 9-1)
- Tìm giao điểm của hai đường thẳng hoặc đường thẳng với đường tròn.
- Tìm tâm đường tròn đi qua 3 điểm (Giải hệ 3 ẩn $a, b, c$).
### ✅ Tính toán Vectơ (Menu 5)
- Tính tích vô hướng để kiểm tra vuông góc hoặc tính góc.
- Tính độ dài đoạn thẳng: $\text{Norm}(\text{VctA} - \text{VctB})$.
### ✅ Kiểm tra phương trình (CALC)
- Nhập phương trình đường thẳng/đường tròn, nhấn `CALC` và tọa độ điểm để kiểm tra điểm có thuộc hình đó hay không.

## ⚠️ Lưu ý của Giáo viên
- Luôn kiểm tra điều kiện tồn tại của đường tròn ($a^2 + b^2 - c > 0$).
- Góc giữa hai đường thẳng luôn là góc nhọn hoặc góc vuông ($0^\circ \le \varphi \le 90^\circ$).
- Khi làm bài Conic, cần đưa phương trình về đúng dạng chính tắc (vế phải bằng 1) trước khi xác định $a, b, c$.