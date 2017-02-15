Ta quan sát lệnh sau đây:

```
[~]$ echo "hello, world"
```

Lệnh này sẽ output ra màn hình dòng:

```
hello, world
```

Bây giờ, nếu bạn muốn lưu lại output trên vào một file text thì làm thế nào? Để lưu output trên vào một file text ta gõ:

```
[~]$ echo "hello, world" > hello.txt
```

Ta thấy là output của lệnh _echo_ "hello, world" đã được redirect vào một file được gọi tên là hello.txt.

Để kiểm tra ta dùng lệnh sau:

```
[~]$ cat hello.txt
```

Lệnh này sẽ output ra nội dung của file hello.txt.

```
hello, world
```

Như vậy rõ ràng output của lệnh _echo_ ở trên đã được redirect vào file hello.txt.

Lưu ý là _cat_ có thể nhận nhiều argument, **&gt;** được gọi là **redirect operator **\(toán tử redirect\).

Để thêm nội dung vào một file nào đó, ta dùng **append operator &gt;&gt;**.

Ví dụ ta muốn thêm dòng Hi, everybody vào file hello.txt. Ta gõ lệnh như sau:

```
[~]$ echo "Hi, everybody" >> hello.txt
```

Để kiểm tra lại nội dung của file hello.txt. Ta gõ:

```
[~]$ cat hello.txt
```

Kết quả:

```
hello, world
Hi, everybody
```

Ta thấy là toán tử &gt;&gt; đã thêm \(append\) dòng thứ 2 có nội dung Hello, everybody vào file hello.txt.

