# Multiagent
### 1.  Reflex Agent
* Chúng ta sẽ cần quan tâm đến khoảng cách gần nhất của Pacman đến vị trí đồ ăn và vị trí của con ma. Hai tham số này sẽ ảnh hưởng đến điểm số cho mỗi hành động của Pacman.
### 2. Minimax Agent
* Chúng ta sẽ cần biết cách để cập nhật chỉ số của agent và độ sâu dựa trên việc agent đó là Pacman hay ma.
### 3. Alpha - Beta
* Dựa vào cài đặt các hàm maxValue và minValue để lược bớt những trạng thái không cần thiết, thuật toán sẽ tiếp tục so sánh giá trị alpha hoặc beta để maxValue và minValue hiện tại sẽ không có giá trị xấu hơn dọc theo từ vị trí root.
### 4. Expectimax Agent
* Chúng ta cần trả về hành hộng có giá trị minimax lớn nhất khi đi từ vị trí root xuống các tầng bên dưới.
### 5. Evaluation Fuction
* Tương tự như hàm evaluationFuction của Reflex Agent, chúng ta sẽ cần xem xét 3 vị trí gần nhất của Pacman với thức ăn, ma, và thuốc.
