Exploratory Data Analysis (EDA): là một phương pháp phân tích dữ liệu chủ yếu sử dụng các kỹ thuật về biểu đồ, hình vẽ.Từ đó để hiểu dữ liệu, hiểu các biến và quan hệ giữa các biến.

Các bước để phân tích EDA:
- Chuẩn bị dữ liệu.
- Import các thư viện của python: seaborn, numpy, panda, matplotlib...
- Xử lý dữ liệu: kiểm tra dữ liệu có bị rỗng, trùng hay không (dùng hàm inull).
- Nếu dữ liệu bị rỗng là các biến định luợng thì thay thế bằng giá trị trung vị hoặc trung bình, còn biến phân loại thì thay thế bằng giá trị xuất hiện nhiều nhất.
- Sau đó thống kê mô tả dữ liệu. (dùng hàm describe) để biết được các giá trị min, max, tứ phân vị, độ lệch chuẩn, phương, giá trị trung bình...
- Sau đó phân tích dữ liệu:
            Phân tích trực quan các biến định lượng dùng histogram.
            Phân tích trực quan các biến phân loại dùng count plot, bar plot...
            Phân tích tương quan giữa 2 biến định lượng dùng Scatter plot 
            Phân tích tương quan giữa biến định lượng và biến phân loại dùng box plot.
            Complex conditional plots được dùng để trực quan sự tương quan có điều kiện.
- Từ biểu đồ rút ra kết luận 
