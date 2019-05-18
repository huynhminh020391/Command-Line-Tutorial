# Copy

Để copy file hello\_world.txt và đặt tên file copy từ nó thành hello.txt. Ta dùng lệnh _cp_:

```text
[~]$ cp hello_world.txt hello.txt
```

Dùng lệnh _ls_ để kiểm tra:

```text
bye.txt hello.txt hello_world.txt one two
```

Kiểm tra lại nội dung của file hello.txt và hello\_world.txt:

```text
[~]$ cat hello.txt
```

Output:

```text
hello, world
Hi, everybody
```

```text
[~]$ cat hello_world.txt
```

Output:

```text
hello, world
Hi, everybody
```

Ngoài ra ta có thể dùng lệnh _diff_ để so sánh nội dung 2 file:

```text
[~]$ diff hello.txt hello_world.txt
```

Nếu 2 file giống nhau thì chương trình sẽ không in ra gì cả.

