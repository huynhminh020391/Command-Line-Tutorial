Pipe \(ký tự \| \) được dùng để đẩy kết quả của một lệnh vào một lệnh khác.

Ví dụ:

```
[~]$ echo "Goodbye, Pipe!" | wc
```

Output:

```
1 2 15
```

Lệnh _echo_ bình thường sẽ in ra màn hình chuỗi string mà bạn muốn nhưng trong trường hợp này chúng ta đã sử dụng ký tự \| \(pipe\) để đẩy kết quả vào lệnh_ wc_, do đó lệnh _wc_ sẽ nhận nội dung đó làm input. Chính vì thế mà chuỗi "Goodbye, Pipe!" khi được đẩy vào _wc_, thì sẽ được đếm là 1 dòng, 2 từ và 15 bytes.

