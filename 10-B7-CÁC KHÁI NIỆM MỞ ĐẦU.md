---
markmap:
  colorScheme: default
  math: katex
---

# 🚀 BÀI 7: CÁC KHÁI NIỆM MỞ ĐẦU VỀ VECTƠ (TOÁN 10)

## 1. 📘 Định nghĩa và Ký hiệu
### ✅ Định nghĩa Vectơ
- Vectơ là một đoạn thẳng có hướng.
- Ký hiệu: $\overrightarrow{AB}$ (điểm đầu $A$, điểm cuối $B$) hoặc $\vec{a}, \vec{b}$.
- **Ý nghĩa:** Biểu diễn các đại lượng có hướng như lực, vận tốc, độ dời.
### ✅ Giá và Độ dài của Vectơ
- **Giá:** Đường thẳng đi qua điểm đầu và điểm cuối của vectơ.
- **Độ dài:** Khoảng cách giữa điểm đầu và điểm cuối. Ký hiệu: $|\overrightarrow{AB}| = AB$.
- **Vectơ đơn vị:** Vectơ có độ dài bằng 1.

## 2. 📏 Quan hệ giữa hai Vectơ
### ✅ Vectơ cùng phương, cùng hướng
- **Cùng phương:** Hai vectơ có giá song song hoặc trùng nhau.
- **Cùng hướng:** Hai vectơ cùng phương và có hướng giống nhau.
- **Ngược hướng:** Hai vectơ cùng phương nhưng hướng ngược nhau.
- **Lưu ý:** Ba điểm $A, B, C$ thẳng hàng $\Leftrightarrow \overrightarrow{AB}, \overrightarrow{AC}$ cùng phương.
### ✅ Hai vectơ bằng nhau
- **Điều kiện:** Cùng hướng và cùng độ dài.
- **Ký hiệu:** $\vec{a} = \vec{b}$.
- **Ý nghĩa:** Cho trước một điểm $O$ và một vectơ $\vec{a}$, luôn tồn tại duy nhất điểm $M$ sao cho $\overrightarrow{OM} = \vec{a}$.
### ✅ Vectơ-không ($\vec{0}$)
- Điểm đầu và điểm cuối trùng nhau: $\overrightarrow{AA}, \overrightarrow{BB}$.
- Độ dài $|\vec{0}| = 0$.
- Quy ước: $\vec{0}$ cùng phương, cùng hướng với mọi vectơ.

## 🧩 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định Vectơ cùng phương, cùng hướng, bằng nhau
- **Phương pháp:** Dựa vào định nghĩa và tính chất hình học của hình đề bài cho (hình bình hành, hình vuông, lục giác đều).
- **Ví dụ:** Trong hình bình hành $ABCD$, các vectơ bằng nhau là $\overrightarrow{AB} = \overrightarrow{DC}$ và $\overrightarrow{AD} = \overrightarrow{BC}$.
### 🔹 Dạng 2: Chứng minh đẳng thức vectơ đơn giản
- **Phương pháp:** Sử dụng định nghĩa hai vectơ bằng nhau để chứng minh các cặp cạnh song song và bằng nhau.
### 🔹 Dạng 3: Tính độ dài Vectơ
- **Phương pháp:** Độ dài $|\overrightarrow{AB}|$ chính là độ dài đoạn thẳng $AB$. Sử dụng hệ thức lượng hoặc định lý Pythagoras để tính.

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý học
- **Lực:** Biểu diễn lực tác động vào một vật tại một điểm xác định.
- **Vận tốc:** Biểu diễn hướng và tốc độ di chuyển của máy bay, tàu thủy.
### ✅ Địa lý và Định vị
- Xác định hướng di chuyển từ điểm $A$ đến điểm $B$ trên bản đồ (độ dời).
### 📝 Ví dụ thực tế
- Một chiếc thuyền chuyển động từ bờ bên này sang bờ bên kia với vận tốc $\overrightarrow{v_1}$, dòng nước chảy với vận tốc $\overrightarrow{v_2}$. Vectơ vận tốc thực tế của thuyền là tổng các vectơ này.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Khai báo Vectơ (Menu 5)
- **Thao tác:** `Menu` -> `5` (Vectơ).
- **Khai báo:** Chọn `1: VctA` -> Chọn kích thước `2` (cho mặt phẳng Oxy).
- **Nhập tọa độ:** Giúp kiểm tra độ dài và hướng khi bài toán gắn vào trục tọa độ.
### ✅ Tính độ dài Vectơ (Abs)
- **Cú pháp:** `Abs(VctA)`.
- **Thao tác:** `OPTN` -> Nhấn mũi tên xuống -> `4: Unit Vector` (Vectơ đơn vị) hoặc dùng phím `Abs` (`SHIFT` + `(`) để tính độ dài $|\vec{a}| = \sqrt{x^2+y^2}$.
### ✅ Kiểm tra tính cùng phương
- Tỷ lệ tọa độ: $\frac{x_1}{x_2} = \frac{y_1}{y_2}$.

## ⚠️ Lưu ý của Giáo viên
- Phân biệt rõ **đoạn thẳng** $AB$ (không hướng) và **vectơ** $\overrightarrow{AB}$ (có hướng).
- Hai vectơ bằng nhau không nhất thiết phải có điểm đầu trùng nhau, chỉ cần cùng hướng và cùng độ dài.
- Khi làm bài về hình bình hành $ABCD$, nhớ thứ tự đỉnh để xác định đúng các vectơ bằng nhau: $\overrightarrow{AB} = \overrightarrow{DC}$ (không phải $\overrightarrow{CD}$).