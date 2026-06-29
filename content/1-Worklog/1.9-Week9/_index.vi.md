---
title: "Worklog Tuần 9"
date: 2026-06-21
weight: 9
chapter: false
pre: " <b> 1.9. </b> "
---

### Mục tiêu tuần 9:
* Lập trình mã nguồn xử lý logic nghiệp vụ và cấu hình các điểm đầu cuối API (API Endpoints).
* Triển khai kiểm thử tích hợp toàn diện hệ thống, tối ưu độ trễ xử lý và cấu hình giám sát thu thập log tập trung.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Chủ | - Viết mã nguồn xử lý logic nghiệp vụ bên trong các hàm AWS Lambda; tích hợp AWS SDK để truy xuất DynamoDB/S3 | 21/06/2026 | 22/06/2026 | AWS Lambda Developer Guide |
| 2 | - Thiết lập và cấu hình các tài nguyên REST API trên Amazon API Gateway để định tuyến các request từ client | 23/06/2026 | 24/06/2026 | Amazon API Gateway Docs |
| 4 | - Thực hành kiểm thử hệ thống đầu cuối (End-to-End); theo dõi hiệu năng hệ thống và gỡ lỗi (debug) thông qua Amazon CloudWatch | 25/06/2026 | 26/06/2026 | CloudWatch Logs Management |

### Kết quả đạt được tuần 9:
* Hoàn thành viết mã ứng dụng cho các API xử lý logic hóa đơn; tích hợp thành công chuỗi API Gateway -> Lambda -> DynamoDB/S3.
* Hệ thống backend Serverless vận hành ổn định, vượt qua các kịch bản kiểm thử tải nghiêm ngặt với độ trễ phản hồi cực thấp (Low Latency) kèm hệ thống log tập trung hoàn chỉnh trên CloudWatch.