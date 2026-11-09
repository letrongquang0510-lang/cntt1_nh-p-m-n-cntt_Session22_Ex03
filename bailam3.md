# yêu cầu

## 1. Báo cáo phân tích (IPO)

* Input : Câu trả lời của AI đề xuất câu lệnh chạy trên Terminal để sửa lỗi "Path not found" khi cài đặt Python (ví dụ: một lệnh lạ can thiệp sâu vào hệ thống).
* Process : 
  1. Kiểm tra từng tham số và cấu trúc lệnh bằng cách tra cứu trên Google với toán tử `site:stackoverflow.com` hoặc tài liệu chính thức từ trang chủ Python (`python.org`).
  2. Xác minh xem lệnh có thực hiện các thao tác nguy hiểm (như xóa file hệ thống, phân quyền sai, tải mã độc từ bên thứ ba) hay không.
* Output : Kết luận lệnh là an toàn (nếu khớp với tài liệu chuẩn) hoặc không an toàn (nếu có dấu hiệu bất thường) để quyết định có thực thi hay không.

## 2. Câu lệnh (Prompt) "hỏi ngược lại" AI

> "Hãy giải thích chi tiết từng thành phần trong câu lệnh bạn vừa đưa ra có tác dụng gì đối với hệ thống của tôi? Đồng thời, hãy chỉ ra rủi ro tiềm ẩn (nếu có) và xác nhận rằng câu lệnh này hoàn toàn an toàn, không làm thay đổi các thiết lập cốt lõi của hệ điều hành trước khi tôi thực thi."
