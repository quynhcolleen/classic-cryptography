# Các thuật toán mật mã cổ điển (Classical Cryptography)

Repository này chứa các **Jupyter Notebook cài đặt và minh họa các hệ mật mã ĐỐI XỨNG cổ điển** trong môn học **ET3310 - Lý thuyết mật mã**.

Mỗi thuật toán được trình bày bao gồm:

- Cơ sở lý thuyết
- Ý tưởng thuật toán
- Cài đặt mã hóa
- Cài đặt giải mã
- Ví dụ minh họa
- Bảng minh họa quá trình mã hóa / giải mã

Mục đích của repository là phục vụ **học tập, thí nghiệm và thuyết trình** về các thuật toán mật mã cổ điển.

---

## Hướng dẫn sử dụng Notebook

Mỗi thuật toán trong repository được cài đặt dưới dạng **Jupyter Notebook**.  
Để chạy các notebook này, thực hiện các bước sau:

1. Cài đặt Python (khuyến nghị Python 3.x).
2. Cài đặt Jupyter Notebook nếu chưa có:

```bash
pip install notebook
```

3. Mở terminal tại thư mục repository và chạy:

```bash
jupyter notebook
```

4. Trong trình duyệt, mở notebook của thuật toán cần chạy (ví dụ: `hill_cipher.ipynb`, `playfair_cipher.ipynb`, ...).

5. Chạy từng cell theo thứ tự bằng cách nhấn **Shift + Enter**.

---

## Nội dung

### 1. Hệ mật thay thế đơn ký tự - Monoalphabetic

- Mã cộng (Additive Cipher)
- Mã nhân (Multiplicative Cipher)
- Mã Affine (Affine Cipher)
- Mã thay thế đơn ký tự (Monoalphabetic Substitution Cipher)

### 2. Hệ mật thay thế đa ký tự - Polyalphabetic
- Mã Autokey
- Mã Playfair
- Mã Vigenere
- Mã Hill

---

## Công nghệ sử dụng

- Python
- Jupyter Notebook
- Markdown

---

## Mục đích

Repository này được xây dựng nhằm:

- học tập và tìm hiểu **mật mã cổ điển**
- minh họa các thuật toán bằng **Jupyter Notebook**
- phục vụ **bài tập và thuyết trình môn học**

---

## Lưu ý

Các thuật toán trong repository này **không an toàn cho các hệ thống bảo mật hiện đại** và chỉ được sử dụng cho **mục đích học tập**.
