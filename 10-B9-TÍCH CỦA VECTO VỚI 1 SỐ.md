---
markmap:
  colorScheme: default
  math: katex
---

# ✖️ BÀI 9. TÍCH CỦA MỘT SỐ VỚI MỘT VECTƠ (TOÁN 10)

## 1. 📘 Định nghĩa và Tính chất
### ✅ Định nghĩa
- Tích của một số thực $k$ với vectơ $\overrightarrow{a} \neq \overrightarrow{0}$ là một vectơ, ký hiệu là $k\overrightarrow{a}$.
- **Hướng:**
    - Cùng hướng với $\overrightarrow{a}$ nếu $k > 0$.
    - Ngược hướng với $\overrightarrow{a}$ nếu $k < 0$.
- **Độ dài:** $|k\overrightarrow{a}| = |k| \cdot |\overrightarrow{a}|$.
- **Quy ước:** $0\overrightarrow{a} = \overrightarrow{0}$ và $k\overrightarrow{0} = \overrightarrow{0}$.
### ✅ Tính chất toán học
- Phân phối đối với phép cộng vectơ: $k(\overrightarrow{a} + \overrightarrow{b}) = k\overrightarrow{a} + k\overrightarrow{b}$.
- Phân phối đối với phép cộng số thực: $(h + k)\overrightarrow{a} = h\overrightarrow{a} + k\overrightarrow{a}$.
- Kết hợp: $h(k\overrightarrow{a}) = (hk)\overrightarrow{a}$.
- Nhân với 1 và -1: $1\overrightarrow{a} = \overrightarrow{a}; (-1)\overrightarrow{a} = -\overrightarrow{a}$.

## 2. 📍 Các hệ thức vectơ quan trọng
### ✅ Trung điểm đoạn thẳng
- Nếu $I$ là trung điểm của $AB$, với điểm $O$ bất kỳ:
- $\overrightarrow{IA} + \overrightarrow{IB} = \overrightarrow{0}$.
- $\overrightarrow{OA} + \overrightarrow{OB} = 2\overrightarrow{OI}$.
### ✅ Trọng tâm tam giác
- Nếu $G$ là trọng tâm của $\triangle ABC$, với điểm $O$ bất kỳ:
- $\overrightarrow{GA} + \overrightarrow{GB} + \overrightarrow{GC} = \overrightarrow{0}$.
- $\overrightarrow{OA} + \overrightarrow{OB} + \overrightarrow{OC} = 3\overrightarrow{OG}$.
### ✅ Điều kiện hai vectơ cùng phương
- $\overrightarrow{b}$ cùng phương với $\overrightarrow{a} \neq \overrightarrow{0} \Leftrightarrow \exists k \in \mathbb{R}: \overrightarrow{b} = k\overrightarrow{a}$.
- **Ứng dụng:** Ba điểm $A, B, C$ thẳng hàng $\Leftrightarrow \overrightarrow{AB} = k\overrightarrow{AC}$.

## 🧩 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Phân tích một vectơ theo hai vectơ không cùng phương
- **Phương pháp:** Sử dụng quy tắc chèn điểm, quy tắc hình bình hành <br>và các hệ thức trung điểm, trọng tâm để biến đổi về các vectơ gốc.
- **Ví dụ:** Cho $I$ là trung điểm $AB$, phân tích $\overrightarrow{OI}$ theo $\overrightarrow{OA}$ và $\overrightarrow{OB}$.
### 🔹 Dạng 2: Chứng minh ba điểm thẳng hàng
- **Phương pháp:** Biến đổi để chỉ ra $\overrightarrow{AB} = k\overrightarrow{AC}$.
### 🔹 Dạng 3: Chứng minh đẳng thức vectơ phức tạp
- **Phương pháp:** Sử dụng tính chất phân phối và chèn điểm <br> để đưa về các vectơ có chung gốc hoặc các vectơ đơn giản.
### 🔹 Dạng 4: Tìm tập hợp điểm (Quỹ tích)
- **Phương pháp:** Biến đổi đẳng thức vectơ về dạng $| \overrightarrow{MA} + \dots | = \text{const}$ hoặc $\overrightarrow{MA} = k\overrightarrow{v}$.

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý (Đòn bẩy & Cân bằng lực)
- **Quy tắc momen:** $k_1\overrightarrow{F_1} + k_2\overrightarrow{F_2} = \overrightarrow{0}$.
- Ví dụ: Hai người có khối lượng khác nhau ngồi trên bập bênh để đạt trạng thái cân bằng.
### ✅ Đồ họa máy tính
- Phóng to/thu nhỏ hình ảnh: Tịnh tiến các điểm theo một tỉ số $k$.
- Thiết kế Font chữ (Vectơ graphics).
### ✅ Xây dựng
- Tính toán lực căng của dây cáp khi treo các vật nặng tại các vị trí không đối xứng (tỉ lệ nghịch với khoảng cách).

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Thực hiện phép nhân số với vectơ (Menu 5)
- **Thao tác:** `Menu` -> `5` (Vector).
- Khai báo `VctA` (ví dụ tọa độ $(2; 3)$).
- **Tính toán:** Nhấn `2` x `OPTN` -> `3 (VctA)`. Máy sẽ trả về tọa độ của $2\overrightarrow{a}$.
### ✅ Kiểm tra tính cùng phương
- **Cách làm:** Nhập tọa độ hai vectơ $\overrightarrow{a}$ và $\overrightarrow{b}$.
- Nếu tỷ lệ $\frac{x_1}{x_2} = \frac{y_1}{y_2}$ (với mẫu khác 0) thì hai vectơ cùng phương.
### ✅ Tính độ dài sau khi nhân số
- Sử dụng lệnh `Abs`: `Abs(k * VctA)`.

## ⚠️ Lưu ý của Giáo viên
- Khi $k = -1$, vectơ $(-1)\overrightarrow{a}$ chính là vectơ đối $-\overrightarrow{a}$.
- Trong các bài toán chứng minh thẳng hàng, nếu tìm được $k$ thì còn xác định được vị trí tương đối (ví dụ $B$ nằm giữa $A, C$ nếu $0 < k < 1$ trong $\overrightarrow{AB} = k\overrightarrow{AC}$).
- Chú ý phân biệt số $0$ và vectơ-không $\overrightarrow{0}$ trong các đẳng thức.