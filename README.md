# CRM-Customer-Behaviour-Churn-Analysis

Phân tích hành vi khách hàng và xác định các yếu tố ảnh hưởng đến tỷ lệ rời bỏ của khách hàng.

## 📌 Tổng quan dự án

Dự án sử dụng **Power BI** để phân tích hành vi khách hàng và tỷ lệ rời bỏ (Customer Churn). Mục tiêu là xác định các yếu tố ảnh hưởng đến quyết định rời bỏ của khách hàng, đánh giá mức độ tương tác của người dùng và đưa ra các đề xuất giúp doanh nghiệp cải thiện khả năng giữ chân khách hàng cũng như tối đa hóa giá trị vòng đời khách hàng (Customer Lifetime Value - CLV).

---

## 🎯 Bài toán kinh doanh

Tỷ lệ khách hàng rời bỏ ảnh hưởng trực tiếp đến sự tăng trưởng và lợi nhuận lâu dài của doanh nghiệp. Dự án tập trung trả lời các câu hỏi sau:

- Tỷ lệ khách hàng rời bỏ hiện tại là bao nhiêu?
- Nhóm khách hàng nào có nguy cơ rời bỏ cao nhất?
- Mức độ tương tác và sự hài lòng ảnh hưởng như thế nào đến tỷ lệ rời bỏ?
- Gói đăng ký nào mang lại doanh thu cao nhất?
- Doanh nghiệp có thể làm gì để cải thiện khả năng giữ chân khách hàng và gia tăng doanh thu?

---

## 📂 Bộ dữ liệu

**Nguồn dữ liệu:** Kaggle – Netflix Large User Dataset

Bộ dữ liệu bao gồm thông tin nhân khẩu học của khách hàng, thông tin gói đăng ký, mức độ tương tác và trạng thái rời bỏ của khách hàng.

### Các trường dữ liệu chính

- Mã khách hàng (Customer ID)
- Tuổi (Age)
- Khu vực (Region)
- Gói đăng ký (Subscription Plan)
- Phí đăng ký hàng tháng (Monthly Charge)
- Thời gian xem trung bình mỗi ngày (Daily Watch Time)
- Điểm tương tác (Engagement Score)
- Điểm hài lòng (Satisfaction Score)
- Số lần liên hệ hỗ trợ (Support Queries)
- Lịch sử thanh toán (Payment History)
- Trạng thái rời bỏ (Churn Status)

---

## 🧹 Chuẩn bị dữ liệu

Quá trình chuẩn bị dữ liệu được thực hiện bằng **Microsoft Excel**.

### Làm sạch dữ liệu

- Loại bỏ dữ liệu trùng lặp
- Xử lý giá trị thiếu
- Chuẩn hóa dữ liệu phân loại
- Chuẩn hóa kiểu dữ liệu
- Kiểm tra tính nhất quán của dữ liệu

### Xây dựng dữ liệu bổ sung (Feature Engineering)

Tạo thêm các chỉ số phục vụ cho quá trình phân tích:

- Giá trị vòng đời khách hàng (Customer Lifetime Value - CLV)
- Tổng doanh thu (Total Revenue)
- Doanh thu theo quý (Quarterly Revenue)
- Thời gian gắn bó của khách hàng (Customer Tenure)

---

## 📊 Dashboard

Dashboard được xây dựng bằng **Power BI** và gồm **4 trang phân tích**.

### 📄 Trang 1 – Tổng quan (Executive Overview)

Cung cấp cái nhìn tổng quan về tình hình kinh doanh thông qua các chỉ số quan trọng.

**Các KPI chính**

- Tổng số khách hàng
- Số khách hàng đang hoạt động
- Tỷ lệ khách hàng rời bỏ
- Doanh thu
- Giá trị vòng đời khách hàng (CLV)

---

### 📄 Trang 2 – Phân tích hành vi khách hàng

Phân tích mức độ tương tác và hành vi sử dụng dịch vụ của khách hàng.

Bao gồm:

- Thời gian xem trung bình mỗi ngày
- Mức độ tương tác
- Mức độ hài lòng
- Thiết bị sử dụng
- Thể loại nội dung yêu thích

---

### 📄 Trang 3 – Phân tích tỷ lệ rời bỏ

Phân tích xu hướng và các yếu tố ảnh hưởng đến tỷ lệ rời bỏ của khách hàng.

Các biểu đồ chính:

- Tỷ lệ rời bỏ theo gói đăng ký
- Tỷ lệ rời bỏ theo khu vực
- Tỷ lệ rời bỏ theo nhóm tuổi
- Xu hướng rời bỏ theo thời gian
- Mối quan hệ giữa mức độ hài lòng và tỷ lệ rời bỏ

---

### 📄 Trang 4 – Phân tích giá trị khách hàng

Đánh giá mức độ đóng góp doanh thu và giá trị của từng nhóm khách hàng.

Bao gồm:

- Doanh thu theo gói đăng ký
- Giá trị vòng đời khách hàng (CLV)
- Doanh thu theo các châu lục
- Nhóm khách hàng có giá trị cao

---

## 💡 Kết quả phân tích

- Khách hàng sử dụng gói Premium tạo ra doanh thu và giá trị vòng đời khách hàng cao nhất. 
- Khách hàng có mức độ tương tác thấp có điểm hài lòng thấp và có xu hướng rời bỏ nhiều hơn.
- Khách hàng có điểm hài lòng thấp thường có tỷ lệ rời bỏ cao.
- Gói đăng ký theo tháng có tỷ lệ rời bỏ cao hơn các gói đăng ký dài hạn.
- Khách hàng thường xuyên liên hệ bộ phận hỗ trợ có nguy cơ rời bỏ cao hơn.

---

## 📌 Đề xuất

Dựa trên kết quả phân tích, đề xuất một số giải pháp nhằm cải thiện khả năng giữ chân khách hàng:

- Xây dựng chương trình khách hàng thân thiết dành cho nhóm khách hàng Premium.
- Tăng mức độ tương tác thông qua các chiến dịch cá nhân hóa nội dung.
- Nâng cao chất lượng dịch vụ hỗ trợ khách hàng nhằm cải thiện mức độ hài lòng.
- Khuyến khích khách hàng chuyển từ gói đăng ký theo tháng sang các gói dài hạn.
- Chủ động theo dõi và chăm sóc nhóm khách hàng có mức độ tương tác thấp để giảm nguy cơ rời bỏ.

---

## 🛠 Công cụ sử dụng

- Microsoft Excel (Làm sạch và chuẩn bị dữ liệu)
- Power BI (Mô hình hóa dữ liệu và xây dựng Dashboard)

---

## 📁 Cấu trúc dự án

```text
CRM-Customer-Behaviour-Churn-Analysis/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── dashboard/
│   ├── CRM_Customer_Behaviour.pbix
│   ├── overview.png
│   ├── customer_behaviour.png
│   ├── churn_analysis.png
│   └── customer_value.png
│
├── docs/
│
├── README.md
└── LICENSE
```

---

## 📷 Dashboard Preview

### Tổng quan

![Executive Overview](dashboard/image/Overview.png)

### Phân tích hành vi khách hàng

![Customer Behaviour](dashboard/image/Customer_voice_Satisfaction.png)

### Phân tích tỷ lệ rời bỏ

![Churn Analysis](dashboard/image/Churn_analysis.png)

### Phân tích giá trị khách hàng

![Customer Value](dashboard/image/Customer_lifetime_value.png)

---

## 📈 Kỹ năng áp dụng

- Phân tích nghiệp vụ (Business Analysis)
- Làm sạch dữ liệu (Data Cleaning)
- Chuẩn bị dữ liệu (Data Preparation)
- Feature Engineering
- Thiết kế KPI
- Trực quan hóa dữ liệu (Data Visualization)
- Phân tích hành vi khách hàng (Customer Analytics)
- Phân tích tỷ lệ rời bỏ (Churn Analysis)
- Phân tích giá trị vòng đời khách hàng (Customer Lifetime Value - CLV)
- Phân tích dữ liệu và xây dựng Insight
- Xây dựng Dashboard bằng Power BI
