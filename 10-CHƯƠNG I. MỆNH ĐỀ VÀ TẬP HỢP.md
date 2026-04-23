---
markmap:
  colorScheme: google
  math: katex
---

# 🎓 ÔN TẬP CHƯƠNG I: MỆNH ĐỀ VÀ TẬP HỢP

## 1. 📝 Mệnh đề (Proposition)
### ✅ Định nghĩa và Phân loại
- **Mệnh đề:** Là một câu khẳng định đúng hoặc sai. Một mệnh đề không thể vừa đúng vừa sai.
- **Mệnh đề chứa biến:** Khẳng định có tính đúng/sai phụ thuộc vào giá trị của biến. Ví dụ: $P(n): "n \text{ chia hết cho 2}"$.
### ✅ Các phép toán mệnh đề
- **Mệnh đề phủ định ($\overline{P}$):** Phủ định tính đúng sai của $P$.
- **Mệnh đề kéo theo ($P \Rightarrow Q$):** Chỉ sai khi $P$ đúng và $Q$ sai.
- **Mệnh đề đảo:** $Q \Rightarrow P$ là mệnh đề đảo của $P \Rightarrow Q$.
- **Mệnh đề tương đương ($P \Leftrightarrow Q$):** Đúng khi $P, Q$ cùng đúng hoặc cùng sai.
### ✅ Ký hiệu với mọi ($\forall$) và Tồn tại ($\exists$)
- Phủ định của $\forall x \in X, P(x)$ là $\exists x \in X, \overline{P(x)}$.
- Phủ định của $\exists x \in X, P(x)$ là $\forall x \in X, \overline{P(x)}$.

## 📦 2. Tập hợp (Sets)
### ✅ Cách xác định tập hợp
- Liệt kê phần tử: $A = \{1; 2; 3\}$.
- Chỉ ra tính chất đặc trưng: $A = \{x \in \mathbb{R} \mid ax^2 + bx + c = 0\}$.
### ✅ Các phép toán trên tập hợp
- **Giao ($A \cap B$):** Lấy phần tử chung.
- **Hợp ($A \cup B$):** Lấy tất cả phần tử của cả hai tập hợp.
- **Hiệu ($A \setminus B$):** Thuộc $A$ nhưng không thuộc $B$.
- **Phần bù ($C_A B$):** Khi $B \subset A$, là tập hợp các phần tử thuộc $A$ nhưng không thuộc $B$.

## 📏 3. Các tập hợp số và Tập con của $\mathbb{R}$
### ✅ Hệ thống tập số
- $\mathbb{N} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R}$.
### ✅ Các tập con thường gặp trên trục số
- **Khoảng:** $(a; b) = \{x \in \mathbb{R} \mid a < x < b\}$.
- **Đoạn:** $[a; b] = \{x \in \mathbb{R} \mid a \le x \le b\}$.
- **Nửa khoảng:** $[a; b), (a; b], (-\infty; a], (a; +\infty)$.

## 🛠️ 4. Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định tính đúng/sai của mệnh đề
- **Phương pháp:** Kiểm tra tính đúng đắn dựa trên kiến thức toán học hoặc dùng phản ví dụ.
### 🔹 Dạng 2: Viết mệnh đề phủ định
- **Phương pháp:** Chuyển $\forall$ thành $\exists$, chuyển $=$ thành $\neq$, chuyển $>$ thành $\le$,...
### 🔹 Dạng 3: Thực hiện phép toán tập hợp
- **Phương pháp:** Với tập số thực $\mathbb{R}$, sử dụng trục số để biểu diễn và tìm phần chung/phần lấy.
### 🔹 Dạng 4: Bài toán đếm phần tử (Biểu đồ Ven)
- **Công thức:** $n(A \cup B) = n(A) + n(B) - n(A \cap B)$.

## 🌍 5. Ứng dụng thực tế
### ✅ Logic học và Công nghệ
- Thiết kế các mạch logic trong máy tính dựa trên mệnh đề đúng/sai (0 và 1).
- Xây dựng các câu lệnh điều kiện `if...then` trong lập trình.
### ✅ Thống kê và Phân loại
- Phân nhóm dữ liệu khách hàng (Ví dụ: Tập hợp khách hàng đã mua sản phẩm A $\cap$ chưa mua sản phẩm B).
- Bài toán quản lý nhân sự: Tìm số người biết ít nhất một trong hai ngoại ngữ.

## ⌨️ 6. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Giải phương trình để tìm phần tử tập hợp (Menu 9)
- Sử dụng để tìm nghiệm của phương trình bậc 2, bậc 3 khi tập hợp được cho dưới dạng tính chất đặc trưng.
- **Thao tác:** `Menu 9` ⮕ `2` ⮕ Chọn bậc.
### ✅ Kiểm tra tính đúng sai (Check Mode - Một số dòng máy cũ)
- Nhập một biểu thức logic hoặc so sánh để máy trả về kết quả True/False.
### ✅ Tính toán với số thực (Phím dấu phẩy, phím căn)
- Giúp xác định giá trị xấp xỉ của các đầu mút khoảng/đoạn (ví dụ: $\sqrt{2} \approx 1,41$) để biểu diễn chính xác trên trục số.

## ⚠️ Lưu ý của Giáo viên
- Cẩn thận khi lấy phần bù hoặc hiệu của hai tập hợp tại các đầu mút (ngoặc vuông/ngoặc tròn).
- Khi liệt kê phần tử, mỗi phần tử chỉ được viết **một lần**.
- Một câu cảm thán hoặc câu hỏi không phải là mệnh đề.