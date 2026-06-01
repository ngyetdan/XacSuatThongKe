# 📊 Dashboard Phân Tích Doanh Số Shopee Tết

Ứng dụng web phân tích và dự báo doanh thu bán hàng trên Shopee trong dịp Tết, xây dựng bằng Streamlit.

## Tính năng

- Xu hướng doanh số theo ngày
- Top 10 sản phẩm bán chạy
- Giờ cao điểm mua sắm
- Dự báo doanh thu bằng Linear Regression

## Yêu cầu

```
streamlit
pandas
matplotlib
scikit-learn
numpy
openpyxl
```

Cài đặt:

```bash
pip install streamlit pandas matplotlib scikit-learn numpy openpyxl
```

## Chạy ứng dụng

```bash
streamlit run shop.py
```

## Dữ liệu

File `shopee_tet_sales_fixed.xlsx` cần có các cột:

| Cột | Mô tả |
|---|---|
| `Date` | Ngày đặt hàng |
| `Time` | Giờ đặt hàng (HH:MM:SS) |
| `Product` | Tên sản phẩm |
| `Quantity` | Số lượng |
| `Total_Price` | Tổng tiền (VNĐ) |
| `Order_ID` | Mã đơn hàng |

## Nguồn dữ liệu

Dữ liệu mẫu từ Shopee Tết 2023–2024.
