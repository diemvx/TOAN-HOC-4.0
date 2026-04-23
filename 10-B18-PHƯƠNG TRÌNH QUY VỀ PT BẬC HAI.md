---
markmap:
  colorScheme: google
  math: katex
---

# 📑 PHƯƠNG TRÌNH QUY VỀ PHƯƠNG TRÌNH BẬC HAI

## 1. 📂 Phương trình dạng $\sqrt{ax^2 + bx + c} = \sqrt{dx^2 + ex + f}$
### ✅ Cách giải (Bình phương hai vế)
- **Bước 1:** Bình phương hai vế để khử căn: $ax^2 + bx + c = dx^2 + ex + f$.
- **Bước 2:** Giải phương trình bậc hai vừa nhận được.
- **Bước 3:** **Thử lại** các nghiệm tìm được vào phương trình ban đầu hoặc đặt điều kiện cho một trong hai biểu thức dưới căn không âm ($\ge 0$).
### ✅ Ví dụ
- $\sqrt{x^2 - 3x + 2} = \sqrt{x - 1}$.
- Bình phương: $x^2 - 3x + 2 = x - 1 \Leftrightarrow x^2 - 4x + 3 = 0 \Rightarrow x=1; x=3$.
- Thử lại: Cả hai nghiệm đều thỏa mãn.

## 2. 📂 Phương trình dạng $\sqrt{ax^2 + bx + c} = dx + e$
### ✅ Cách giải (Điều kiện có nghiệm)
- **Phương pháp 1 (Nâng cao):** - Điều kiện: $dx + e \ge 0$.
  - Bình phương: $ax^2 + bx + c = (dx + e)^2$.
- **Phương pháp 2 (Phổ thông):**
  - Bình phương hai vế thu được phương trình bậc hai.
  - Giải phương trình và **bắt buộc thử lại** nghiệm vào phương trình gốc.
### ✅ Ý nghĩa
- Đảm bảo vế phải không âm trước khi bình phương giúp loại bỏ nghiệm ngoại lai.

## 🛠️ 3. Các phương pháp giải bổ trợ
### 🔹 Phương pháp đặt ẩn phụ
- Sử dụng cho các phương trình có cấu trúc lặp lại.
- Dạng: $m \cdot f(x) + n \cdot \sqrt{f(x)} + p = 0$.
- Đặt $t = \sqrt{f(x)}$ ($t \ge 0$), đưa về phương trình bậc hai theo $t$.
### 🔹 Phương pháp chèn điểm/Vectơ (Nâng cao)
- Sử dụng bất đẳng thức vectơ để đánh giá hai vế: $|\overrightarrow{u}| + |\overrightarrow{v}| \ge |\overrightarrow{u} + \overrightarrow{v}|$.
- Ứng dụng khi phương trình có dạng tổng các căn thức bằng một hằng số.

## 🌍 4. Ứng dụng thực tế
### ✅ Vật lý & Chuyển động
- **Tính thời gian:** Xác định thời điểm hai vật gặp nhau khi một vật chuyển động có vận tốc thay đổi theo căn thức thời gian.
- **Quang học:** Tính toán vị trí đặt thấu kính dựa trên công thức liên quan đến tiêu cự và khoảng cách (thường xuất hiện căn bậc hai).
### ✅ Hình học & Xây dựng
- **Đường ngắn nhất:** Bài toán tìm vị trí điểm $M$ trên trục số sao cho tổng khoảng cách từ $M$ đến hai điểm cho trước đạt giá trị nhỏ nhất (dẫn đến phương trình chứa căn).
- **Thiết kế mái vòm:** Tính toán độ dài các thanh xà dựa trên phương trình quỹ đạo Parabol.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Giải nhanh tìm nghiệm (Lệnh SOLVE)
- **Thao tác:** Nhập toàn bộ phương trình vào máy (Dùng phím `ALPHA` + `)` để nhập $x$).
- Nhấn `SHIFT` + `CALC` (SOLVE).
- Nhập một giá trị dự đoán (ví dụ `0` hoặc `5`) rồi nhấn `=`.
- **Lưu ý:** SOLVE chỉ tìm được 1 nghiệm. Để tìm nghiệm khác, chia biểu thức cho $(x - \text{nghiệm vừa tìm})$ rồi SOLVE tiếp.
### ✅ Kiểm tra nghiệm (CALC)
- Sau khi giải tay được nghiệm $x_0$:
- Nhập vế trái trừ vế phải của phương trình: $\sqrt{ax^2+bx+c} - (dx+e)$.
- Nhấn `CALC`, nhập $x = x_0$. Nếu kết quả bằng `0` thì nghiệm đúng.
### ✅ Dùng TABLE tìm khoảng chứa nghiệm (Menu 8)
- Nhập $f(x) = \text{Vế trái} - \text{Vế phải}$.
- Quan sát cột $f(x)$, nếu giá trị đổi dấu từ âm sang dương (hoặc ngược lại), thì khoảng đó chứa nghiệm.

## ⚠️ Lưu ý của Giáo viên
- **Sai lầm phổ biến:** Quên không thử lại nghiệm dẫn đến nhận cả nghiệm ngoại lai (nghiệm làm cho vế phải của phương trình âm).
- **Vectơ:** Khi gặp phương trình dạng $\sqrt{(x-a)^2 + b^2} + \sqrt{(x-c)^2 + d^2} = k$, hãy liên tưởng đến độ dài của các vectơ $\overrightarrow{u}, \overrightarrow{v}$ để giải nhanh bằng hình học.
- Luôn rút gọn phương trình về dạng chuẩn $Ax^2 + Bx + C = 0$ trước khi bấm máy giải nghiệm.