# Vương Quốc Kẹo Ngọt

## Mô tả
Đến với vương quốc kẹo ngọt của Santa Claus. Bé Minh được ông già Noel tặng cho một hàng dài gồm N món quà, mỗi món quà có các giá trị là Ai (1≤i≤N) và được bọc trong giấy gói quà màu Ci (1≤i≤N). Ông già Noel cho Minh chọn nhiều món quà cùng một lúc nhưng có điều kiện đặt ra là các món quà được chọn khi giữ nguyên thứ tự theo dãy quà ban đầu thì món quà phía sau phải có giá trị lớn hơn giá trị món quà phía trước và đặc biệt là dãy quà đó phải sắc màu. Một dãy quà sắc màu là dãy quà có các gói quà được bọc đủ K màu riêng biệt với nhau.

Bạn hãy giúp Minh thống kê xem có bao nhiêu cách chọn các món quà sao dãy quà được chọn thỏa mãn điều kiện của ông già Noel nhé.

## Input
- Dòng đầu tiên là hai số nguyên dương N (1≤N≤5.10^4) và K (1≤K≤7).
- N dòng tiếp theo là dãy các món quà ở vương quốc kẹo ngọt dòng thứ i thể hiện giá trị món quà Ai (1≤Ai≤5.10^4) và được bọc trong giấy gói quà màu Ci (1≤Ci≤K).

## Output
Một dòng duy nhất là số cách chọn các món quà kết quả chia lấy dư cho 10^9+7.

## Ví dụ
### Input
4 3

1 1

3 2

2 2

4 3

### Output
2
