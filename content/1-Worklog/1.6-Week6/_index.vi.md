---
title: "Worklog Tuần 6"
date: 2026-05-31
weight: 6
chapter: false
pre: " <b> 1.6. </b> "
---

### Mục tiêu tuần 6:
* Nghiên cứu các mô hình, tiêu chuẩn bảo mật nâng cao và quản trị tài khoản tập trung trên quy mô lớn của AWS.
* Thực hành xây dựng các chính sách phân quyền chi tiết (fine-grained access control) và bảo mật thông tin xác thực.

### Các công việc cần triển khai trong tuần này:
| Thứ | Công việc | Ngày bắt đầu | Ngày hoàn thành | Nguồn tài liệu |
| --- | --- | --- | --- | --- |
| Chủ | - Nghiên cứu Mô hình Trách nhiệm chung (Shared Responsibility Model), AWS Identity Center (SSO) và giải pháp quản lý khóa AWS KMS | 31/05/2026 | 01/06/2026 | AWS Security Whitepapers |
| 2 | - Tìm hiểu quy trình khóa thông tin xác thực root, cấu hình phân cấp tài khoản thông qua AWS Organizations | 02/06/2026 | 03/06/2026 | Multi-account Strategy |
| 4 | - **Thực hành (Lab):** Viết mã cấu hình IAM Policy theo nguyên tắc đặc quyền tối thiểu; cưỡng bức kích hoạt bảo mật MFA cho User | 04/06/2026 | 05/06/2026 | AWS IAM Policy Guide |

### Kết quả đạt được tuần 6:
* Hiểu sâu sắc ranh giới bảo mật giữa nhà cung cấp đám mây và khách hàng dựa trên mô hình Shared Responsibility.
* Thiết lập thành công hệ thống phân quyền tùy biến (Custom IAM Policies), hoàn thành bài Lab triển khai cơ chế xác thực đa yếu tố (MFA) bắt buộc đối với mọi định danh người dùng.