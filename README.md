# Coffee_shop
# Tổng quan
1. Tóm tắt
2. Dữ liệu 
3. Công cụ phân tích
4. Các bước thực hiện
5. Phân tích và báo cáo
6. Kết luận và khuyến nghị

# 1. Tóm tắt
Bối cảnh là một doanh nghiệp mở rộng thêm kinh doanh cửa hàng cafe với thêm 3 cửa hàng mới tại New York. Nhóm phân tích thu thập dữ liệu tại 3 cửa hàng để phân tích hoạt động kinh doanh trong tháng đầu khai trương tại 3 cửa hàng mới. Ngoài ra, team sử dụng phương pháp RFM và cohort để phân loại khách hàng và đánh giá mức độ rời bỏ (churn) của khách hàng. Từ đó, nhóm rút ra được các tư vấn để cải thiện hoạt động kinh doanh và gia tăng doanh thu.

# 2. Dữ liệu
Nguồn: https://www.kaggle.com/datasets/ylchang/coffee-shop-sample-data-1113?select=sales_outlet.csv

Dữ liệu gồm 9 bảng:
- 201904 sales reciepts (fact)
- customer
- dates
- pastry inventory
- generations
- product
- sales target
- staff
- sales outlet

Ngoài ra, team tạo thêm bảng RFM segment bên ngoài để phân loại khách hàng

# 3. Công cụ phân tích
Nhóm chỉ sử dụng PowerBI để phân tích và tạo báo cáo do dữ liệu đã sạch

# 4. Các bước thực hiện
- Đưa dữ liệu vào PowerBI để tạo báo cáo
- Đưa ra các thông tin tổng quát về hoạt động kinh doanh trong tháng 4
- Phân tích về tình hình kinh doanh theo từng phần nhóm và tìm  ra các trend và insights
- Phân tích RFM và cohort để đánh giá mức độ rời bỏ của khách hàng
- Đưa ra các tư vấn để cải thiện hoạt động và gia tăng doanh thu

# 5. Phân tích và báo cáo
![image](https://github.com/user-attachments/assets/44b4bea4-f182-424a-8043-fde5da8769bc)

## Phân tích theo từng cửa hàng
- Cửa hàng tại 100 Church Street có doanh thu lớn nhất (tập trung nhiều khách hàng member)
- Doanh thu có sự tăng trưởng từ tuần Week 1 đến Week 3 và giảm nhẹ trong Week 4.
- Khách hàng member có xu hướng churn cao sau Week 1. Trong khi khách hàng vãng lai chiếm tỉ lệ rất ít trước khi tăng đột biến vào các tuần sau đó.

## Phân tích cohort
![image](https://github.com/user-attachments/assets/99ee7a1c-42b1-4593-8ee0-f161b6e7cb16)

- Số lượng khách thành viên mua mới lần đầu tập trung nhiều vào 5 ngày đầu và giảm dần vào các tháng sau.
- Nhiều khách hàng mua lần trong ngày và dừng ngay ngày hôm sau.

---> Nguyên nhân có thể do cửa hàng đã đưa ra các khuyến mãi cho khách hàng member trong tuần đầu dẫn đến doanh số tăng. 

---> Cần tìm hiểu thêm các yếu tố khác dẫn đến doanh thu member lại giảm hàng tuần.

---> Cần đánh giá hiệu quả từ phân tích RFM để có thêm được thông tin về nguyên nhân rời bỏ.

## Phân tích RFM
![image](https://github.com/user-attachments/assets/d1d4769b-d183-495d-b5e2-eb0e00f15c47)

1. Nhóm thường xuyên (Loyal và Champions):

Tăng cường chăm sóc khách hàng, đưa thêm các khuyến mại, tạo các chương trình tích điểm, giới thiệu thêm các loại sản phẩm mới

2. Nhóm có nguy cơ (at risk và cannot lose them):
Nhóm “cannot lose them”: có thể xếp vào đối tượng ưu tiên thấp do giá trị mua hàng và số lượng không lớn.

Nhóm “at risk”: chiếm số lượng nhiều, cần đưa thêm các chương trình khuyến mãi sâu để giữ chân khách hàng và có thêm các cuộc gọi chăm sóc khách hàng.

3. Nhóm tiềm năng (“Potential loyaltist” , “New customer” và “Need Attention”):

Liên lạc hỏi thăm khách hàng, giới thiệu các khuyến mãi và sản phẩm mới của cửa hàng.

## Để xem thêm về các phân tích khác, hãy xem thêm tại đây: 

[Coffee shop-Final Project.pdf](https://github.com/user-attachments/files/18849093/Coffee.shop-Final.Project.pdf)

# 6. Kết luận và khuyến nghị
- Khuyến khích khách hàng vãng lai đăng ký hội viên để mở rộng cơ sở dữ liệu của khách hàng, từ đó có thể theo dõi, phân tích hành vi tiêu dùng của khách hàng tốt hơn.
- Xây dựng thêm các hệ thống để khách hàng có thể đánh giá được chất lượng sản phẩm, làm nguồn dữ liệu đầu vào để đánh giá mức độ hài lòng của khách hàng từ đó gia tăng chất lượng sản phẩm và dich vụ
- Đa dạng hóa và nghiên cứu thêm các loại thức uống mới, thức uống theo trend để tăng trải nghiệm của khách hàng
- Đưa thêm các chương trình tích điểm cho thành viên, quy đổi điểm sang sản phẩm để kích thích khách hàng sử dụng sản phẩm nhiều hơn
- ...




