Lệnh _ls_ dùng để liệt kê tất cả các file và folder \(directory\) trong thư mục hiện hành.

Giả sử trong thư mục mà tôi đang làm việc có 2 thư mục là one và two cùng với một file text có tên hello.txt. Thì khi gõ lệnh _ls_, output sẽ là:

```
hello.txt one two
```

Ngoài ra lệnh _ls_ còn được dùng để kiểm tra xem một file hay folder có tồn tại trong thư mục mà tôi đang làm việc hay không.

Ví dụ khi gõ:

```
[~]$ ls bye.txt
```

Kết quả:

```
ls: cannot access bye.txt: No such file or directory
```

Chương trình báo lỗi, chứng tỏ file bye.txt không tồn tại.

Để tạo file bye.txt, ta có thể gõ lệnh:

```
[~]$ touch bye.txt
```

Kiểm tra xem file bye.txt có tồn tại không:

```
[~]$ ls bye.txt
```

Ta thấy là chương trình không báo lỗi, vậy file bye.txt đã có trong thư mục hiện hành.

Lệnh _ls_ cũng hỗ trợ wildcard character. Ví dụ muốn liệt kê tất cả các file có phần mở rộng là txt, ta gõ:

```
[~]$ ls *.txt
```

Output:

```
bye.txt hello.txt
```



