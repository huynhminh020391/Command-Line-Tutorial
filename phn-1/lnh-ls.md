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

Để coi thêm thông tin chi tiết các file và folder trong thư mục hiện hành, ta có thể bổ sung thêm option _-l_ vào lệnh _ls_. Ví dụ:

```
[~]$ ls -l
```

Output:

```
total 0
-rw-rw-rw- 1 Minima Minima  0 Feb 15 09:12 bye.txt
-rw-rw-rw- 1 Minima Minima 27 Feb 15 08:40 hello.txt
drwxrwxrwx 2 Minima Minima  0 Feb 15 08:41 one
drwxrwxrwx 2 Minima Minima  0 Feb 12 15:21 two
```

Ở cột cuối cùng là thời gian mà lần cuối file được chỉnh sửa. Kế đó là size của file tính bằng byte.

