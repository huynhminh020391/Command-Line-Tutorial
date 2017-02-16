Để tìm chuỗi "hello" trong file hello.txt, ta có thể dùng lệnh _grep_.

```
[~]$ grep hello hello.txt
```

Output:

```
hello, world
```

Lệnh grep sẽ in ra màn hình các dòng có chứa chuỗi "hello". Lưu ý "Hello" khác với "hello". Nên những dòng chỉ có chuỗi "Hello" sẽ không được in ra. Để in ra các dòng có từ hello dù hello được viết hoa hay viết thường, ta dùng option -i.

```
[~]$ grep -i hello hello.txt
```



