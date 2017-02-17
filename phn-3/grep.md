Giả sử ta muốn tìm một chuỗi "hello" trong một file nào đó và file đó ở trong một thư mục nào đó mà ta không biết rõ. Ta có thể dùng lệnh sau:

```
[~]$ grep -r hello folder
```

Lệnh này tìm chuỗi "hello" trong thư mục folder cùng với tất cả các thư mục con của nó, nếu có một file nào đó có nội dung mà ta muốn tìm thì dù nó ở trong thư mục folder hay thư mục con của folder ta vẫn sẽ tìm được.

