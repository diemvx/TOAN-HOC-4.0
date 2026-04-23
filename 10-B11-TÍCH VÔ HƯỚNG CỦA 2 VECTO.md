---
markmap:
  colorScheme: default
  math: katex
---

# 📐 BÀI 11. TÍCH VÔ HƯỚNG CỦA HAI VECTƠ (TOÁN 10)

## 1. 📘 Định nghĩa và Công thức
### ✅ Góc giữa hai vectơ
- Cho $\overrightarrow{a}, \overrightarrow{b} \neq \overrightarrow{0}$. Từ $O$ vẽ $\overrightarrow{OA} = \overrightarrow{a}, \overrightarrow{OB} = \overrightarrow{b}$.
- Góc $\alpha = \widehat{AOB}$ là góc giữa hai vectơ, ký hiệu $(\overrightarrow{a}, \overrightarrow{b})$.
- Quy ước: $0^\circ \le (\overrightarrow{a}, \overrightarrow{b}) \le 180^\circ$.
### ✅ Tích vô hướng (Scalar Product)
- **Định nghĩa:** $\overrightarrow{a} \cdot \overrightarrow{b} = |\overrightarrow{a}| \cdot |\overrightarrow{b}| \cdot \cos(\overrightarrow{a}, \overrightarrow{b})$.
- **Kết quả:** Là một **số thực**, không phải một vectơ.
- **Trường hợp đặc biệt:**
    - $\overrightarrow{a} \perp \overrightarrow{b} \Leftrightarrow \overrightarrow{a} \cdot \overrightarrow{b} = 0$.
    - $\overrightarrow{a} \cdot \overrightarrow{a} = \overrightarrow{a}^2 = |\overrightarrow{a}|^2$ (Bình phương vô hướng bằng bình phương độ dài).
### ✅ Biểu thức tọa độ
- Cho $\overrightarrow{a} = (x_1; y_1), \overrightarrow{b} = (x_2; y_2)$:
- $\overrightarrow{a} \cdot \overrightarrow{b} = x_1 x_2 + y_1 y_2$.

## 2. 📋 Tính chất và Hệ quả
### ✅ Tính chất toán học
- Giao hoán: $\overrightarrow{a} \cdot \overrightarrow{b} = \overrightarrow{b} \cdot \overrightarrow{a}$.
- Phân phối: $\overrightarrow{a} \cdot (\overrightarrow{b} + \overrightarrow{c}) = \overrightarrow{a} \cdot \overrightarrow{b} + \overrightarrow{a} \cdot \overrightarrow{c}$.
- Nhân với số thực: $(k\overrightarrow{a}) \cdot \overrightarrow{b} = k(\overrightarrow{a} \cdot \overrightarrow{b})$.
### ✅ Hệ quả quan trọng
- **Tính độ dài:** $|\overrightarrow{a}| = \sqrt{x^2 + y^2}$.
- **Tính góc:** $\cos(\overrightarrow{a}, \overrightarrow{b}) = \frac{\overrightarrow{a} \cdot \overrightarrow{b}}{|\overrightarrow{a}| \cdot |\overrightarrow{b}|} = \frac{x_1 x_2 + y_1 y_2}{\sqrt{x_1^2 + y_1^2} \cdot \sqrt{x_2^2 + y_2^2}}$.
- **Khoảng cách 2 điểm:** $AB = \sqrt{(x_B - x_A)^2 + (y_B - y_A)^2}$.

## 🧩 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Tính tích vô hướng, độ dài, góc
- **Phương pháp:** Sử dụng trực tiếp định nghĩa hoặc biểu thức tọa độ tùy theo giả thiết của đề bài.
### 🔹 Dạng 2: Chứng minh hai vectơ vuông góc / Thiết lập đẳng thức
- **Phương pháp:** Để chứng minh $\overrightarrow{a} \perp \overrightarrow{b}$, ta chứng minh $\overrightarrow{a} \cdot \overrightarrow{b} = 0$.
- **Ví dụ:** Cho tam giác $ABC$, chứng minh đường cao bằng cách chỉ ra tích vô hướng bằng 0.
### 🔹 Dạng 3: Bài toán cực trị (GTLN, GTNN)
- **Phương pháp:** Biến đổi biểu thức vectơ về bình phương vô hướng hoặc sử dụng tính chất $\cos \alpha \in [-1; 1]$.
### 🔹 Dạng 4: Chứng minh các hệ thức hình học
- **Phương pháp:** Chèn điểm và sử dụng tính chất phân phối để biến đổi các cạnh thành tích vô hướng.

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý (Công của một lực)
- Công $A$ sinh bởi lực $\overrightarrow{F}$ làm vật dịch chuyển một quãng đường $\overrightarrow{s}$ là tích vô hướng: $A = \overrightarrow{F} \cdot \overrightarrow{s}$.
- $A = |\overrightarrow{F}| \cdot |\overrightarrow{s}| \cdot \cos \alpha$.
### ✅ Đồ họa máy tính
- Tính độ sáng của một bề mặt dựa trên góc giữa vectơ pháp tuyến và vectơ nguồn sáng.
- Kiểm tra va chạm (Collision detection) giữa các đối tượng.
### ✅ Xây dựng và Cơ học
- Phân tích sự phân bổ lực lên các thanh dầm dựa trên góc nghiêng của chúng.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính tích vô hướng (Dot Product)
- **Thao tác:** `Menu` -> `5` (Vectơ). Khai báo `VctA`, `VctB` (Kích thước 2).
- Nhấn `AC` thoát ra. Nhấn `OPTN` -> Vuốt xuống chọn `2: Dot Product`.
- Cú pháp: `VctA` $\cdot$ `VctB`.
### ✅ Tính góc giữa hai vectơ
- **Thao tác:** `OPTN` -> Vuốt xuống chọn `3: Angle`.
- Cú pháp: `Angle(VctA, VctB)`. Máy sẽ trả về số đo góc (đảm bảo đang ở chế độ Degree).
### ✅ Tính độ dài (Norm/Abs)
- **Thao tác:** `SHIFT` + `(` (Abs) -> `OPTN` -> `3 (VctA)`.
- Cú pháp: `Abs(VctA)`.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt kỹ: Tích của số với vectơ (ra vectơ) và Tích vô hướng (ra số).
- $(\overrightarrow{a} \cdot \overrightarrow{b})\overrightarrow{c}$ là một vectơ cùng phương với $\overrightarrow{c}$, còn $\overrightarrow{a}(\overrightarrow{b} \cdot \overrightarrow{c})$ cùng phương với $\overrightarrow{a}$.
- Luôn kiểm tra đơn vị máy tính (Độ hay Radian) trước khi tính góc.
- Trong các bài toán thực tế, chú ý đơn vị của Lực (N) và Quãng đường (m) để tính Công (J).