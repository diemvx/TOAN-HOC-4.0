---
markmap:
  colorScheme: default
  math: katex
---

# 📐 BÀI 5. GIÁ TRỊ LƯỢNG GIÁC CỦA GÓC TỪ $0^\circ$ ĐẾN $180^\circ$

## 1. 📘 Định nghĩa trên nửa đường tròn đơn vị
### ✅ Nửa đường tròn đơn vị
- Là nửa đường tròn tâm $O(0;0)$, bán kính $R=1$ nằm phía trên trục hoành.
- Với mỗi góc $\alpha$ ($0^\circ \le \alpha \le 180^\circ$), có duy nhất điểm $M(x_0; y_0)$ trên nửa đường tròn sao cho $\widehat{xOM} = \alpha$.
### ✅ Các giá trị lượng giác (GTLG)
- $\sin \alpha = y_0$
- $\cos \alpha = x_0$
- $\tan \alpha = \frac{y_0}{x_0} = \frac{\sin \alpha}{\cos \alpha}$ ($\alpha \neq 90^\circ$)
- $\cot \alpha = \frac{x_0}{y_0} = \frac{\cos \alpha}{\sin \alpha}$ ($\alpha \neq 0^\circ, \alpha \neq 180^\circ$)
### ✅ Dấu của các GTLG
- $0^\circ < \alpha < 90^\circ$ (Góc nhọn): $\sin, \cos, \tan, \cot$ đều dương ($>0$).
- $90^\circ < \alpha < 180^\circ$ (Góc tù): $\sin > 0$; $\cos, \tan, \cot$ âm ($<0$).

## 2. 📋 Các hệ thức lượng giác cơ bản ,BR>& Quan hệ giữa các góc
### ✅ Công thức cơ bản cần nhớ
- $\sin^2 \alpha + \cos^2 \alpha = 1$
- $1 + \tan^2 \alpha = \frac{1}{\cos^2 \alpha}$ ($\alpha \neq 90^\circ$)
- $1 + \cot^2 \alpha = \frac{1}{\sin^2 \alpha}$ ($\alpha \neq 0^\circ, 180^\circ$)
- $\tan \alpha \cdot \cot \alpha = 1$
### ✅ Hai góc bù nhau ($\alpha$ và $180^\circ - \alpha$)<BR> 
- $\sin(180^\circ - \alpha) = \sin \alpha$  
- $\cos(180^\circ - \alpha) = -\cos \alpha$
- $\tan(180^\circ - \alpha) = -\tan \alpha$
- $\cot(180^\circ - \alpha) = -\cot \alpha$
### ✅ Hai góc phụ nhau ($\alpha$ và $90^\circ - \alpha$)
- $\sin(90^\circ - \alpha) = \cos \alpha$
- $\cos(90^\circ - \alpha) = \sin \alpha$

## 🧩 3. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Tính GTLG dựa vào các hệ thức
- **Phương pháp:** Sử dụng các công thức cơ bản. <br>Lưu ý điều kiện góc nhọn hay góc tù để chọn dấu $\pm$ khi khai căn.
- **Ví dụ:** Cho $\cos \alpha = -\frac{2}{3}$ ($90^\circ < \alpha < 180^\circ$). Tính $\sin \alpha$.
<br> Giải: $\sin^2 \alpha = 1 - \cos^2 \alpha = 1 - \frac{4}{9} = \frac{5}{9} \Rightarrow \sin \alpha = \frac{\sqrt{5}}{3}$ (vì $\sin \alpha > 0$).
### 🔹 Dạng 2: Rút gọn biểu thức lượng giác
- **Phương pháp:** Sử dụng tính chất bù nhau, phụ nhau và các hằng đẳng thức để triệt tiêu các hạng tử.
### 🔹 Dạng 3: Bài toán thực tế
- **Ứng dụng:** Tính chiều cao vật thể, khoảng cách trong đo đạc địa lý bằng cách áp dụng GTLG trong tam giác vuông hoặc định lý Sin, Côsin.
- **Gợi ý:** Tính chiều cao tháp khi biết góc nâng và khoảng cách đến chân tháp; Tính lực phân tích trên mặt phẳng nghiêng bằng vectơ $\overrightarrow{F}$.

## ⌨️ 4. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Thiết lập đơn vị đo góc
- **Bắt buộc:** Chuyển sang đơn vị Độ (Degree).
- **Thao tác:** `SHIFT` + `MENU` (SET UP) $\rightarrow$ `2` (Angle Unit) $\rightarrow$ `1` (Degree).
### ✅ Tính GTLG của một góc cho trước
- Nhấn trực tiếp các phím `sin`, `cos`, `tan`.
- **Lưu ý:** Để tính $\cot \alpha$, ta nhập $\frac{1}{\tan \alpha}$ hoặc $\tan(\alpha)^{-1}$.
### ✅ Tìm số đo góc khi biết GTLG
- Sử dụng các phím hàm ngược: `SHIFT` + `sin` ($\sin^{-1}$), `SHIFT` + `cos` ($\cos^{-1}$).
- **Ví dụ:** Tìm $\alpha$ biết $\sin \alpha = 0.5 \rightarrow$ Nhấn `SHIFT` `sin` `0.5` `=` kết quả $30^\circ$.

## ⚠️ Lưu ý của Giáo viên
- Cần chú ý đặc biệt đến dấu của $\cos \alpha$ khi góc $\alpha$ tù ($> 90^\circ$).
- Khi thực hiện các phép tính vectơ liên quan đến góc (như tích vô hướng), góc giữa hai vectơ $\overrightarrow{a}$ và $\overrightarrow{b}$ luôn nằm trong đoạn $[0^\circ; 180^\circ]$.
- Tận dụng tính chất $\sin(180^\circ - \alpha) = \sin \alpha$ để giải nhanh các bài toán diện tích tam giác $S = \frac{1}{2}ab\sin C$.