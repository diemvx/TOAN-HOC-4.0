---
markmap:
  colorScheme: default
  math: katex
---

# 📐 BÀI 6. HỆ THỨC LƯỢNG TRONG TAM GIÁC (TOÁN 106)

## 1. 📘 Các định lý cơ bản
### ✅ Định lý Côsin
- **Công thức:**
  - $a^2 = b^2 + c^2 - 2bc \cdot \cos A$
  - $b^2 = a^2 + c^2 - 2ac \cdot \cos B$
  - $c^2 = a^2 + b^2 - 2ab \cdot \cos C$
- **Hệ quả (Tính góc):** $\cos A = \frac{b^2 + c^2 - a^2}{2bc}$
- **Ý nghĩa:** Dùng để giải tam giác khi biết (Cạnh - Góc - Cạnh) hoặc (Cạnh - Cạnh - Cạnh).
### ✅ Định lý Sin
- **Công thức:** $\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$
- **Ý nghĩa:** $R$ là bán kính đường tròn ngoại tiếp. Dùng khi biết (Góc - Góc - Cạnh) hoặc (Cạnh - Cạnh - Góc đối).
### ✅ Công thức đường trung tuyến
- **Công thức:** $m_a^2 = \frac{2(b^2 + c^2) - a^2}{4}$
- **Ví dụ:** Cho $a=6, b=8, c=10 \Rightarrow m_a^2 = \frac{2(8^2+10^2)-6^2}{4} = 73 \Rightarrow m_a = \sqrt{73}$.

## 2. 🍀 Các công thức tính diện tích tam giác ($S$)
### ✅ Theo chiều cao
- $S = \frac{1}{2} a \cdot h_a = \frac{1}{2} b \cdot h_b = \frac{1}{2} c \cdot h_c$
### ✅ Theo góc và cạnh
- $S = \frac{1}{2} ab \sin C = \frac{1}{2} bc \sin A = \frac{1}{2} ca \sin B$
### ✅ Theo bán kính đường tròn
- **Ngoại tiếp ($R$):** $S = \frac{abc}{4R}$
- **Nội tiếp ($r$):** $S = p \cdot r$ (với $p = \frac{a+b+c}{2}$)
### ✅ Công thức Heron
- $S = \sqrt{p(p-a)(p-b)(p-c)}$

## 🧩 3. Phương pháp giải các dạng toán
### 🔹 Dạng 1: Giải tam giác (Tìm các cạnh và góc chưa biết)
- **Biết 2 cạnh và góc xen giữa:** Dùng định lý Côsin tìm cạnh thứ ba $\rightarrow$ Dùng định lý Sin tìm góc.
- **Biết 3 cạnh:** Dùng hệ quả định lý Côsin để tìm các góc.
- **Biết 1 cạnh và 2 góc:** Tìm góc thứ ba ($180^\circ - \text{tổng 2 góc}$) $\rightarrow$ Dùng định lý Sin tìm 2 cạnh còn lại.
### 🔹 Dạng 2: Tính diện tích và các đại lượng liên quan ($R, r, h, m$)
- **Bước 1:** Sử dụng các công thức $S$ phù hợp với giả thiết.
- **Bước 2:** Từ $S$, suy ra các đại lượng khác như $R = \frac{abc}{4S}$ hoặc $r = \frac{S}{p}$.

## 🌍 4. Ứng dụng thực tế
### ✅ Đo đạc khoảng cách (Surveying)
- Tính khoảng cách giữa hai địa điểm bị ngăn cách (hai ngọn núi, hai bờ sông) mà không thể đo trực tiếp.
- **Bài toán:** Từ vị trí $A$, đo góc nhìn tới $B$ và $C$ là $\alpha$, biết khoảng cách $AB, AC \rightarrow$ Tính $BC$ bằng định lý Côsin.
### ✅ Hàng hải và Hàng không
- Tính toán quỹ đạo bay hoặc hướng di chuyển của tàu thủy khi chịu tác động của vận tốc dòng nước/gió (biểu diễn bằng các vectơ $\overrightarrow{v_1}, \overrightarrow{v_2}$).
### ✅ Xây dựng và Kiến trúc
- Tính độ dài kèo thép mái nhà, diện tích thửa đất hình tam giác không vuông.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Cài đặt đơn vị Độ (Degree)
- **Thao tác:** `SHIFT` + `MENU` $\rightarrow$ `2` (Angle Unit) $\rightarrow$ `1` (Degree).
### ✅ Tính cạnh bằng định lý Côsin
- **Thao tác:** Nhập biểu thức $\sqrt{b^2 + c^2 - 2bc \cos(A)}$.
- **Ví dụ:** $\sqrt{5^2 + 8^2 - 2 \cdot 5 \cdot 8 \cos(60)} \rightarrow$ Kết quả: $7$.
### ✅ Tính góc (SHIFT COS)
- **Thao tác:** Nhấn `SHIFT` + `cos` ($\cos^{-1}$) của biểu thức $\frac{b^2 + c^2 - a^2}{2bc}$.
- **Kết quả:** Nhấn nút `o ' ''` để đổi sang độ, phút, giây.
### ✅ Sử dụng tính năng SOLVE để giải định lý Sin
- **Cú pháp:** Nhập $\frac{A}{\sin(B)} = \frac{C}{\sin(D)}$ bằng phím `ALPHA`.
- **Thao tác:** Nhấn `SHIFT` + `CALC` (SOLVE) để tìm ẩn số $x$.

## ⚠️ Lưu ý của Giáo viên
- Tổng 3 góc trong một tam giác luôn bằng $180^\circ$.
- Trong định lý Sin, tỉ số $\frac{a}{\sin A}$ luôn bằng đường kính $2R$.
- Khi tính góc từ định lý Côsin, nếu $\cos A < 0$ thì góc $A$ là góc tù.
- Vectơ: Khi bài toán yêu cầu tính tổng lực hoặc vận tốc, nhớ dùng quy tắc hình bình hành và định lý Côsin cho độ dài vectơ tổng $\overrightarrow{v}$.