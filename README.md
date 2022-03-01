# Pandas
- Pandas là một thư viện Python cung cấp các cấu trúc dữ liệu nhanh, mạnh mẽ, linh hoạt và mang hàm ý. 
- Tên thư viện được bắt nguồn từ panel data (bảng dữ liệu). 
- Pandas được thiết kế để làm việc dễ dàng và trực quan với dữ liệu có cấu trúc (dạng bảng, đa chiều, có tiềm năng không đồng nhất) và dữ liệu chuỗi thời gian.

# Data attributes - Thuộc tính của dữ liệu.
- order ID - Mã giao dịch
- quantity  - Số lượng mua
- item_name - Tên món hàng (một item_name có thể có nhiều món ăn)
- choie_description - Mô tả của món ăn
- item_price - Giá tiền 

# Missing data là gì?
Missing data là dữ liệu bị thiếu, được hiển thị như NaN, Nat, Null, N/A, v.v. Missing data xuất hiện do nhiều nguyên nhân như:
- Người dùng quên điền.
- Dữ liệu bị mất trong quá trình chuyển thủ công từ cơ sở dữ liệu cũ.
- Lỗi của chương trình.
- Thiếu dữ liệu do trùng hợp v.v.

Missing data có thể được phân thành 3 loại: 
- Missing at Random (dữ liệu khuyết ngẫu nhiên).
- Missing Completely at Random (dữ liệu thiếu hoàn toàn ngẫu nhiên). 
- Missing Not at Random (dữ liệu khuyết không ngẫu nhiên). 

# Tứ phân vị
- Tứ phân vị là đại lượng mô tả sự phân bố và sự phân tán của tập dữ liệu. 
- Tứ phân vị có 3 giá trị, đó là tứ phân vị thứ nhất Q1 (25th), thứ hai Q2 (50th) hay median, và thứ ba Q3 (75th). 
- Ba giá trị này chia một tập hợp dữ liệu (đã sắp xếp dữ liệu theo trật từ từ bé đến lớn) thành 4 phần có số lượng quan sát đều nhau. 
- Tứ phân vị được xác định như sau:
    - Sắp xếp các số theo thứ tự tăng dần
    - Cắt dãy số thành 4 phàn bằng nhau
    - Tứ phân vị là các giá trị tại vị trí cắt