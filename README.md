Exploratory Data Analysis (EDA): là một phương pháp phân tích dữ liệu chủ yếu sử dụng các kỹ thuật về biểu đồ, hình vẽ.
Những kỹ thuật biểu đồ được sử dụng trong EDA thường khá đơn giản, bao gồm một vài kỹ thuật sau:
- Vẽ dữ liệu nguyên bản sử dụng data traces, histograms, block plots, ...
- Vẽ phân bố của dữ liệu nguyên bản sử dụng mean plots, standard deviation plots, box plots, ...
- Sắp xếp các biểu đồ giúp tối đa hoá khả năng tự nhiên về nhận biết mô hình của con người.

Các bước để phân tích EDA:
- Chuẩn bị dữ liệu.
- Xử lý dữ liệu: kiểm tra dữ liệu có bị rỗng, trùng hay không (dùng hàm inull).
- Nếu dữ liệu bị rỗng là các biến định luợng thì thay thế bằng giá trị trung vị hoặc trung bình, còn biến phân loại thì thay thế bằng giá trị xuất hiện nhiều nhất.
- Sau đó thống kê mô tả dữ liệu. (dùng hàm describe) để biết được các giá trị min, max, tứ phân vị, độ lệch chuẩn, phương, giá trị trung bình...
- Sau đó phân tích dữ liệu:
            Phân tích trực quan các biến định lượng dùng histogram.
            Phân tích trực quan các biến phân loại dùng count plot, bar plot...
            Phân tích tương quan giữa 2 biến định lượng dùng Scatter plot 
            Phân tích tương quan giữa biến định lượng và biến phân loại dùng box plot 
            Complex conditional plots được dùng để trực quan sự tương quan có điều kiện.-
- Từ biểu đồ rút ra kết luận và định ra các dự báo.

