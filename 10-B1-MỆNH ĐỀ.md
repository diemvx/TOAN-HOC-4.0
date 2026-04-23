---
markmap:
  colorScheme: default
  math: katex
---

# 🧠 BÀI 1. MỆNH ĐỀ (LOGIC)

## 1. 📘 Khái niệm cơ bản
### ✅ Mệnh đề toán học
- Là một khẳng định có tính đúng hoặc sai rõ ràng.
- Không thể vừa đúng vừa sai.
- **Ví dụ:** "$2+3=5$" (Mệnh đề đúng); "$\pi$ là số hữu tỉ" (Mệnh đề sai).
### ✅ Mệnh đề chứa biến
- Là khẳng định chứa biến $x, y \dots$ mà tính đúng sai phụ thuộc vào giá trị của biến.
- **Ví dụ:** $P(x): "x > 5"$. Với $x=6$ thì $P(6)$ đúng.

## 2. 📋 Các phép toán trên mệnh đề
### 🔹 Mệnh đề phủ định ($\overline{P}$)
- Nếu $P$ đúng thì $\overline{P}$ sai và ngược lại.
- **Quy tắc:** Phủ định của "$\forall$" là "$\exists$", phủ định của "$=$" là "$\neq$".
### 🔹 Mệnh đề kéo theo ($P \Rightarrow Q$)
- Chỉ sai khi $P$ đúng mà $Q$ sai.
- **Ý nghĩa:** $P$ là giả thiết (điều kiện đủ), $Q$ là kết luận (điều kiện cần).
### 🔹 Mệnh đề đảo & Tương đương
- **Mệnh đề đảo:** $Q \Rightarrow P$.
- **Mệnh đề tương đương ($P \Leftrightarrow Q$):** Đúng khi $P, Q$ cùng đúng hoặc cùng sai.
### 🔹 Ký hiệu với mọi ($\forall$) và Tồn tại ($\exists$)
- $\forall x \in X, P(x)$: Đúng nếu mọi giá trị của $x$ đều thỏa mãn.
- $\exists x \in X, P(x)$: Đúng nếu có ít nhất một giá trị $x$ thỏa mãn.

## 3. 🧩 Các dạng toán và Phương pháp giải
### 🔹 Dạng 1: Xác định tính đúng sai
- Sử dụng các kiến thức toán học về số học, hình học để kiểm tra khẳng định.
### 🔹 Dạng 2: Phủ định một mệnh đề
- **Phương pháp:** - Chuyển $\forall \to \exists$ và ngược lại.
    - Phủ định tính chất: $x > a \to x \le a$.
### 🔹 Dạng 3: Phát biểu điều kiện cần và đủ
- $P$ là điều kiện đủ để có $Q$.
- $Q$ là điều kiện cần để có $P$.

## 🌍 4. Ứng dụng thực tế
### ✅ Tư duy logic & Lập trình
- Sử dụng trong cấu trúc rẽ nhánh `if...then...` của máy tính.
- Xây dựng các thuật toán kiểm tra điều kiện.
### ✅ Chứng minh toán học
- Phương pháp chứng minh phản chứng: Giả sử phủ định $\overline{P}$ đúng rồi suy ra điều vô lý.
### ✅ Đời sống
- Phân tích các phát biểu trong tranh luận để tìm ra sơ hở logic.

## ⌨️ 5. Hướng dẫn Máy tính cầm tay (Casio 580VNX / 880BTG)
### ✅ Kiểm tra tính đúng sai của mệnh đề chứa biến
- **B1:** Nhập biểu thức (vế trái trừ vế phải) hoặc bất đẳng thức.
- **B2:** Sử dụng phím `CALC`.
- **B3:** Nhập các giá trị $x$ khác nhau để kiểm tra.
- **Kết quả:** Nếu mọi $x$ đều cho kết quả thỏa mãn thì mệnh đề có thể là $\forall$. Nếu chỉ cần một giá trị thỏa mãn thì là $\exists$.
### ✅ Giải phương trình/bất phương trình (Hỗ trợ mệnh đề $\exists$)
- Sử dụng `SOLVE` hoặc `TABLE` (Menu 8) để xem có tồn tại giá trị nào làm cho khẳng định đúng hay không.
- **Ví dụ:** Kiểm tra $\exists x \in \mathbb{R}: x^2 - x + 1 = 0$. Dùng `Menu 9` giải phương trình bậc 2, thấy nghiệm phức $\Rightarrow$ Mệnh đề sai.

## ⚠️ Lưu ý của Giáo viên
- Cẩn thận với các câu cảm thán, câu hỏi, câu mệnh lệnh $\rightarrow$ Không phải mệnh đề.
- Chú ý tập hợp số khi xét $\forall, \exists$ (ví dụ: $x \in \mathbb{N}$ khác với $x \in \mathbb{R}$).
- Khi phủ định mệnh đề kéo theo $P \Rightarrow Q$, kết quả là $P$ và $\overline{Q}$.