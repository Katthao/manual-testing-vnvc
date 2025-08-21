Manual Testing – VNVC Vaccination Scheduling System  

Dự án này bao gồm các **test case manual** cho website **Quản lý đăng ký lịch tiêm của Hệ thống tiêm chủng VNVC**.  
Mục tiêu là kiểm thử các chức năng chính của hệ thống, đảm bảo tính đúng đắn, khả dụng và trải nghiệm người dùng.  

---

Nội dung  

- **TestCases/**: Chứa toàn bộ test case dưới dạng file Excel.  
- Các sheet chính trong file test case:  
  - **Module**: Kiểm thử từng chức năng riêng lẻ.  
  - **Integration**: Kiểm thử luồng tích hợp giữa các module.  
  - **System**: Kiểm thử toàn hệ thống từ đầu đến cuối.  
  - **Database**: Kiểm thử dữ liệu trong CSDL (CRUD, ràng buộc, toàn vẹn dữ liệu).  
  - **Procedure**: Quy trình thực hiện kiểm thử.  
  - **RTM (Requirement Traceability Matrix)**: Bảng liên kết giữa yêu cầu và test case.  

---

Cách sử dụng  

1. Clone hoặc tải repo này về máy.  
2. Mở file Excel trong thư mục `VNVC_Testcases/`.  
3. Thực hiện kiểm thử theo kịch bản, ghi lại **Actual Result** và cập nhật cột **Status**.  
4. Sử dụng sheet **RTM** để đối chiếu test case với yêu cầu.  

---
Mục tiêu kiểm thử  

- Đảm bảo người dùng có thể **đăng ký lịch tiêm** thành công.  
- Kiểm tra quy trình **xác nhận, hủy, cập nhật lịch tiêm**.  
- Kiểm tra **tính chính xác dữ liệu** lưu trong cơ sở dữ liệu.  
- Đảm bảo hệ thống **thân thiện, ổn định và đáng tin cậy**.  

---

Công cụ sử dụng  

- **Excel (.xlsx)**: Quản lý và ghi chép test case.  
- **GitHub**: Lưu trữ và quản lý version test case.  

---
