# Chương 1: Bắt Đầu

## Cài đặt Python trong MacOS

### Kiểm tra phiên bản Python hiện có

Mặc định trên MacOS đã cài sẵn Python 2.

Mở Terminal, nhập `python --version` và nhấn Enter.

```sh
python --version
```

hoặc bạn có thể nhập `python3 --version` để kiểm tra xem Python 3 đã được cài chưa.

```sh
python3 --version
```

### Cài đặt Python 3

Nếu Python 3 chưa được cài đặt, bạn cần phải cài đặt nó. Bởi vì trong quyển sách này xử dụng *python3 command*. Bạn có thể gặp một số lỗi nếu chạy code trong quyển sách bằng Python 2.

- Cài đặt qua website:

Bạn có thể tìm thấy bản mới nhất của Python ở [https://www.python.org/downloads][python_download]. Sau khi tải và cài đặt, chạy lệnh `python3 --version` để kiểm tra phiên bản.

- Cài đặt qua [brew]:

```sh
brew install python
```

## Cài đặt Editor

Trong quyển sách này, tác giả giới thiệu chúng ta dùng [Sublime Text][slt] nhưng bạn có thể dùng bất cứ editor nào cũng được. Ví dụ như: [Visual Studio Code][vsc], [Atom][atom], [PyCharm][pyc]...

Trong trường hợp tôi thì tôi đang dùng Visual Studio Code. Bạn có thể tham khảo các bước sau để cài Visual Studio Code cho Python:

- Cài đặt [Visual Studio Code][vsc]

- Cài đặt [Python extension][python_vsc] cho Visual Studio Code.

## Chạy Hello World

Bạn tạo 1 file mới với tên là `hello_world.py` có nội dung sau:

```python
print('Hello World')
```

Phần mở rộng *.py* để chỉ rằng code trong file đó là được viết bằng Python. Ngay file bạn mới tạo, bạn có thể chạy thử chương trình bằng cách chọn ***Run > Start Debug(F5)*** hoặc ***Run > Run Without Debug(^ F5)***.

1 cửa sổ terminal sẽ xuất hiện ở bên dưới Visual Studio Code, và in ra kết quả:

```python
Hello World
```

> ## Tổng kết
>
> Ở chương này, bạn đã biết thêm 1 ít về Python, bạn có thể cài đặt Python trên hệ điều hành của mình (ở đây là MacOS).
> Bạn cũng đã cài đặt được 1 text editor để viết code Python 1 cách dễ dàng hơn.

[//]: # (reference links)
[python_download]: https://www.python.org/downloads
[brew]: https://brew.sh/#install
[slt]: https://www.sublimetext.com
[vsc]: https://code.visualstudio.com
[atom]: https://atom.io
[pyc]: https://www.jetbrains.com/pycharm
[python_vsc]: https://marketplace.visualstudio.com/items?itemName=ms-python.python
