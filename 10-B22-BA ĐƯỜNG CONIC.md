---
markmap:
  colorScheme: google
  math: katex
---

# 🛸 BA ĐƯỜNG CONIC<BR>(ELLIPSE, HYPERBOLA, PARABOLA)

## 1. 🥥 Elip (Ellipse)
### ✅ Định nghĩa & Phương trình chính tắc
- **Định nghĩa:** Tập hợp các điểm $M$ sao cho $MF_1 + MF_2 = 2a$ ($a > c$).
- **Phương trình:** $\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1$ ($a > b > 0$).
- **Liên hệ:** $a^2 = b^2 + c^2$.
### ✅ Các yếu tố
- **Tiêu điểm:** $F_1(-c; 0), F_2(c; 0)$.
- **Đỉnh:** $A_1(-a; 0), A_2(a; 0), B_1(0; -b), B_2(0; b)$.
- **Độ dài trục:** Trục lớn $2a$, trục nhỏ $2b$. Tiêu cự $2c$.
- **Tâm sai:** $e = \frac{c}{a} < 1$.

## 2. 🎡 Hypebol (Hyperbola)
### ✅ Định nghĩa & Phương trình chính tắc
- **Định nghĩa:** Tập hợp các điểm $M$ sao cho $|MF_1 - MF_2| = 2a$ ($a < c$).
- **Phương trình:** $\frac{x^2}{a^2} - \frac{y^2}{b^2} = 1$ ($a, b > 0$).
- **Liên hệ:** $c^2 = a^2 + b^2$.
### ✅ Các yếu tố
- **Tiêu điểm:** $F_1(-c; 0), F_2(c; 0)$.
- **Đỉnh:** $A_1(-a; 0), A_2(a; 0)$.
- **Độ dài trục:** Trục thực $2a$, trục ảo $2b$. Tiêu cự $2c$.
- **Tâm sai:** $e = \frac{c}{a} > 1$.
- **Tiệm cận:** $y = \pm \frac{b}{a}x$.

## 3. 📡 Parabol (Parabola)
### ✅ Định nghĩa & Phương trình chính tắc
- **Định nghĩa:** Tập hợp các điểm $M$ cách đều tiêu điểm $F$ và đường chuẩn $\Delta$.
- **Phương trình:** $y^2 = 2px$ ($p > 0$ - tham số tiêu).
### ✅ Các yếu tố
- **Tiêu điểm:** $F(\frac{p}{2}; 0)$.
- **Đường chuẩn:** $\Delta: x = -\frac{p}{2}$.
- **Đỉnh:** $O(0; 0)$.
- **Tâm sai:** $e = 1$.

## 🛠️ 4. Phương pháp giải các dạng toán
### 🔹 Dạng 1: Xác định các yếu tố của Conic
- **Phương pháp:** Đưa phương trình về dạng chính tắc để xác định $a, b, c, p$.
### 🔹 Dạng 2: Viết phương trình chính tắc
- **Elip/Hypebol:** Sử dụng các dữ kiện về đỉnh, tiêu điểm hoặc điểm đi qua để lập hệ phương trình ẩn $a^2, b^2$.
- **Parabol:** Dựa vào khoảng cách từ tiêu điểm đến đường chuẩn để tìm $p$.
### 🔹 Dạng 3: Bài toán thực tế & Điểm thuộc Conic
- Thay tọa độ điểm $M(x_0; y_0)$ vào phương trình để kiểm tra hoặc tìm tham số.

## 🌍 5. Ứng dụng thực tế
### ✅ Thiên văn học
- Quỹ đạo của các hành tinh quanh Mặt Trời là đường **Elip**.
- Quỹ đạo của một số sao chổi không chu kỳ là đường **Hypebol** hoặc **Parabol**.
### ✅ Kỹ thuật & Đời sống
- **Parabol:** Chóa đèn pin, ăng-ten parabol, cầu máng (tập trung ánh sáng/tín hiệu tại tiêu điểm).
- **Elip:** Trần nhà thì thầm (âm thanh từ một tiêu điểm phản xạ đến tiêu điểm kia), tán sỏi thận bằng sóng cú sốc.
- **Hypebol:** Tháp giải nhiệt trong các nhà máy nhiệt điện, hệ thống định vị tầm xa (LORAN).

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Tính toán thông số $c = \sqrt{a^2 \pm b^2}$
- Nhập trực tiếp biểu thức khai căn để tìm tiêu cự.
- Sử dụng phím `S⇔D` để đổi sang số thập phân khi cần vẽ hình.
### ✅ Giải hệ phương trình tìm $a^2, b^2$ (Menu 9-1-2)
- Khi biết Elip đi qua 2 điểm $M, N$: Đặt $X = \frac{1}{a^2}, Y = \frac{1}{b^2}$.
- Giải hệ: $\begin{cases} x_M^2 X + y_M^2 Y = 1 \\ x_N^2 X + y_N^2 Y = 1 \end{cases}$
### ✅ Kiểm tra điểm thuộc Conic (Phím CALC)
- Nhập biểu thức vế trái (ví dụ $\frac{x^2}{a^2} + \frac{y^2}{b^2}$).
- Nhấn `CALC`, nhập tọa độ điểm. Nếu kết quả $= 1$ thì điểm thuộc Elip/Hypebol.

## ⚠️ Lưu ý của Giáo viên
- **Elip:** $a^2$ luôn là mẫu số lớn nhất dưới $x^2$ hoặc $y^2$ (trong chương trình lớp 10 chỉ xét trục lớn nằm trên $Ox$).
- **Hypebol:** $a^2$ là mẫu số của hạng tử dương.
- **Đơn vị:** Trong bài toán thực tế (cầu, hầm), cần chọn hệ trục tọa độ phù hợp (thường đặt đỉnh tại gốc tọa độ hoặc trục đối xứng trùng $Oy$).