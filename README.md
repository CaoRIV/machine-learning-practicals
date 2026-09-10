# Machine Learning Practicals

Just to do homework for machine learning module.

## Mô tả

Kho này chứa các bài tập thực hành (Jupyter Notebooks) cho môn học Machine Learning. Mục tiêu là tập hợp các notebook minh họa các thuật toán, quy trình tiền xử lý dữ liệu, huấn luyện mô hình và đánh giá kết quả.

## Nội dung

- Các file chính: Jupyter Notebook (*.ipynb)
- Các notebook có thể bao gồm: tiền xử lý dữ liệu, hồi quy, phân lớp, clustering, giảm chiều, và đánh giá mô hình.

> Lưu ý: Nếu bạn muốn thêm mô tả chi tiết cho từng notebook, vui lòng cập nhật README hoặc thêm một file SUMMARY.md liệt kê tên và mô tả từng bài tập.

## Yêu cầu

- Python 3.8+
- Jupyter Notebook hoặc JupyterLab
- Thư viện phổ biến: numpy, pandas, scikit-learn, matplotlib, seaborn

Bạn có thể cài nhanh các gói cần thiết bằng cách:

```bash
python -m venv .venv
source .venv/bin/activate  # trên macOS/Linux
.venv\Scripts\activate     # trên Windows (PowerShell/Command Prompt)

pip install --upgrade pip
pip install jupyter numpy pandas scikit-learn matplotlib seaborn
```

Nếu repo có file `requirements.txt`, bạn có thể dùng:

```bash
pip install -r requirements.txt
```

## Cách chạy

1. Kích hoạt môi trường ảo (nếu có).
2. Chạy Jupyter Notebook hoặc JupyterLab:

```bash
jupyter notebook
# hoặc
jupyter lab
```

3. Mở notebook (*.ipynb) từ giao diện web và chạy các ô (cells).

## Gợi ý tổ chức

- Đặt mỗi bài tập dưới dạng một notebook riêng, ví dụ: `01-data-preprocessing.ipynb`, `02-linear-regression.ipynb`, ...
- Nếu có dữ liệu mẫu lớn, cân nhắc để dữ liệu ngoài repo và cung cấp script download hoặc hướng dẫn tải về.

## Đóng góp

Rất hoan nghênh PR chứa:
- Bài tập mới (notebook) với mô tả rõ ràng
- Nâng cấp README với mô tả từng notebook
- Tập tin `requirements.txt` để tái tạo môi trường

Vui lòng tạo PR và mô tả mục đích, thay đổi chính, và cách kiểm thử.

## Giấy phép

Mặc định không có giấy phép cụ thể — nếu bạn muốn cho phép người khác tái sử dụng mã nguồn, hãy thêm file `LICENSE` (ví dụ MIT).

---

Cần mình thêm phần nào (ví dụ liệt kê các notebook hiện có, mẫu requirements.txt, hoặc badge) không?