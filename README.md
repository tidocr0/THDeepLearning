# Lab 1: Cơ bản về Numpy và Pandas trong Tiền Xử Lý Dữ Liệu

Đây là mã nguồn thực hành các thao tác cơ bản với ma trận và cấu trúc dữ liệu, phục vụ cho bước tiền xử lý trước khi đưa vào mô hình Deep Learning.

## Nội dung đã thực hiện

Đoạn code bao gồm các kỹ thuật xử lý chính sau:

### 1. Khởi tạo và kiểm tra thuộc tính mảng (Numpy Array)
- Chuyển đổi Python list sang mảng Numpy.
- Khởi tạo ma trận đa chiều (1D, 2D, 3D).
- Kiểm tra kích thước (`shape`) và kiểu dữ liệu (`dtype`).
- Tạo nhanh ma trận toàn số 0 (`np.zeros`) và toàn số 1 (`np.ones`).

### 2. Biến đổi cấu trúc ma trận (Reshape & Flatten)
- Định dạng lại số dòng, số cột của ma trận bằng `reshape()`.
- Duỗi phẳng ma trận nhiều chiều thành mảng 1 chiều bằng `flatten()`.

### 3. Ghép nối dữ liệu (Stacking)
- Nối hai mảng theo chiều ngang (`np.hstack`).
- Nối hai mảng theo chiều dọc (`np.vstack`).

### 4. Khởi tạo dữ liệu ngẫu nhiên (Randomization)
- Tạo mảng số nguyên ngẫu nhiên (`np.random.randint`).
- Tạo mảng số thực ngẫu nhiên trong khoảng [0, 1) (`np.random.rand`).
- Tạo dữ liệu tuân theo phân phối chuẩn (`np.random.normal`).
- Chọn ngẫu nhiên phần tử từ một danh sách có sẵn (`np.random.choice`).

### 5. Tạo dãy số tự động
- Khởi tạo cấp số cộng (`np.arange()`).
- Chia đều khoảng giá trị thành các điểm (`np.linspace()`).

### 6. Trích xuất dữ liệu (Indexing & Slicing)
- Lấy phần tử theo dòng, cột hoặc lấy theo một vùng điều kiện cụ thể.

### 7. Cấu trúc Pandas Series
- Khởi tạo Series từ list và dictionary.
- Gán và truy xuất dữ liệu thông qua Custom Index.

## Môi trường yêu cầu

```bash
pip install numpy pandas
