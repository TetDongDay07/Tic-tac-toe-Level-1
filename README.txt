content = """# TIC-TAC-TOE MỞ RỘNG (GENERALIZED TIC-TAC-TOE) - LEVEL 1
============================================================

## 1. GIỚI THIỆU
Đây là chương trình trò chơi Tic-Tac-Toe mở rộng được phát triển bằng ngôn ngữ C++ theo phong cách lập trình thủ tục. 
Dự án là bài tập lớn thuộc học phần Phương pháp luận lập trình (UET).

Các tính năng chính:
- Kích thước bàn cờ động: N x N (3 <= N <= 12).
- Mục tiêu chiến thắng (Goal): Tùy chỉnh (3 <= goal <= N).
- Chế độ chơi đa dạng: 
    + Người vs Người (PvP)
    + Người vs Máy (PvE)
    + Máy vs Máy (EvE)
- Cấp độ Bot: 
    + EASY: Chọn nước đi ngẫu nhiên.
    + MEDIUM: Heuristic đơn giản (Chặn thắng/thua).
    + HARD: Thuật toán Minimax kết hợp cắt tỉa Alpha-Beta.
- Luật kết thúc: Mặc định OPEN_TWO (Hở hai đầu).

## 2. YÊU CẦU HỆ THỐNG
- Trình biên dịch: g++ hỗ trợ chuẩn C++20.
- Hệ điều hành: Windows, Linux hoặc macOS.

## 3. HƯỚNG DẪN BIÊN DỊCH
Sử dụng terminal và chạy lệnh sau để biên dịch chương trình:
    g++ -std=c++20 starter-code.cpp -o game.exe

##4. HƯỚNG DẪN CHẠY CHƯƠNG TRÌNH
4.1. Chế độ tương tác (Interactive Mode)
Chạy trực tiếp file thực thi để vào giao diện menu:
    ./game.exe

4.2. Chế độ chấm điểm (Judge Mode)
Sử dụng cho kiểm thử tự động với file đầu vào:
    ./game.exe --judge --input input.txt

4.3. Chạy Test Script (Grader)
Để kiểm tra độ chính xác với bộ testcase đi kèm:
    python grader.py --target game    

## 5. TÁC GIẢ
Họ và tên: Nguyễn Quốc Hiếu
MSSV: 25022853
