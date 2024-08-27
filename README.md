# Khai phá Đồ Thị Con Dày Đặc Có Độ Tin Cậy Cao từ Đồ Thị Không Chắc Chắn

## Giới thiệu

File GreedyUWDDS_GreedyOβWDS.ipynb thực hiện các thực nghiệm liên quan đến việc khai phá các đồ thị con dày đặc có độ tin cậy cao từ đồ thị có hướng, có trọng số và không chắc chắn. Các thuật toán chính được sử dụng bao gồm GreedyUWDDS và GreedyOβWDS, với mục tiêu tối ưu hóa các chỉ số như mật độ cạnh kỳ vọng, trọng số cạnh trung bình, độ lệch chuẩn, mật độ kỳ vọng, xác xuất cạnh trung bình, độ tin cậy đính kèm.

## Mục tiêu

- Áp dụng và đánh giá hiệu suất của các thuật toán GreedyUWDDS và GreedyOβWDS trên nhiều bộ dữ liệu khác nhau.
- So sánh kết quả giữa các phương pháp.
- Phân tích ảnh hưởng của tham số beta trong thuật toán GreedyOβWDS đối với kết quả thực nghiệm.

## Cài đặt

### Yêu cầu hệ thống

- Python 3.x
- Jupyter Notebook

### Cài đặt các thư viện cần thiết

Chạy lệnh sau để cài đặt các thư viện cần thiết:

```bash
pip install networkx matplotlib numpy tqdm pandas
```

## Dữ liệu 

Các bộ dữ liệu sử dụng trong thực nghiệm bao gồm các tập dữ liệu thực tế được mô tả trong báo cáo. Nằm trong thư mục Data.

## Kết quả

Notebook sẽ tạo ra các kết quả bao gồm:
- Đồ thị mô tả phân phối xác suất cạnh.
- Kết quả các chỉ số như mật độ cạnh kỳ vọng, trọng số cạnh trung bình,... của các thuật toán GreedyUWDDS và GreedyOβWDS.
- Phân tích ảnh hưởng của tham số beta đến kết quả khai phá đồ thị.
