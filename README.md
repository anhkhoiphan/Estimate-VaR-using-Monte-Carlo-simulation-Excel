# Estimate VaR using Monte Carlo simulation Excel
Mô phỏng phân phối tổn thất (loss distribution) để xác định vốn rủi ro hoạt động theo cách tiếp cận AMA với các thông tin:

1. Loss Frequency: có phân phối Poisson với tham số 2
2. Loss Severity: có phân phối loga chuẩn với tham số 70+a và 20+a.

Thực hiện mô phỏng 500 giá trị của phân phối tổn thất, sau đó tính VaR(99%).
Trong đó a được xác định như sau: lấy số cuối của mã sinh viên của bạn chia cho 5, a được xác định là phần dư của phép chia đó.
 
