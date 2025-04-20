# A. SƠ QUA VỀ "XƯƠNG SỐNG" CỦA MỘT CHƯƠNG TRÌNH GUI :

### - Một program GUI sẽ có một bộ khung gần gần như sau :

1. Label

2. Entry

3. Button

4. Frame

# B. TÌM HIỂU VỀ CÁC THÀNH PHẦN CHI TIẾT :

## 1, LABEL :

### a> Mục đích :

- Hiển thị đoạn text cố định hoặc được cập nhật bằng `.config()`

### b> Prompt :

- Mẫu :

```python
label=tk.Label(parent, text="Nội dung", options...)
```
- Ví dụ :
```python
label=tk.Label(root,text="Địt mẹ mày", fg="black", bg="green",font=("Time New Romans",12))
label.pack()
```
- VD 2 :
```python
label.config(text="ND")
```

### c> Lưu ý quan trọng :
 
- Không thể tương tác với cái này.

- Có khả năng hiển thị ảnh bằng `image=PhotoImage(...)`

- Địt mẹ thằng nào đọc xong đéo donate...

## 2, ENTRY :

### a> Mục đích :

- Cho người dùng gõ một dòng văn bản như mật khẩu, câu lệnh, tên hoặc một trường nào đó

### b> Prompt :

```python
entry=tk.Entry(parent, options)
entry.pack()
```

- Các tham số thường dùng : `width`, `show="*"`(dùng để ẩn mật khẩu,...) và `font`(phông chữ)

- Ví dụ :
```python
entry=tk.Entry(root, width=30, show="*")
entry.pack() 
```

### c> Lưu ý quan trọng :

## 3, BUTTON :

### a> Mục đích :

### b> Prompt :

### c> Lưu ý quan trọng :

## 4, Frame :

### a> Mục đích :

### b> Prompt :

### c> Lưu ý quan trọng :