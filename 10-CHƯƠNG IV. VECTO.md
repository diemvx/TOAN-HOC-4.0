---
markmap:
  colorScheme: google
  math: katex
---

# 📐 ÔN TẬP CHƯƠNG IV: VECTƠ (TOÁN 10)

## 1. 📂 Khái niệm cơ bản
### ✅ Định nghĩa
- Vectơ là một đoạn thẳng có hướng. Ký hiệu: $\overrightarrow{AB}$ (điểm đầu $A$, điểm cuối $B$) hoặc $\overrightarrow{a}$.
- Độ dài vectơ: $|\overrightarrow{AB}| = AB$.
### ✅ Quan hệ giữa hai vectơ
- **Vectơ cùng phương:** Có giá song song hoặc trùng nhau.
- **Vectơ bằng nhau:** Cùng hướng và cùng độ dài.
- **Vectơ đối:** Ngược hướng và cùng độ dài. $\overrightarrow{AB} = -\overrightarrow{BA}$.
- **Vectơ không ($\overrightarrow{0}$):** Điểm đầu trùng điểm cuối, độ dài bằng 0, cùng phương với mọi vectơ.

## 2. ➕ Các phép toán vectơ
### ✅ Phép cộng và phép trừ
- **Quy tắc 3 điểm:** $\overrightarrow{AB} + \overrightarrow{BC} = \overrightarrow{AC}$.
- **Quy tắc hình bình hành:** Nếu $ABCD$ là hình bình hành thì $\overrightarrow{AB} + \overrightarrow{AD} = \overrightarrow{AC}$.
- **Quy tắc hiệu:** $\overrightarrow{OB} - \overrightarrow{OA} = \overrightarrow{AB}$.
### ✅ Tích của vectơ với một số ($k\overrightarrow{a}$)
- Kết quả là một vectơ.
- Cùng hướng với $\overrightarrow{a}$ nếu $k > 0$, ngược hướng nếu $k < 0$.
- Độ dài: $|k\overrightarrow{a}| = |k| \cdot |\overrightarrow{a}|$.
### ✅ Tích vô hướng của hai vectơ
- **Công thức:** $\overrightarrow{a} \cdot \overrightarrow{b} = |\overrightarrow{a}| \cdot |\overrightarrow{b}| \cdot \cos(\overrightarrow{a}, \overrightarrow{b})$.
- **Hệ quả:** $\overrightarrow{a} \perp \overrightarrow{b} \Leftrightarrow \overrightarrow{a} \cdot \overrightarrow{b} = 0$.
- **Bình phương vô hướng:** $\overrightarrow{a}^2 = |\overrightarrow{a}|^2$.

## 🛠️ 3. Các hệ thức lượng & Tọa độ
### ✅ Hệ thức điểm đặc biệt
- **Trung điểm $M$ của $AB$:** $\overrightarrow{MA} + \overrightarrow{MB} = \overrightarrow{0}$ hoặc $\overrightarrow{OA} + \overrightarrow{OB} = 2\overrightarrow{OM}$.
- **Trọng tâm $G$ của $\triangle ABC$:** $\overrightarrow{GA} + \overrightarrow{GB} + \overrightarrow{GC} = \overrightarrow{0}$ hoặc $\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} = 3\overrightarrow{OG}$.
### ✅ Tọa độ vectơ trong mặt phẳng $Oxy$
- Cho $\overrightarrow{a} = (a_1; a_2)$ và $\overrightarrow{b} = (b_1; b_2)$:
    - $\overrightarrow{a} + \overrightarrow{b} = (a_1+b_1; a_2+b_2)$.
    - $k\overrightarrow{a} = (ka_1; ka_2)$.
    - $\overrightarrow{a} \cdot \overrightarrow{b} = a_1b_1 + a_2b_2$.
    - $|\overrightarrow{a}| = \sqrt{a_1^2 + a_2^2}$.

## 🧩 4. Các dạng toán trọng tâm
### 🔹 Dạng 1: Chứng minh đẳng thức vectơ
- **Phương pháp:** Sử dụng quy tắc 3 điểm, quy tắc hình bình hành để biến đổi vế này thành vế kia hoặc cả hai cùng về một biểu thức trung gian.
### 🔹 Dạng 2: Biểu diễn một vectơ qua hai vectơ không cùng phương
- **Phương pháp:** Chèn điểm thích hợp hoặc sử dụng hệ thức trung điểm, trọng tâm.
### 🔹 Dạng 3: Tìm tập hợp điểm thỏa mãn đẳng thức vectơ
- **Phương pháp:** Biến đổi đẳng thức về dạng $|\overrightarrow{MA}| = R$ (đường tròn) hoặc $|\overrightarrow{MA}| = |\overrightarrow{MB}|$ (đường trung trực).
### 🔹 Dạng 4: Bài toán tọa độ và tích vô hướng
- Tìm tọa độ điểm, tính góc giữa hai vectơ, chứng minh vuông góc.

## 🌍 5. Ứng dụng thực tế
### ✅ Vật lý (Lực và Vận tốc)
- **Tổng hợp lực:** Khi hai lực $\overrightarrow{F_1}, \overrightarrow{F_2}$ cùng tác động vào một vật, hợp lực là $\overrightarrow{F} = \overrightarrow{F_1} + \overrightarrow{F_2}$.
- **Vận tốc máy bay/tàu thủy:** Vận tốc thực bằng tổng vectơ vận tốc riêng và vận tốc của gió/dòng nước.
### ✅ Công việc (Công của lực)
- Công $A$ sinh ra bởi lực $\overrightarrow{F}$ làm vật dịch chuyển quãng đường $\overrightarrow{s}$ là tích vô hướng: $A = \overrightarrow{F} \cdot \overrightarrow{s}$.
### ✅ Kỹ thuật & Đồ họa
- Xác định hướng di chuyển và vị trí của vật thể trong không gian 2D/3D.

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Khởi tạo Vectơ (Menu 5)
- **Bước 1:** `Menu` ⮕ `5` (Vector).
- **Bước 2:** Chọn `1` (VctA), chọn kích thước `2` (cho Oxy). Nhập tọa độ.
### ✅ Các phép toán Vectơ
- Nhấn `OPTN` để gọi các lệnh:
    - `3`: VctA, `4`: VctB.
    - **Tích vô hướng (Dot Product):** `OPTN` ⮕ `Mũi tên xuống` ⮕ `2`.
    - **Tính độ dài (Abs):** `SHIFT` ⮕ `(` (Abs) ⮕ `OPTN` ⮕ `3` (VctA).
    - **Tính góc giữa 2 vectơ:** `OPTN` ⮕ `Mũi tên xuống` ⮕ `3` (Angle).
### ✅ Ví dụ tính $\overrightarrow{a} \cdot \overrightarrow{b}$
- Nhập VctA, VctB ⮕ Màn hình tính toán: `VctA` `DotP` `VctB` ⮕ `=`.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt rõ **vectơ** (có hướng) và **độ dài vectơ** (số thực không âm).
- Tích vô hướng của hai vectơ là một **số**, không phải là một vectơ.
- Khi làm bài tập tọa độ, hãy luôn vẽ hình phác thảo để kiểm tra tính hợp lý của kết quả.