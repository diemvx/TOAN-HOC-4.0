---
markmap:
  colorScheme: google
  math: katex
---

# 🛣️ PHƯƠNG TRÌNH ĐƯỜNG THẲNG TRONG MẶT PHẲNG $OXY$

## 1. 📘 Các vectơ đặc trưng
### ✅ Vectơ pháp tuyến (VPTP) $\overrightarrow{n}$
- **Định nghĩa:** Vectơ khác $\overrightarrow{0}$ và có giá vuông góc với đường thẳng.
- **Ký hiệu:** $\overrightarrow{n} = (a; b)$.
### ✅ Vectơ chỉ phương (VTCP) $\overrightarrow{u}$
- **Định nghĩa:** Vectơ khác $\overrightarrow{0}$ và có giá song song hoặc trùng với đường thẳng.
- **Ký hiệu:** $\overrightarrow{u} = (u_1; u_2)$.
### ✅ Mối quan hệ
- $\overrightarrow{n} \perp \overrightarrow{u} \Leftrightarrow a \cdot u_1 + b \cdot u_2 = 0$.
- Chuyển đổi: Nếu $\overrightarrow{n} = (a; b) \Rightarrow \overrightarrow{u} = (-b; a)$ hoặc $(b; -a)$.

## 2. 📝 Các dạng phương trình đường thẳng
### ✅ Phương trình tổng quát (PTTQ)
- **Dạng:** $ax + by + c = 0$ ($a^2 + b^2 > 0$).
- **Yếu tố cần:** Điểm $M_0(x_0; y_0)$ và VPTP $\overrightarrow{n} = (a; b)$.
- **Công thức:** $a(x - x_0) + b(y - y_0) = 0$.
### ✅ Phương trình tham số (PTTS)
- **Dạng:** $\begin{cases} x = x_0 + u_1 t \\ y = y_0 + u_2 t \end{cases}$ ($t \in \mathbb{R}$).
- **Yếu tố cần:** Điểm $M_0(x_0; y_0)$ và VTCP $\overrightarrow{u} = (u_1; u_2)$.
### ✅ Phương trình đoạn chắn
- **Dạng:** $\frac{x}{a} + \frac{y}{b} = 1$.
- **Ý nghĩa:** Đường thẳng cắt $Ox$ tại $(a; 0)$ và cắt $Oy$ tại $(0; b)$ với $a, b \neq 0$.

## 🧩 3. Các công thức về khoảng cách và góc
### ✅ Khoảng cách từ điểm đến đường thẳng
- Cho $M_0(x_0; y_0)$ và $\Delta: ax + by + c = 0$.
- **Công thức:** $d(M_0, \Delta) = \frac{|ax_0 + by_0 + c|}{\sqrt{a^2 + b^2}}$.
### ✅ Góc giữa hai đường thẳng
- Cho $\Delta_1, \Delta_2$ có các VPTP lần lượt là $\overrightarrow{n_1}, \overrightarrow{n_2}$.
- **Công thức:** $\cos(\Delta_1, \Delta_2) = \frac{|\overrightarrow{n_1} \cdot \overrightarrow{n_2}|}{|\overrightarrow{n_1}| \cdot |\overrightarrow{n_2}|} = \frac{|a_1 a_2 + b_1 b_2|}{\sqrt{a_1^2 + b_1^2} \cdot \sqrt{a_2^2 + b_2^2}}$.

## 🛠️ 4. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Viết phương trình đường thẳng
- **Đi qua 2 điểm $A, B$:** VTCP là $\overrightarrow{AB} \Rightarrow$ VPTP $\Rightarrow$ PTTQ.
- **Đi qua 1 điểm và song song $\Delta'$:** Dùng chung VPTP với $\Delta'$.
- **Đi qua 1 điểm và vuông góc $\Delta'$:** VPTP của đường này là VTCP của đường kia.
### 🔹 Dạng 2: Vị trí tương đối của hai đường thẳng
- Xét hệ phương trình hai đường thẳng.
- **Cắt nhau:** Hệ có 1 nghiệm duy nhất.
- **Song song:** Hệ vô nghiệm.
- **Trùng nhau:** Hệ có vô số nghiệm.
### 🔹 Dạng 3: Bài toán tìm điểm
- **Phương pháp:** Tham số hóa tọa độ điểm thuộc đường thẳng theo biến $t$, <BR>sau đó dựa vào dữ kiện (khoảng cách, góc, vuông góc) để lập phương trình ẩn $t$.

## 🌍 5. Ứng dụng thực tế
### ✅ Giao thông & Quy hoạch
- Xác định lộ trình ngắn nhất của một con đường nối hai khu dân cư.
- Tính toán khoảng cách an toàn từ một trạm biến áp đến trục đường chính.
### ✅ Đồ họa máy tính
- Thuật toán vẽ đoạn thẳng nối các pixel.
- Tính toán va chạm giữa các nhân vật (di chuyển theo đường thẳng) trong game.
### ✅ Kinh tế
- Biểu diễn đường giới hạn ngân sách hoặc đường cung - cầu trong kinh mô hình kinh tế tuyến tính.

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tìm giao điểm (Menu 9 - 1 - 2)
- **Mục đích:** Tìm tọa độ giao điểm của hai đường thẳng.
- **Thao tác:** Nhập hệ số của hai PTTQ vào hệ phương trình bậc nhất 2 ẩn.
### ✅ Tính khoảng cách (Phép tính vectơ - Menu 5)
- Nhập $a, b$ vào `VctA`. Nhập $x_0, y_0, c$ để tính tử số.
- Sử dụng `Abs` để tính độ dài $|\overrightarrow{n}| = \sqrt{a^2 + b^2}$ ở mẫu số.
### ✅ Kiểm tra điểm thuộc đường thẳng
- Nhập biểu thức $ax + by + c$.
- Nhấn `CALC`, nhập tọa độ điểm $(x_0; y_0)$. Nếu kết quả bằng `0` thì điểm thuộc đường thẳng.

## ⚠️ Lưu ý của Giáo viên
- Phải chuyển PTTS về PTTQ (hoặc ngược lại) linh hoạt để sử dụng công thức khoảng cách.
- Góc giữa hai đường thẳng luôn $\in [0^\circ; 90^\circ]$, do đó công thức $\cos$ luôn có dấu trị tuyệt đối ở tử số.
- Khi viết phương trình đường thẳng đi qua $M$ và song song với $d: ax+by+c=0$, có thể giả sử phương trình là $ax+by+c'=0$ với $c' \neq c$.