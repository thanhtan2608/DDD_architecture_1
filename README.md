# Ví dụ đơn giản về một dự án được xây dựng theo mô hình DDD và sử dụng MultiMaven với Spring Boot.

🚀 Công nghệ sử dụng

Java 17 & Spring Boot 2.3.1.RELEASE

Spring Data JPA: Quản lý thực thể và truy vấn dữ liệu.

H2 Database: Cơ sở dữ liệu in-memory phục vụ demo và test.

Maven: Quản lý dự án và các module.

🏗️ Cấu trúc dự án (Architecture)

Domain: Chứa các thực thể nghiệp vụ (Customer), Repository Interface và các logic lõi.

Service: Chứa Business Logic (CustomerService) xử lý luồng dữ liệu.

Controller: Cung cấp các REST API Endpoints và điều hướng giao diện.

Application: Module chính chứa file chạy (CustomerApplication) và các cấu hình hệ thống (JPA Mapping, Liquibase).

🛠️ Hướng dẫn cài đặt & Chạy ứng dụng

1. Clone dự án:
git clone https://github.com/thanhtan2608/DDD_architecture_1.git

2. Build dự án với Maven: mvn clean install

3. Chạy ứng dụng:
Mở module Application, tìm class CustomerApplication và nhấn Run.

4. Truy cập giao diện:
Mở trình duyệt và truy cập: http://localhost:8080/index.html
