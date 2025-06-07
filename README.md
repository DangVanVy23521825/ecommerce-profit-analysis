# 📦 Ecommerce Profit Analysis

## 📊 Mục tiêu dự án

Phân tích dữ liệu bán hàng từ nhiều nền tảng thương mại điện tử như Amazon, Flipkart, Myntra,... để:
- Hiểu rõ hiệu suất bán hàng của từng SKU, category, kênh bán hàng
- Xác định các yếu tố ảnh hưởng đến doanh thu và lợi nhuận
- Hỗ trợ đưa ra quyết định chiến lược dựa trên dữ liệu

Dự án sử dụng **Python** để xử lý dữ liệu và **Tableau** để trực quan hóa thông tin.

---

## 📁 Dataset

Nguồn: [Unlock Profits with E-commerce Sales Data](https://www.kaggle.com/datasets/thedevastator/unlock-profits-with-e-commerce-sales-data)

Các file chính:
- `Amazon Sale Report.csv`: Thông tin đơn hàng trên Amazon
- `International Sale Report.csv`: Bán hàng quốc tế
- `P & L March 2021.csv`, `May-2022.csv`: Thông tin giá bán, MRP, và nền tảng
- `Sale Report.csv`: Thông tin sản phẩm (SKU, stock, màu sắc, size)
- `Cloud Warehouse Comparison Chart.csv`: So sánh lợi nhuận giữa các nền tảng logistics
- `Expense IIGF.csv`: Doanh thu tổng

---

## 🧠 Quy trình phân tích

1. **Hiểu vấn đề & mục tiêu**  
   → Xác định các KPI: doanh thu theo SKU, nền tảng, thời gian; so sánh lợi nhuận giữa các kênh

2. **Tiền xử lý dữ liệu** 
   - Làm sạch dữ liệu từ nhiều file
   - Merge dữ liệu theo SKU
   - Chuyển đổi định dạng để phù hợp với Tableau

3. **Trực quan hóa với Tableau** 
   - Doanh thu theo nền tảng, danh mục
   - So sánh giá bán giữa các nền tảng
   - Hiệu suất SKU theo thời gian
   - Bán hàng quốc tế theo tháng

---

## 📌 Output

- 📁 Dữ liệu sau xử lý: `data/processed/`
- 📈 Dashboard Tableau: `tableau/twb`
- 🖼️ Hình ảnh demo: `tableau/screenshot.png`

---

## 🛠️ Công nghệ sử dụng

| Công cụ | Vai trò |
|--------|---------|
| **Python** (Pandas, Seaborn) | Làm sạch và xử lý dữ liệu |
| **Tableau** | Xây dựng dashboard trực quan |
| **Jupyter Notebook** | Ghi lại quy trình xử lý |
| **Git** | Quản lý phiên bản |
| **VSCode** | Viết mã và tổ chức project |

---

## 🖼️ Demo Dashboard

![Demo Dashboard](trong folder tableau)

Hoặc xem trực tiếp trên Tableau Public (nếu có):  
👉 [Xem bản công khai](https://public.tableau.com/...)

---
