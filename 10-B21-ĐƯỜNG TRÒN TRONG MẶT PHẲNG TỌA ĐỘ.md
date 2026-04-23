---
markmap:
  colorScheme: google
  math: katex
---

# ⭕ ĐƯỜNG TRÒN TRONG MẶT PHẲNG TỌA ĐỘ (TOÁN 10)

## 1. 📘 Phương trình đường tròn
### ✅ Dạng chính tắc
- **Điều kiện:** Biết tâm $I(a; b)$ và bán kính $R$.
- **Công thức:** $(x - a)^2 + (y - b)^2 = R^2$.
- **Ý nghĩa:** Tập hợp các điểm $M(x; y)$ cách tâm $I$ một khoảng không đổi bằng $R$.
### ✅ Dạng tổng quát
- **Công thức:** $x^2 + y^2 - 2ax - 2by + c = 0$.
- **Điều kiện là đường tròn:** $a^2 + b^2 - c > 0$.
- **Xác định tâm và bán kính:**
    - Tâm $I(a; b)$.
    - Bán kính $R = \sqrt{a^2 + b^2 - c}$.

## 📝 2. Phương trình tiếp tuyến của đường tròn
### ✅ Tiếp tuyến tại điểm $M_0(x_0; y_0) \in (C)$
- **Đặc điểm:** Tiếp tuyến vuông góc với bán kính $IM_0$ tại $M_0$.
- **Công thức:** $(x_0 - a)(x - x_0) + (y_0 - b)(y - y_0) = 0$.
### ✅ Tiếp tuyến có phương cho trước (song song/vuông góc đường thẳng $d$)
- **Phương pháp:** - Viết dạng tổng quát của tiếp tuyến $\Delta$ (dựa vào $d$).
- Sử dụng điều kiện tiếp xúc: $d(I, \Delta) = R$.

## 🛠️ 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Nhận dạng và tìm yếu tố đường tròn
- **Phương pháp:** Đưa phương trình về dạng tổng quát, kiểm tra điều kiện $a^2 + b^2 - c > 0$.
### 🔹 Dạng 2: Viết phương trình đường tròn
- **Biết tâm $I$ và đi qua điểm $A$:** $R = IA = \sqrt{(x_A - a)^2 + (y_A - b)^2}$.
- **Nhận $AB$ làm đường kính:** Tâm $I$ là trung điểm $AB$, bán kính $R = \frac{AB}{2}$.
- **Đi qua 3 điểm $A, B, C$:** Gọi phương trình dạng tổng quát, thay tọa độ 3 điểm vào để giải hệ phương trình tìm $a, b, c$.
- **Tâm $I \in d$ và tiếp xúc với đường thẳng $\Delta$:** $R = d(I, \Delta)$.
### 🔹 Dạng 3: Vị trí tương đối
- **Đường thẳng và đường tròn:** So sánh $d(I, \Delta)$ với $R$.
    - $d < R$: Cắt tại 2 điểm.
    - $d = R$: Tiếp xúc.
    - $d > R$: Không giao nhau.

## 🌍 4. Ứng dụng thực tế
### ✅ Định vị GPS và Radar
- Xác định phạm vi phủ sóng của một trạm phát tín hiệu (hình tròn bán kính $R$).
- Giao của các đường tròn từ 3 trạm phát giúp xác định vị trí chính xác của thiết bị.
### ✅ Kiến trúc và Thiết kế
- Thiết kế vòm cửa hình cung tròn, bánh răng máy móc, hoặc các quỹ đạo chuyển động tròn trong kỹ thuật.
### ✅ Thiên văn học
- Mô phỏng quỹ đạo gần tròn của các vệ tinh nhân tạo quanh Trái Đất (tâm đường tròn trùng với tâm Trái Đất).

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Giải hệ phương trình tìm tâm (3 điểm)
- **Thao tác:** `Menu 9` $\rightarrow$ `1` $\rightarrow$ `3`.
- Nhập hệ phương trình từ 3 điểm $A, B, C$ vào dạng: $x^2 + y^2 - 2ax - 2by + c = 0$ (ẩn là $a, b, c$).
### ✅ Kiểm tra điểm nằm trong/ngoài đường tròn
- Nhập biểu thức $(x - a)^2 + (y - b)^2 - R^2$.
- Sử dụng phím `CALC`, nhập tọa độ điểm cần kiểm tra.
    - Kết quả $< 0$: Điểm nằm trong.
    - Kết quả $= 0$: Điểm nằm trên.
    - Kết quả $> 0$: Điểm nằm ngoài.
### ✅ Tính khoảng cách nhanh (d(I, d))
- Sử dụng phân số và trị tuyệt đối `Abs` để tính nhanh công thức khoảng cách nhằm kiểm tra điều kiện tiếp xúc.

## ⚠️ Lưu ý của Giáo viên
- Luôn kiểm tra điều kiện của bán kính $R > 0$.
- Khi đề bài cho phương trình có hệ số trước $x^2$ và $y^2$ khác 1 (nhưng bằng nhau), phải chia cả hai vế cho hệ số đó trước khi tìm $a, b, c$.
- Tiếp tuyến của đường tròn luôn vuông góc với bán kính tại tiếp điểm: $\overrightarrow{IM_0} \perp \overrightarrow{u_{\Delta}}$.