# Hướng dẫn sử dụng Unix Command Line

###### Tài liệu này cung cấp các kiến thức cơ bản về Unix Command Line.

Người viết: [https://www.facebook.com/minh.huynh.520357](https://www.facebook.com/minh.huynh.520357)

---

**GUI: Graphical User Interface.** Giao diện đồ họa, người dùng tương tác với máy tính thông qua các nút bấm, hình ảnh. Ví dụ: trình duyệt, hệ điều hành Windows 10, ...

**CLI: Command-line Interface. **Giao diện dòng lệnh,** **người dùng tương tác với máy tính thông qua các dòng lệnh. Ví dụ: Command Prompt trên Windows, ...

**Unix: **là một họ các hệ điều hành bao gồm Linux, Android, iOS và macOS.

**Terminal**: text input/output environment. \(Môi trường để nhập/ xuất text\)

**Shell**: command line interpreter. \(Trình thông dịch\)

Mặc dù GUI có thể đơn giản hóa việc tương tác với máy tính nhưng trong nhiều trường hợp, cách mạnh mẽ và linh hoạt nhất để tương tác với máy tính là thông qua CLI.

Ví dụ về một câu lệnh command-line:

```
[~]$ ls -l foo
```

Trong câu lệnh trên thì:

* \[~\]$ được gọi là một **prompt**. Bạn không cần gõ vào vì máy tính sẽ tự động thêm vào cho bạn.
* ls gọi là một **command**.
* -l gọi là **option**. \(Nếu có nhiều option thì thứ tự các option không quan trọng\)
* foo gọi là **argument**.

Để chạy một câu lệnh các bạn cần phải khởi động một chương trình gọi là **terminal**.

Đối với các bạn dùng Linux hay macOS thì không cần cài đặt thêm gì nhiều vì terminal đã được cài sẵn trên máy.

Đối với các bạn dùng hệ điều hành Windows, để chạy các câu lệnh trong tài liệu này, các bạn có thể sử dụng dịch vụ cloud [https://c9.io/](https://c9.io/) hoặc cài đặt VirtualBox [https://www.virtualbox.org/](https://www.virtualbox.org/). Ngoài ra các bạn dùng Windows 10 cũng có thể làm theo hướng dẫn sau để cài Bash trên Ubuntu cho Windows: [https://msdn.microsoft.com/en-us/commandline/wsl/install\_guide.](https://msdn.microsoft.com/en-us/commandline/wsl/install_guide)

Cách cài đặt các ứng dụng cũng như set up môi trường làm việc các bạn có thể tìm trên google.

