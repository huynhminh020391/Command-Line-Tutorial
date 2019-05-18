# Grep

Để tìm chuỗi "hello" trong file hello.txt, ta có thể dùng lệnh _grep_.

```text
[~]$ grep hello hello.txt
```

Output:

```text
hello, world
```

Lệnh grep sẽ in ra màn hình các dòng có chứa chuỗi "hello". Lưu ý "Hello" khác với "hello". Nên những dòng chỉ có chuỗi "Hello" sẽ không được in ra. Để in ra các dòng có từ hello dù hello được viết hoa hay viết thường, ta dùng option -i.

```text
[~]$ grep -i hello hello.txt
```

Option -n: in ra dòng kèm với số dòng của file.

```text
[~]$ grep -n Hi hello.txt
```

Output:

```text
2:Hi, everybody
```

