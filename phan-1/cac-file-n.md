# Các file ẩn

Các file ẩn là các file mà tên của nó bắt đầu bằng dấu chấm ".".

Khi dùng lệnh _ls_, ta sẽ không thấy các file này.

Ví dụ ta tạo một file ẩn như sau:

```text
[~]$ touch .hidden.txt
```

Dùng lệnh _ls_:

```text
[~]$ ls
```

Output:

```text
bye.txt hello.txt one two
```

Để thấy được file ẩn ta dùng thêm option -a:

```text
[~]$ ls -a
```

Output:

```text
. .. bye.txt hello.txt .hidden.txt one two
```

