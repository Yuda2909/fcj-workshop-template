---
title: "Worklog Tuần 8"
date: 2026-06-14
weight: 8
chapter: false
pre: " <b> 1.8. </b> "
---

### Mục tiêu tuần 8:
* Thiết kế mô hình dữ liệu và quy hoạch kiến trúc Cloud-Native dạng Serverless (Không máy chủ) hoàn chỉnh cho dự án.
* Khởi tạo tầng lưu trữ phân tán và cấu hình cơ sở dữ liệu trên môi trường Cloud thực tế.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Chủ | - Nghiên cứu sâu và định nghĩa cấu trúc dữ liệu JSON/NoSQL để mô hình hóa thông tin cho Biên lai điện tử (Preview Bill) | 14/06/2026 | 15/06/2026 | NoSQL Design Patterns |
| 2 | - Thiết kế sơ đồ kiến trúc Serverless chi tiết kết hợp các dịch vụ đám mây tự quản trị của AWS | 16/06/2026 | 17/06/2026 | AWS Serverless Blueprint |
| 4 | - **Triển khai hạ tầng:** Tạo các bảng dữ liệu trong Amazon DynamoDB; cấu hình kho lưu trữ tệp tin đầu vào Amazon S3 | 18/06/2026 | 19/06/2026 | AWS DynamoDB & S3 Console |

### Kết quả đạt được tuần 8:
* Chuẩn hóa thành công cấu trúc NoSQL Schema tối ưu hóa cho việc truy vấn danh mục hóa đơn, biên lai với hiệu năng ổn định.
* Khởi tạo thành công phân vùng lưu trữ S3 Bucket bảo mật cao và các thực thể bảng dữ liệu Amazon DynamoDB, hoàn thiện toàn bộ tầng dữ liệu (Data Layer) cho ứng dụng.