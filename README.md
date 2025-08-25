# MyWebApp

***
# Php Programming

### Chương 1: Giới thiệu về Php và Laravel
Khoá Coursera (Khóa 1):

Module 1:

1.1 Giới thiệu PHP
- PHP (Hypertext Preprocessor) là một ngôn ngữ lập trình kịch bản mã nguồn mở được sử dụng rộng rãi, đặc biệt phù hợp cho việc phát triển web. Nó có thể được nhúng trực tiếp vào các tệp HTML.

- PHP ban đầu được tạo ra bởi Rasmus Lerdorf vào năm 1994. Đến nay, nó đã trở thành một trong những ngôn ngữ phổ biến nhất để xây dựng các trang web động.

1.2 Cú pháp PHP
- Mã PHP luôn được đặt trong các thẻ < ?php và ? >. Một câu lệnh PHP kết thúc bằng dấu chấm phẩy (;).

Ví dụ:

PHP
```
<?php
    echo "Chào mừng bạn đến với PHP!";
    $ten = "Việt Nam";
    echo "Đất nước của tôi là " . $ten;
?>
```
- Biến: Biến trong PHP bắt đầu bằng ký tự $.

- Ghi chú (Comment): Bạn có thể sử dụng // cho một dòng hoặc /* ... */ cho nhiều dòng để ghi chú.

- Phân biệt chữ hoa/thường: Các từ khóa, hàm, và lớp (class) không phân biệt chữ hoa/thường (case-insensitive). Tuy nhiên, tên biến lại phân biệt chữ hoa/thường (case-sensitive).

1.3 Cấu trúc điều khiển
- Cấu trúc điều khiển giúp bạn kiểm soát luồng thực thi của chương trình.

- Câu lệnh điều kiện (Conditional Statements):

- if...else...elseif: Dùng để thực thi các khối mã khác nhau dựa trên các điều kiện.

- switch: Dùng để chọn một trong nhiều khối mã để thực thi.

Ví dụ:
```
<?php
    $diem = 8;
    if ($diem >= 9) {
        echo "Xuất sắc!";
    } elseif ($diem >= 7) {
        echo "Giỏi!";
    } else {
        echo "Cố gắng hơn nhé!";
    }
?>
```
Vòng lặp (Loops):

- for: Lặp qua một khối mã một số lần nhất định.

- while: Lặp qua một khối mã chừng nào điều kiện còn đúng.

- do...while: Tương tự while, nhưng khối mã sẽ được thực thi ít nhất một lần.

- foreach: Lặp qua các phần tử của một mảng.

Ví dụ:
```
<?php
    for ($i = 1; $i <= 5; $i++) {
        echo "Số: " . $i . "<br>";
    }
?>
```
1.4 Hàm
```
<?php
    function chaoMung($ten) {
        return "Xin chào, " . $ten . "!";
    }

    echo chaoMung("Minh Anh");
?>
```
1.5 Vai trò của PHP trong phát triển ứng dụng web
PHP giữ vai trò cốt lõi trong lập trình web phía server, cụ thể:

Xử lý dữ liệu từ biểu mẫu (form) người dùng.

Kết nối và thao tác với cơ sở dữ liệu.

Control/Điều khiển nôi dung động (dynamic content) từ CSDL về View hoặc từ View về Model (CSDL).

Xử lý các nghiệp vụ phát triển phần mềm: Ví dụ:

Xử lý xác thực, định dạnh và phần quyền người dùng (login, register).
CRUD
Phân tích xử lý nghiệp vụ doanh nghiệp (business logic)
Tích hợp dễ dàng với các framework Frontend, HTML, CSS, JavaScript.

Tạo API hoặc làm việc với JSON, XML.

PHP thường được sử dụng để xây dựng các hệ thống như:

Website thương mại điện tử

Hệ quản trị nội dung (CMS) như WordPress, Joomla

Diễn đàn (forums), mạng xã hội

Web service, RESTful API
