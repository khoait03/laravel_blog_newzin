# laravel_blog_newzin

laravel_blog_newzin là một website đăng tin tức blog cá nhân cấu trúc trang web chuẩn SEO phù hợp cho các trang tin tức thời sự

## Tính năng

- Website tin tức, đăng bài, xem bài, bình luận,
- Quản lý danh mục, bài viết, tags, thành viên....
- Phân quyền

## Cài đặt

Để cài đặt dự án, bạn cần thực hiện các bước sau:

1. Clone repository:

   ```bash
   git clone https://github.com/khoait03/laravel_blog_newzin.git


2. Cài đặt các phụ thuộc:
   ```bash
   composer install

3. Tạo file .env:
   ```bash
   cp .env.example .env

4. Cấu hình file .env:
   Mở file .env và cấu hình các thông số kết nối cơ sở dữ liệu, ứng dụng, và các thông tin khác cần thiết cho dự án.


5. Tạo khóa ứng dụng:
   ```bash
   php artisan key:generate

6. Chạy migration:
   ```bash
   php artisan migrate
   
7. Chạy seeder:
   ```bash
   php artisan db:seed
   
8. Run project:
   ```bash
   php artisan serve



10. Truy cập vào địa chỉ: http://127.0.0.1:8000 để xem ứng dụng:
 
    


Đóng góp
Nếu bạn muốn đóng góp cho dự án, vui lòng tạo pull request và tuân thủ các quy tắc đóng góp.

Giấy phép
Dự án này được cấp phép theo MIT License.
