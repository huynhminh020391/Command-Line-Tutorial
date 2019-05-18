# Tải file

Để tải một file từ Internet, ta dùng lệnh _curl_.

Trước hết, ta phải kiểm tra xem _curl_ đã được cài trong máy hay chưa. Dùng lệnh _which_ để kiểm tra.

```text
[~]$ which curl
```

Output:

```text
/usr/bin/curl
```

Vậy là _curl_ đã có sẵn và ta có thể dùng, trường hợp máy bạn không có lệnh này bạn có thể tìm cách cài đặt trên Google.

Giả sử ta muốn tải file goodnight.txt từ [https://www.example.com/goodnight.txt](https://www.example.com/goodnight.txt). Ta gõ:

```text
[~]$ curl -OL https://www.example.com/goodnight.txt
```

-O: dùng để ghi output thành một file có tên như tên file ở trên server, ở đây file sẽ có tên là goodnight.txt.

-L: dùng để follow redirects. \(Google "redirect" nếu bạn không rõ nó là gì ^\_^\).

Một số option khác:

-I: xem thông tin header.

-h: coi thông tin các option có thể sử dụng chung với lệnh _curl_.

