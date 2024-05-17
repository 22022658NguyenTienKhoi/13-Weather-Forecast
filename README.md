# Dự Án Dự Đoán Nhiệt Độ Không Khí Ngày Tiếp Theo

## Mô tả dự án

Dự án này sử dụng các mô hình khác nhau để dự đoán nhiệt độ không khí của ngày tiếp theo dựa trên dữ liệu thời tiết trong quá khứ.

## Dữ liệu

- **Tuấn**: Dữ liệu từ 01/01/1990 đến 31/12/1999
- **Tân**: Dữ liệu từ 01/01/2000 đến 31/12/2009
- **Khôi**: Dữ liệu từ 01/01/2010 đến hiện tại

## Mô hình sử dụng

- **Tuấn**: Ridge Regression
- **Tân**: Random Forest, rbf SVR
- **Khôi**: FB Prophet, mahalanobis SVR

## Hướng dẫn sử dụng

1. **Thu thập dữ liệu**:
   - Truy cập Visual Crossing:https://www.visualcrossing.com/ và tải dữ liệu thời tiết.
   
2. **Chuẩn bị dữ liệu**:
   - Tiền xử lý dữ liệu với Pandas, NumPy.

3. **Triển khai và huấn luyện mô hình**:
   - Ridge Regression, Random Forest, FB Prophet, rbf SVR, mahalanobis SVR.

4. **Đánh giá và dự đoán**:
   - Đánh giá mô hình và dự đoán nhiệt độ cho ngày tiếp theo.

## Kết quả

Kết quả của dự án sẽ được lưu trong báo cáo chi tiết: [Báo cáo dự án](https://docs.google.com/document/d/1p1ojGy7LZg16s_MVlr2Oyx0Q7kG7wCzrreKy9DvXVaE/edit?usp=sharing).
