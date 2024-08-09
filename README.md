# Website Quản lý Thông tin Khoa Toán - Tin học (Mathematics_Information_Management)

## Mô tả

Một website quản lý thông tin được xây dựng bằng stack MVPL (MySQL, VueJS, PHP, Laravel), cho phép quản lý và chia sẻ thông tin của Khoa Toán - Tin học. Website này hỗ trợ hai luồng hoặc vai trò chính:

1. Sinh viên duyệt thông tin khoa, tin tức, chương trình đào tạo, bình luận bài viết, gửi thư đến quản trị viên
2. Quản trị viên quản lý và kiểm soát toàn bộ nội dung của website

- Tính năng chính:
  - PHP và Laravel cung cấp môi trường backend cho ứng dụng này
  - VueJS để hiển thị các thành phần giao diện người dùng
  - MySQL để lưu trữ và quản lý dữ liệu
  - Xác thực và phân quyền người dùng
  - Quản lý tin tức, thông báo, bình luận bài viết
  - Quản lý chương trình đào tạo, bộ môn, chuyên ngành, nhân sự
  - Hệ thống gửi câu hỏi và phản hồi

## Hướng dẫn cài đặt

1. Clone repository:

```bash
$ git clone https://github.com/maitheduc/Mathematics_Information_Management/tree/main/server/database
$ cd project
```

2. Cài đặt dependencies:

```bash
$ composer install
$ npm install
```

3. Cài đặt và cấu hình cơ sở dữ liệu:

   - Cài đặt XAMPP (nếu chưa có): Tải và cài đặt từ trang chủ XAMPP
   - Khởi động XAMPP và bật Apache và MySQL
   - Mở phpMyAdmin (thường là http://localhost/phpmyadmin/)
   - Tạo một database mới (ví dụ: 'khoatinhoc_new2')
   - Import file database từ thư mục ..\server\database\khoatinhoc_new2.sql

4. Chạy migrations (nếu cần):

```bash
$ php artisan migrate
```

## Khởi chạy môi trường phát triển

- Tại client:

```bash
$ cd ..\client
$ npm run dev
```

- Tại server:

```bash
$ cd ..\server
$ php artisan serve
```

## Build cho production

```bash
$ npm run build
```

## Chạy ứng dụng production

```bash
$ php artisan serve
```

## Ngôn ngữ & công cụ

- [PHP](https://www.php.net/)
- [Laravel](https://laravel.com/)
- [VueJS](https://vuejs.org/)
- [MySQL](https://www.mysql.com/)
- [Vuetify](https://vuetifyjs.com/)

## Tác giả

- Đinh Thị Nhật Diễn(DinhThiNhatDien)
- Mai Thế Đức (MaiTheDuc)

## Giảng viên hướng dẫn

- TS. Trần Anh Tuấn
