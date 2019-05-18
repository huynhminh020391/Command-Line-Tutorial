# Cách thao tác với các file

Ta quan sát lệnh sau đây:

```text
[~]$ echo "hello, world"
```

Lệnh này sẽ output ra màn hình dòng:

```text
hello, world
```

Bây giờ, nếu bạn muốn lưu lại output trên vào một file text thì làm thế nào? Để lưu output trên vào một file text ta gõ:

```text
[~]$ echo "hello, world" > hello.txt
```

Ta thấy là output của lệnh _echo_ "hello, world" đã được redirect vào một file được gọi tên là hello.txt.

Để kiểm tra ta dùng lệnh sau:

```text
[~]$ cat hello.txt
```

Lệnh này sẽ output ra nội dung của file hello.txt.

```text
hello, world
```

Như vậy rõ ràng output của lệnh _echo_ ở trên đã được redirect vào file hello.txt.

Lưu ý là _cat_ có thể nhận nhiều argument, **&gt;** được gọi là **redirect operator** \(toán tử redirect\).

Để thêm nội dung vào một file nào đó, ta dùng **append operator &gt;&gt;**.

Ví dụ ta muốn thêm dòng Hi, everybody vào file hello.txt. Ta gõ lệnh như sau:

```text
[~]$ echo "Hi, everybody" >> hello.txt
```

Để kiểm tra lại nội dung của file hello.txt. Ta gõ:

```text
[~]$ cat hello.txt
```

Kết quả:

```text
hello, world
Hi, everybody
```

Ta thấy là toán tử &gt;&gt; đã thêm \(append\) dòng thứ 2 có nội dung Hello, everybody vào file hello.txt.

Lưu ý là redirect operator &gt; sẽ chép đè file, còn append operator &gt;&gt; sẽ thêm nội dung vào file.

