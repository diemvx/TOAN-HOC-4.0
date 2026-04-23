---
markmap:
  colorScheme: default
  math: katex
---

# 📐 BÀI 4. HỆ BẤT PHƯƠNG TRÌNH BẬC NHẤT HAI ẨN (LỚP 10)

## 1. 📘 Khái niệm chung
### ✅ Định nghĩa
- Là một hệ gồm hai hay nhiều bất phương trình bậc nhất hai ẩn $x, y$.
- Mỗi nghiệm chung của các bất phương trình trong hệ được gọi là một nghiệm của hệ đó.
### ✅ Miền nghiệm
- Là phần giao của các miền nghiệm của các bất phương trình thành phần.
- Biểu diễn hình học: Thường là một miền đa giác (lồi) hoặc một miền không giới hạn trên mặt phẳng tọa độ $Oxy$.

## 2. 🛠️ Phương pháp biểu diễn miền nghiệm
### 🔹 Bước 1: Vẽ các đường thẳng biên
- Vẽ các đường thẳng $d_i: a_i x + b_i y = c_i$ tương ứng với từng bất phương trình.
- **Quy ước:** Nét liền cho dấu $\le, \ge$ và nét đứt cho dấu $<, >$.
### 🔹 Bước 2: Xác định miền nghiệm từng BPT
- Chọn điểm thử $M_0(x_0; y_0)$ (thường là gốc tọa độ $O(0;0)$) để xác định nửa mặt phẳng nghiệm của mỗi BPT.
- Gạch bỏ phần không thuộc miền nghiệm.
### 🔹 Bước 3: Kết luận miền nghiệm của hệ
- Miền không bị gạch chính là miền nghiệm của hệ bất phương trình.

## 📈 3. Bài toán tối ưu
### ✅ Bài toán
- Tìm giá trị lớn nhất (GTLN) hoặc giá trị nhỏ nhất (GTNN) của biểu thức $F(x; y) = ax + by$ trên một miền nghiệm đa giác.
### ✅ Định lý quan trọng
- GTLN hoặc GTNN của $F(x; y)$ trên miền đa giác luôn đạt được tại một trong các **đỉnh** của đa giác đó.
### ✅ Quy trình giải
1. Biểu diễn miền nghiệm của hệ (là đa giác).
2. Tìm tọa độ các đỉnh của đa giác bằng cách giải các hệ phương trình đường thẳng giao nhau.
3. Tính giá trị $F$ tại tất cả các đỉnh.
4. So sánh kết quả để chọn ra GTLN/GTNN.

## 🌍 4. Ứng dụng thực tế
### ✅ Bài toán Sản xuất
- Tính toán số lượng sản phẩm $A$ và $B$ cần sản xuất để lợi nhuận cao nhất dựa trên giới hạn về: nguyên liệu, nhân công, chi phí.
### ✅ Bài toán Dinh dưỡng
- Phối hợp các loại thực phẩm $X, Y$ để cung cấp đủ lượng calo, protein cần thiết với giá thành thấp nhất.
### ✅ Bài toán Vận tải / Quảng cáo
- Phân bổ ngân sách quảng cáo trên các kênh khác nhau sao cho tiếp cận khách hàng tối đa trong phạm vi ngân sách cho phép.
### 📝 Ví dụ thực tế
- Một xưởng đóng bàn và ghế. Mỗi cái bàn cần 10 giờ công, mỗi cái ghế cần 5 giờ công. <BR>Quỹ thời gian có 100 giờ. Lợi nhuận bàn là 500k, ghế là 200k. Tìm phương án tối ưu.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay <BR>(Casio 580VNX / 880BTG)
### ✅ Tìm tọa độ các đỉnh (Giao điểm)
- Sử dụng chức năng giải hệ phương trình bậc nhất hai ẩn.
- **Thao tác:** `Menu 9` $\rightarrow$ `1` $\rightarrow$ `2`.
- Nhập hệ số của các đường thẳng biên để tìm tọa độ $(x; y)$.
### ✅ Tính giá trị biểu thức $F(x; y)$ tại đỉnh
- Nhập biểu thức $F = AX + BY$ (Dùng phím `ALPHA` để gọi biến).
- Sử dụng phím `CALC`. Máy hỏi $X?$, nhập hoành độ đỉnh; $Y?$, nhập tung độ đỉnh. Nhấn `=` để xem kết quả.
### ✅ Kiểm tra điểm có thuộc miền nghiệm
- Nhập các biểu thức vế trái của hệ BPT.
- Dùng `CALC` để thử tọa độ điểm. Nếu thỏa mãn tất cả các BPT thì điểm đó thuộc miền nghiệm.

## ⚠️ Lưu ý của Giáo viên
- **Điều kiện thực tế:** Đừng quên các điều kiện hiển nhiên như $x \ge 0, y \ge 0$ (số lượng vật thể không âm).
- **Vẽ hình:** Cần vẽ chính xác các giao điểm và trục tọa độ để tránh xác định sai đỉnh của đa giác.
- **Vectơ:** Trong các bài toán liên quan đến hướng di chuyển của đường thẳng mức $ax + by = k$, <BR>cần chú ý vectơ pháp tuyến $\overrightarrow{n} = (a; b)$ để xác định hướng tăng/giảm của $k$.