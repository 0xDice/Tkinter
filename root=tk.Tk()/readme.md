# 1. CÁCH 1 CHƯƠNG TRÌNH GUI HOẠT ĐỘNG :

### - GUI hoạt động nhìn trông giống một cây thư mục, theo mình biết là vậy :))

### - Tất cả đều bắt nguồn từ cửa sổ root trở đi

# 2. KHỞI TẠO WINDOW CHÍNH TRONG TKINTER?

## - Câu lệnh :

```python
import tkinter as tk
root=tk.Tk()
```

## - Câu lệnh này sẽ làm ăn được gì? Nó sẽ làm được các việc sau :

#### 1. Khởi tạo một phiên.

#### 2. Tạo cửa sổ gốc (root).

#### 3. Bắt đầu vòng lặp sự kiện (event loop).

### - Nhìn sơ đồ sau để dễ hình dung :

```text
╔══════════════════════╗
║      root window     ║  ← do dòng tk.Tk() tạo ra
║ ┌──────────────────┐ ║
║ │   Label()        │ ║  ← gắn vào root
║ │   Button()       │ ║
║ └──────────────────┘ ║
╚══════════════════════╝
```

### - Vì đây nó giống như xương sườn của một con người cho nên nếu thiếu sẽ dẫn đến lỗi TclError hoặc không hiển thị như ý muốn khi sử dụng các widget :)))

### - Không nên tạo 2 root windows. Cái này là kinh nghiệm riêng của mình còn bạn nào xem mà không nghe thì kệ mẹ bạn :))

# 3. Vậy root còn có thể làm trò mèo gì nữa?

### - Có thể làm rất nhiều trò với root.

## 1. Cấu hình giao diện :

|Func|Tác dụng|
|----|--------|
|`root.title("...")`|Đặt tiêu đề|
|`root.geometry("width x height")`|Đặt kích thước cửa sổ|
|`root.resizable("x, y")`|Cho phép resize|
|`root.configure(bg="...")`|Đổi màu nền|
|`root.iconbitmap("file.ico")`|Đổi ảnh cửa số|
