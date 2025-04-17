# 📊 Loan Default Prediction

## 🎯 Mục tiêu
Dự đoán xác suất vỡ nợ của một khoản vay mới dựa trên các đặc trưng đầu vào như tuổi, thu nhập, số tiền vay, nghề nghiệp và các yếu tố khác.  
Điều này giúp các tổ chức tài chính đánh giá rủi ro và quyết định có nên cấp khoản vay cho một khách hàng cụ thể hay không.

---

## 📁 Mô tả dữ liệu

| Biến | Mô tả |
|------|-------|
| `age` | Tuổi của người nộp đơn |
| `income` | Thu nhập hàng năm của người nộp đơn |
| `loan_amount` | Số tiền vay |
| `gender` | Giới tính của người nộp đơn (ví dụ: `"male"`, `"female"`) |
| `occupation` | Nghề nghiệp (ví dụ: `"engineer"`, `"doctor"`, `"lawyer"`, `"teacher"`) |
| `person_home_ownership` | Hình thức sở hữu nhà (ví dụ: `"rent"`, `"mortgage"`, `"own"`) |
| `person_emp_length` | Thời gian làm việc (năm) |
| `loan_intent` | Mục đích vay (ví dụ: `"education"`, `"medical"`, `"venture"`) |
| `loan_int_rate` | Lãi suất vay |
| `loan_percent_income` | Tỷ lệ phần trăm thu nhập dành cho khoản vay |
| `cb_person_default_on_file` | Hồ sơ vỡ nợ lịch sử (`"Y"`: Có, `"N"`: Không) |
| `cb_person_cred_hist_length` | Thời gian lịch sử tín dụng (năm) |
| `term` | Thời hạn vay (ví dụ: `"36 months"`, `"60 months"`) |
| `int_rate` | Lãi suất vay |
| `installment` | Khoản trả góp hàng tháng |
| `grade` | Xếp hạng tín dụng (ví dụ: `"A"`, `"B"`, `"C"`, `"D"`) |
| `member_id` | ID thành viên |

🔑 Các biến chính
- `age`: Tuổi của người vay  
- `income`: Thu nhập hàng năm  
- `loan_amount`: Số tiền vay  
- `gender`: Giới tính  
- `occupation`: Nghề nghiệp  
- `target`: Trạng thái khoản vay (`0`: không vỡ nợ, `1`: vỡ nợ)
- 

🎯 Biến mục tiêu (`target`)

Xác định trạng thái khoản vay:

- `0`: Không bị vỡ nợ (người vay trả nợ đúng hạn)  
- `1`: Bị vỡ nợ (người vay không trả nợ đúng hạn)

---

## Các Bước Thực Hiện 
◦ Thu thập dữ liệu. 
◦ Tiền xử lý dữ liệu. 
◦ Tạo và huấn luyện mô hình. 
◦ Đánh giá mô hình. 
◦ Xây dựng API để dự đoán.

