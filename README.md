# Báo cáo P2

## Q1

* Hướng làm:

    Ý tưởng nâng cấp hàm evaluationFunction() là trả về giá trị trong khoảng từ -1 đến 1 tính toán dựa trên vị trí thức ăn và vị trị trí ma gần nhất, cần gần thức ăn thì giá trị càng gần 1.

## Q2

* Hướng làm:

    Ý tưởng nâng cấp hàm getAction() là với độ sâu cho trước lần lượt thực hiện findMax với Pacman và findMin với các con ma, độ sau chỉ cập nhật khi chuyển từ findMax sang findMin hoặc ngược lại.

    Sau khi tính toán sẽ nhận được mảng gồm các actions và điểm cho action đó, dựa vào đó ta chọ action tốt nhất và trả về.

## Q3

* Hướng làm:

    Ý tưởng nâng cấp hàm getAction() là vẫn hoạt động tương tự như ở Q3 nhưng thêm phần cập nhật giá trị alpha và beta, có thể hiểu là điểm số tốt nhất của hành động đối với pacman và với các con ma.

    Phần chọn hành động tối ưu vẫn dựa trên giá trị trả về tương tự câu trên.

## Q4

* Hướng làm:

    Ý tưởng nâng cấp hàm getAction() là tương tự AlphaBetaAgent tuy nhiên thay hàm findMin tìm giá trị nhỏ nhất bằng hàm findAvg trong hàm đó giá trị value trả về là tổng các giá trị của từng con ma nhân với xác suất của nó.

    Phần chọn hành động tối ưu vẫn dựa trên giá trị trả về tương tự câu trên.

## Q5

* Hướng làm:

    Ý tưởng nâng cấp hàm betterEvaluationFunction() là vẫn sử dụng một phần hàm Ý tưởng nâng cấp hàm evaluationFunction() tuy nhiên thay vì dùng giá trị -1 và 1 ta dùng -inf và inf ùng với đó là tính toán giá trị dựa trên khoảng cách đến thức ăn gần nhất, ma gần nhất và mà xa nhất cùng với các trọng số thích hợp.
