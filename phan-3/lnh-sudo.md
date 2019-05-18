# Lệnh sudo

Mọi hệ điều hành Unix đều có các thư mục hệ thống, các thư mục này đóng vai trò quan trọng để máy tính có thể hoạt động bình thường.

Để thay đổi thư mục và các file hệ thống bạn cần đăng nhập với tư cách superuser hay root. Tuy nhiên vẫn có cách khác để can thiệp vào file hệ thống mà không cần đăng nhập với tư cách superuser. Đó là dùng lệnh _sudo_.

Giả sử ta muốn dùng lệnh _touch_ trong thư mục hệ thống opt.

```text
[~]$ touch /opt/foo
```

Output:

```text
touch: cannot touch '/opt/foo': Permission denied
```

Kết quả cho thấy ta không thể can thiệp vào thư mục. Nhưng nếu ta dùng lệnh _sudo_.

```text
[~]$ sudo touch /opt/foo
```

Output:

```text
[sudo] password for user:
```

Nếu bạn gõ đúng password thì lệnh sẽ được thực thi.

