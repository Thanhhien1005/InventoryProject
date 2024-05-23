# Inventory Analytics Project

## Mô tả
Dự án này tập trung vào xây dựng một kho dữ liệu (Data Warehouse) để phân tích dữ liệu về inventory. Sử dụng SQL Server Integration Services (SSIS) để xử lý dữ liệu từ tập dữ liệu gốc, SQL Server Analysis Services (SSAS) để xây dựng các cube phân tích, và Power BI để tạo các báo cáo và trực quan hóa.

## Hướng dẫn cài đặt
### Yêu cầu
- Visual Studio 2022
- SQL Server (bản mới nhất được khuyến nghị)
- Power BI Desktop

### Cài đặt
1. Clone dự án từ repository GitHub.
2. Mở Visual Studio 2022 và mở solution của dự án.
3. Thiết lập kết nối với cơ sở dữ liệu SQL Server và tập dữ liệu gốc.
4. Chạy các gói SSIS để xử lý dữ liệu và tạo các bảng dim và fact.
5. Xây dựng các cube phân tích trong SSAS.
6. Sử dụng Power BI để kết nối đến cube SSAS và tạo các báo cáo và trực quan hóa.

## Hướng dẫn sử dụng
1. Mở Power BI Desktop.
2. Kết nối đến cube SSAS đã xây dựng từ dự án.
3. Tạo các bảng điều khiển, biểu đồ, và báo cáo dựa trên dữ liệu từ cube.
4. Thực hiện phân tích và tùy chỉnh báo cáo theo nhu cầu của bạn.

## Tài liệu kỹ thuật
- File SSIS Package Files (.dtsx)
- File Backup SQL Server
- File SSAS (Analysis Services)
- Tệp Excel SSAS (ssas.xlsx)
- Tệp Power BI (ssas.pbix)
# Kết quả và Giải pháp cho Business Process

Câu hỏi: Số lượng các sản phẩm bán ra trong tháng/ quý/ năm.

### Sử dụng công cụ SSAS
- Kết quả: Hiển thị số lượng các mặt hàng, sản phẩm bán được theo thời gian.
- Giải pháp: Sử dụng SSAS để tạo cube phân tích dựa trên dữ liệu bán hàng, từ đó có thể truy vấn và hiển thị số lượng sản phẩm bán ra theo tháng, quý, hoặc năm.
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/042c4d3b-9b66-4bd7-b460-68734c228394)
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/95baac72-5471-4f1b-8884-cd1c298bafd7)


### Sử dụng Pivot Table trong Excel
- Kết quả: Hiển thị theo thời gian năm/ quý/ tháng.
- Giải pháp: Sử dụng Pivot Table trong Excel để tạo bảng tổng hợp dữ liệu bán hàng và hiển thị số lượng sản phẩm bán ra theo tháng, quý, hoặc năm.
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/b6a19390-595e-4746-a92e-01a10bf3145b)

### Sử dụng Power BI
- Kết quả: Biểu đồ thể hiện top 10 sản phẩm có số lượng được bán ra nhiều nhất và được lọc theo danh mục sản phẩm và theo thời gian (Năm, quý, tháng, ngày).
- Giải pháp: Sử dụng Power BI để kết nối và trực quan hóa dữ liệu từ cube SSAS, từ đó tạo biểu đồ và báo cáo hiển thị số lượng sản phẩm bán ra theo thời gian và danh mục sản phẩm.
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/77b5a31e-2d0e-4217-82c8-1c66de45a2d4)
## Câu hỏi: Cho biết giá trị tồn kho của các sản phẩm trong từng cửa hàng theo tháng/ quý/ năm.

### Sử dụng công cụ SSAS và Power BI:
- **Kết quả**: Hiển thị giá trị tồn kho của các sản phẩm theo từng cửa hàng.
- **Giải pháp**: Sử dụng SSAS để tạo cube phân tích dựa trên dữ liệu tồn kho, từ đó có thể truy vấn và hiển thị giá trị tồn kho của sản phẩm theo tháng, quý, hoặc năm. Sử dụng Power BI để kết nối và trực quan hóa dữ liệu từ cube SSAS, từ đó tạo biểu đồ và báo cáo hiển thị giá trị tồn kho của sản phẩm theo thời gian và cửa hàng.
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/3713f2da-8db1-4287-8516-be3198d5b227)

## Câu hỏi: Cho biết số lượng sản phẩm tồn kho theo từng cửa hàng trong tháng/ quý/ năm.

### Sử dụng công cụ SSAS và Power BI:
- **Kết quả**: Hiển thị số lượng tồn kho của sản phẩm theo từng loại sản phẩm.
- **Giải pháp**: Sử dụng SSAS để tạo cube phân tích dựa trên dữ liệu tồn kho, từ đó có thể truy vấn và hiển thị số lượng tồn kho của sản phẩm theo tháng, quý, hoặc năm. Sử dụng Power BI để kết nối và trực quan hóa dữ liệu từ cube SSAS, từ đó tạo biểu đồ và báo cáo hiển thị số lượng tồn kho của sản phẩm theo thời gian và cửa hàng.
![image](https://github.com/Thanhhien1005/InventoryProject/assets/170362430/ace56e12-b30a-4a65-ad75-3c8fe93b7926)



