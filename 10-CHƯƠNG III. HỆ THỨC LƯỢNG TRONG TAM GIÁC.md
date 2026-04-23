---
markmap:
  colorScheme: google
  math: katex
---

# 📐 ÔN TẬP CHƯƠNG III: HỆ THỨC LƯỢNG TRONG TAM GIÁC

## 1. 📂 Giá trị lượng giác của một góc từ $0^\circ$ đến $180^\circ$
### ✅ Định nghĩa trên nửa đường tròn đơn vị
- $\sin \alpha = y_0$ (tung độ)
- $\cos \alpha = x_0$ (hoành độ)
- $\tan \alpha = \frac{y_0}{x_0}$ ($x_0 \neq 0$)
- $\cot \alpha = \frac{x_0}{y_0}$ ($y_0 \neq 0$)
### ✅ Tính chất và Mối liên hệ
- **Góc bù nhau:** $\sin(180^\circ - \alpha) = \sin \alpha$; $\cos(180^\circ - \alpha) = -\cos \alpha$.
- **Góc phụ nhau:** $\sin(90^\circ - \alpha) = \cos \alpha$; $\cos(90^\circ - \alpha) = \sin \alpha$.
- **Các hệ thức cơ bản:** - $\sin^2 \alpha + \cos^2 \alpha = 1$
    - $1 + \tan^2 \alpha = \frac{1}{\cos^2 \alpha}$ ($\alpha \neq 90^\circ$)
    - $1 + \cot^2 \alpha = \frac{1}{\sin^2 \alpha}$ ($0^\circ < \alpha < 180^\circ$)

## 2. 📏 Các định lý cơ bản trong tam giác
### ✅ Định lý Côsin (Cosine Rule)
- **Công thức:** $a^2 = b^2 + c^2 - 2bc \cos A$.
- **Hệ quả (Tính góc):** $\cos A = \frac{b^2 + c^2 - a^2}{2bc}$.
- **Ứng dụng:** Biết 2 cạnh và góc xen giữa, hoặc biết 3 cạnh.
### ✅ Định lý Sin (Sine Rule)
- **Công thức:** $\frac{a}{\sin A} = \frac{b}{\sin B} = \frac{c}{\sin C} = 2R$.
- **Ứng dụng:** Biết 1 cạnh và 2 góc, hoặc biết 2 cạnh và 1 góc đối diện.
### ✅ Độ dài đường trung tuyến
- $m_a^2 = \frac{2(b^2 + c^2) - a^2}{4}$.

## 📐 3. Các công thức tính diện tích tam giác ($S$)
### ✅ Các công thức phổ biến
- $S = \frac{1}{2} a h_a = \frac{1}{2} b h_b = \frac{1}{2} c h_c$ (Cạnh đáy và chiều cao).
- $S = \frac{1}{2} bc \sin A = \frac{1}{2} ac \sin B = \frac{1}{2} ab \sin C$ (Hai cạnh và góc xen giữa).
- $S = \frac{abc}{4R}$ ($R$ là bán kính đường tròn ngoại tiếp).
- $S = pr$ ($p = \frac{a+b+c}{2}$ là nửa chu vi, $r$ là bán kính đường tròn nội tiếp).
### ✅ Công thức Heron
- $S = \sqrt{p(p-a)(p-b)(p-c)}$.

## 🛠️ 4. Phương pháp giải & Bài toán thực tế
### 🔹 Giải tam giác
- **Dạng 1:** Biết 3 cạnh $\Rightarrow$ Dùng hệ quả định lý Côsin tìm các góc.
- **Dạng 2:** Biết 2 cạnh và góc xen giữa $\Rightarrow$ Dùng định lý Côsin tìm cạnh thứ ba.
- **Dạng 3:** Biết 1 cạnh và 2 góc $\Rightarrow$ Dùng định lý Sin tìm các cạnh còn lại.
### 🔹 Ứng dụng thực tế
- **Đo đạc:** Tính khoảng cách giữa hai điểm bị ngăn cách (ví dụ hai đầu hồ nước, hai đỉnh núi).
- **Hàng hải/Hàng không:** Tính khoảng cách di chuyển khi biết vận tốc và góc lệch hướng.
- **Xây dựng:** Tính toán độ dốc mái nhà, chiều dài dây cáp cầu treo.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Cài đặt đơn vị Góc (Độ)
- **Thao tác:** `Shift` ⮕ `Menu` ⮕ `2` (Angle Unit) ⮕ `1` (Degree).
- *Lưu ý:* Luôn kiểm tra chữ **D** trên màn hình trước khi tính lượng giác.
### ✅ Tính giá trị lượng giác và Góc
- **Tính giá trị:** Nhấn `sin`, `cos`, `tan` trực tiếp. 
    - Ví dụ $\sin 150^\circ$: Nhấn `sin` `150` `=`.
- **Tìm góc khi biết giá trị:** Nhấn `Shift` + `sin/cos/tan`.
    - Ví dụ $\cos A = 0,5 \Rightarrow$ Nhấn `Shift` `cos` `0.5` `=` (Kết quả $60^\circ$).
### ✅ Giải nhanh tam giác (Phép tính phân số)
- Sử dụng phím phân số $\frac{\square}{\square}$ để nhập định lý Sin: `a` `÷` `sin(A)` `x` `sin(B)` để tìm cạnh $b$.

## ⚠️ Lưu ý của Giáo viên
- Trong tam giác, nếu $\cos A < 0$ thì góc $A$ là góc tù ($> 90^\circ$).
- Khi dùng định lý Sin để tìm góc, cần chú ý trường hợp có thể có hai góc (một nhọn, một tù) có cùng giá trị $\sin$.
- Vectơ trong hệ thức lượng: Có thể chứng minh định lý Côsin bằng tích vô hướng $\overrightarrow{BC}^2 = (\overrightarrow{AC} - \overrightarrow{AB})^2$.