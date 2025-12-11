Nội dung môn học
1. Tìm kiếm trong không gian trạng thái

Sinh viên được tiếp cận các khái niệm nền tảng:

🔹 8-Puzzle

Mô hình hóa trạng thái, hành động và mô hình chuyển tiếp

Thuật toán được cài đặt:

Breadth-First Search (BFS)

A* Search (Manhattan, Euclidean heuristic)

Phân tích: admissibility, consistency của heuristic

Thử nghiệm 1000 trạng thái ngẫu nhiên và so sánh hiệu suất thuật toán

🔹 Pacman Search

Mô hình hoá bản đồ, vị trí Pacman, thức ăn và vật cản

Thuật toán sử dụng:

Uniform-Cost Search (UCS)

A* Search (Manhattan, Euclidean)

Mục tiêu: ăn tất cả thức ăn và đi qua 4 góc

Triển khai bộ sinh kế thừa trạng thái, kiểm tra mục tiêu, tính chi phí

2. Local Search Algorithms

Bài trình bày tập trung vào ba thuật toán tìm kiếm cục bộ:

🔹 Random Restart Hill-Climbing

Tránh kẹt ở cực trị địa phương

Chạy nhiều lần và chọn lời giải tốt nhất

🔹 Simulated Annealing

Cho phép “nhảy” ra khỏi local optimum nhờ xác suất Boltzmann

Biến thiên nhiệt độ theo schedule

🔹 Local Beam Search

Duy trì k trạng thái tốt nhất mỗi vòng

Tập trung khai thác các ứng viên tiềm năng

Các thuật toán được áp dụng để tìm điểm cực đại trên ảnh được ánh xạ thành evaluation surface.

3. Logic và Ràng buộc – N-Queens với CNFs

Nhóm triển khai bài toán đặt N quân hậu thông qua:

Biến hóa từng ô thành biến logic

Thiết lập ràng buộc:

1 hậu mỗi hàng

1 hậu mỗi cột

Không trùng đường chéo chính/phụ

Chuyển đổi công thức sang Conjunctive Normal Form (CNF)

Giải bằng Glucose3 SAT Solver

In lại bàn cờ lời giải dưới dạng ma trận

4. Minimax & Alpha-Beta – 8x8 Tic-Tac-Toe

Xây dựng trò chơi Tic-Tac-Toe mở rộng:

Bảng 8×8, thắng khi liên tiếp 4 quân

Người chơi đấu với máy

Máy sử dụng:

Minimax + Alpha-Beta Pruning

Hàm đánh giá (Evaluate):

Chiến lược tấn công: tạo chuỗi 1/2/3

Chiến lược phòng thủ: chặn chuỗi đối thủ

Điểm ưu tiên theo vùng trên bảng (center control)

5. Machine Learning – Decision Tree

Với tập dữ liệu gồm Rank và các điểm Q1–Q9:

🔹 Phần 1: Tính toán thông tin

Entropy

Average Entropy

Information Gain
→ Chọn thuộc tính tốt nhất cho root node

🔹 Phần 2: Cây quyết định (Decision Tree – Scikit-learn)

Tách dữ liệu train/test

Huấn luyện mô hình độ sâu tối ưu

Đánh giá bằng:

Accuracy

Confusion Matrix

Feature Importance

Trực quan hóa cây quyết định

📘 Các kỹ thuật & thư viện sử dụng

Python, NumPy, Pandas, Matplotlib,
Scikit-learn, Glucose3 (SAT Solver),
thuật toán tìm kiếm cổ điển & heuristic AI.

👥 Thành viên thực hiện

Lý Tuấn An – 52000620

Lý Tiểu Long – 52200168

Giản Hoàng Huy – 52200147

Huỳnh Hoài Nam – 52200151

Lê Hồng Quang – 52200156
