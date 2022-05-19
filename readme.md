# BÀI THỰC HÀNH SỐ 4: Semantics Analysis

## Phân tích ngữ nghĩa là gì?
* Phân tích cú pháp chỉ kiểm tra cấu trúc ngữ pháp hợp lệ của chương trình
    * Những yêu cầu khác ngoài cấu trúc ngữ pháp:
    * “x” là tên một biến hay một hàm?
    * “x” đã được định nghĩa chưa?
    * “x” được định nghĩa ở đâu?
    * Biểu thức “a+b” có kiểu nhất quán không?
* Phân tích ngữ nghữ nghĩa trả lời các câu hỏi đó để làm rõ hơn ngữ nghĩa của chương trình.

## Nhiệm vụ của một bộ phân tích ngữ nghĩa
* Quản lý thông tin về các định danh
    * Hằng
    * Biến
    * Kiểu người dùng định nghĩa
    * Chương trình con (hàm, thủ tục)
* Kiểm tra một số luật ngữ nghĩa
    * Phạm vi định danh
    * Nhất quán kiểu

## Cách sử dụng
```
git clone https://github.com/mhai247/Semantics-Analysis
cd Semantics-Analysis/completed
make
./kplc <.kpl file>
```
## Test
```
bash test.sh
```