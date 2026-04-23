---
markmap:
  colorScheme: default
  math: katex
---

# ➕➖ BÀI 8. TỔNG VÀ HIỆU CỦA HAI VECTƠ (TOÁN 10)

## 1. 📘 Tổng của hai vectơ
### ✅ Quy tắc ba điểm (Phép cộng nối đuôi)
- **Công thức:** Với ba điểm $A, B, C$ bất kỳ: $\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$.
- **Ý nghĩa:** Hợp của hai sự dịch chuyển liên tiếp.
### ✅ Quy tắc hình bình hành
- **Công thức:** Nếu $ABCD$ là hình bình hành thì: $\overrightarrow{AB} + \overrightarrow{AD} = \overrightarrow{AC}$.
- **Ý nghĩa:** Tổng hợp hai lực cùng tác động vào một điểm.
### ✅ Tính chất phép cộng
- Giao hoán: $\overrightarrow{a} + \overrightarrow{b} = \overrightarrow{b} + \overrightarrow{a}$.
- Kết hợp: $(\overrightarrow{a} + \overrightarrow{b}) + \overrightarrow{c} = \overrightarrow{a} + (\overrightarrow{b} + \overrightarrow{c})$.
- Cộng với vectơ-không: $\overrightarrow{a} + \overrightarrow{0} = \overrightarrow{a}$.

## 2. 📙 Hiệu của hai vectơ
### ✅ Vectơ đối
- **Định nghĩa:** Vectơ đối của $\overrightarrow{a}$ là vectơ ngược hướng và cùng độ dài với $\overrightarrow{a}$. Ký hiệu là $-\overrightarrow{a}$.
- **Tính chất:** $\overrightarrow{a} + (-\overrightarrow{a}) = \overrightarrow{0}$. Vectơ đối của $\overrightarrow{AB}$ là $\overrightarrow{BA}$.
### ✅ Quy tắc hiệu (Quy tắc chung gốc)
- **Công thức:** Với ba điểm $O, A, B$ bất kỳ: $\overrightarrow{OB} - \overrightarrow{OA} = \overrightarrow{AB}$.
- **Mẹo nhớ:** "Cuối trừ Đầu": Ngọn của vectơ hiệu là điểm của vectơ bị trừ.

## 3. 🧩 Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Chứng minh đẳng thức vectơ
- **Phương pháp:** - Biến đổi vế này thành vế kia.
    - Biến đổi tương đương về một đẳng thức luôn đúng (ví dụ $\overrightarrow{0} = \overrightarrow{0}$).
    - Sử dụng quy tắc chèn điểm: $\overrightarrow{AB} = \overrightarrow{AM} + \overrightarrow{MB}$.
### 🔹 Dạng 2: Tính độ dài của vectơ tổng, hiệu
- **Phương pháp:** - Bước 1: Dựng vectơ tổng/hiệu thành một vectơ duy nhất dựa vào quy tắc hình bình hành hoặc quy tắc ba điểm.
- Bước 2: Sử dụng định lý Pythagoras hoặc hệ thức lượng trong tam giác để tính độ dài đoạn thẳng đó.
- **Ví dụ:** Cho hình vuông $ABCD$ cạnh $a$. Tính $|\overrightarrow{AB} + \overrightarrow{AD}|$.
    - Ta có $\overrightarrow{AB} + \overrightarrow{AD} = \overrightarrow{AC}$. Độ dài $|\overrightarrow{AC}| = a\sqrt{2}$.
### 🔹 Dạng 3: Xác định điểm thỏa mãn đẳng thức vectơ
- **Phương pháp:** Biến đổi đẳng thức về dạng $\overrightarrow{OM} = \overrightarrow{v}$ (với $O$ và $\overrightarrow{v}$ cố định).

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý học (Tổng hợp lực)
- Một vật chịu tác động của hai lực $\overrightarrow{F_1}$ và $\overrightarrow{F_2}$. Lực tổng hợp $\overrightarrow{F} = \overrightarrow{F_1} + \overrightarrow{F_2}$ quyết định hướng và gia tốc của vật.
- **Ví dụ:** Hai người cùng kéo một chiếc thuyền theo hai hướng khác nhau.
### ✅ Vận tốc máy bay/tàu thủy
- Vận tốc thực tế của máy bay đối với mặt đất $\overrightarrow{v}$ là tổng của vận tốc máy bay đối với không khí $\overrightarrow{v_b}$ và vận tốc của gió $\overrightarrow{v_g}$: $\overrightarrow{v} = \overrightarrow{v_b} + \overrightarrow{v_g}$.
### ✅ Bài toán độ dời
- Một người đi từ $A$ đến $B$, sau đó từ $B$ đến $C$. Tổng độ dời là $\overrightarrow{AC}$.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Khai báo Vectơ (Menu 5)
- **Thao tác:** `Menu` -> `5` (Vector) -> Chọn `1: VctA` -> Kích thước `2`.
- Nhập tọa độ tương ứng (nếu bài toán cho tọa độ hoặc gắn trục Oxy).
### ✅ Thực hiện phép cộng, hiệu
- Sau khi nhập `VctA` và `VctB`, nhấn `AC`.
- Gọi vectơ: `OPTN` -> `3 (VctA)` + `OPTN` -> `4 (VctB)`.
### ✅ Tính độ dài vectơ tổng/hiệu
- Sử dụng phím `Abs` (trị tuyệt đối): `SHIFT` + `(` (Abs).
- Nhập: `Abs(VctA + VctB)`. Máy sẽ xuất kết quả độ dài $|\overrightarrow{a} + \overrightarrow{b}|$.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt rõ: Độ dài của tổng khác với tổng các độ dài: $|\overrightarrow{a} + \overrightarrow{b}| \le |\overrightarrow{a}| + |\overrightarrow{b}|$.
- Quy tắc hiệu cực kỳ hữu ích khi muốn đưa các vectơ về cùng một gốc để dễ tính toán.
- Khi làm bài hình học, hãy luôn vẽ hình để xác định hướng của vectơ, tránh nhầm lẫn giữa $\overrightarrow{AB}$ và $\overrightarrow{BA}$.