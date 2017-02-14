Câu lệnh _man_ \(viết tắt của từ manual\), dùng để xem chức năng của các câu lệnh mà ta muốn sử dụng.

Ví dụ như ta muốn xem chi tiết chức năng của lệnh _echo_, ta gõ:

```
[~]$ man echo
```

Trong trường hợp này thì bản thân _echo_ là một argument, còn _man_ là một command.

Khi nhấn enter, màn hình sẽ hiện ra như sau:

    ECHO(1)          BSD General Commands Manual         ECHO(1)

    NAME
       echo -- write arguments to the standard output

    SYNOPSIS
       echo [-n] [string ...]

    DESCRIPTION
       The echo utility writes any specified operands, separated by single blank
       (` ') characters and followed by a newline (`\n') character, to the stan-
       dard output.

       The following option is available:

       -n  Do not print the trailing newline character. This may also be
          achieved by appending `\c' to the end of the string, as is done by
          iBCS2 compatible systems. Note that this option as well as the
    ...

Ta có thể nhấn phím mũi tên chỉ xuống để xem từng dòng một hoặc nhấn phím spacebar để xem trang tiếp theo. Để thoát, ta nhấn phím q.

Bản thân _man_ cũng là một command, vì thế ta có thể dùng lệnh _man_ lên chính nó.

```
[~]$ man man
```

Kết quả:



