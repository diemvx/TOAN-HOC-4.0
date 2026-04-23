---
markmap:
  colorScheme: google
  math: katex
---

# 📐 VỊ TRÍ TƯƠNG ĐỐI - GÓC - KHOẢNG CÁCH (OXY)

## 1. 🔄 Vị trí tương đối của hai đường thẳng
### ✅ Cho hai đường thẳng
- $\Delta_1: a_1x + b_1y + c_1 = 0$
- $\Delta_2: a_2x + b_2y + c_2 = 0$
### ✅ Phương pháp đại số (Xét hệ phương trình)
- Xét hệ: $\begin{cases} a_1x + b_1y = -c_1 \\ a_2x + b_2y = -c_2 \end{cases}$
- **Cắt nhau:** Hệ có nghiệm duy nhất $(x_0; y_0)$. (Điều kiện: $\frac{a_1}{a_2} \neq \frac{b_1}{b_2}$)
- **Song song:** Hệ vô nghiệm. (Điều kiện: $\frac{a_1}{a_2} = \frac{b_1}{b_2} \neq \frac{c_1}{c_2}$)
- **Trùng nhau:** Hệ vô số nghiệm. (Điều kiện: $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$)
### ✅ Trường hợp đặc biệt
- **Vuông góc:** $\Delta_1 \perp \Delta_2 \Leftrightarrow \overrightarrow{n_1} \cdot \overrightarrow{n_2} = 0 \Leftrightarrow a_1a_2 + b_1b_2 = 0$.

## 2. 📐 Góc giữa hai đường thẳng
### ✅ Công thức tính
- Gọi $\varphi$ là góc giữa $\Delta_1$ và $\Delta_2$ ($0^\circ \le \varphi \le 90^\circ$).
- $\cos \varphi = \frac{|\overrightarrow{n_1} \cdot \overrightarrow{n_2}|}{|\overrightarrow{n_1}| \cdot |\overrightarrow{n_2}|} = \frac{|a_1a_2 + b_1b_2|}{\sqrt{a_1^2 + b_1^2} \cdot \sqrt{a_2^2 + b_2^2}}$
### ✅ Ý nghĩa
- Dùng để xác định độ nghiêng tương đối giữa hai lộ trình, hai cạnh của đa giác hoặc trong thiết kế kỹ thuật.

## 📏 3. Khoảng cách
### ✅ Khoảng cách từ điểm đến đường thẳng
- Cho $M(x_0; y_0)$ và $\Delta: ax + by + c = 0$.
- $d(M, \Delta) = \frac{|ax_0 + by_0 + c|}{\sqrt{a^2 + b^2}}$
### ✅ Khoảng cách giữa hai đường thẳng song song
- Cho $\Delta_1: ax + by + c_1 = 0$ và $\Delta_2: ax + by + c_2 = 0$.
- $d(\Delta_1, \Delta_2) = \frac{|c_1 - c_2|}{\sqrt{a^2 + b^2}}$
### ✅ Bài toán phân giác
- Phương trình hai đường phân giác của góc tạo bởi $\Delta_1, \Delta_2$:
- $\frac{a_1x + b_1y + c_1}{\sqrt{a_1^2 + b_1^2}} = \pm \frac{a_2x + b_2y + c_2}{\sqrt{a_2^2 + b_2^2}}$

## 🌍 4. Ứng dụng thực tế
### ✅ Quy hoạch đô thị
- Tính khoảng cách từ một căn nhà (điểm $M$) đến trục đường quốc lộ ($\Delta$) để đảm bảo hành lang an toàn giao thông.
### ✅ Viễn thông
- Xác định vị trí đặt trạm phát sóng sao cho khoảng cách đến ba trục đường chính là bằng nhau (điểm cách đều 3 đường thẳng).
### ✅ Thiết kế đồ họa & Robot
- Lập trình cho robot di chuyển theo đường thẳng $\Delta_1$ và chuyển hướng sang $\Delta_2$ với một góc $\varphi$ cho trước.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tìm giao điểm (Vị trí tương đối)
- Sử dụng chức năng giải hệ phương trình bậc nhất 2 ẩn.
- **Thao tác:** `Menu 9` ⮕ `1` ⮕ `2`.
- Nhập các hệ số $a, b, -c$. Nếu máy báo `No Solution` (vô nghiệm) thì song song; `Infinite Solution` (vô số nghiệm) thì trùng nhau.
### ✅ Tính nhanh Khoảng cách
- Nhập biểu thức $\frac{|Ax + By + C|}{\sqrt{A^2 + B^2}}$ vào máy.
- Sử dụng phím `CALC`: Máy hỏi $A, B, C$ (hệ số đường thẳng) và $x, y$ (tọa độ điểm). Nhấn `=` để nhận kết quả.
### ✅ Tính Góc nhanh (Sử dụng Vector)
- `Menu 5` (Vector): Nhập $\overrightarrow{n_1}$ vào `VctA`, $\overrightarrow{n_2}$ vào `VctB`.
- Sử dụng lệnh `Angle(VctA, VctB)` trong mục `OPTN` để tìm góc.
- *Lưu ý:* Nếu góc $> 90^\circ$, góc giữa hai đường thẳng sẽ là $180^\circ - \text{kết quả}$.

## ⚠️ Lưu ý của Giáo viên
- **Góc:** Góc giữa hai đường thẳng không bao giờ tù. Luôn lấy trị tuyệt đối ở tử số công thức $\cos$.
- **Tọa độ:** Khi dùng công thức khoảng cách, đường thẳng **bắt buộc** phải đưa về dạng tổng quát $ax + by + c = 0$.
- **Vectơ:** Vectơ pháp tuyến $\overrightarrow{n} = (a; b)$ vuông góc với đường thẳng, đừng nhầm lẫn với vectơ chỉ phương $\overrightarrow{u} = (-b; a)$.