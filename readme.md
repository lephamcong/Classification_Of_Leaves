## Đề tài: Ứng dụng Machine Learing Ứng dụng Machine Learning để phân loại lá cây

## Nhóm 2:

| **Tên**              | **Lớp**               | **Mã sinh viên**          |
|-------------------    |-------------------------|--------------------------|
| **Lê Phạm Công**    | 20KTMT1                 | 106200221                |
| **Phan Công Danh**       | 20KTMT1                 | 106200222                |
| **Đoàn Thế Lên**    | 20KTMT1                 | 106200233                |
| **Lê Minh Nhật**       | 20KTMT1                 | 106200238                |


## Mô tả

Nghiên cứu này nhằm phân loại ba loại lá cây Cercis chinensis, Indigofera
tinctoria, và Acer palmatum nằm trong bộ dữ liệu Flavia được công bố tại [1]
bằng cách sử dụng hai kỹ thuật học máy, K-Nearest Neighbors (KNN) và Support
Vector Machine (SVM), với hai loại đặc trưng khác nhau: Moment Invariants [2] (HU’s
Moments) và Histogram of Oriented Gradients [3] (HOG).

## Cấu trúc thư mục

- `HOG_nhom_02/`: Thư mục có dữ liệu và code khi trích xuất đặc trưng HOG
- `HU_nhom_02/`: Thư mục có dữ liệu và code khi trích xuất đặc trưng HU's Moments
- `KNN/`: Thư mục có dataset, code và các kết quả thu được khi sử dụng KNN với 2 loại đặc trưng HOG và HU's Moments
- `Leaf_nhom_02/`: Thư mục có ảnh thô chưa trích xuất đặc trưng
- `report/`: Thư mục chứa mã nguồn latex của báo cáo
- `result/`: Thư mục chứa một số ảnh sơ đồ sử dụng trong báo cáo
- `SVM/`: Thư mục có dataset, code và các kết quả thu được khi sử dụng SVM với 2 loại đặc trưng HOG và HU's Moments
- `readme.md`: file này
- `requirements.txt`: file thư viện cần thiết (hướng dẫn cài thư viện bên dưới)
## Cách sử dụng

1. Clone repo:

```
https://github.com/lephamcong/Classification_Of_Leaves.git
```

2. Cài đặt các thư viện cần thiết:

```
pip install -r requirements.txt
```


## Tài liệu tham khảo

[1] Wu, Stephen Gang, et al. “A leaf recognition algorithm for plant classification using probabilistic neural network." 2007 IEEE international symposium on signal processing and information technology. IEEE, 2007

[2] Hu, Ming-Kuei. “Visual pattern recognition by moment invariants." IRE trans-
actions on information theory 8.2 (1962): 179-187.

[3] Dalal, Navneet, and Bill Triggs. “Histograms of oriented gradients for human
detection." 2005 IEEE computer society conference on computer vision and
pattern recognition (CVPR’05). Vol. 1. Ieee, 2005.

## Thông tin liên hệ
- Lê Phạm Công
- Email: lpc051002@gmail.com


