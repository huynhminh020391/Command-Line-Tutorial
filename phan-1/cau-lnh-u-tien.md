# Câu lệnh đầu tiên

Bật terminal lên và gõ:

```text
[~]$ echo "hello, world"
```

Nhấn enter ta thấy câu lệnh trên in ra màn hình dòng chữ:

```text
hello, world
```

Nơi mà dòng chữ này được in ra được gọi là **standard out.**

Nơi mà lệnh được nhập vào được gọi là **standard in**.

\*Định nghĩa chính xác hơn về standard in và standard out cùng với **standard error**:

```text
Standard input - this is the file handle that your process reads to get information from you.

Standard output - your process writes normal information to this file handle.

Standard error - your process writes error information here.
```

Ở đây _echo_ là một command, còn "hello, world" là một argument, argument này là một string \(chuỗi ký tự\) mà ta muốn in ra màn hình.

Ví dụ ta muốn in ra màn hình dòng chữ _This is my program!_ Ta có thể gõ:

```text
[~]$ echo "This is my program!"
```

Sau đó nhấn enter thì màn hình sẽ hiện ra:

```text
This is my program!
```

Chú ý là ta nên đặt chuỗi ký tự mà ta muốn in ra trên màn hình trong cặp dấu " " hoặc ' '.

Nếu ta gõ thiếu một dấu ". Ví dụ:

```text
[~]$ echo "hello, world
```

Thì khi nhấn enter ta không thể nhập tiếp các câu lệnh khác được nữa. Để thoát khỏi tình huống này hoặc các tình huống mà terminal bị treo ta dùng tổ hợp phím Ctrl-C \(nhấn giữ phím Ctrl rồi sau đó nhấn phím C\).

Thật ra nếu ta nhập thiếu dấu ", ta vẫn có thể enter xuống dòng và bổ sung sau cũng được. Việc enter xuống dòng rồi bổ sung dấu nháy " cho phép ta in ra màn hình nhiều dòng cùng lúc.

Lưu ý là bản thân _echo_ sẽ tự động thêm vào newline "\n" ở cuối, nếu nó không tự động thêm vào "\n". Kết quả của lệnh _echo_ "hello" sẽ là:

```text
hello[~]$
```

Để làm cho lệnh _echo_ không in ra newline ở cuối, ta bổ sung option -n.

```text
[~]$ echo -n "hello"
```

Bạn có thể gõ thử để xem sự khác biệt giữa echo "hello" và echo -n "hello".

