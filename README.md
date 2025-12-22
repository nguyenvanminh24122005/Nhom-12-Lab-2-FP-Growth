# Lab 1 – Market Basket Analysis with Apriori

## Mục tiêu
Thực hiện phân tích giỏ hàng (Market Basket Analysis) bằng thuật toán Apriori trên bộ dữ liệu Online Retail nhằm tìm ra các luật kết hợp giữa các sản phẩm.

## Dữ liệu
- Nguồn: UCI Machine Learning Repository – Online Retail Dataset
- Số dòng ban đầu: 541,909
- Sau làm sạch: ~485,000 giao dịch (United Kingdom)

## Quy trình thực hiện
1. Tiền xử lý & EDA (`preprocessing_and_eda.ipynb`)
2. Chuẩn bị dữ liệu giỏ hàng (`basket_preparation.ipynb`)
3. Khai phá luật kết hợp (`apriori_modelling.ipynb`)

## Thuật toán
- Thuật toán: Apriori
- Thư viện: mlxtend
- Tham số chính:
  - min_support = 0.03
  - min_confidence = 0.6
  - min_lift = 1.5

## Kết quả
- Sinh ra các tập phổ biến và luật kết hợp có ý nghĩa.
- Các luật phản ánh hành vi mua sắm theo nhóm sản phẩm.

## Ứng dụng
- Gợi ý sản phẩm
- Thiết kế combo
- Tối ưu trưng bày

## Cách chạy
```bash
pip install -r requirements.txt
