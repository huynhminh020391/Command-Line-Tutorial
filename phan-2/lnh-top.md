# Lệnh top

Lệnh top dùng để in ra màn hình những process đang ngốn nhiều tài nguyên máy tính nhất.

```text
[~]$ top
```

Kết quả của lệnh này tùy thuộc vào máy của bạn.

Ngoài ra để xem tất cả các process đang chạy ta có thể dùng lệnh _ps_ với option _aux_.

```text
[~]$ ps aux
```

Chú ý là aux không cần có dấu trừ ở đằng trước như các option khác.

Để tắt một process mà bạn không muốn, bạn có thể dùng lệnh kill -15 pid. Ở đây pid là process id.

Để tắt tất cả các process với tên hello, bạn có thể dùng lệnh pkill -15 -f hello.

